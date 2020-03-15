# 少女前线自用版

CSS样式表做了小幅修改


少女前线自用版API，**CDN已配置**，**接口未配置**，不可直接调用请下载到本地使用


1. `autoload.js` 中的 `apiPath: "https://你的API接口/"` 为live2d API接口，下载本项目的 **live2d_api** 目录到你的服务器，修改此地址即可（不使用CDN的请下载完整版）


2. `autoload.js` 中的 `cdnPath: "https://fogforest.cn-sh2.ufileos.com/BLOG/live2d_api/"` 为CDN接口，如果你使用我的CDN则不需要修改，如果你 **使用完整版且不使用CDN** 请务必注释掉此行。


注意 **跨域访问** 的问题 `Access-Control-Allow-Origin *;`