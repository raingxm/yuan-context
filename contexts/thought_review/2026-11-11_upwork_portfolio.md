# Upwork 首单与 RTC 作品集

2026-11-11

**先用 RTC Inbox 去谈一个可以独立验收的小项目。** 工单里同时出现录制故障和迁移意向，你做的系统让支持继续排障，让解决方案工程师接到有原文依据的跟进任务。这个案例能说明你怎么把 AI 加进客户已有流程，以及你会把哪个决定留给人。接下来最值得花时间的是把这个判断拍出来，拿它去换客户回复。

## 案例的辨识度来自你怎么处理工单

录制故障、迁移试点和一句「你们支持录制吗」可能出现在同一个队列里。最能体现你经验的是把三者分清，解释何时该排障、何时该追问、何时值得交接。90 秒录屏先展示混合工单里真正支持交接的原话，再点一次确认，让观众同时看见接手的人和仍开放的技术工单。最后用一句只问录制能力的工单收尾，展示系统会先追问。封面可以定格在「有负责人」和「支持仍开放」同时出现的一刻。用虚构工单，标注这是自建 demo。[项目规格](C:/Users/92551/Documents/repos/github/self-attention/plan/first-portfolio-project.md) · [工作台 README](C:/Users/92551/Documents/repos/github/rtc-support-to-sales-inbox/README.md)

代码校验了引文确实出现在工单里，审核者仍需判断那句话能否支持交接。建议在复验中加一条「客户明确否认正在迁移」的工单。关键字和原文引用都可能正确，正确动作却可能是继续排障。这个场景很适合展示你在公司做模型治理时形成的工程判断，也适合拿来和客户一起约定验收标准。[引文校验](C:/Users/92551/Documents/repos/github/rtc-support-to-sales-inbox/api/inbox.py:157)

## 用同一份作品验证两种购买理由

公开 Profile 可以先试 **Full-Stack Engineer | AI Workflows & RTC Integrations**。对有支持或运营流程的客户，提案里用这个案例证明你能把一段 AI 建议嵌进现有界面，由人确认后执行。对有实时音视频需求的客户，优先找录制、SDK 集成或迁移故障的小项目，提案用你自己的 RTC 经验说明排查方法。这个 demo 的 RTC 场景可以辅助讲解。客户明确采购 Coding Agent 工具或评测时，再拿一份真实 PR 及复跑结果证明那项能力。对客户来说，会用 Coding Agent 可以提升交付效率。只有客户需要改善自己的编码流程时，这才是他采购的对象。[当前文案](C:/Users/92551/Documents/repos/github/self-attention/plan/copy.md) · [方向](C:/Users/92551/Documents/repos/github/self-attention/plan/direction.md)

样本里有客户要给支持流程加审批，也有客户要给广告 Agent 加预算审批。这两条帖子说明「有证据、审批后才执行」可以跨行业解释。反过来，一条明确要求会用 Coding Agent 的全栈帖同时要求每周超过 30 小时，与现有时间不合。样本有搜索词、排序与截断偏差，适合提炼客户措辞和过滤条件。现有搜索未专门覆盖 RTC，值得用一小段时间独立验证，现有样本不能估计这个方向的供需。[支持流程样本](C:/Users/92551/Documents/repos/github/self-attention/plan/job-sample/022118244251001985105.md) · [广告审批样本](C:/Users/92551/Documents/repos/github/self-attention/plan/job-sample/022118426127350499587.md) · [全栈样本](C:/Users/92551/Documents/repos/github/self-attention/plan/job-sample/022118265442407042544.md) · [采集记录](C:/Users/92551/Documents/repos/github/self-attention/plan/job-sample/_run.md)

## 让下一次开发来自客户反馈

用一个晚上把录屏和作品卡收尾。原计划的 8 条投递可以先分成 4 条「给现有产品加一个需要人审核的 AI 步骤」和 4 条「RTC/全栈的明确小改动」。4+4 是试投配额。找不到够匹配的 RTC 帖时，记下缺口，把余下名额给符合约束的全栈小单。每条先写清能独立交付的第一步、验收条件和需要客户给的材料。按实际投递日记下提案是否获看（页面有显示时）、有效回复和客户追问。现有两周预算边界照原计划保留。如果 8 条没有有效回复，先用记录判断是否卡在岗位筛选、提案开头、作品相关性或可用工时，再决定要改什么。小样本只够提示下一步，无法给整个方向判输赢。[当前行动](C:/Users/92551/Documents/repos/github/self-attention/plan/this-week.md) · [Upwork 提案与作品附件说明](https://support.upwork.com/hc/en-us/articles/211062998-How-to-submit-a-proposal-on-Upwork)

工作日每天约 3～4 小时，首单的价值也包括验证这种合作能否长期并入你的生活。第一阶段可以报价做一段清楚的流程或一次带复现记录的诊断，把扩展放进后续里程碑。优先争取书面需求、异步反馈和可预期的支持边界。有客户反复愿意为某一段交付付钱，再考虑做模板或加 CRM 集成。[时间和合作约束](C:/Users/92551/Documents/repos/github/self-attention/plan/direction.md)

<details>
<summary>本次核验范围</summary>

- 以两个仓库当前本地内容为准。作品仓库最新提交为 `fb68ea9`，计划仓库有进行中的职位帖采集。《本周动作》保留 11 月 3 日的旧项目与待办，无法据此判断当前 Upwork 投递状态。
- `npm.cmd run verify` 两条浏览器测试通过，覆盖三张工单及新来信的原文校验路径。新来信测试用固定模型响应。Python 测试 3 通过、2 跳过，跳过项需要 PostgreSQL 测试连接。真实模型和数据库本次未联跑。
- 本地语义检索服务连接超时。对近期工作与偏好的判断依据为你指定的仓库、当前对话和工作区约定。

</details>

