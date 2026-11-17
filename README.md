# 初高中提分口播文案大师 · Spoken Script Rewrite Master

> 给一个教育话题，或者贴一段已有文案。从 15 个开头里挑一句你愿意对镜头说的，拿到一篇约 400 字、可以直接拍的抖音口播稿。

**技能名** `spoken-script-rewrite-master` · **作者** [Yujie Chen](https://github.com/Yu-Jie-Chen) · [查看技能入口](skills/spoken-script-rewrite-master/SKILL.md)

## 它解决什么问题

老师想拍一期“我教学生学好物理的三个秘诀”，提纲上写着“重视基础、勤于思考、举一反三”。道理都对，可镜头一开，第一句话怎么说？如果花一分钟讲浮力，又容易把一期学习方法视频讲成一道题的解析。

这个技能帮老师把**教什么、讲给谁、第一句怎么开口**想清楚。讲给学生，可以从“一听就懂，一写就卡？”切入；讲给家长，可以从“答案一遮，孩子还会吗？”切入。同一个知识点，观众换了，开头、例子和最后请对方做的事也跟着换。

## 快速开始

**安装到 Codex。** 把下面这句话发给能访问本仓库的 Codex：

```text
请从 https://github.com/Yu-Jie-Chen/Spoken_Script_Rewrite_Master 安装
skills/spoken-script-rewrite-master 这个技能。
```

手动安装时，先克隆仓库，再把 [spoken-script-rewrite-master 整个文件夹](skills/spoken-script-rewrite-master/) 复制到 Codex 的技能目录。默认装好后，入口位于 `~/.codex/skills/spoken-script-rewrite-master/SKILL.md`；设置了 `CODEX_HOME` 时，使用该目录下的 `skills` 文件夹。

```bash
git clone https://github.com/Yu-Jie-Chen/Spoken_Script_Rewrite_Master.git
```

**在新对话里给一个主题。** 年级、学科、想说给谁听，这些信息有多少就写多少。例如：

```text
用 $spoken-script-rewrite-master 策划一条抖音口播：
我教学生学好物理的三个秘诀。讲给学生听，例子点到为止。
```

## 两轮对话会拿到什么

| 什么时候 | 你会看到什么 |
|---|---|
| 发出主题或原稿后 | 一次收到四张表：目标用户分析、热门话题与关键词、10 个选题方案、15 个开头模板。每个开头都写出可以直接念的前两句话。 |
| 看到喜欢的开头时 | 回复开头表里的序号，例如 `8`。也可以写“8，戳中痛点”。序号对应本轮生成的开头。 |
| 选定开头后 | 直接收到约 400 字、约一分半钟的纯文本口播稿。所选第一句独立成行，下一段接第二句。正文用一个具体场景展开，给观众一个能试的方法，最后自然收束。 |

**成稿预览（节选）**

> 一听就懂，一写就卡？
>
> 咱就停在你拿起笔、还没写下第一个字的那一秒。
>
> 上课的时候，老师说“先画个图”，你会画；老师说“看这个条件”，你也看得懂。可回家把书一合，没人提醒第一步了。

## 常用场景

| 手头有什么 | 可以直接这样说 |
|---|---|
| 一个课堂上反复遇到的问题 | “贵阳初三数学，孩子错题本抄满了，同类题还是错。拍给陪孩子复习的家长看。” |
| 一个家长拿不定主意的话题 | “高考选学校、专业还是城市？讲给贵阳高三家长，每个分数段给一句能用的建议。” |
| 一段写得像讲义的原稿 | “把下面这段改成老师对镜头说的话。保留三个方法，例子留一个就够。”然后粘贴原稿。 |
| 一篇已经生成的口播稿 | “这版太像在讲浮力题。把重点放回三个学习方法，例子点到为止，语气再口语化一点。” |

## 内容与素材

“热门话题”表会注明判断依据。有近期公开资料时，可以用来支撑选题；缺少热度数据时，按“常见问题”或“选题推测”表述。改写已有文案时保留原意和可核实的事实。涉及课堂素材，只提炼获准用于口播的内容，文件名、路径和学生隐私留在稿外。

## 仓库结构

```text
Spoken_Script_Rewrite_Master/
├── README.md
└── skills/
    └── spoken-script-rewrite-master/
        ├── SKILL.md             # 选题、开头、成稿与续聊规则
        └── agents/openai.yaml   # Codex 中的展示名称和默认调用示例
```

## 相关项目

- 把一道错题整理成可讲、可复习的错题卡。[错题整理 · Mistake Question Studio](https://github.com/Yu-Jie-Chen/mistake-question-studio)
- 从整份试卷定位失分原因，安排下一阶段训练。[试卷分析 · Exam Analysis Studio](https://github.com/Yu-Jie-Chen/exam-analysis-studio)
- 根据课程录屏、逐字稿和纪要生成家长能读懂的反馈报告。[试听课反馈与学情诊断 · Trial Feedback Studio](https://github.com/Yu-Jie-Chen/trial-feedback-studio)

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
