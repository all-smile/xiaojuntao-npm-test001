> 这是我发布的第一个npm

## 安装

```bash
npm install xiaojuntao-npm-test001 -S

or

yarn add xiaojuntao-npm-test001
```

## 使用

```js
var test_npm = require('xiaojuntao-npm-test001');
console.log(test_npm)
```

## 更新npm包

```bash
npm version patch
npm publish
```

## 添加 dist-tag 指定稳定版本 stable

```
npm dist-tag add yourpackagename@1.0.2 stable

+stable: yourpackagename@1.0.2
```

## notes

[👉创建发布包流程](https://juejin.cn/post/7123082252614893575)