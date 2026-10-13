# DeskWork 小D · 本地优先办公助手

DeskWork 是一款本地优先的桌面 AI 办公助手（pywebview + WebView2 前端、Python 后端），内置模型昵称"小D"，数据与模型均在本地，隐私可控。

## 主要能力
- 文件整理与文档处理（docx/xlsx/pdf 等）
- 联网搜索（开关控制，按需开启）
- 本地知识库（向量检索、融合搜索）
- MCP 生态工具（文件、Git、SQLite、时间、记忆，以及逆向工程工具 rea 等）
- 代码开发（创建项目、读写代码、运行命令、排查 BUG）
- 语音交互（连续对话、语音唤醒、TTS 朗读）
- 富产物输出（表格、图表、文档）

## 下载
前往 [Releases](https://github.com/haoeastspeed/DeskWork-Release/releases) 下载最新版本。

## 版本形态
| 形态 | 说明 |
|---|---|
| 安装包 `DeskWork_Setup.exe` | 推荐，安装到本机 |
| 便携版 `DeskWork_Portable.zip` | 解压即用 |
| 单文件 `DeskWork_Single.exe` | 免安装，单一可执行文件 |

## 运行环境
- Windows 10/11（x64）
- 需自行安装 [Ollama](https://ollama.com) 并拉取本地模型（如 Qwen 系列）