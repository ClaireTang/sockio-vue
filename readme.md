
## 用socket.io实现页面数据及时更新

#### 1.  查看效果：
    cd 项目根目录；
    node trends.js： 
    用浏览器打开 根目录/publick/index.html页面，等待10s，数字更改，
    更改 根目录/data/两个json文件的值，
    再次查看index.html页面的变化
#### 2.  文件目录介绍：
    trends.js：服务端代码
    data/json：模拟数据
    publick/.html： 客户端页面
    
    