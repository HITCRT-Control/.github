<h1 align="center">HITCRT · Control Group</h1>

<p align="center"><strong>哈尔滨工业大学竞技机器人队 · 控制组</strong></p>
<p align="center">ROBOCON &nbsp;/&nbsp; Code &nbsp;/&nbsp; Experiments &nbsp;/&nbsp; Knowledge</p>
<p align="center"><em>极限犹可突破，至臻亦不可止。</em></p>

## 团队协作

我们参加 ROBOCON 机器人大赛，每个赛季围绕 R1、R2 两台机器人协作开发。

项目通常分为上层与下层：

- **上层**主要负责机器人的各种动作和任务功能。
- **下层**主要负责机器人的导航相关功能。

这只是常见的模块划分，不是固定岗位或固定编制。每个赛季的参与人数、负责人、任务边界和协作方式，由当季队员根据比赛任务、技术方案和实际进度自行安排。成员可以跨机器人、跨上下层协作。

## 仓库导航

- `control-new-member-training`：新成员培训、机构验证与协作练习
- `control-old-2026-archive`：2026 赛季 R1/R2 旧代码归档；公开前须完成安全与许可证检查
- `control-ros2-2027-competition`：2027 赛季 R1/R2 比赛代码，默认保持私有

## 协作约定

正式代码通过功能分支和 Pull Request 合并，`main` 应始终保持可编译、可运行。涉及上下层接口、消息定义、通信协议、坐标系或配置格式的修改，应同步相关成员并在 PR 中说明影响。请勿提交账号口令、密钥、网络凭据、构建产物或未经授权分发的第三方资料。

<p align="center"><strong>惟实 · 惟简 · 惟新 &nbsp;/&nbsp; 惟稳 · 惟强 · 惟快</strong></p>
