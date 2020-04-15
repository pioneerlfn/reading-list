# Gopher-reading-list
A curated selection of blog posts on Go


## Basic

- [Go By Example](https://gobyexample.com/)
- [Go语言实战读书笔记](https://www.flysnow.org/2017/03/04/go-in-action-go-package.html)
- [Essential Go](https://www.programming-books.io/essential/go/)

### iota
- [彻底搞懂 golang 里的 iota](https://blog.wolfogre.com/posts/golang-iota/)

### sort
- [Sorting custom structures in Golang. A quick recipe.](https://thenotexpert.com/golang-sorting/) (可以用sort.Slice()绕开Len,Less,Swap这三个冗长乏味的函数)

### make


### json
- [Go json cookbook](https://eli.thegreenplace.net/2019/go-json-cookbook/) (json处理)

### 函数
- [First class function in Go](https://mp.weixin.qq.com/s/0zSFzPVLdTl_5IoFgwtnFA)

### Context
- [Using context cancellation in Go 💀](https://www.sohamkamani.com/blog/golang/2018-06-17-golang-using-context-cancellation/)

## 进阶

### web

- [Implementing OAuth 2.0 with Go(Golang) 🔐](https://www.sohamkamani.com/blog/golang/2018-06-24-oauth-with-golang/)
- [How to do Google sign-in with Go](https://skarlso.github.io/2016/06/12/google-signin-with-go/)
- [How to do Google Sign-In with Go - Part 2](https://skarlso.github.io/2016/11/02/google-signin-with-go-part2/)

### TCP
- [graceful-shutdown-of-a-tcp-server-in-go/](https://eli.thegreenplace.net/2020/graceful-shutdown-of-a-tcp-server-in-go/) (优雅关闭TCP服务器)
- [Go语言中如何开启 TCP keepalive？](https://mp.weixin.qq.com/s/v8QPxefWLfAmgPNW2HOYHA)
- [Golang netpoll](http://likakuli.com/post/2018/06/06/golang-network/) (通过读这篇文章，终于搞清楚了`netFd`和`poll.FD`的江湖地位)

### 热加载
- [Go配置文件热加载 - 发送系统信号](https://segmentfault.com/a/1190000019436438)

### How to
- [Writing a simple shell in Go](https://sj14.gitlab.io/post/2018/07-01-go-unix-shell/)
- [动手实现raft](https://eli.thegreenplace.net/2020/implementing-raft-part-0-introduction/)

### patterns
- [3-ways-to-iterate-in-go.html](https://blog.kowalczyk.info/article/1Bkr/3-ways-to-iterate-in-go.html) (迭代器)

- [PubSub using channels in Go](https://eli.thegreenplace.net/2020/pubsub-using-channels-in-go/) (发布-订阅模式)

- [Go: Broadcast channels?](https://science.mroman.ch/gobroadcastchannels.html) (广播📢)

- [Let's Create a Simple Load Balancer With Go](https://kasvith.me/posts/lets-create-a-simple-lb-go/) (负载均衡)

- [Go: Factories I](https://science.mroman.ch/gofactory.html)

- [Go Decorator Function Pattern Tutorial](https://tutorialedge.net/golang/go-decorator-function-pattern-tutorial/)(装饰器)


- connection pool
    - [Go夜读:#67 SQL 连接池分析 （database/sql pool reading）[ Go Golang 学习]](https://www.bilibili.com/video/av75690189?from=search&seid=5328732865312480571)
    - [Golang连接池的几种实现案例](https://juejin.im/post/5e58e3b7f265da57537eb7ed#heading-7)



### 性能优化
- [Simple techniques to optimise Go programs](https://stephen.sh/posts/quick-go-performance-improvements)


### 软件工程
- [Dependency Injection in Go](https://blog.drewolson.org/dependency-injection-in-go) (依赖注入)
- [Go lessons learnt by refactoring](https://anto.pt/post/go-lessons-learnt-by-refactoring)
- [Moving Towards Domain Driven Design in Go](https://www.calhoun.io/moving-towards-domain-driven-design-in-go/)
- [用面向对象设计原则理解 Go 中 interface](https://mp.weixin.qq.com/s/MqQ6b-Z_wvYe9YpNI5LDeA)

### runtime
- [深入golang runtime的调度](https://zboya.github.io/post/go_scheduler/#runtime%E8%B0%83%E5%BA%A6%E5%99%A8%E7%9A%84%E5%90%AF%E5%8A%A8) (调度器)

- [深度解密调度器源码系列(饶全成)](https://qcrao.com/2019/09/06/dive-into-go-scheduler-source-code/)

### 测试
- [Testing in Go](https://ieftimov.com/categories/testing-in-go/) (测试)

### 包管理
- [从 goinstall 到 module —— golang 包管理的前世今生](https://blog.wolfogre.com/posts/golang-package-history/)
- [Go Modules 终极入门](https://mp.weixin.qq.com/s/fNMXfpBhBC3UWTbYCnwIMg)
- [Russ Cox:The Principles of Versioning in Go](https://research.swtch.com/vgo-principles)

### Web编程
- [Go Web编程之静态文件](https://juejin.im/post/5e1cfd2d6fb9a02ffd6eb56c)


### 数据库
- [Go Web编程之数据库](https://juejin.im/post/5e277a85e51d450234249c7e)
- [使用golang理解mysql的两阶段提交](https://mp.weixin.qq.com/s/KeZId8WScnS-rlc0kedEzw)
    > 通过这篇文章，知道了Go中怎么写XA，也重读了mysql XA文档.

    > 又学习了下2PC(DDIA),发现这篇文章中自己实现的TM太简陋了。合格的TM需要对任何决策或者指令或者收到的Prepare的回复做持久化日志。显然让client手动写这些代码是不对的，应该有相应的库封装一下。



### Code Style
- [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- [The Uber Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md)
- [Clean Go Code](https://github.com/Pungyeon/clean-go-article#Interfaces-in-Go)
- [Thanos Coding Style Guide](https://thanos.io/contributing/coding-style-guide.md/)

### Tools
- [An Overview of Go's Tooling](https://www.alexedwards.net/blog/an-overview-of-go-tooling)

### 其他
- [IM系统的前世今生—2小时用Go快速搭建高性能、可拓展的IM系统](https://mp.weixin.qq.com/s/6LG4D4Bt3_lM0QW2RkqI_A)
- [Understanding bytes in Go by building a TCP pro (slack server)](https://ieftimov.com/post/understanding-bytes-golang-build-tcp-protocol/)

## Books
- [Essential Go](https://www.programming-books.io/essential/go/)
- [Go 101](https://go101.org/)
- [Go语言圣经](https://yar999.gitbooks.io/gopl-zh/content/)
- [Go语言高级编程](https://yar999.gitbooks.io/gopl-zh/content/)
- [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang)


## Repositories
- [Awesome Go Books](https://github.com/dariubs/GoBooks)
- [Gopher Reading List](https://github.com/enocom/gopher-reading-list)
- [Awesome Go LeetCode](https://github.com/kylesliu/awesome-golang-leetcode)
- [Data Structure Libraries and Algorithms implementation](https://github.com/priyankchheda/algorithms)
- [awesome Go](https://github.com/avelino/awesome-go) (A curated list of awesome Go frameworks, libraries and software.)
- [Go Patterns](https://github.com/tmrts/go-patterns)
- [每日一库](https://github.com/darjun/go-daily-lib)

## 博客订阅
- [Dave Cheney](https://dave.cheney.net/)
- [Eli BenderSky](eli.thegreenplace.net/)
- [Alex Edward](https://www.alexedwards.net/blog/)
- [Go, the unwritten parts](https://rakyll.org/archive/)
- [tony_Bai](https://tonybai.com/)
- [鸟窝](https://colobu.com/)
- [飞雪无情](https://www.flysnow.org/)
- [饶全成](http://qcrao.com/)
- [Draveness](https://draveness.me/index)
- [calhoun.io](https://www.calhoun.io/)
- [ieftimov](https://ieftimov.com/)

## web site
- [程序员开发效率神器汇总！](https://mp.weixin.qq.com/s/WjaHJHE7ZPbgo7QwIDwZzQ)(tencent)
- [awesomer-go](https://awesomer-go.pantas.net/) (可查询、排序的awesome-go列表)
