### Hi, I'm krictfus 👋

**English** — An ordinary Linux ops engineer moving from *classic operations* towards *automation / platform*
work. **I have just started using GitHub**; this profile and my project are my first serious attempt here.
Code is written with AI assistance — the architecture, the constraints and the lessons learned came from my
own field work. Red Hat certified: **RHCA** plus seven more current credentials (verifiable in one click
below). Main project: [agentless-fieldkit](https://github.com/krictfus/agentless-fieldkit) — a
payload-pluggable batch task runner for isolated, no-platform environments. **Feedback is very welcome.**

---

### 你好，我是 krictfus

普通的 Linux 运维，正在从"传统运维"往 **自动化 / 平台方向** 走。

- 🔭 目前在做：**[agentless-fieldkit](https://github.com/krictfus/agentless-fieldkit)** —— 面向隔离网络、
  无平台环境的**载荷可替换批量任务框架**
- 🌱 正在学：Redhat知识体系 ；**GitHub 刚上手**
- 💬 交流：欢迎开 issue 或直接找我。
  **代码借助 AI 完成，但架构、理念、踩坑是我自己实现的**

---

## 作品 / Projects

### [agentless-fieldkit](https://github.com/krictfus/agentless-fieldkit)

载荷可替换的批量任务执行框架：给它一份主机清单 + 一份你自己的脚本，它负责下发一次性密钥、并行执行、
按台回收产物、分类结果，并在目标机上**零残留**（含失败路径）。
**不需要平台、不需要预置凭据，操作者只需要会 `cd` 和 `vim`。**

- 实测：三层漏斗让"2 台可达 + 1 台口令错 + 1 台不可达"从 **138 秒降到 21 秒**；单台端到端约 10~12 秒
- 最新版本：[**v3.4.0**](https://github.com/krictfus/agentless-fieldkit/releases/tag/v3.4.0)
  （Release 附件含控制端镜像，附 sha256 可校验）
- 中文说明（权威版本）：[README.md](https://github.com/krictfus/agentless-fieldkit/blob/main/README.md)
- 设计理由（为什么这么设计）：[docs/DESIGN.md](https://github.com/krictfus/agentless-fieldkit/blob/main/docs/DESIGN.md)

---

> 中文文档是这个账号的权威版本；英文内容以摘要为主。
> The Chinese docs are authoritative on this account; English content is mostly summary.
