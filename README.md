 # winqjs是什么
 winqjs是一个很小的js引擎，基于quickjs基础上改造支持微软的visual studio（后文使用vs表述）进行开发、调试。可以认为winqjs就是for msvc,for windows的quickjs。
 目前winqjs基于quickjs的2020年7月05日版本基础上开发。
 
# winqjs有什么用
 使用winqjs，可以动态执行js脚本，甚至可以自定义C语言函数，让js执行你自定义的C语言函数。
 
# 怎么用winqjs
使用winqjs的lib静态库，连接到你的源码工程里面去，就和你的程序合为一体，调用相关函数初始化，必要的时候您可以添加关联您自定义的扩展接口。
 
# 怎么编译winqjs
 安装vs2012或者高于vs2012的版本。
 winqjs源码工程使用vs默认的编译器进行编译，为了支持XP，默认选用了“Visual Studio 2012 - Windows XP (v110_xp)”平台工具集（需要额外安装VS2012平台工具集补丁支持）。
 当然了，如果有需要，您可以修改工程选择其它平台工具集，例如vs2017或者vs2019等等。
 
 有任何问题，加扣扣群：222670733

