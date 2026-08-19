# 从零读懂 DeepSeek Harness

一本写给**不读代码的人**的 DeepSeek Harness（dsh）学习书。

- 📖 **在线阅读**：https://makewheels.github.io/deepseek-harness-book/
- 风格参照李博杰《深入理解 AI Agent》（案例驱动、编号实验、思考题、章末小结），但全部用大白话讲，图多字少。
- 源材料：[deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) 源码与官方文档 + 实机运行验证。
- 构建：Markdown + Material for MkDocs。

## 全书结构

| 部分 | 章节 | 内容 |
|---|---|---|
| 第一部分 初见 | 第1-3章 | harness 是什么、怎么跑起来、仓库地图 |
| 第二部分 解剖器官 | 第4-8章 | 插件机制、对话旅程、工具流水线、目标计划、上下文工程 |
| 第三部分 手脚与外设 | 第9-10章 | 沙箱安全、MCP/LSP/skill 等外部连接 |
| 第四部分 自己动手 | 第11-13章 | 写插件、组装 agent、设计智慧盘点 |

## 本地阅读

```sh
pip install mkdocs-material   # 或用仓库内 .venv
mkdocs serve
```

浏览器打开 http://127.0.0.1:8000 。

## 发布站点

```sh
mkdocs gh-deploy   # 构建并推送到 gh-pages 分支（GitHub Pages）
```

## 许可证

书稿内容：**CC BY-NC-SA 4.0**（见 [LICENSE.md](LICENSE.md)）；构建配置与脚本：MIT。

## 状态

全书完稿（2026-08-19）。dsh 处于开发者预览阶段，接口可能变动，书稿以 2026 年 8 月中旬源码为准，阅读时以本机实跑为准。
