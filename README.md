
## 说明


拿 `golang.org/x/tools/cmd/stringer` 源码做修改，用法相同。

新增 `go generate` 生成代码包含解析方法 `func Parse%{typeName}String(s string) (%{typeName}s, bool) `。
