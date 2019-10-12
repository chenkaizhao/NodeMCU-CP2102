#配置NodeMCU 
----
ESP8266是一款高度集成的芯片，旨在满足新的互联世界的需求。它提供了一个完整且自包含的Wi-Fi网络解决方案，允许它托管应用程序或从另一个应用程序处理器卸载所有Wi-Fi网络功能。

----

##使用说明和步骤：

1.下载最新版本的Arduino IDE。

2.安装IDE。

3.将Arduino IDE设置为：转到“文件”->“首选项”，复制以下URL以获取ESP板管理器扩展：http://arduino.esp8266.com/stable/package_esp8266com_index.json在URL允许Arduino IDE使用它之前使用http：// ...否则会给一个协议错误。

4.转到工具>板>板管理器>键入“ esp8266”并下载社区esp8266并安装。

5.将芯片设置为：
工具->板-> NodeMCU 1.0（ESP-12E模块）
工具->闪存大小-> 4M（3M SPIFFS）
工具-> CPU频率-> 80 Mhz
工具->上传速度-> 921600
工具->端口->（无论什么）

6.在Github下载并运行32位flasher exe（在Github上搜索nodemcu / nodemcu-flasher / tree / master /）github.com/nodemcu/nodemcu- flasher / tree / master / Win32 / Release或在以下位置下载并运行64位flasher exe：github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release

7.在Arduino IDE中，寻找老式的Blink程序。加载，编译和上传。

8.转到文件>示例> ESP8266>闪烁，它将开始闪烁。
