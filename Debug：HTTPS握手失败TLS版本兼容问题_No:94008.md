最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.i3g84c.asia/blog/026033.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.i3g84c.asia/blog/128838.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.i3g84c.asia/blog/619185.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.i3g84c.asia/blog/504706.Doc

原标题：golang goroutine 池任务调度
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.i3g84c.asia/blog/619170.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.i3g84c.asia/blog/231863.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.i3g84c.asia/blog/890696.Doc

原标题：服务熔断防止故障级联传播
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.i3g84c.asia/blog/385747.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.i3g84c.asia/blog/648058.Doc

原标题：golang 重试退避机制代码实现
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.i3g84c.asia/blog/407399.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.i3g84c.asia/blog/423277.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.i3g84c.asia/blog/466202.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.i3g84c.asia/blog/837843.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.i3g84c.asia/blog/860400.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.i3g84c.asia/blog/455705.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.i3g84c.asia/blog/240969.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.i3g84c.asia/blog/529557.Doc

原标题：线程调度优化减少上下文切换
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.i3g84c.asia/blog/883159.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.i3g84c.asia/blog/537925.Doc

原标题：golang kafka 监控指标简单梳理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.i3g84c.asia/blog/759339.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.i3g84c.asia/blog/178043.Doc

原标题：接口请求重试容错机制实现
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.i3g84c.asia/blog/604273.Doc

原标题：Performance：数据库join优化，大表join规避
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.i3g84c.asia/blog/373187.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.i3g84c.asia/blog/275782.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.i3g84c.asia/blog/606566.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.i3g84c.asia/blog/729104.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.i3g84c.asia/blog/953422.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.i3g84c.asia/blog/912745.Doc

原标题：golang mysql limit 大分页优化
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.i3g84c.asia/blog/774360.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.i3g84c.asia/blog/359512.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.i3g84c.asia/blog/290625.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.i3g84c.asia/blog/979134.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.i3g84c.asia/blog/205874.Doc

原标题：golang 分库分表简单路由实现
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.i3g84c.asia/blog/129626.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.i3g84c.asia/blog/791714.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.i3g84c.asia/blog/578310.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.i3g84c.asia/blog/486877.Doc

原标题：新手参与开源社区贡献指南
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.i3g84c.asia/blog/203952.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.i3g84c.asia/blog/312211.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.i3g84c.asia/blog/673236.Doc


二、踩坑排错｜Troubleshooting
原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.i3g84c.asia/blog/141677.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.i3g84c.asia/blog/385535.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.i3g84c.asia/blog/159147.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.i3g84c.asia/blog/011688.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.i3g84c.asia/blog/937775.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.i3g84c.asia/blog/423298.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.i3g84c.asia/blog/082646.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.i3g84c.asia/blog/981153.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.i3g84c.asia/blog/647456.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.i3g84c.asia/blog/363631.Doc

原标题：服务健康检查告警监控体系
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.i3g84c.asia/blog/601414.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.i3g84c.asia/blog/059270.Doc

原标题：golang 协程泄露问题排查方法
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.i3g84c.asia/blog/645510.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.i3g84c.asia/blog/082326.Doc

原标题：从零学习简单分布式ID生成思路
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.i3g84c.asia/blog/801594.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.i3g84c.asia/blog/707446.Doc

原标题：golang 开发环境快速搭建指南
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.i3g84c.asia/blog/277060.Doc

原标题：nodejs 全局异常捕获进程防护
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.i3g84c.asia/blog/044818.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.i3g84c.asia/blog/712665.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.i3g84c.asia/blog/374662.Doc

原标题：golang redis 客户端业务使用
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.i3g84c.asia/blog/885469.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.i3g84c.asia/blog/189017.Doc

原标题：前端国际化多语言方案落地
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.i3g84c.asia/blog/019329.Doc

原标题：golang prometheus histogram 指标
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.i3g84c.asia/blog/458144.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.i3g84c.asia/blog/974030.Doc

原标题：内存泄漏定位分析完整流程
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.i3g84c.asia/blog/014866.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.i3g84c.asia/blog/315119.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.i3g84c.asia/blog/496502.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.i3g84c.asia/blog/258775.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.i3g84c.asia/blog/341269.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.i3g84c.asia/blog/128586.Doc

