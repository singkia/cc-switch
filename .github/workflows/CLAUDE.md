# workflows/
> L2 | 父级: ../CLAUDE.md

成员清单
ci.yml: 检查前端与 Rust 宿主，不发布产物。
claude.yml: 由 GitHub 事件触发 Claude 协作。
release.yml: 版本 tag 驱动签名构建与发布；macOS 使用 macos-15 ARM64，保留 universal 双架构产物。
stale.yml: 按定时规则标记与关闭闲置 Issue。

[PROTOCOL]: 变更时更新此头部，然后检查 CLAUDE.md
