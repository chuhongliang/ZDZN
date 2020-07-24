# ZDZN-专业开发者导航
ZDZN导航是国内最专业的技术导航网,收录了大量的前端,后台,移动端,服务器,数据库等开发者常用网.ZDZN旨在为广大开发者提供专业的技术网址导航,方便开发者平时日常工作;并为不同阶段的开发者学习进阶提供一定的引导作用.

主页: [https://zdzn.net](https://zdzn.net)

邮箱: [chl01003698@126.com]()

## 添加指南

### 1. 复制代码库
通过 Fork 代码库或直接通过 [Propose new file](https://github.com/chuhongliang/ZDZN/new/master) 创建文件。

### 2. 添加导航链接
链接数量必须小于或等于 7 个，链接名称少于 7 个汉字或其等宽字符。

参考 [website/javascript.js](https://github.com/chuhongliang/ZDZN/website/javascript.js) 的格式添加链接。

```javascript
const websiteList = {
  "classify": "Javascript",
  "link": [
    {
      "name": "MDN文档",
      "url": "https://developer.mozilla.org/zh-CN/"
    },
    {
      "name": "ES6教程",
      "url": "https://es6.ruanyifeng.com/"
    },
    {
      "name": "Vue.js",
      "url": "https://cn.vuejs.org/"
    },
  ]
}
```

### 3. 提交代码
通过 Pull request 或 [Propose new file](https://github.com/chuhongliang/ZDZN/new/master) 提交代码。