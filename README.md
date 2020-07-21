微信小程序文档

```
npm i wechat-docs
```

这个接口通常在开发微信插件时使用

```js
const docs = require('wechat-docs')

console.log(docs.api) // 输出结果如下
```

```

[
  {
    "desc": [
      "视图容器。"
    ],
    "attrs": [
      {
        "name": "hover-class",
        "type": {
          "name": "string"
        },
        "desc": [
          "指定按下去的样式类。当 `hover-class=\"none\"` 时，没有点击态效果"
        ],
        "defaultValue": "none"
      },
      {
        "name": "hover-stop-propagation",
        "type": {
          "name": "boolean"
        },
        "desc": [
          "指定是否阻止本节点的祖先节点出现点击态"
        ],
        "since": "1.5.0",
        "defaultValue": "false"
      },
      {
        "name": "hover-start-time",
        "type": {
          "name": "number"
        },
        "desc": [
          "按住后多久出现点击态，单位毫秒"
        ],
        "defaultValue": "50"
      },
      {
        "name": "hover-stay-time",
        "type": {
          "name": "number"
        },
        "desc": [
          "手指松开后点击态保留时间，单位毫秒"
        ],
        "defaultValue": "400"
      }
    ],
    "tips": [
      "如果需要使用滚动视图，请使用 [scroll-view](https://developers.weixin.qq.com/miniprogram/dev/component/scroll-view.html)"
    ],
    "demoImages": [
      "https://developers.weixin.qq.com/miniprogram/dev/image/pic/view.png"
    ],
    "name": "view",
    "docLink": "https://developers.weixin.qq.com/miniprogram/dev/component/view.html"
  }
  ...
]
```