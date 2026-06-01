# yuan-claw-idea-plugin

在 IDEA 中一键运行 `yuan-claw` 命令行工具。

## 功能

- **一键运行** — 点击工具栏按钮、选择菜单或按快捷键即可执行
- **终端复用** — 始终使用同一个终端标签页，不会反复弹出新终端
- **零配置** — 安装即用，无需额外设置

## 安装

1. 构建插件：
   ```bash
   ./gradlew buildPlugin
   ```
2. 生成的插件包位于 `build/distributions/yuan-claw-1.0.0.zip`
3. 在 IDEA 中安装：`设置 > 插件 > ⚙️ > 从磁盘安装插件...` → 选择该 zip 文件

## 使用

安装完成后，有三种方式可以运行 `yuan-claw`：

| 方式    | 说明 |
| ------- | ---- |
| 工具栏  | 点击运行/调试按钮旁的爪痕图标 |
| 菜单    | `工具 → Run Yuan-Claw` |
| 快捷键  | `Ctrl + Alt + Y` |

## 前置条件

- IntelliJ IDEA 2025.2+（或兼容的 JetBrains IDE）
- Terminal 插件已启用（IDE 默认自带）
- 系统 PATH 中已安装 `yuan-claw` 命令

## 技术栈

- Kotlin 2.2.0
- Gradle 8.12
- IntelliJ Platform Gradle Plugin 2.3.0
- JVM 21

## 许可证

MIT
