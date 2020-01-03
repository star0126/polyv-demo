

## POLYV视频上传与播放Demo说明

#### 一、SDK

Polyv JavaScript上传、下载SDK。使用该SDK实现保利威云点播功能。



#### 二、SDK使用前提

（1）开通保利威云点播服务

（2）获取secretKey、writetoken、readtoken等相关信息，该信息在[云点播管理平台-->设置-->API接口]中获取



#### 三、相关网址链接

（1）Polyv管理系统登录页：http://my.polyv.net/v2/login

（2）Polyv云点播H5播放器使用：http://dev.polyv.net/2017/videoproduct/v-playerapi/html5player/html5-docs/

（3）Polyv云点播视频上传：http://dev.polyv.net/2014/videoproduct/v-api/v-api-upload/uploadfile/

（4）Polyv云点播帮助文档首页：http://dev.polyv.net/category/videoproduct/



#### 四、Polyv视频上传

**upload-video.html**

（1）根据帮助文档writetoken、JSONRPC、Filedata为必传参数。

（2）上传视频的接口为

```javascript
http://v.polyv.net/uc/services/rest?method=uploadfile
```



#### 五、Polyv视频播放

**player.html**

（1）需要引入player.polyv.net/script/player.js

```javas
<script src="//player.polyv.net/script/player.js"></script>
```

（2）播放事件

```javascript
var player = polyvPlayer({

});
```

