### 你好，我是 krictfus 👋

普通 Linux 运维，正在从"传统运维"往 **自动化 / 平台方向** 走。
Red Hat 认证 **RHCA** 等 8 项（[点这里一键核验](https://rhtapps.redhat.com/verify?certId=250-056-041)）。
代码借助 AI 完成；**架构、约束与取舍由我自己定义并负责**。

---

## 作品 / Projects

### [agentless-fieldkit](https://github.com/krictfus/agentless-fieldkit)

**拎包入驻"三无机房"的现场批量任务工具**（无平台 / 无预置凭据 / 无台账）：
给它一份主机清单 + 一份你自己的脚本，它负责下发一次性密钥、并行执行、按台回收产物、
五分类结果，目标机**零残留**（含失败与中断路径）。操作者只需要会 `cd` 和 `vi`。

- **实测数字**：三层漏斗让「2 台可达 + 1 台口令错 + 1 台不可达」从 **138 秒降到 21 秒**；单台端到端约 10~12 秒
- **工程质量**：离线自检 `selftest.sh`；逐行评审修复记录（[docs/REVIEW.md](https://github.com/krictfus/agentless-fieldkit/blob/main/docs/REVIEW.md)）；
  中断语义实测——Ctrl-C 不再被报成"成功"（v3.4.2）
- **定位诚实**：与 Ansible EE / Puppet Bolt / Fabric / OliveTin 等的逐项对照写在 README 第 5 节——
  它不是"更好的平台"，是"没有平台可依赖时的作战包"
- 文档：[README（中文权威版）](https://github.com/krictfus/agentless-fieldkit/blob/main/README.md) ·
  [设计理念](https://github.com/krictfus/agentless-fieldkit/blob/main/docs/DESIGN.md) ·
  [实战记录](https://github.com/krictfus/agentless-fieldkit/blob/main/docs/实战记录.md)

---

**English** — A Linux ops engineer moving from classic operations toward automation / platform work.
RHCA plus seven more current credentials (verifiable above). Main project:
[agentless-fieldkit](https://github.com/krictfus/agentless-fieldkit) — a walk-in batch task runner for
"three-nothing" sites (no platform, no pre-provisioned credentials, no inventory): containerized,
agentless, payload-pluggable, zero residue on targets. Code is written with AI assistance; the
architecture, constraints and trade-offs are my own. **Chinese docs are authoritative on this account.**
Feedback is very welcome — issues and PRs please.
