## Introduction

`libcsp` is a high performance concurrency C library influenced by the
[CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) model.

## Features

- Multiple cpu cores supported.
- High performance scheduler.
- Stack size statically analyzed in compile time.
- Lock-free channel.
- Netpoll and timer are supported.

## Documentation

Go to [https://libcsp.com](https://libcsp.com) for the documentation.

## License

Libcsp is licensed under the MIT license.

随着 Go 语言受到众多人的关注，协程受到大家的追捧，之前没有这些概念的语言都搞起了“协程”。作为现在依然位居榜首的 C 语言，也出现了基于 CSP 模型的并发库。这和 Go 语言的模型是一样的。由于天生丽质，C 语言的这个并发库号称比 Go 语言快 10 倍。
项目地址：https://github.com/shiyanhui/libcsp，刚开源 7 天，Star 数 831+，文档首页：https://libcsp.com。
主要特性如下：
支持多个 cpu 核心。
高性能调度程序。
在编译时静态分析堆栈大小。
无锁通道。
支持 Netpoll 和计时器。
