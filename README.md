# fed-nav
A chrome插件 🚀🚀🚀

做了一个前端的网站导航插件，可检索，可搜索。希望帮助大家在学习上有一些便利。

<img src='http://7xw3j4.com1.z0.glb.clouddn.com/QQ20160803-0@2x.png' width=300/>

<img src='http://7xw3j4.com1.z0.glb.clouddn.com/QQ20160803-1@2x.png' width=300/>



###使用方法：

1,fork  https://github.com/Pearyman/chrome_plugin;

2, download 此项目或者 git clone https://github.com/Pearyman/chrome_plugin.git；

3, 进入chrome浏览器的拓展程序页面（你也可以打开chrome浏览器 ，在地址栏上输入 chrome://extensions/）；

4, 将文件夹中的fed_nav.crx 拖进去即可。


[谷歌商店传送门](https://chrome.google.com/webstore/detail/%E5%89%8D%E7%AB%AF%E5%AF%BC%E8%88%AA/kimhkkondjpjhnllknndckjppgbjnjai?hl=zh-CN)

项目wiki:[https://github.com/Pearyman/chrome_plugin/wiki/%E6%AC%A2%E8%BF%8Efork%E5%B9%B6%E8%B4%A1%E7%8C%AE%E7%BD%91%E7%AB%99%E6%95%B0%E6%8D%AE%E3%80%82](https://github.com/Pearyman/chrome_plugin/wiki/%E6%AC%A2%E8%BF%8Efork%E5%B9%B6%E8%B4%A1%E7%8C%AE%E7%BD%91%E7%AB%99%E6%95%B0%E6%8D%AE%E3%80%82)



### 提交数据的方式

1 本数据根据人工进行了a-z的区分，所以需要你来区分一下对应name位置。

  比如：慕课网--M; W3c--W; 数字或者特殊字符--jing。

```
            {
                "name": "365psd",  //必填
                "url": "http://365psd.com/",  //必填
                "des": "兢兢业业每天更新着用户界面相关的PSD",  //选填
                "tags": [
                    "界面设计"   //必填，至少一个
                ]
            }

```

2， 新建一个issue，在issue中填上数据即可。
