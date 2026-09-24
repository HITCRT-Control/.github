<h1 align="center">HITCRT · Control Group</h1>

<p align="center"><strong>哈尔滨工业大学竞技机器人队 · 控制组</strong></p>
<p align="center">ROBOCON &nbsp;/&nbsp; Code &nbsp;/&nbsp; Experiments &nbsp;/&nbsp; Knowledge</p>
<p align="center"><em>极限犹可突破，至臻亦不可止。</em></p>

## 团队协作

我们参加 ROBOCON 机器人大赛。每个赛季围绕两台机器人协作开发：

- **R1**：一名上层电控 + 一名下层电控
- **R2**：一名上层电控 + 一名下层电控

上层侧重 ROS 2、任务流程、感知/决策与机器人间协同；下层侧重执行机构、传感器、实时控制与硬件通信。具体边界以当年方案为准，四名电控共同维护接口、配置、联调记录和比赛版本，不把机器人或上下层做成彼此隔离的信息孤岛。

## 仓库导航

- `control-new-member-training`：新成员培训、机构验证与上下层接口练习
- `control-old-2026-archive`：2026 赛季 R1/R2 旧代码归档；公开前须完成安全与许可证检查
- `control-ros2-2027-competition`：2027 赛季 R1/R2 比赛代码，默认保持私有

## 协作约定

正式代码通过功能分支和 Pull Request 合并，`main` 应始终保持可编译、可运行。涉及上下层接口、消息定义、通信协议、坐标系或配置格式的修改，必须同步通知同机器人搭档，并在 PR 中说明影响。请勿提交账号口令、密钥、网络凭据、构建产物或未经授权分发的第三方资料。

<p align="center"><strong>惟实 · 惟简 · 惟新 &nbsp;/&nbsp; 惟稳 · 惟强 · 惟快</strong></p>
