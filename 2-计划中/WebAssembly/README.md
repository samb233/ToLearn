# WebAssembly

## WASM的现状

学习材料：[.NET Core 和 WASI（服务器上的 WebAssembly）的未来可能性](https://www.bilibili.com/video/BV1vr4y1x7a8)

这个视频是微软对其.NET WASI DEMO的介绍，非常清晰地介绍了WASM、WASI，并通过一些DEMO完整的演示了WASI程序从编码到部署到简单应用的过程。

WASM是为了让用户能在浏览器沙箱中运行一些复杂的应用程序

而WASI将WASM带到服务端，通过WASI运行时，去除架构差异


## 项目思考

图片色域转换工具：利用rust与wasm，部署在github pages