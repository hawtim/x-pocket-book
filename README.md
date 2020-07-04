# x-pocket-book

简易记账本

`Refer`: [XMind 前端面试大作业 - 1](https://github.com/xmindltd/hiring/blob/master/frontend-1/README.md)

`Notes`: [解决本题目时的思考文档](https://github.com/hawtim/x-pocket-book/blob/master/POINT.md)

`Deploy`: [线上链接](https://pocket.hawtim.com/), 建议桌面模式查看，移动端做了适当的调整，也可操作。

`Environment`: 开发环境为 mac / windows , node 版本为 v12.13.1，理论上 node@8.x 即可支持，按照 `package-lock.json` 安装依赖即可。

`Compatible`: 页面兼容性 IE9+ 及其他现代浏览器，取决于 VueJS 的兼容性。

以上任何问题，欢迎 issues。

## Basic requirement

1. 加载我们所提供的数据；
2. 以列表的形式展示账单内容，并且提供下拉框选择月份进行筛选，其中列表中所展示的账单为选择月份的账单；
3. 支持使用者添加账单；
4. 简单地统计并展示所选月份的收入和支出总金额。

## Advance requirement

1. 对账单分类进行二次筛选；
2. 对选择月份内的所有账单根据账单分类进行支出金额统计，并进行排序。

## For remote

写一篇[简单的文档](https://github.com/hawtim/x-pocket-book/blob/master/POINT.md)来描述你对解决本题目时的思考过程，并对其中所遇到的问题和你的解决方案进行描述。

## Build with

VueJS, ElementUI, Vuex, Vue-Router, Dayjs, v-chart

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

### Webpack bundle analysis
```
npm run analyzer
```
