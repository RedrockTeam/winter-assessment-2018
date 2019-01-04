> ### 网校 2018 - 2019 寒假考核

本次的寒假考核旨在以实战的方式，进一步的让大家感受 **Web** 的强大。

考核分为前后端协作的双人作业与单人作业两种形式进行。

考核中所涉及的知识点以及还需掌握的东西会在后面的 **知识勘查** 中提到。

#### 双人作业

请从以下两个项目中二选一，并完成所要求实现的功能。

> 注：本次考核的双人作业中前端统一用 rem 或 vw 单位编写移动端网页，不允许使用任何库和框架，但可以使用 VScode 自带插件或者学习 Gulp / Webpack 进而使用 CSS 预处理器。在功能完成差不多的时候，可以考虑将网页升级为 PWA ，进一步优化网页加载性能。

**微博** 

登录 / 注册页

* 注册
* 登录
* 退出登录
* 统一形式 : 用户名 + 密码

列表信息页

* 搜索
* 信息分类
* 关注
* 收藏
* 下滑 / 点击刷新按钮  =>  更新列表信息

详情信息页

* 图片、文字数据的展示

* 点赞 / 取消点赞
* 发表评论 / 回复评论
  * 发送表情
  * 发送图片

个人信息页

* 关注、粉丝数
* 发微博 / 显示已发微博
* 能够上传头像、修改昵称与个人简介

**网易云音乐**

登录 / 注册页

- 注册
- 登录
- 退出登录
- 统一形式 : 用户名 + 密码

首页

* 搜索 ( 歌曲、歌手、专辑 )
* 日推轮播
* 推荐歌单 / 歌手 / 专辑

歌手详情页

* 单曲显示
  * 点击播放
  * 加入歌单
  * 查看专辑

* 专辑显示
* 歌手简介

音乐播放页
* 播放 / 暂停
* 切换歌曲
* 单曲循环 / 顺序播放 / 随机播放
* 时间进度条显示 / 可拖拽更改进度
* 弹幕显示 / 发送弹幕
* 歌词跟进

#### 单人作业

> **前端**

**瀑布流布局**  

* HTML 文件中的 body 标签中不允许写任何标签，整个瀑布流布局用纯 JS 实现。

* 实现响应式的瀑布流布局，即用鼠标拖拽改变浏览器页面大小的同时一行存放的图片数量会跟着改变。
* 给你的瀑布流实现懒加载，且图片进入时要有 CSS3 渐变效果。

大致样式如下：

![](https://s1.ax1x.com/2018/11/04/i5oKOS.png) 

**切图**

* 依照 2018 迎新网 PC 端首页来切图。
* 实现首页中所有的动效和功能。
  * 各种 CSS3 动效
  * 开学倒计时
  * 返回顶部
  * 地图查找、缩放

**静态资源服务器**  

* 学习 Node.js 
* 用原生 Node 搭建一个静态资源服务器
* 用该服务器展示前面瀑布流、切图所写的 HTML、CSS、JS、IMG 等文件

#### 知识勘查 

> **前端** 

**CSS 基础** 

* CSS 居中与基础布局

* Flex、Grid 布局

* CSS3 过渡及动画

* CSS Houdini 

* CSS 工作流

  * PostCSS

  * Sass / Less / Stylus

**JS 基础**

* 基本类型与引用类型
* 原型与原型链
* 闭包
* 执行上下文与函数执行栈
* 对象的深浅拷贝
* 函数的防抖、节流
* this 指向
* new 的实现
* call，apply，bind 的区别及实现
* 模块化机制
* **ES6 + ** 

**安全** 

- 理解 XSS、CSRF 攻击，如何防范？
- 理解 CSP 
- 考虑密码安全
  - 加盐
  - 加密算法 ( 信息摘要、对称加密、非对称加密 )
- 登录态验证
  - Cookie
  - Session
  - JWT

**浏览器** 

* 理解跨域
  * JSONP
  * CORS
  * Proxy
* 存储
  * localStorage
  * sessionStorage
  * cacheStorage
  * Service Worker
* 理解浏览器渲染机制
  * 页面渲染的几个步骤
  * 重绘 ( Repaint ) 与回流 ( Reflow )
* 理解事件机制
  * 事件捕获与冒泡
  * 事件代理
* 理解 Event Loop 机制
  * 浏览器中的 Event Loop
  * JS 中的异步编程

**性能优化** 

* 浏览器缓存机制
* prefetch、preload、prerender 标签
* 懒加载、懒执行
* `requestAnimationFrame` 与 `document.createDocumentFragment()` 
* 图片优化、开启 HTTP gzip 压缩、CDN 加速

**编程范式** 

- 命令式编程
- 函数式编程
  - 函数的递归与迭代
  - 函数组合与柯里化
  - 高阶函数与纯函数
- 面向对象编程
  - 如何在 JS 中实现封装、继承、多态
  - **GoF** 23 种设计模式在 JS 中的应用

