# eleme-cube
```
本项目使用vue-cli 3.0、vue 2.0、cube-ui、axios、stylus开发
```

## Vue-cli 3.0
```
与Vue-cli2.0不同，项目目录更加简洁、易懂，所有配置都在vue.config.js
```

### 开发中发现的Vue 2.0与1.0的区别
```
1.0：
  1. <a v-link="adress">
  2. <div v-for="val in arr">
2.0:
  1. <router-link :to="adressName" tag="tagName"></router-link>
  2. <div v-for="val in arr" :key="val.id">
  3. 编写template的时候2.0必须要用一个根元素将代码片段包裹起来，否则会报错
```

### cube-ui
```
cube-ui是由滴滴团队开发的一个库，最开始接触的是better-scroll，better-scroll是由之前滴滴团队的黄轶前辈开发的滚动效果库，蛮好用的，用了这些库之后手写节省了好多代码！
```

### axios
```
axios是一个基于promise的HTTP库，可以用在浏览器和node.js中
npm install axios
```

### stylus
```
一个css插件
```
