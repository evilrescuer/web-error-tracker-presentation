# web-error-tracker-presentation
此项目是[前端错误收集器](https://github.com/evilrescuer/web-error-tracker)项目的演示项目

安装 | [测试](./README_demo.md)
#### 引入

* npm包方式
    * `yarn add web-error-tracker`
    * 或者`npm install web-error-tracker`

* 文件引用方式
```
// html
<body>
...
...
...

// body的最后引入
<script src="https://github.com/evilrescuer/web-error-tracker/blob/master/index-file.js"></script>
</body>
```

#### 获取当前收集到到错误
`errorTracker.getErrors()`

