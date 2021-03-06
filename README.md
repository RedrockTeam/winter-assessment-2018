# 网校 2018 - 2019 寒假考核

> 本次的寒假考核旨在以实战的方式，熟悉Web开发，进一步的让大家感受 **Web** 的强大。
>
> 考核分为前后端协作的**双人作业**与**单人作业**两种形式进行。
>
> 考核中所涉及的知识点以及还需掌握的东西会在后面的 **知识勘查** 中提到。

## 写在前面

- 尽可能的找到队友，做双人作业。首先单人作业比较难，其次跟其他人合作开发项目有助于理解web开发的整体流程
- 选择双人合作作业的同学请**自行寻找队友**，自己主动些去找人私聊。实在找不到请联系你们的导师帮你们找
- **后端的单人作业难度系数会比较高**。如果想挑战自己可以选择单人套作业
- 请在**一月十三日二十四点之前**决定好做哪一个项目并在[云文档](https://docs.qq.com/sheet/DRkVNSW12WFV0ZGdO)上填写相关信息

- 双人作业是为了培养你们的合作能力和从实战提升你们的综合能力
- 本次双人作业全部使用**前后端分离**的形式，后端的接口格式等等要你们自己沟通决定
- **沟通很重要**。请多加沟通
- 禁止互相甩锅
- 如果你觉得你队友坑了你，给你三条路
  1. 自己也一起坑
  2. 自己顶上去做原本他做的事
  3. 写好自己的那部分
- **作业禁止抄袭**，我们会codereview
- 有问题及时联系自己的导师
- 下学期开学你们将要展示自己在寒假完成的作品

## 双人作业

请从以下两个项目中**二选一**，并完成所要求实现的功能。

> 注：
>
> 下面给出的需求和功能也许比较多，尽最大努力去完成，做不完也没关系，能做多少做多少。
>
> 前端：本次作业的双人作业中前端优先考虑做PC端，有能力的尽量兼做移动端的适配。**不允许使用任何库和框架** ，但可以使用Gulp / Webpack 等打包部署工具。在功能完成差不多的时候，可以考虑将网页升级为 PWA ，进一步优化网页加载性能。
>
> 后端：双人作业**禁止使用一切框架**。类库只允许使用`json-lib`、`dbcp`之类的基本的库。完成作业可以考虑使用一些设计模式来让自己的代码更加优雅，但**不要为了使用设计模式而使用设计模式**。

### 微博

[参考传送门](https://weibo.com/)

- 登录 / 注册页

  - 注册
  - 登录（保持登录状态）
  - 退出登录

  tip：登陆方式可以不限于用户名+密码，比如手机号+手机验证码

- 主页

  - 搜索
  - 信息分类
  - 关注
  - 收藏
  - 下滑 / 点击刷新按钮  =>  更新列表信息
  - 发送微博

- 详情信息页

  - 图片、文字数据的展示
  - 点赞 / 取消点赞
  - 发表评论 / 回复评论
    - 发送emoji表情
    - 发送图片

- 个人信息页

  - 关注、粉丝数
  - 发微博 / 显示已发微博
  - 能够上传头像、修改昵称与个人简介

加分项：

- 发送带图片的微博
- 发送带视频的微博
- 微博热门
- 微博热搜
- 后台管理
- 使用https
- 考虑安全性(比如xss、sql注入、csrf)
- 考虑缓存与性能
- 反爬虫
- 部署在自己的云服务器上（HTTP/HTTPS/CDN）

### 网易云音乐

[参考传送门](https://music.163.com/)

- 登录 / 注册页

  - 注册
  - 登录（保持登录状态）
  - 退出登录

  tip：登录方式可以不限于用户名+密码，比如手机号+手机验证码

- 首页

  - 搜索 ( 歌曲、歌手、专辑 )
  - 日推轮播

- 歌手详情页

  - 单曲显示
    - 点击播放
    - 加入歌单
    - 查看专辑
  - 专辑显示
  - 歌手简介

- 音乐播放页

  - 播放 / 暂停
  - 切换歌曲
  - 单曲循环 / 顺序播放 / 随机播放
  - 时间进度条显示 / 可拖拽更改进度
  - 弹幕显示 / 发送弹幕
  - 歌词跟进

加分项：

- 后台管理
- 防止盗链
- 推荐歌单 / 歌手 / 专辑
- 使用https
- 考虑安全性(比如xss、sql注入、csrf)
- 考虑缓存与性能
- 反爬虫
- 部署在自己的云服务器上（HTTP/HTTPS/CDN）

## 单人作业

### 前端

**瀑布流布局**  

- HTML 文件中的 body 标签中不允许写任何标签，整个瀑布流布局用纯 JS 实现。
- 实现响应式的瀑布流布局，即用鼠标拖拽改变浏览器页面大小的同时一行存放的图片数量会跟着改变。
- 给你的瀑布流实现懒加载，且图片进入时要有 CSS3 渐变效果。

大致样式如下：

![](https://s1.ax1x.com/2018/11/04/i5oKOS.png) 

**切图**

- 依照 2018 迎新网 PC 端首页来切图。
- 实现首页中所有的动效和功能。
  - 各种 CSS3 动效
  - 开学倒计时
  - 返回顶部
  - 地图查找、缩放

**静态资源服务器**  

- 学习 Node.js 
- 用原生 Node 搭建一个静态资源服务器
- 用该服务器展示前面瀑布流、切图所写的 HTML、CSS、JS、IMG 等文件

### 后端

**微派桌游助手-谁是卧底**

- 请打开微信，搜索`微派桌游助手`，使用其中的`狼人杀`操作两局看看。
- 你要写的是其中的`狼人杀`这一个模块。

要求：

- 能够创建房间、加入房间
- 可以获得惩罚
- 申请一个微信公众平台测试号，你需要做的是微信开发

tip：

- 注意多个用户同时加入房间的线程安全问题

## 知识勘查

### 前端

**CSS 基础** 

- CSS 居中与基础布局
- Flex、Grid 布局
- CSS3 过渡及动画
- CSS Houdini 
- CSS 工作流
  - PostCSS
  - Sass / Less / Stylus

**JS 基础**

- 基本类型与引用类型
- 原型与原型链
- 闭包
- 执行上下文与函数执行栈
- 对象的深浅拷贝
- 函数的防抖、节流
- 错误与异常的防护处理
- this 指向
- new 的实现
- call，apply，bind 的区别及实现
- 模块化机制
- **ES6 +** 
- canvas

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

- 理解跨域
  - JSONP
  - CORS
  - Proxy
- 存储
  - localStorage
  - sessionStorage
  - cacheStorage
  - Service Worker
- 理解浏览器渲染机制
  - 页面渲染的几个步骤
  - 重绘 ( Repaint ) 与回流 ( Reflow )
- 理解事件机制
  - 事件捕获与冒泡
  - 事件代理
- 理解 Event Loop 机制
  - 浏览器中的 Event Loop
  - JS 中的异步编程

**性能优化** 

- 浏览器缓存机制
- prefetch、preload、prerender 标签
- 懒加载、懒执行
- 图片优化、开启 HTTP gzip 压缩、CDN 加速
- 首屏渲染

**编程范式** 

- 命令式编程
- 函数式编程
  - 函数的递归与迭代
  - 函数组合与柯里化
  - 高阶函数与纯函数
- 面向对象编程
  - 如何在 JS 中实现封装、继承、多态
  - **GoF** 23 种设计模式在 JS 中的应用

**其它**

- [代码规范]( https://github.com/fex-team/styleguide/blob/master/javascript.md)
- github要有详细的commit记录
- 提前了解Node，对你使用一些工具化的东西很有帮助 

 

### 后端

**java基础**

- 面向对象
  - 封装
  - 继承
  - 多态
  - 接口、抽象类
- 容器
  - Map
  - List
  - Set
  - Stack
  - Queue
- 异常
  - throw
  - try / catch / finally
- I / O
  - File类
  - InputStream / OutputStream
  - Reader / Writer
  - 序列化
- 并发
  - 多线程的两种方式
  - 线程安全
  - 死锁 / 活锁

**数据库**

- 基础sql语法
  - insert
  - update
  - select
  - delete
- 数据库表设计
  - rbac
  - 表优化
- Java的数据库连接
- 数据库连接池

**Web**

- Servlet的声明周期与初始化过程
- Servlet与Filter的使用
- 业务逻辑的实现
- session / cookie
- 权限控制



### 最后

新年快乐～

记得找导师要红包