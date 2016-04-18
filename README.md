1. 下载安装：<br>
Brackets是Adobe公司开发的HTML/CSS/JavaScript 集成开发环境，下载地址：<br>
http://www.oschina.net/news/67118/adobe-brackets-1-5<br><br>


2.安装插件：<br>
安装好直接打开项目所在文件夹即可查看文件，调试nodejs代码需要安装插件：<br>
点击窗口右侧第二个按钮，打开扩展应用插件管理窗口：<br>

搜索Node.js Debugger插件，点击install进行安装。由于网络等原因可能出现安装失败的提示，没关系，重新再点击install安装。<br><br>

3.调试方法：<br>
（1）用Brackets打开js文件，然后点击Ctrl+Shift+I打开调试界面；<br>
（2）命令行运行js，需要用调试模式的命令，如下：<br><br>

这样就启动了brackets的调试端口，并启动了js的应用端口；<br>
（3）建立调试连接，点击界面调试窗口中的红色叉小按钮：<br>
点击后<br>
（4）打断点调试，点击行号可添加或删除断点。程序运行到断点处自动暂停，手动复制代码或变量名到调试窗口的输入框，可以查看当前值和状态。调试快捷键与chrome开发者工具相同，F10下一步，F11进入函数等。<br>

详细内容可参见：<br>
https://github.com/TheBenji/brackets-node-debugger<br>



模拟测试可以用Postman工具：（Google应用）<br>

左上角可以选择不同的连接发送模式，下面可输入需要发送时传递的参数，点击Send按钮可以查看到界面下方的结果内容。<br>