原标题：golang 单例模式实现几种方式
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.i3g84c.asia/blog/918657.Doc

原标题：golang 系统设计分布式任务调度
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.i3g84c.asia/blog/688214.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.i3g84c.asia/blog/413274.Doc

原标题：本地运行正常线上报错排查
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.i3g84c.asia/blog/381899.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.i3g84c.asia/blog/229955.Doc

原标题：不必要字符转义关闭业务异常
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.i3g84c.asia/blog/907688.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.i3g84c.asia/blog/105841.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.i3g84c.asia/blog/524337.Doc

原标题：全量回归测试提升代码质量
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.i3g84c.asia/blog/016469.Doc

三、实战开发｜Practice
原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.i3g84c.asia/blog/668295.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.i3g84c.asia/blog/654666.Doc

原标题：数据库读写分离性能优化
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.i3g84c.asia/blog/263746.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.i3g84c.asia/blog/665570.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.i3g84c.asia/blog/493643.Doc

原标题：express 中间件开发业务实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.i3g84c.asia/blog/166124.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.i3g84c.asia/blog/383492.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.i3g84c.asia/blog/458048.Doc

原标题：golang redis hyperloglog 基数统计
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.i3g84c.asia/blog/094490.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.i3g84c.asia/blog/202025.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.i3g84c.asia/blog/390973.Doc

原标题：JWT 令牌过期异常处理
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.i3g84c.asia/blog/354411.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.i3g84c.asia/blog/883275.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.i3g84c.asia/blog/507019.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.i3g84c.asia/blog/158090.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.i3g84c.asia/blog/029013.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.i3g84c.asia/blog/216172.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.i3g84c.asia/blog/963342.Doc

原标题：golang 时间时区处理避坑指南
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.i3g84c.asia/blog/371265.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.i3g84c.asia/blog/340762.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.i3g84c.asia/blog/631065.Doc

原标题：golang 系统设计错误码体系完整设计
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.i3g84c.asia/blog/490633.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.i3g84c.asia/blog/914097.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.i3g84c.asia/blog/373152.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.i3g84c.asia/blog/120719.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.i3g84c.asia/blog/508445.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.i3g84c.asia/blog/768363.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.i3g84c.asia/blog/508747.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.i3g84c.asia/blog/004148.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.i3g84c.asia/blog/920117.Doc

原标题：重复提交幂等防护再次讲解
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.i3g84c.asia/blog/595960.Doc

原标题：git rebase 整理提交历史实操
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.i3g84c.asia/blog/544222.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.i3g84c.asia/blog/260926.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.i3g84c.asia/blog/486998.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.i3g84c.asia/blog/864740.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.i3g84c.asia/blog/079824.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.i3g84c.asia/blog/600515.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.i3g84c.asia/blog/293554.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.i3g84c.asia/blog/158475.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.i3g84c.asia/blog/208694.Doc

四、架构设计｜Architecture
原标题：golang 系统设计读写分离延迟业务兼容
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.i3g84c.asia/blog/496838.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.i3g84c.asia/blog/365661.Doc

原标题：golang redis lua 脚本开发调试
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.i3g84c.asia/blog/117239.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.i3g84c.asia/blog/607631.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.i3g84c.asia/blog/129150.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.i3g84c.asia/blog/073211.Doc

原标题：golang git 提交信息规范校验
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.i3g84c.asia/blog/639438.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.i3g84c.asia/blog/047952.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.i3g84c.asia/blog/190710.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.i3g84c.asia/blog/530929.Doc

原标题：git stash 代码暂存切换分支
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.i3g84c.asia/blog/649857.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.i3g84c.asia/blog/501606.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.i3g84c.asia/blog/257067.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.i3g84c.asia/blog/783099.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.i3g84c.asia/blog/960644.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.i3g84c.asia/blog/334080.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.i3g84c.asia/blog/427103.Doc

原标题：多线程线程安全脏数据规避
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.i3g84c.asia/blog/333334.Doc

?
