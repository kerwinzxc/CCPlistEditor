CCPlistEditor
=============

Edit plist file on windows (with .net framework4.0)
---------------------------------------------------

plist文件在ios和mac开发中用的很多，在xcode中编辑也很方便。但是如果同一个团队有人使用windows又是负责提供配置参数的比较麻烦，找了一圈也没有很好的编辑工具。所以就只能自己动手。  
  
###功能特点：  
支持array，dictionary，datetime，bool，string，number类型，不支持data
所见即所得
支持快捷键和鼠标拖动
Free for all!


###使用方法：  
Alt+A 添加array   
Alt+B 添加bool  
Alt+D 添加dictionary  
Alt+N 添加number  
Alt+S 添加string  
Alt+T 添加datetome  
只会添加到选中节点的子节点中，如果没有选中，添加到第一层。实际上有一个默认隐藏的根节点的。  

有问题或者bug可以联系weibo.com/ccimage  

特别感谢  
使用了TreeViewAdv控件，确实比较好用。[代码库地址](http://sourceforge.net/projects/treeviewadv/)  
