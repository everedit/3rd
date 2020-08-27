# 关于
![](http://www.everedit.cn/frontend/everedit/imgs/logo.png)
* [EverEdit](http://www.everedit.cn)是一款专注于纯文本编辑的软件，身躯小巧、性能强劲，同时也具有不错的扩展性
* [下载最新版EverEdit](http://www.everedit.cn/download)
* [购买支持](http://www.everedit.cn/buy)

# 须知

* 此处收集第三方提供的各种主题、脚本、模式、语法着色等打包文件
* 用户按照需求到各个分类文件夹内，自行找寻符合自己需求的文件
* 各打包文件的版权归第三方所有
* 用户自行对安装文件的安全性进行检查，EverEdit不负责任因第三方扩展造成的数据损坏、丢失等责任

# 如何制作

用户在日常使用中所创建的各种着色文件、主题、脚本，甚至自定义工具都可以打包为一个后缀.ezip的文件，其它用户只需要把这个文件拖放进EverEdit就可以安装并使用了。用户在打包的过程中需要注意路径的规范，如下所示。

```
abc.ezip
|--syntax
|----|--abc.mac
|--package
|----|--abc.pkg
```

上述abc.ezip直接包含了syntax和package目录, 其内又分别包含了.mac和.pkg。EverEdit会直接把上述压缩包内的文件放到安装目录，用户重启EE之后就可以使用了。

# 各目录意义

* theme: 主题
* script: 各种脚本
* mode: 模式
* syntax: 着色(通常应包括.mac/.pkg以及相关的模板和snippet/calltip等)
* tool: 自定义工具
* misc: 杂项

注意，上述目录是指在本git内的各目录所存放的文件，并不是EverEdit内的各目录。第三方贡献者在上传文件时，请把打包好的文件按照分类push到上述目录。

# 其它

对于优秀的第三方扩展，在征得原作者同意下，将会集成到官方的扩展管理器中！
