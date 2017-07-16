# iot2017
### Wk1
	1-1 下載安裝工具程式(mono)與Hello World 測試
	1-2 常用指令
	編譯 
	mcs xxx.cs   or mcs xxx.cs -pkg:dotnet
	執行
	mono xxx.exe

	螢幕複製
	cmd+shift+3
	文字複製
	cmd+c
	貼上
	cmd+v
	1-3 C# Basic structure
	using System;
	namespace N1
	{
	class C1
	{
		public static void Main()
		{
			Console.WriteLine("Hello");
		}
	}
	}
	1-4 表單應用程式(Hello World)
	1-5 表單控制項(Button)
### Wk2
	2-1 Button 物件
    Button.Click 事件
2-2 迴圈語法 (Console)
2-3 繼承語法
2-4 4 if 語法
### Wk3
3-1. ASP.NET XSP4
http://www.mono-project.com/docs/getting-started/mono-basics/
3-2 ASP.NET 基本型
3-3 RWD 範例
https://www.w3schools.com/css/css_rwd_templates.asp

### Wk4
4-1. Mac 熱點設定

4-2. ASP.NET XSP4
http://www.mono-project.com/docs/getting-started/mono-basics/

4-3 ASP.NET 基本型
https://www.tutorialspoint.com/asp.net/asp.net_quick_guide.htm

4-4 RWD 範例(bootstrap)
https://getbootstrap.com/

### Wk5
5-1. ASP.NET XSP4 (確認 asp.net 問題 1-1 檔案編碼 1-2 缺少套件 1-3 版本問題)
http://www.mono-project.com/docs/getting-started/mono-basics/
ASP.NET 基本型
https://www.tutorialspoint.com/asp.net/asp.net_quick_guide.htm
5-2 RWD 範例(bootstrap)
https://getbootstrap.com/
5-3. Boostrap Image/video 應用
https://www.w3schools.com/bootstrap/bootstrap_images.asp
https://gist.github.com/anam-hossain/7a10734514a9c53d88a8

### Wk6
6-1. Boostrap Image/video 應用
https://www.w3schools.com/bootstrap/bootstrap_images.asp
https://gist.github.com/anam-hossain/7a10734514a9c53d88a8
6-2. Boostrap國小教學網站建置
https://www.youtube.com/channel/UCKYNiDBdbnfMPYwKe4kQH-g
6-3. ASP.NET + Boostrap 整合應用
6-4. 無線熱點手機測試 ASP.NET + Boostrap

### Wk7
7-1. Boostrap SPA 影片網站建置
https://www.w3schools.com/bootstrap/bootstrap_theme_company.asp
https://www.youtube.com/channel/UCKYNiDBdbnfMPYwKe4kQH-g
https://gist.github.com/anam-hossain/7a10734514a9c53d88a8
7-2. ASP.NET + Boostrap + SPA 整合應用
7-3. 無線熱點手機測試 ASP.NET + Boostrap

### Wk8
8-1 下載JDK, EsPlorer, USB 驅動測
https://esp8266.ru/esplorer/ 
https://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx#mac
8-2 摘記NodeMCU主要功能 (WiFi, I/O 數位 類比)
http://www.nodemcu.com/index_cn.html
8-3 Hello World (lua 語法)
https://wotcity.com/blog/2015/08/31/esp8266-nodemcu-iot-starter-part-1/

### Wk9 期中考試

### Wk10
10-1 NodeMCUFile IO
下載JDK, EsPlorer, USB 驅動測
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
https://esp8266.ru/esplorer/
https://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx#mac
 
https://blog.falafel.com/working-with-files-in-nodemcu-on-the-esp8266/
10-2 NodeMCU http
https://wotcity.com/blog/2015/08/31/esp8266-nodemcu-iot-starter-part-2/

10-3 NodeMCU http 程式庫
https://wotcity.com/blog/2015/09/22/esp8266-nodemcu-iot-starter-part-4/

 
### Wk11
電競教室Windows 10環境 建置 Esplorer工作環境
相同網址下載 for Windows 版
0-1 Download and install JDK
0-2 Download USB2UART driver for Winx64 and install
0-3 Download esplorer.zip 解壓縮
Mobile web server
 RWD 8266
1-1 Direct init.lua
1-2 IO 
1-3 C# 

### Wk12
12-1 lua 基本語法
http://yhhuang1966.blogspot.tw/2015/07/lua_14.html
I/O print
+ (加) - (減) * (乘) / (除) % (餘數) ^ (次方) - (單元運算, 負數), 
Lua 的判斷式語法
if
for/while 
 
function
scope name(arguments)
    body
    return values
end

12-2 NodeMCUFile IO
https://blog.falafel.com/working-with-files-in-nodemcu-on-the-esp8266/
https://www.tutorialspoint.com/lua/lua_file_io.htm
http://stackoverflow.com/questions/5094417/how-do-i-read-until-the-end-of-file
12-3 Create and close Server
https://wotcity.com/blog/2015/08/31/esp8266-nodemcu-iot-starter-part-2/
https://nodemcu.readthedocs.io/en/master/en/modules/net/#netserverclose
-- creates a server
sv = net.createServer(net.TCP, 30)
-- closes the server
sv:close()

### Wk13
13-1 NodeMCUFile IO
https://blog.falafel.com/working-with-files-in-nodemcu-on-the-esp8266/
https://www.tutorialspoint.com/lua/lua_file_io.htm
http://stackoverflow.com/questions/5094417/how-do-i-read-until-the-end-of-file
確認上週init.lua

13-2 Create and close Server
https://wotcity.com/blog/2015/08/31/esp8266-nodemcu-iot-starter-part-2/
https://nodemcu.readthedocs.io/en/master/en/modules/net/#netserverclose
-- creates a server
sv = net.createServer(net.TCP, 30)
-- closes the server
sv:close()


13-3 Jumbotron(bootstrap)

### Wk14
14-1 NodeMCUFile IO http
https://blog.falafel.com/working-with-files-in-nodemcu-on-the-esp8266/
https://www.tutorialspoint.com/lua/lua_file_io.htm
http://stackoverflow.com/questions/5094417/how-do-i-read-until-the-end-of-file

14-2 Create RWD video  (Wk7)
 
14-3 mono C# RWD ⇒ Nodemcu

### Wk15
15-1 Revise RWD video  (Wk7)

Download mono
Download VS Code
Revise RW video
Mat.html test
15-1-2 jQuery Test
15-1-3. bootstrap test

15-2 To implement Video RW into nodemcu by File IO.

15-3 To implement Video RW into nodemcu by R/W of C#.


### Wk16
16-1 To implement Video RW into nodemcu by R/W of C#.
16-2 多頁Nodemcu網頁程式(由簡入繁)。
https://wotcity.com/blog/2015/09/01/esp8266-nodemcu-iot-starter-part-3/
16-3 Wk7 多頁網頁建置(Nodemcu)

### Wk17
17-1 nodemcu app/ wifi-car
https://smartarduino.gitbooks.io/user-manual-for-wifi-car-by-nodemcu-doitcar-/content/

17-2 各週課程要點整理與討論
