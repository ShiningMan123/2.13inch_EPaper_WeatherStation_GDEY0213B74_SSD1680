# 2.13inch_EPaper_WeatherStation_GDEY0213B74_SSD1680_GOODDISPLAY_PopularItem

Using 2.13 inch E-paper from GoodDisplay GDEY0213B74 250x122 SSD1680 for a simple, easy use EPD Weather Station (in the demo we used a Chinese API but later on you can change it into any other you like.)

### Product Page
https://www.good-display.com/product/391.html


该项目基于arduinoIDE开发的，所使用的的库有：Adafruit-GFX、ArduinoJson、GxEPD，请自行的在IDE中安装以上相关的库
This project is developed based on arduinoIDE, and the libraries used are: Adafruit-GFX, ArduinoJson, GxEPD, please install the above related libraries.

## 代码修改 Editing the code


![image](https://user-images.githubusercontent.com/122499079/236391669-9aeaf579-1c7a-4309-99c9-38bd1a4b2717.png)

![image](https://user-images.githubusercontent.com/122499079/236391686-b60061f1-7b71-4c48-b193-f3033ce4cdf4.png)



## 私钥和城市代号获取 Obtain private key and city code


First enter the official website: https://www.seniverse.com/



## 免费申请 Apply for free


![image](https://user-images.githubusercontent.com/122499079/236391769-9fe07430-ff9c-4c38-81b6-f333232fea05.png)
![image](https://user-images.githubusercontent.com/122499079/236391825-ea39a44f-0617-4e13-a3ed-61da19466804.png)


申请好API之后，就要去检验一下自己的API接口了，在浏览器中输入https://api.seniverse.com/v3/weather/now.json？key=自己API接口的私钥&location=chengdu&language=zh-Hans&unit=c 
<br>
如下图可以直接通过浏览器来访问自己的API接口。以下是访问我们这边的城市的，如果亲想换成自己的城市可自行下载城市代号列表:城市代号下载

After applying for the API, it is time to check the API interface. 
Enter: 
https://api.seniverse.com/v3/weather/now.json？key=自己API接口的私钥&location=chengdu&language=zh-Hans&unit=c
<br>
As shown in the figure below, you can directly access your own API interface through a browser.
The following are the cities that visit our side. If you want to change to your own city, you can download the list of city codes:


### City Code:
https://docs.seniverse.com/api/start/start.html

![image](https://user-images.githubusercontent.com/122499079/236391859-a35fb6a1-85fd-4aa4-a893-a2e36a643557.png)
<br>
<br>
<br>
![759e9f87045b43f4c1c2f9036e16d82](https://user-images.githubusercontent.com/122499079/236392041-88bfcbe8-a7b5-46fa-8cb2-76cede6af0b9.jpg)
<br>

![image](https://user-images.githubusercontent.com/122499079/236396029-bdf0a445-bcdb-4c94-8060-bac8f5fd40fe.png)
<br>
<br>


### About Author
![shiningman](https://user-images.githubusercontent.com/122499079/236393795-482e1327-a77e-4e5f-9617-cb56452ed535.jpg)
Feel free to contact:
https://twitter.com/iluvsuaoni
or mailto:zh@good-display.com

<br>

