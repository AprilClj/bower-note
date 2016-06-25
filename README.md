## Bower 概念

>Bower是一个客户端技术的软件包管理器，它可用于搜索、安装和卸载
如JavaScript、HTML、CSS之类的网络资源，方便包文件以及包之间依赖的更新操作
解决项目中因更新不及时而造成的各种问题。

## 准备工作

- Node环境
- NPM
- Git　从git仓库获取一些代码包

## 全局安装Bower

npm install -g bower 

## Bower init

在应用程序的根目录下创建一个名为“bower.json”的文件，并定义它的依赖关系。

## Bower　常用命令

### bower install 

安装包使用 bower install <package>　命令
所有的安装包文件放在bower_components/目录下

- bower install 安装bower.json中的项目依赖

- bower install <package> --save 安装包文件并写入bower.json的依赖项中

- bower install bootstrap 安装已经注册的包文件

- bower install <package>#<version> --save 安装某个指定版本的包文件并写入bower.json的依赖项中

- bower install desandro/masonry 安装Github上的简明地址中的文件

  https://github.com/desandro/masonry/archive/v4.1.0.tar.gz

- bower install git://github.com/user/package.git 　从git　endpoint 完整地址上安装

- bower install http://example.com/script.js 从制定的URL上下载安装包文件


#### bower cache　缓存管理

#### bower help 显示Bower命令的帮助信息

#### bower home 通过浏览器打开一个包的github发布页

#### bower info 查看包的信息

#### bower init　创建bower.json文件

#### bower install　安装包到项目
#### bower link　在本地bower库建立一个项目链接

#### bower list　列举项目已安装的包

#### bower login　获得github的认证并存储凭据

#### bower lookup　根据包名查询包的URL

#### bower prune 删除项目无关的包

#### bower register　注册一个包

#### bower search　搜索包

#### bower update　更新项目的包

### bower uninstall　删除项目的包

### bower version　



## 注意事项

1.prezto and oh-my-zsh 用户　需要给bower取个别名　bower='noglob bower'

或者在安装时在路径上增加'\' 如:　bower install jquery\#1.9.1

2.Bower 是一个普通用户命令　因此无需使用超级管理员权限sudo关键字进行操作

## 相关链接

### Bower homepage https://bower.io/


