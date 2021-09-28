> 本项目名称为 Angulr，对！没错！就是少个 a，少个 a 就是它正确的拼写。
是一个以 Bootstrap 和 AngularJS 为基础，并使用了大量前端开源组件合成的一个前端UI框架，是非常棒的UI框架。
官方原版是要收费的，并且是英文的，我已经搞到一份最新版(v2.2)的源码，并且汉化好了哟
此版本只用于学习和技术交流，请勿用于商业用途，出现任何法律责任与翻译者无关

> 下面的内容是翻译自 readme.md，主要是教你如何编译项目的
可是不管你懂不懂如何编译前端项目，你也最好不要去编译此项目
因为一编译就会有一部分内容又会变成英文，这一点一定要注意！

> 其实你就没必要编译了，因为已经是编译好的了。
你只需要将网站配置到 Web容器 下运行就可以，比如 IIS、IIS Express、Tomcat 等...

> 如果你不知道怎么将网站配置到 Web容器，那你可以安装一个 Visual Studio
然后点击主菜单->文件->打开->网站，然后打开此文件夹，再按 Ctrl+F5 运行即可。

> 汉化版由湖南长沙华瑞IT教育周游老师提供
此版本只用于学习和技术交流，请勿用于商业用途，出现任何法律责任与翻译者无关

1. 请把项目放在服务器上或本地主机预览。  

然后预览:  
```
http://localhost:端口/src/
http://localhost:端口/src/index.html
http://localhost:端口/src/index.rtl.html
http://localhost:端口/src/material.html
http://localhost:端口/src/#/music/home     
http://localhost:端口/html/index.html
http://localhost:端口/landing/index.html
http://localhost:端口/src/index.html#/app/docs
```

相对路径:  
```
src/                     主要风格UI界面
src/index.html           主要风格UI界面
src/index.rtl.html       反转风格UI界面
src/material.html        工匠风格UI界面
src/#/music/home         音乐平台UI界面
html/index.html          主要风格UI界面 (静态页，只是静态页而已，没用angularjs)
landing/index.html       官方网站UI界面 (静态页)
src/index.html#/app/docs 帮助文档
```

2: 帮助文档位于 "src/tpl/docs.html" 或者 "http://localhost:端口/src/index.html#/app/docs"
在线阅读帮助文档: http://flatfull.com/themes/angulr/angular/#/app/docs


3: 使用 Grunt 和 Bower (Grunt和Bower是前端构建工具，不懂啥是Grunt的，这一环节可以忽略)

安装 node.js
进入的app根目录
```
>npm install -g grunt-cli
>npm install
>bower install
>npm start

>grunt build:angular
```

构建 'angular' 文件夹

4: 目录说明

* grunt     构建配置文件 (这个文件夹里的东西可忽略，不用管它)
* html      静态页面
* landing   官方网站
* libs      支持库 jquery,bootstrap,angular 等
* src       主要、工匠、反转、音乐、帮助等，都在这个文件夹里面
* swig      前端swig源代码 (这个文件夹里的东西可忽略，不用管它)