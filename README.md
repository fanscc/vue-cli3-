# vue-skeleton

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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

注意，作为模板的html文件，需要在被写入内容的位置添加<!--vue-ssr-outlet-->占位符，本例子在div#root里写入：

<div id="root">
 <!--vue-ssr-outlet-->
</div>