# 少女前线自用版

少女前线自用版，CSS样式表做了小幅修改


1. `autoload.js` 中的 `apiPath: "https://你的域名/live2d_api/"` 为live2d API接口，下载本项目的 **live2d_api** 目录到你的服务器，修改此地址即可


2. `autoload.js` 中的 `cdnPath: "https://你的CDN域名/live2d_api/"` 为CDN接口，如果你不使用CDN则不需要修改。


配置CDN注意 **跨域访问** 的问题 `Access-Control-Allow-Origin *;`