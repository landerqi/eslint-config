# npm

## eslint-config
## babel-preset

## 安装

```bash
# eslint-config
# for js
yarn add -D eslint @landerqi/eslint-config-js
# for vue
yarn add -D eslint @landerqi/eslint-config-vue
# for react
yarn add -D eslint @landerqi/eslint-config-react
# for ts
yarn add -D eslint @landerqi/eslint-config-ts
# for ts-vue
yarn add -D eslint @landerqi/eslint-config-ts-vue

# babel-preset
# for js
yarn add -D @landerqi/babel-preset-js
# for vue
yarn add -D @landerqi/babel-preset-vue
```

## 使用

> package.json 中添加

```js
  // eslint-config
  "eslintConfig": {
    "extends": [
      "@landerqi/js"
    ]
  },

  // babel-preset
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
