# websocket
html5+php


使用方法
1、解压文件至本地目录，如D:\www\websocket  这里我是放在了Apache服务器的文件目录下
2、运行脚本run.bat
3、浏览器地址栏打开  http://127.0.0.1/websocket/wobsocket.html
4、可以看到效果
5、如果没有反应，请用F12  调试，查看原因。如果是火狐浏览器请确保打开了有关的websocket配置
6、php需要打开websocket的配置，在php安装目录下的php.ini
extension=php_sockets.dll
找到这句话，去掉前面的;
保存，重启apache服务器生效，可以使用run.bat
