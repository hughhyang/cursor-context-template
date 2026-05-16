# cursor-context-template

极简 **Cursor 跨设备续聊** 模板：`.cursorrules` + `context/chat-summary.md`。

## 使用

1. 在 GitHub 点击 **Use this template** 创建新仓库。
2. `git clone` 到本机，用 Cursor 打开。
3. 离开设备时说 **「同步上传」**（或类似说法）；换设备后说 **「继续聊」**。

## 文件说明

| 文件 | 作用 |
|------|------|
| `.cursorrules` | 告诉 Cursor：何时写摘要、何时 pull、如何回复 |
| `context/chat-summary.md` | 对话与进度的唯一上下文（每次同步覆盖更新） |

无需 `state.md`、`decisions.md`、`sessions/` 等多文件体系。
