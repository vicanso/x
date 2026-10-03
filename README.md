## 我的开源项目

### rust

- [zedis](https://github.com/vicanso/zedis) :fire: 一款使用 Rust 和 GPUI 构建的极速原生 Redis 图形用户界面。![Github stars](https://img.shields.io/github/stars/vicanso/zedis)
- [Pingap](https://github.com/vicanso/pingap) :fire: 基于pingora开发的类似nginx反向代理。![Github stars](https://img.shields.io/github/stars/vicanso/pingap)
- [charts-rs](https://github.com/vicanso/charts-rs) :fire: 纯rust的图表库，简单的json配置快速生成图表，支持`svg`、`png`、`jpeg`、`webp`与`avif`输出，提供`bar`，`line`，`horizon bar`，`pie`，`radar`，`scatter`，`candlestick`，`table`，`heatmap`，`funnel`，`waterfall`，`gauge`，`treemap`，`sankey`以及`multi chart`等二十二种图表类型。![Github stars](https://img.shields.io/github/stars/vicanso/charts-rs)
- [charts-rs-web](https://github.com/vicanso/charts-rs-web) charts-rs 的在线演示与 HTTP 服务，以 json 的形式定义图表参数，可选择以 svg、png、jpeg、webp 或 avif 的形式返回，[在线体验](https://charts.npmtrend.com/)。
- [zstats.app](https://github.com/vicanso/zstats.app) macOS 菜单栏系统监控，围绕「按应用定规则」构建：托盘实时显示 CPU，面板提供进程监控、每个程序可各设一条线的阈值告警与磁盘空间分析，支持识别并安全清理可再生缓存。
- [zstats](https://github.com/vicanso/zstats) zstats.app 背后的系统性能指标采集库与命令行工具：统一且可序列化的数据模型（CPU、内存、磁盘、网络、进程、温度、GPU 等），采集与输出完全解耦，可并发写入多个 sink，采集开销可调低至托盘应用的水平。
- [CyberAPI](https://github.com/vicanso/cyberapi) :fire: 基于tauri的HTTP API客户端工具，更小更快。![Github stars](https://img.shields.io/github/stars/vicanso/cyberapi)
- [diving-rs](https://github.com/vicanso/diving-rs) :fire: rust实现的镜像分析工具，直接从 registry 拉取镜像，不再依赖于docker client，性能更快更便捷。可逐层浏览文件，检测空间浪费、跨层重复文件以及泄漏的密钥文件等安全问题，支持 AI 优化报告与 CI 卡口，提供终端 TUI、Web、MCP 等多种使用方式。![Github stars](https://img.shields.io/github/stars/vicanso/diving-rs)
- [ai-diving](https://github.com/vicanso/ai-diving) 把镜像分析（diving-rs）与 LLM 优化建议串成自动化流水线：镜像 push 后通过 Docker Hub Webhook 触发，自动产出「哪里劣化了、Dockerfile 该怎么改」的中文报告，支持企业微信与邮件通知，[在线体验](https://ai-diving.npmtrend.com/)。
- [springbok](https://github.com/vicanso/springbok) :fire: 基于 Tauri 的桌面图片优化工具，支持 PNG、JPEG 压缩以及转换为 WebP、AVIF、JXL 格式，多系统版本的GUI工具，方便简单。![Github stars](https://img.shields.io/github/stars/vicanso/springbok)
- [imageoptimize](https://github.com/vicanso/imageoptimize) 图片处理库与命令行工具，支持缩放、灰度、裁剪、翻转、旋转、亮度、对比度、锐化、模糊、填充、水印和优化，可批量压缩目录下的图片并转换为 WebP、AVIF、JXL 格式。
- [image-optim](https://github.com/vicanso/image-optim) :fire: 图片压缩服务，支持缩放、裁剪、水印以及图片格式转换功能，并计算压缩之后(同样的尺寸)的图片的差异值。![Github stars](https://img.shields.io/github/stars/vicanso/image-optim)
- [tibba](https://github.com/vicanso/tibba) 基于 Axum + PostgreSQL + Redis 的 REST 服务脚手架，提供会话与多种鉴权（Cookie Session / JWT / API Key）、RBAC、限流、CSRF、任务队列、对象存储、OpenAPI、Admin SPA 等横切能力，可按需裁剪后用于新业务。
- [httpstat](https://github.com/vicanso/http-stat-rs) :fire: 获取http请求各阶段（DNS、TCP、TLS、服务端处理、内容传输）的耗时统计，支持http1、http2、http3与gRPC，并提供基准测试模式。![Github stars](https://img.shields.io/github/stars/vicanso/http-stat-rs)
- [static](https://github.com/vicanso/static) 基于 Axum 与 OpenDAL 的高性能静态文件HTTP服务，支持本地文件系统、S3、FTP 与 MongoDB GridFS 等存储，内置压缩、缓存、Range 请求、SPA fallback 等功能。![Github stars](https://img.shields.io/github/stars/vicanso/static)
- [browser-headless](https://github.com/vicanso/browser-headless) 一个 headless Chrome 的 HTTP 服务。传入 URL，一次请求拿回页面的结构化快照： 渲染后的 HTML / 纯文本 / Markdown、性能时间线、每条网络资源、JS 异常、 console 日志、Cookie，以及可选的截图 / PDF / HAR / DOM snapshot。
- [ferry](https://github.com/vicanso/ferry) 把 Redis 当作反向隧道的传输层，让网络不通、但都能连上同一个 Redis 的两台机器之间跑通 HTTP 调用。


### golang

- [diving](https://github.com/vicanso/diving) 基于dive的镜像分析工具网页版，可以简单的查看镜像中每层的修改(后续不再维护，请使用diving-rs)
- [dnscache](https://github.com/vicanso/dnscache) :fire: DNS缓存，可以缓存DNS的解析记录，避免过多的DNS解析影响性能。![Github stars](https://img.shields.io/github/stars/vicanso/dnscache)
- [elton](https://github.com/vicanso/elton) :fire: 简单高性能的HTTP框架。![Github stars](https://img.shields.io/github/stars/vicanso/elton)
- [elton-compress](https://github.com/vicanso/elton-compress) elton压缩中间件扩展，提供`snappy`、`zstd`与`lz4`压缩方式
- [elton-json-picker](https://github.com/vicanso/elton-json-picker) 可指定从响应的json中挑选需要返回的字段，减少数据传输
- [elton-jwt](https://github.com/vicanso/elton-jwt) elton的jwt中间件
- [elton-session](https://github.com/vicanso/elton-session) elton session模块，默认支持memory形式保存session，可自定义存储方式，如redis
- [forest](https://github.com/vicanso/forest) 基于elton的web服务框架
- [keygrip](https://github.com/vicanso/keygrip) 生成签名与校验的工具，参考`crypto-utils/keygrip`实现
- [go-axios](https://github.com/vicanso/go-axios) golang的http客户端模块，提供简便强大的HTTP调用方式
- [go-cache](https://github.com/vicanso/go-cache) :fire: 封装了常用的基于redis的缓存，以及基于redis+lru的二级缓存。![Github stars](https://img.shields.io/github/stars/vicanso/go-cache)
- [go-gauge](https://github.com/vicanso/go-gauge) 提供简单的计算函数，如总和、平均值、最大值等。
- [go-mask](https://github.com/vicanso/go-mask) 提供转换struct为map[string]interface{}，并根据字段\*\*\*或截断处理
- [go-performance](https://github.com/vicanso/go-performance) 获取golang应用程序的各类指标，如内存、CPU等
- [hes](https://github.com/vicanso/hes) 统一的HTTP出错类，用于规范化REST接口的出错响应
- [http-trace](https://github.com/vicanso/http-trace) :fire: http trace模块，用于生成http请求各阶段：dns、tcp连接等的耗时记录。![Github stars](https://img.shields.io/github/stars/vicanso/http-trace)
- [ips](https://github.com/vicanso/ips) 校验IP地址是否符合列表中的值，支持网络组
- [lru-ttl](https://github.com/vicanso/lru-ttl) 基于LRU的带ttl的缓存
- [superjson](https://github.com/vicanso/superjson) 提供从json中挑选指定字段或字段格式转换（驼峰式、下划线式等）
- [tiny](https://github.com/vicanso/tiny) 图片、文本的各类压缩处理
- [upstream](https://github.com/vicanso/upstream) HTTP Upstream模块，提供多种upstream的选择方式
- [viperx](https://github.com/vicanso/viperx) viper配置模块的增强，支持指定多配置文件自动合并，以及提供常用的配置获取函数
- [web-screenshot](https://github.com/vicanso/web-screenshot) 网页截屏工具，可指定地址生成截图

### nodejs

- [influxdb-nodejs](https://github.com/vicanso/influxdb-nodejs) influxdb的nodejs客户端模块
- [nano-seconds](https://github.com/vicanso/nano-seconds) 用于在nodejs或浏览器中生成nano second级别的时间
