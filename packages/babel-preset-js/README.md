# @landerqi/babel-preset-js

## 安装

```bash
yarn add -D @landerqi/babel-preset-js
```

## 使用

> package.json 中添加

```js
  "babel": {
    "presets": [
      ["@landerqi/js", {
        "useBuiltIns": "usage"
      }]
    ]
  },
  "browserslist": [
    "iOS >= 8",
    "Android >= 4.4"
  ]
```
