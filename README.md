# 少女前线版
适用于 `Sakura主题` 的 少女前线live2D


使用方法：[给你的网站添加一个萌萌哒的Live2D看板娘](https://m1314.cn/287.html)


1. `autoload.js` 中的 `apiPath: "https://你的API接口/"` 为live2d API接口，下载本项目的 **live2d_api** 目录到你的服务器，修改为对应地址即可。
2. `autoload.js` 中的 `cdnPath: "https://localhost/live2d_api/"` 为CDN接口，如果你使用对象存储存放模型修改为对应地址的即可，否则请务必注释掉此行。


PS：注意 **跨域访问** 的问题 `Access-Control-Allow-Origin *;`


感谢以下开源项目：[fghrsh/live2d_api](https://github.com/fghrsh/live2d_api)，[stevenjoezhang/live2d-widget](https://github.com/stevenjoezhang/live2d-widget)，[TaylorLottner](https://github.com/TaylorLottner)