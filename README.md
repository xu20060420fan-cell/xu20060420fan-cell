# xu20060420fan-cell

开源小工具与自用项目。

| 项目 | 面向谁 | 仓库 |
| --- | --- | --- |
| **WorkBuddy2API Panel** | 用 AI 编程工具的人：WorkBuddy / CodeBuddy / Trae / Qoder / MiniMax / 豆包 / 华为云 CodeArts 全部账号收进一个面板，统一 OpenAI 兼容网关，全平台每日签到 | [workbuddy2api-trae-qoder-minimax-panel](https://github.com/xu20060420fan-cell/workbuddy2api-trae-qoder-minimax-panel) |
| **氢课表** | **安徽工业大学（安工大）**本科生的专用课表 App：绑定学号即自动同步课表、考试、成绩、签到 | [AHUT-timetable](https://github.com/xu20060420fan-cell/AHUT-timetable) |
| **氧课表 Wake Up（Oxgeny）** | **全体大学生**的全高校通用课表 App（Wake Up 课表），不限学校，导入课表就能用 | [WakeUp-timetable](https://github.com/xu20060420fan-cell/WakeUp-timetable) |

## WorkBuddy2API Panel 一句话

- WorkBuddy / CodeBuddy / Trae / Qoder / MiniMax / 豆包 Doubao / 华为云 CodeArts 码道 **多账号合集** → 一个 **OpenAI 兼容网关** + **Web 管理面板**。
- 账号池轮转、一键切号、断路冷却、会话粘性、**全平台每日签到与保活**、CodeArts 积分总览（每天可领 / 剩余 / 将过期）、成长任务一键完成。
- 模型按前缀分流：`cn:`（国服 CodeBuddy）、`global:`（国际版）、`trae:`、`minimax:`，同一套 `/v1/chat/completions` 与 `/v1/responses` 端点调用全部平台。
- 账号凭证只落本机 `auths/`、`data/`，**不入库**。
- 搜索词：`workbuddy` `workbuddy2api` `codebuddy` `trae` `qoder` `minimax` `doubao` `codearts` `码道` `openai api gateway` `openai 兼容` `账号池` `多账号` `自动签到` `每日签到` `保活` `反向代理` `管理面板`。

## 课表 App 一句话

- 安徽工业大学课表 / 安工大课表 / AHUT course schedule / 安徽工业大学 timetable → 看氢课表仓库。
- Wake Up 课表 / WakeUp timetable / 大学生课表 / 全高校通用课表 / 课表 App → 看氧课表仓库。

官网：<https://xspirt.online>（下载、晚寝签到、学习通签到都在网页上，不装 App 也能用）

## 其它开源小工具

- [chaoxing-auto-answer-script](https://github.com/xu20060420fan-cell/chaoxing-auto-answer-script) —— 超星学习通自动答题 / 刷课脚本（油猴脚本、浏览器扩展）
- [xiaoman-ble-protocol](https://github.com/xu20060420fan-cell/xiaoman-ble-protocol) —— 小满电动车 BLE 协议库（Kotlin 纯实现）
- [WinCleaner](https://github.com/xu20060420fan-cell/WinCleaner) —— Windows 清理与安全分析工具
