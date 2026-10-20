# CC Switch - Claude Code、Codex 与 Gemini CLI 桌面配置工具
React 18 + TypeScript 5 + Vite 7 + Tailwind CSS 3 + Tauri 2 + Rust

<directory>
src/ - React 界面、配置表单与前端状态。
src-tauri/ - Rust 桌面宿主、系统接口与打包配置。
tests/ - 前端与集成测试。
scripts/ - 开发和构建脚本。
docs/ - 用户指南与开发说明。
assets/ - 仓库图片与品牌素材。
flatpak/ - Linux Flatpak 打包配置。
.github/ - GitHub 协作与自动化，见 .github/CLAUDE.md。
</directory>

<config>
package.json - 前端依赖、开发、构建与测试命令。
pnpm-lock.yaml - 前端依赖锁定文件。
src-tauri/Cargo.toml - Rust 宿主依赖与 crate 定义。
src-tauri/tauri.conf.json - 桌面应用与安装包配置。
</config>

发布仅由版本 tag 触发。macOS 使用固定 `macos-15` ARM64 runner，保留 universal 双架构构建。

法则: 极简·稳定·导航·版本精确
