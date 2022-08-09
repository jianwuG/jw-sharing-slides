# 前端分享

> 使用 [nodeppt@1](https://www.npmjs.com/package/nodeppt/v/1.4.5) 实时将 markdown 文件转为可在线浏览的 slide

## 快速上手

安装依赖

```shell
yarn install
```

启动服务

```shell
yarn start
```

## 目录说明

```
├── slides
│   ├── images  // 图片资源
│   │   └── {yyyymmdd}  // 每次分享的图片独立使用一个目录存放，命名规则为分享日期的字符串
│   ├── styles  // CSS 样式文件
│   ├── {yyyymmdd-topic}.md  // 每次分享的 markdown 文件
├── package.json
├── README.md
```

## 语法

大部分语法遵循 [Markdown 语法](https://www.markdown.xyz/basic-syntax/)，页面及一些特效可以参考 [nodeppt@1](https://www.npmjs.com/package/nodeppt/v/1.4.5) 的语法。

> 注意：没有采用 nodeppt@2 的原因是因为 2 不支持 workspace 级别启动，这样无法把内容线上化。
