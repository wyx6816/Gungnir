Gungnir
=======

###简介
代理线上文件到本地(fiddler,支持代理整个目录以及自动下载线上文件),代码编辑器,web服务器.  
请求日记,重写response等更多功能将在目前功能稳定后开始开发.

###下载
[v0.2.6.0版本](http://7ktooc.com1.z0.glb.clouddn.com/gungnir.zip)



###帮助文档

[简易教程](http://benq.im/2015/04/17/gungnir-01/)  

1. 当web服务器使用   
2. 调试线上文件  
3. 使用已存在的本地文件  
4. 代理整个目录   
5. 模拟接口
6. 代码编辑器


###CHANGELOG   
v0.2.2.0  

1. NETWORK完善  
2. bug修复

v0.2.6.0

1. 代码编辑器样式可选择.
2. 优化自动更新
3. bug修复
4. codemirror更行到5.7版

v0.2.0.0  

1. 增加多窗口的支持
2. 增加http代理日记模块.
3. 修复一大堆bug.

v0.1.8.6   

1. 重写代理模块,提高速度,减少出错概率.
2. 被设置了代理的文件,图片将显示为一个地球以区分普通本地文件

v0.1.8.5  

1. 支持coffeescript和markdown语法提示
2. 增加快捷键:Ctrl+W关闭窗口,Ctrl+Tab循环切换编辑页

v0.1.8.2  

1. 因为拖动目录打开来打开项目的方式比较不符合大众口味,所以增加了打开项目的按钮.  

v0.1.8.1  

1. bug修复 
 
v0.1.8.0  

1. 添加代理时,可以勾选"返回代码执行结果",则服务端会把所有文本当做一个js函数执行,并返回执行结果.函数签名为:function(query){},其中query为url参数对象.  
2. 目录工具条上增加"打开控制台"的按钮.  
3. 修复url参数不能识别大小写的bug.

v0.1.7.1  

1 修复自动bug  
  
v0.1.7.0  

1. 添加简单的SSI功能(目前只实现include语法).
2. 修复codemirror自带的文件拖动功能导致的编辑器重复加载文本的bug.
3. 其他bug修复
  
v0.1.6.0  

1. 语法分析,提示功能现在使用独立的worker进程来实现,使UI界面更流畅.
2. 可以直接添加非工作目录内的独立代理设置项,文件树上与workspace同级显示,并使用特别的图标来区分.  


v0.1.5.4  

1. 拖动文件到编辑器,可以直接编辑文件.  
2. 完善adv.js的语法提示   

v0.1.5.3 2014-11-20 16:08:24  

1. 语法提示改为按"."即弹出,而不用按Ctrl+".". 

v0.1.5.2 2014-11-20 12:41:27  

1. 编辑器增加广告开发框架(adv.js)的语法提示,这是公司内部的广告开发框架.后面会做成可选,现在先做强制了.  

v0.1.5.1 2014-11-20 12:41:27  

1. 编辑器增加jquery和浏览器自带对象的语法提示  

v0.1.5.0 2014-11-19 17:59:37  

1. 编辑器增加ecma5语法提示  
Ctrl+. 显示语法提示  
Ctrl+I 显示变量类型说明  
Alt +. 跳转到定义,如果不存在,则显示变量查找框  
Ctrl+Q 修改变量名  

v0.1.4.1 2014-11-18 17:32:24  


1. 改为手动点击才检查更新. 

v0.1.4.0 2014-11-18 16:46:39  
  
1. 打开软件时,如果有新版本,会提示自动更新.如果要关掉此功能,请修改package.json里的autoupdate为false

v0.1.3.1 2014-11-18 10:38:55  

bug修复  

1. 切换标签页后保存路径错误的严重bug.  
2. 切换标签页不会自动获得焦点


v0.1.3.0 2014-11-17 16:47:18     

1. 代码编辑器变成多tab页.

v0.1.2.2 2014-11-17 11:50:17     

1. bug修复.
2. 可以拖动树节点来移动文件位置. 


v0.1.2.1 2014-11-13 12:45:40   

1. bug修复.
2. 程序路径包含特殊字符串时代理无法生效的bug
3. 更新树改为局部更新. 


v0.1.2.0 2014-11-13 12:45:40   

1. 文件管理器

v0.1.1.4 2014-11-12 18:08:54 

1. bug修复
2. 简单的展示图片文件


v0.1.1.3 2014-11-11 16:57:03 

1. bug修复

v0.1.1.2   2014-11-11 15:42:46  

1. 代码编辑器增加Emmett(zencoding)支持,快捷键ctrl+E. 
2. bug修复


v0.1.1.1   2014-11-11 15:42:49  

1. bug修复.  
2. 可以移除代理设置  



v0.1.1.0   

1. 可以代理整个目录.  
2. 未配置代理的文件或者目录,预览时将使用本机ip打开  



v0.1.0.1 2014-11-10 14:43:05   

1. 不可识别的后缀名,默认为文本.  
2. 拖动文件夹的操作,改为整个软件界面都可识别.



v0.1.0.0 2014-11-7 14:42:18  

1. 第一个可用版本