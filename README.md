# skills

本仓库收集若干面向 **Cursor / OpenClaw** 的 Agent Skill：每个子目录包含 `SKILL.md`（行为说明与契约）及配套脚本。

## 子项目

| 目录 | 说明 |
|------|------|
| [bill-claw](./bill-claw/) | 本地记账：SQLite 账本、CLI、报表图表与 Flask 看板（见该目录 `SKILL.md`）。 |
| [cctv-news](./cctv-news/) | 按日期抓取新闻联播文字版并整理摘要的流程说明（`SKILL.md`）。 |
| [md2Img](./md2Img/) | 将 Markdown 渲染为单张 PNG（Playwright 截图，见 `SKILL.md`）。 |

## 使用说明

- 进入对应子目录，阅读 `SKILL.md` 中的输入输出约定与依赖。
- Python 项目建议在各自目录下创建虚拟环境并安装依赖（本仓库根目录 `.gitignore` 已忽略 `.venv`）。

## 许可证

若未在各子目录中另行说明，默认以仓库内文件为准；对外分发前请自行补充许可证文件。
