Live2D 看板娘（少女前线）

详细说明：[给你的网站添加一个萌萌哒的Live2D看板娘](https://fairysen.com/287.html)


### 默认
1. 下载项目代码，将 `live2d_default` 放到你的站点根目录，`waifu-tips.json` 中为触发内容可以修改，最后引用 `autoload.js` 即可，一般放到 `footer.php` 的 `</body>` 标签之前：
```HTML
<script src="/live2d_load/autoload.js"></script>
```

### 少女前线
1. 下载项目代码，除了 `live2d_default` 将其他目录放到你的站点根目录，`waifu-tips.json` 中为触发内容可以修改

2. `live2d/model_list.json` 和 `live2d/model` 为加载的模型列表，可以自己精简

3. 然后在你主题的 `footer.php` 文件 `</body>` 标签之前引用即可
```HTML
<script src="/live2d_girls/autoload.js"></script>
```

4. 如果你要修改更多请查看下面引用的前两个项目的说明文档


### 补充
`autoload.js` 中的 `apiPath:` 为 live2d API 接口，默认即可，如果你有其他的也可以修改
`autoload.js` 中的 `cdnPath:` 为对象存储路径，注意跨域的问题，不使用请注释掉
Json配置(SDK 2)：<http://live2d.pavostudio.com/doc/zh-cn/live2d/model-config/>


### 引用
[Live2D API](https://github.com/fghrsh/live2d_api)

[Live2D Widget](https://github.com/stevenjoezhang/live2d-widget)