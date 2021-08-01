## 我的开源项目

### golang

- [diving](https://github.com/vicanso/diving) 基于dive的镜像分析工具网页版，可以简单的查看镜像中每层的修改
- [dnscache](https://github.com/vicanso/dnscache) DNS缓存，可以缓存DNS的解析记录，避免过多的DNS解析影响性能
- [elton](https://github.com/vicanso/elton) 简单高性能的HTTP框架
- [elton-compress](https://github.com/vicanso/elton-compress) elton压缩中间件扩展，提供`br`、`snappy`、`zstd`与`lz4`压缩方式
- [elton-json-picker](https://github.com/vicanso/elton-json-picker) 可指定从响应的json中挑选需要返回的字段，减少数据传输
- [elton-jwt](https://github.com/vicanso/elton-jwt) elton的jwt中间件
- [elton-session](https://github.com/vicanso/elton-session) elton session模块，默认支持memory形式保存session，可自定义存储方式，如redis
- [keygrip](https://github.com/vicanso/keygrip) 生成签名与校验的工具，参考`crypto-utils/keygrip`实现
- [pike](https://github.com/vicanso/pike) HTTP缓存服务（与varnish类似）
- [go-axios](https://github.com/vicanso/go-axios) golang的http客户端模块，提供简便强大的HTTP调用方式
- [go-cache](https://github.com/vicanso/go-cache) 封装了常用的基于redis的缓存，以及基于redis+lru的二级缓存
- [go-gauge](https://github.com/vicanso/go-gauge) 提供简单的计算函数，如总和、平均值、最大值等。 
- [go-parallel](https://github.com/vicanso/go-parallel) golang的各类并发处理函数，如parallel、race等
- [go-performance](https://github.com/vicanso/go-performance) 获取golang应用程序的各类指标，如内存、CPU等
- [hes](https://github.com/vicanso/hes) 统一的HTTP出错类，用于规范化REST接口的出错响应
- [http-trace](https://github.com/vicanso/http-trace) http trace模块，用于生成http请求各阶段：dns、tcp连接等的耗时记录
- [ips](https://github.com/vicanso/ips) 校验IP地址是否符合列表中的值，支持网络组
- [lru-ttl](https://github.com/vicanso/lru-ttl) 基于LRU的带ttl的缓存
- [static](https://github.com/vicanso/static) 静态文件HTTP服务，提供对静态文件的HTTP访问
- [tiny](https://github.com/vicanso/tiny) 图片、文本的各类压缩处理
- [upstream](https://github.com/vicanso/upstream) HTTP Upstream模块，提供多种upstream的选择方式
- [viperx](https://github.com/vicanso/viperx) viper配置模块的增强，支持指定多配置文件自动合并，以及提供常用的配置获取函数

### nodejs

- [influxdb-nodejs](https://github.com/vicanso/influxdb-nodejs) influxdb的nodejs客户端模块
- [nano-seconds](https://github.com/vicanso/nano-seconds) 用于在nodejs或浏览器中生成nano second级别的时间