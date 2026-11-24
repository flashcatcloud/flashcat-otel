# flashcat-otel

用于集中维护不同语言 OpenTelemetry SDK 开源版本源码的仓库。

## 目录结构

```text
├── java/      # Java SDK 源码
├── go/        # Go SDK 源码
├── python/    # Python SDK 源码
├── nodejs/    # Node.js SDK 源码
└── dotnet/    # C#/.NET SDK 源码
```

每种语言的 SDK 开源版本源码直接放在对应的根目录子目录下，并建议保留：

- `README.md`：SDK 来源、版本、构建和测试方式；
- 上游许可证及版权声明；
- 该语言原有的源码、依赖和构建目录结构；
- 本仓库对上游 SDK 的修改说明；
- 版本升级与兼容性记录。
