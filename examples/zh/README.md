# 中文示例库

idea-killer 不是模板填空。这里全是**真实跑出来的判决与本地状态**：

- `PROFILE.md` —— 作者画像的脱敏示例（决定后续每个 idea 的 founder-fit 分）
- `signatures.jsonl` —— 失败结构指纹示例（用来 dedup 换皮 idea）
- `sample-*.md` —— 三个示例，演示 Kill / Pivot / Go 各长什么样
- `01-*.md` ~ `10-*.md` —— 作者自己 30 天内被 idea-killer 压测过的 10 个真方向，**全部 Kill 或 Pivot**

## 真实档案：作者自己的 10 连判决

按时间倒序。每一份报告都是 idea-killer 在真实对话中产出，没有事后修饰。

| # | Idea | Verdict | 压测分 | 最致命假设 |
|---|---|---|---|---|
| 10 | [跨境电商 AI 代运营数字员工](10-cross-border-ai-operator.md) | Kill | 3.8 | "高客单 AI 数字员工 + 我能切进去做差异化" → 没跨境 know-how + 没卖家入口 |
| 09 | [跨境电商选品 Agent](09-cross-border-selection-agent.md) | Kill | 3.5 | "AI 热潮 + 大热赛道 = 我能切进去" → 头部全部已 AI 化 + 无 know-how |
| 08 | [运动软件机会地图（教练/俱乐部 SaaS）](08-sports-app-opportunities.md) | **Pivot** | 6.3 | 从 C 端健身工具 Pivot 到 B 端教练工作流 |
| 07 | [健身记录 + AI 视频实时教练](07-fitness-tracker-ai-coach.md) | Kill | 2.5 | "在家健身用户会为 AI 视频教练付费" → Keep 卡卡免费同款都没人付费 |
| 06 | [主动式推荐推送号 v2](06-proactive-recommendation-push.md) | Kill | 3.3 | 与 v1 几乎同构，二次换皮 |
| 05 | [AI 主动推送号（公域+私域+UGC）](05-proactive-push-channel.md) | Kill | 3.0 | 用户研究反向证明：解药是减法不是加法 |
| 04 | [GTM 案例内容 IP → 主动推荐产品](04-gtm-stories-content-to-product.md) | Kill | 3.5 | 阶段 1 = 创作者工具同构；阶段 2 = 垂类推荐死路换皮 |
| 03 | [开源 Memory SDK（主动调度）](03-ai-memory-sdk-proactive.md) | **Pivot** | 5.0 | 主线对齐但形态错——建议 Pivot 到「业务内核」 |
| 02 | [Pre-session Memory 可视化管控](02-pre-session-memory-control.md) | Kill | 4.0 | 与 #01 结构同构 |
| 01 | [GPT 聊天信息管理工具](01-gpt-chat-history-manager.md) | Kill | 4.6 | C 端工具 + 通用 AI 即将原生覆盖 |

**10 个 idea，8 Kill / 2 Pivot / 0 Go。**

## ⭐ 元案例：第 10 个 Kill 后才出现的真正价值

最有用的不是任一份单独的 Kill。**是连续 9 个 Kill 之后，skill 主动停下来做的诊断**：

> "你前 9 个 idea 全 Kill 不是因为 idea 想得不够多。
> 是因为我之前对你画像的'非对称优势'本身是光环假设——
> 落到真竞争层（不是简历层），你在每条赛道都是 0。
> 这是画像错配的直接产物。"

skill 没有再推第 10 个 idea，而是给了三条根本性选项（找合伙人 / 降级预期做副业 / 蓄力 6 月进圈），让作者首次跳出"再选一个 idea"的循环。

详情：见仓库 README 的 [「meta-twist」section](../../README.md#meta-twist第-10-个-kill-后才出现的真正价值)。

## 这 10 份报告里反复出现的 4 种失败结构

idea-killer 的真正能力不是逐个判 Kill，是**识别同一个 founder 在反复换皮做同一种死法**。这 10 份报告看起来是 10 个不同方向，结构上只是 4 种重复模式：

### ① 外行做高信任/高 know-how 垂直

- #07 健身、#09 跨境选品、#10 跨境代运营

### ② 软价值订阅 + C 端不付费

- #01 #02 #04 #05 #06

### ③ 通用 AI 6-12 月内会原生覆盖

- #01 #02 #05 #06

### ④ 渠道与 founder 画像不匹配

- 几乎全部 idea 都需要内容 IP / 视频出镜 / 线下 BD —— 但 founder 是内向工程背景，没有这些通道

## 三种 Verdict 模板

| 文件 | Verdict | 看点 |
|---|---|---|
| [sample-go-report.md](sample-go-report.md) | Go | Channel / craft / delivery 三向匹配 |
| [sample-pivot-report.md](sample-pivot-report.md) | Pivot | 市场是真的，但当前切法和 founder 不匹配 |
| [sample-kill-report.md](sample-kill-report.md) | Kill | 高信任垂直 + founder 没行业入口 + 不愿 BD |

## 怎么读这些报告

每份报告都包含：

- `verdict` + `score_pressure`
- 5 硬条件 Gate 表
- 8 维评分明细
- 最致命假设 / 最关键发现
- falsification condition（什么证据能推翻 Kill）
- 1-2 个 reshape（如果你不想完全放弃）

关键不是分数，是 `cap_reason` —— 把方向死掉的原因，落到一句关于"你这个人"的话上。
