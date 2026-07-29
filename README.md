# Stephen Skills

可重复安装、持续维护的个人 Codex Skill 仓库。每个 Skill 都位于 `skills/<skill-name>/` 目录。

## 使用约定

每个 Skill 只提供一个 GitHub 目录链接作为学习与安装的唯一主入口。复制对应 Skill 下方的整段文字发给 Agent 即可；飞书文档作为完整方法论与使用说明。

## Skill 索引

### AI会议纪要｜会议分析、诊断与行动闭环

基于飞书会议产物、用户粘贴的文字或上传的逐字稿与会议资料，生成精炼、证据化、可执行的 Stephen 风格 AI 会议纪要。

- Skill 目录：https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/ai-meeting-minutes
- 触发方式：`AI会议纪要`、`帮我总结纪要云文档`、`整理一下昨天的会`、`分析或诊断这场会议` 或 `$ai-meeting-minutes`

复制下面一整行发给豆包、Codex、Claude 或其他 Agent：

```text
请安装或学习并使用这个「AI会议纪要」Skill：支持 $skill-installer 时直接安装；不支持时请读取目录内的 SKILL.md、references 和 assets 后遵循执行。https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/ai-meeting-minutes
```

这个 GitHub 目录是唯一公开入口：支持 Skill 安装的 Agent 直接安装；不支持安装机制的 Agent 读取目录内容后按方法执行。

### Stephen 圆桌｜开放探索与圆桌求真

让思想发生碰撞，让碰撞相互启发，让启发形成共识，让共识形成决策。默认不限轮数地探索；用户说“圆桌求真”后，才对关键命题进行证据审判，保留真实分歧并形成暂时最优判断。

- Skill 目录：https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/stephen-roundtable
- 触发方式：`圆桌讨论`、`发起或继续圆桌`、`组织几位专家讨论`、`圆桌求真` 或 `$stephen-roundtable`

复制下面一整行发给豆包、Codex、Claude 或其他 Agent：

```text
请安装或学习并使用这个「Stephen 圆桌」Skill：支持 $skill-installer 时直接安装；不支持时请读取目录内的 SKILL.md 和 references 后遵循执行。https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/stephen-roundtable
```

这个 GitHub 目录是唯一公开入口。真实人物必须与议题直接相关；无法核验的发言须标注为思想体系推演。何时从探索转向求真，由用户决定。

### Stephen 精读｜书籍、播客与视频

以证据还原表达者，以反方校准观点，以现实检验判断，以记忆形成复利。支持书籍、播客和视频三条内容路由，形成可回溯的原文或原话金句、精读笔记、个人校准、行动实验和长期记忆。

- Skill 目录：https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/stephen-deep-read
- 触发方式：`把这本书精读一下`、`把这个播客细听一下`、`把这个视频精读一下`、`细看一下`、`精度一下` 或 `$stephen-deep-read`

复制下面一整行发给豆包、Codex、Claude 或其他 Agent：

```text
请安装或学习并使用这个「Stephen 精读」Skill：支持 $skill-installer 时直接安装；不支持时请读取目录内的 SKILL.md、references 和 assets 后遵循执行。https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/stephen-deep-read
```

这个 GitHub 目录是唯一公开入口。书籍沿论证单元和页码，播客沿对话语义段和时间码，视频沿语义镜头和时间码；三类内容共享同一套证据、金句、校验、行动与记忆闭环。

### AVM｜确认式任务协议

把模糊请求转化为双方确认的任务协议，再执行任务。A 定义角色与知识视角；V 定义对象、结果、使用者与用途；M 定义步骤、输出结构、判断标准与验收方式。

- Skill 目录：https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/avm
- 触发方式：`按照 AVM 答复`、`用 AVM`、`AVM 模式`、`先按 AVM 确认` 或 `$avm`

复制下面整句话发给 Codex：

```text
请使用 $skill-installer 安装这个 Skill：https://github.com/lizechen228-hue/stephen-skills/tree/main/skills/avm
```

Codex 支持从这个 GitHub 目录原生安装。Aily SkillHub 当前未上架 AVM，因此在 SkillHub 搜不到安装包是正常现象；可先把 `SKILL.md` 全文放入 agent 知识或系统提示，并以“按照 AVM 答复”“用 AVM”作为语义触发。若要获得 Aily 原生 SkillHub 触发，需要在后台提交上架申请。
