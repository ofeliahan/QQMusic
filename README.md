# Vue仿制移动端QQ音乐

### 技术栈

 - vue
 - vue-router
 - vuex
 - jsonp
 - audio
 - flex
 - mint-ui

### 实现的功能

- [x] 推荐歌单页、电台、歌手、搜素页面
- [x] 线上抓取100名歌手信息
- [x] 编写播放器组件（包括前进、后退、上一首、下一首、播放暂停等功能）
- [x] 全页面播放（随机播放、顺序播放、单曲循环等模式切换）
- [x] 搜索页面下拉获取更多数据
- [x] localStorage存储用户播放历史和喜欢歌曲
- [x] 加载loading
- [x] 数据全是通过线上抓取
<br/>



### 项目目录结构

api存放获取后端数据的js;  
assets主要存放静态的img、js、font、css等  
components主要存放公用组件  
page主要存放路由跳转的组件  
router存放路由  
store存放状态管理  
App.vue是项目根组件  
min.js是项目入口文件  
<br/>

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
<br/>



