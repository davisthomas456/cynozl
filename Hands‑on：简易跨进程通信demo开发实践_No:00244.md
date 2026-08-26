最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/166051.Doc

原标题：缓存基础原理与简单代码实现
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/044935.Doc

原标题：golang 系统设计多级缓存架构落地
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.mljc3b.asia/arts/209543.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.mljc3b.asia/arts/734380.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.mljc3b.asia/arts/230269.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/945271.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.mljc3b.asia/arts/375289.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.mljc3b.asia/arts/858954.Doc

原标题：golang mysql 避免 select * 查询
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.mljc3b.asia/arts/748695.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/833653.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.mljc3b.asia/arts/152383.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.mljc3b.asia/arts/298494.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/041225.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.mljc3b.asia/arts/085308.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.mljc3b.asia/arts/017220.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/972033.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/344259.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.mljc3b.asia/arts/808175.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.mljc3b.asia/arts/187362.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.mljc3b.asia/arts/139968.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/668295.Doc

原标题：golang redis 分布式计数器开发
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/816648.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.mljc3b.asia/arts/291851.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/603814.Doc

原标题：golang github actions 发布 release 包
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.mljc3b.asia/arts/646322.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/015782.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/963116.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.mljc3b.asia/arts/376871.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.mljc3b.asia/arts/459738.Doc

原标题：文件批量导入导出功能实现
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.mljc3b.asia/arts/904613.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.mljc3b.asia/arts/112990.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/702848.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.mljc3b.asia/arts/134789.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/840104.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.mljc3b.asia/arts/837788.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/478784.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.mljc3b.asia/arts/643932.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.mljc3b.asia/arts/893814.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/634732.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.mljc3b.asia/arts/566739.Doc


二、踩坑排错｜Troubleshooting
原标题：golang jwt 过期刷新 token 实现
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/634040.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/229511.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.mljc3b.asia/arts/698158.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.mljc3b.asia/arts/376320.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.mljc3b.asia/arts/892332.Doc

原标题：集成测试业务流程编写示例
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.mljc3b.asia/arts/453016.Doc

原标题：golang gin 静态资源访问配置
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.mljc3b.asia/arts/673595.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.mljc3b.asia/arts/318787.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.mljc3b.asia/arts/048427.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/739149.Doc

原标题：golang 系统设计读写分离架构示例
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.mljc3b.asia/arts/560561.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/960594.Doc

原标题：程序信号中断退出处理逻辑
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.mljc3b.asia/arts/147555.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.mljc3b.asia/arts/359567.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.mljc3b.asia/arts/082461.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.mljc3b.asia/arts/099438.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.mljc3b.asia/arts/029807.Doc

原标题：golang mysql 事务回滚异常处理
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.mljc3b.asia/arts/949414.Doc

原标题：服务健康检查告警监控体系
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.mljc3b.asia/arts/093150.Doc

原标题：请求工具封装统一异常处理
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/507358.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/903046.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.mljc3b.asia/arts/999684.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/347119.Doc

原标题：数据库事务 ACID 原理讲解
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.mljc3b.asia/arts/741806.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/258087.Doc

原标题：前端错误监控上报系统搭建
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/393831.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/715991.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/317093.Doc

原标题：vue pinia 状态管理实战教程
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.mljc3b.asia/arts/675941.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/236272.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.mljc3b.asia/arts/197315.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/293972.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/893668.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.mljc3b.asia/arts/263390.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.mljc3b.asia/arts/169437.Doc

原标题：hosts 配置本地回环访问修复
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.mljc3b.asia/arts/660900.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/966654.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.mljc3b.asia/arts/309687.Doc

原标题：大事务拆分防止连接池耗尽
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/481334.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.mljc3b.asia/arts/974586.Doc

三、实战开发｜Practice
原标题：golang 系统设计开源项目 release 发布流程
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.mljc3b.asia/arts/115553.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.mljc3b.asia/arts/523864.Doc

原标题：全局异常处理器接口返回统一
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.mljc3b.asia/arts/350420.Doc

原标题：多版本开发环境共存配置
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/488884.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/618988.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.mljc3b.asia/arts/367128.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.mljc3b.asia/arts/279884.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.mljc3b.asia/arts/076465.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.mljc3b.asia/arts/661634.Doc

原标题：项目语义化版本号规范管理
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.mljc3b.asia/arts/907224.Doc

原标题：golang docker 部署 redis 配置要点
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.mljc3b.asia/arts/279754.Doc

原标题：前端国际化多语言方案落地
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/382456.Doc

原标题：golang grafana 监控面板简单配置
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.mljc3b.asia/arts/453780.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.mljc3b.asia/arts/680610.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.mljc3b.asia/arts/048559.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.mljc3b.asia/arts/807327.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.mljc3b.asia/arts/718005.Doc

原标题：任务执行锁防止并发重复调度
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.mljc3b.asia/arts/827361.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/208755.Doc

原标题：系统文件描述符上限调大
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/035913.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/744045.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/960182.Doc

原标题：golang redis stream 消息队列实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/591847.Doc

原标题：golang 时间时区处理避坑指南
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/936036.Doc

原标题：golang grafana 监控面板简单配置
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.mljc3b.asia/arts/168926.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.mljc3b.asia/arts/350430.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/004641.Doc

原标题：短信服务封装失败自动重试
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.mljc3b.asia/arts/142809.Doc

原标题：请求工具封装统一异常处理
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.mljc3b.asia/arts/381013.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/478361.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/441022.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.mljc3b.asia/arts/599864.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.mljc3b.asia/arts/929116.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.mljc3b.asia/arts/852549.Doc

原标题：golang 优雅处理数据库事务
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/158298.Doc

原标题：异步编程 Promise 执行流程解析
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/774131.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.mljc3b.asia/arts/606164.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.mljc3b.asia/arts/700672.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.mljc3b.asia/arts/120521.Doc

原标题：golang 单元测试 mock http 请求
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.mljc3b.asia/arts/445581.Doc

四、架构设计｜Architecture
原标题：golang 系统设计日志规范结构化日志落地
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.mljc3b.asia/arts/645283.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.mljc3b.asia/arts/573367.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.mljc3b.asia/arts/552399.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/705815.Doc

原标题：磁盘占满服务不可用清理方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/074364.Doc

原标题：vue3 组合式 API 业务开发实战
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.mljc3b.asia/arts/962331.Doc

原标题：nodejs 集群模式多核利用实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.mljc3b.asia/arts/783932.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.mljc3b.asia/arts/580431.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.mljc3b.asia/arts/691924.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.mljc3b.asia/arts/423210.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.mljc3b.asia/arts/123778.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.mljc3b.asia/arts/199479.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.mljc3b.asia/arts/156415.Doc

原标题：git stash 代码暂存切换分支
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.mljc3b.asia/arts/835286.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/854694.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/079796.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/660505.Doc

原标题：golang yaml 解析配置加载实操
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/118656.Doc

?
