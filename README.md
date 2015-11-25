# premotedroid
Automatically exported from code.google.com/p/premotedroid

Use your phone as a remote control device (like GMote) for your computer over Wifi and Bluetooth !

Main features :

（1）Bluetooth and Wifi connections；

（2）Mouse and keyboard control；

（3）File explorer；

（4）Screen capture；

（5）Secure (password) connection；

# 特别提醒 <br>
Android client端仍旧没有画面，只是可以操控远程电脑的键盘、鼠标。<br>
在编译server端时，需要PRemoteDroid Protocol、PRemoteDroid Server、launch4j（开源，可自行下载最新版）这三个工程同时导入。<br>
导入以后，会出现错误，Unbound classpath container: 'JRE System Library [JavaSE-1.6]' in project ****。解决办法：（1）先去修改.classpath 文件（我的是JDK1.7）；（2）然后继续接下来的http://blog.csdn.net/songshimvp1/article/details/50038381    <br>
编译成功后，server设定密码，client新建connect。
