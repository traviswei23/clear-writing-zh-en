# 493 项写作技能怎样用到这份手册中

这份对照覆盖 2026 年 11 月 22 日调研清单中的 493 个技能入口，来自 475 个公开仓库。同仓的语言版本、仅审阅入口和改稿入口可以分别列出。不同项目重复提出的做法共用一个判断方法。这个数字表示本次检索的范围，GitHub 上还会出现新项目。

每行给出来源正文、选取的一条写作做法，以及本技能中实际对应的判断。“通用”表示可以在常规写作中直接检查。“按场景”表示须先确认文体、读者或编辑权限。有特定工具、篇幅或风格偏好的来源另写处理办法。表中记录的是采纳点，完整的上游流程与其他要求可点开原文查看。扩展条目的链接带有调研时的行号，源文件更新后行号可能移动。

日常写作从[技能入口](../SKILL.md)选择手册。要找某个仓库，用浏览器或编辑器搜索作者名。要看相同建议如何合并，在本页搜索对应规则名。

## 直接回答与进度消息（31）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 1 | [molang163/chinese-natural-reply · chinese-natural-reply](https://github.com/molang163/chinese-natural-reply/blob/main/skills/chinese-natural-reply/SKILL.md) | 先答用户问的事，再补原因。进度消息也去掉自我辩护和套话。 | [直接作答](decision-rules.md#answer) | 通用 |
| 2 | [huzhongyyuan/anti-defensive-writing](https://github.com/huzhongyyuan/anti-defensive-writing/blob/main/SKILL.md) | 汇报时交代实际进展与依据，把真正影响判断的不确定性说一次。 | [进展与纠错](decision-rules.md#status) | 按场景 |
| 3 | [HarryWeasley3/anti-defensive-writing · anti-defensive-writing](https://github.com/HarryWeasley3/anti-defensive-writing/blob/main/anti-defensive-writing/SKILL.md) | 把含糊的限定改成具体条件。纠正观点后，正文里也要清掉旧说法。 | [进展与纠错](decision-rules.md#status)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 4 | [smartcmd/humanizer](https://github.com/smartcmd/humanizer/blob/main/SKILL.md) | 检查每个无对象的否定式对比。先写事情实际怎样，再判断读者是否需要例外。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 5 | [ehmo/slopkit · slopgent](https://github.com/ehmo/slopkit/blob/main/skills/slopgent/SKILL.md) | 先交代做了什么、实际验证了什么。结论以外行能读懂的方式呈现。 | [进展与纠错](decision-rules.md#status) | 按场景 |
| 6 | [hexiecs/talk-normal · skill](https://github.com/hexiecs/talk-normal/blob/main/skill/SKILL.md) | 从回答中去掉复述问题、客服式开场和无信息量的缓冲语。规则可写入工作区的长期指令。 | [直接作答](decision-rules.md#answer) | 通用 |
| 7 | [chang416/im-human](https://github.com/chang416/im-human/blob/main/SKILL.md) | 用户开启语态模式后，每条回复都按对应语言的口语习惯写。编辑模式另行处理原稿。 | [作者声音](decision-rules.md#voice)、[编辑权限](decision-rules.md#scope) | 用户选择后使用特定语气 |
| 8 | [susuky/im-human](https://github.com/susuky/im-human/blob/main/SKILL.md) | 专门处理代理汇报里过多的免责与复盘语气，也检查行销用语。 | [进展与纠错](decision-rules.md#status)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 9 | [NTCoding/claude-skillz · concise-output](https://github.com/NTCoding/claude-skillz/blob/main/concise-output/SKILL.md) | 答复只交代问题需要的信息，压缩例行确认、铺垫和重复说明。 | [直接作答](decision-rules.md#answer) | 通用 |
| 10 | [jagreehal/jagreehal-claude-skills · concise-output](https://github.com/jagreehal/jagreehal-claude-skills/blob/main/skills/concise-output/SKILL.md) | 压缩重复解释和凑篇幅的段落，尤其重视短答。 | [直接作答](decision-rules.md#answer) | 通用 |
| 11 | [denfry/claude-skills · token-efficiency](https://github.com/denfry/claude-skills/blob/main/skills/token-efficiency/SKILL.md) | 在每次答复中控制冗余，连贯叙述和任务说明也按信息量取舍。 | [长文结构](decision-rules.md#structure) | 通用 |
| 12 | [loulouzy/skills-for-gpt · concise-response](https://github.com/loulouzy/skills-for-gpt/blob/main/concise-response/SKILL.md) | 回答和报告都先放结论，再用准确的常用词解释。 | [直接作答](decision-rules.md#answer) | 通用 |
| 13 | [handsomeZR-netizen/claude-code-style-skill](https://github.com/handsomeZR-netizen/claude-code-style-skill/blob/main/SKILL.md) | 终端工作汇报要求短而具体，用文件位置指向实际变动。 | [进展与纠错](decision-rules.md#status) | 按场景 |
| 14 | [Galaxy-Dawn/expression-skill](https://github.com/Galaxy-Dawn/expression-skill/blob/main/SKILL.md) | 工作汇报从读者要做的决定或行动写起，并交代依据。 | [进展与纠错](decision-rules.md#status) | 按场景 |
| 15 | [DeVenLucaz/Elucid](https://github.com/DeVenLucaz/Elucid/blob/main/SKILL.md) | 在回答问题时同步解释行话，适合学习型对话。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 16 | [krismakesstuff/deslop](https://github.com/krismakesstuff/deslop/blob/main/SKILL.md) | 去掉助手习惯性的前言、复述和无依据的软化语。 | [直接作答](decision-rules.md#answer) | 通用 |
| 17 | [suenyiyang/human-talk-skill](https://github.com/suenyiyang/human-talk-skill/blob/main/SKILL.md) | 把含糊、冗长的工作答复改为读者能直接使用的信息。 | [直接作答](decision-rules.md#answer) | 通用 |
| 18 | [sanjusss/shuorenhua](https://github.com/sanjusss/shuorenhua/blob/master/SKILL.md) | 按读者决定在回复、说明文档或代码注释里需要解释哪些术语。 | [通俗解释](decision-rules.md#plain)、[变更与代码](decision-rules.md#engineering) | 通用 |
| 19 | [Haor/speak-human](https://github.com/Haor/speak-human/blob/main/SKILL.md) | 报告和调查结果先交代读者需要的实际结论，再给相关依据。 | [直接作答](decision-rules.md#answer) | 通用 |
| 20 | [Jonty-Zhang/speak-human](https://github.com/Jonty-Zhang/speak-human/blob/main/SKILL.md) | 手动开启熟人聊天口吻，只影响对话里的中文消息。 | [作者声音](decision-rules.md#voice) | 熟人聊天限定 |
| 21 | [gabrielmongefranco/privatium-app-meds · response-style](https://github.com/gabrielmongefranco/privatium-app-meds/blob/main/skills/response-style/SKILL.md) | 在工作讨论、审阅意见和界面文案中使用自然英语，明确谁做什么。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 22 | [juliusbrussee/caveman · caveman](https://github.com/juliusbrussee/caveman/blob/main/skills/caveman/SKILL.md) | 把回答压缩成电报式短语。适合看极短状态，完整文章会有刻意的文风。 | [进展与纠错](decision-rules.md#status)、[直接作答](decision-rules.md#answer) | 只取压缩冗词，极短句按需 |
| 23 | [chenyongquan2/plain-chinese-skills · no-wenyan](https://github.com/chenyongquan2/plain-chinese-skills/blob/main/no-wenyan/SKILL.md) | 把工程团队内部绰号、压缩过头的动词换成读者认识的动作。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 24 | [chenyongquan2/plain-chinese-skills · wait-what](https://github.com/chenyongquan2/plain-chinese-skills/blob/main/wait-what/SKILL.md) | 上一条没讲明白时触发重讲，让助手用另一种方式解释。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 25 | [Mark-Life/agent-skills · agent-to-human](https://github.com/Mark-Life/agent-skills/blob/main/skills/communication/agent-to-human/SKILL.md) | 任务结束时按人要读的消息组织回复，覆盖交接、摘要与状态汇报。 | [进展与纠错](decision-rules.md#status) | 按场景 |
| 26 | [monasprox/humanizer](https://github.com/monasprox/humanizer/blob/main/SKILL.md) | 提供即时回复和修改现稿两种用法。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 27 | [junlinwk/tw-humanizer-skills](https://github.com/junlinwk/tw-humanizer-skills/blob/main/SKILL.md) | 按闲聊、求助、意见冲突或教学等语境调整说话方式。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 28 | [JacobYim/plain-writing](https://github.com/JacobYim/plain-writing/blob/master/SKILL.md) | 以读者能一遍读懂为目标，要求每条事实与主张有据可依。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 29 | [Shourya-Thoota/humanizer](https://github.com/Shourya-Thoota/humanizer/blob/main/SKILL.md) | 对普通答复采用轻量的写作要求，另有改稿和声线匹配模式。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 30 | [iizcm/stop-slop-skill](https://github.com/iizcm/stop-slop-skill/blob/main/SKILL.md) | 规则针对助手自己的每条答复，逐项删除开场废话和套路句。 | [直接作答](decision-rules.md#answer) | 通用 |
| 31 | [Solvync/humanizer](https://github.com/Solvync/humanizer/blob/main/SKILL.md) | 将自然写作规则用于邮件、聊天消息及其他面向读者的文字。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |

## 反防御性写作与修订（43）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 32 | [Devilyuu/anti-defensive-writing-zh](https://github.com/Devilyuu/anti-defensive-writing-zh/blob/main/SKILL.md) | 按目标读者删去自我削弱和重复免责。保留会影响判断的范围、风险和作者口吻。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 33 | [Kiterlin/anti-defensive-writing · anti-defensive-writing](https://github.com/Kiterlin/anti-defensive-writing/blob/main/skill/anti-defensive-writing/SKILL.md) | 正面说出证据支持的结论，把方法限制写在真正影响解读的位置。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 34 | [EtherealClarity/remove-defensive-writing-skill](https://github.com/EtherealClarity/remove-defensive-writing-skill/blob/main/SKILL.md) | 写前找准主张，再删掉提前反驳、假平衡以及反复解释自己没说什么。 | [否定、反例与排比](decision-rules.md#contrast)、[限定与防御](decision-rules.md#limit) | 通用 |
| 35 | [zalee6666-crypto/anti-defensive-writing](https://github.com/zalee6666-crypto/anti-defensive-writing/blob/main/SKILL.md) | 逐条判断限定语的用途，用最小改动留下证据所需的不确定性。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 36 | [Yila-AI/awesome-defensive-writing · yila-clear-writing](https://github.com/Yila-AI/awesome-defensive-writing/blob/main/skills/yila-clear-writing/SKILL.md) | 从报告、邮件与公开说明里删减防御性填充，保留能指导读者行动的内容。 | [渠道与工作消息](decision-rules.md#channel)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 37 | [0118Zimu/anti-defensive-writing-general](https://github.com/0118Zimu/anti-defensive-writing-general/blob/main/SKILL.md) | 按目标读者和证据检查无谓的道歉、免责和层层保留。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 38 | [git-zyyang/anti-defensive-writing · anti-defensive-writing](https://github.com/git-zyyang/anti-defensive-writing/blob/main/skill/anti-defensive-writing/SKILL.md) | 对每个限定判断它是否真的改变主张，并补够解释。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 39 | [ShiyuanDong-Robot/anti-defensive-writing](https://github.com/ShiyuanDong-Robot/anti-defensive-writing/blob/main/SKILL.md) | 用直接陈述替换先虚设反方、再否定反方的套式。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 40 | [wzk1015/Codex-Humanize-Skill](https://github.com/wzk1015/Codex-Humanize-Skill/blob/main/SKILL.md) | 先弄清读者要做什么，再把分散的要求放在一起，删除防御性话术。 | [长文结构](decision-rules.md#structure)、[限定与防御](decision-rules.md#limit) | 通用 |
| 41 | [ggbondpromax666/humanize-writing-skill · humanize-en](https://github.com/ggbondpromax666/humanize-writing-skill/blob/main/skills/humanize-en/SKILL.md) | 分开处理防御性措辞和过度解释，删去重复定义与虚设反方。 | [否定、反例与排比](decision-rules.md#contrast)、[通俗解释](decision-rules.md#plain) | 通用 |
| 42 | [ggbondpromax666/humanize-writing-skill · humanize-zh](https://github.com/ggbondpromax666/humanize-writing-skill/blob/main/skills/humanize-zh/SKILL.md) | 先看证据和读者，再清理自贬、层层限定及重复交代背景。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 43 | [zhu-chen/anti-defensive-writing-tutorial · anti-defensive-writing-tutorial-en](https://github.com/zhu-chen/anti-defensive-writing-tutorial/blob/main/skills/anti-defensive-writing-tutorial-en/SKILL.md) | 教程里把必要限制写成条件和后果，把选择理由说清楚。 | [可执行的说明](decision-rules.md#procedure)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 44 | [zhu-chen/anti-defensive-writing-tutorial · anti-defensive-writing-tutorial](https://github.com/zhu-chen/anti-defensive-writing-tutorial/blob/main/skills/anti-defensive-writing-tutorial/SKILL.md) | 教学材料直接说明机制，用发生条件和结果代替反复声明适用边界。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 45 | [OvOYu/anti-defensive-writing](https://github.com/OvOYu/anti-defensive-writing/blob/main/SKILL.md) | 保留重要反例和真实不确定性，默认小改。技能明确排除一般问答。 | [编辑权限](decision-rules.md#scope)、[限定与防御](decision-rules.md#limit) | 用于已有文稿的最小改动 |
| 46 | [Simon-Chng/anti-defensive-writing](https://github.com/Simon-Chng/anti-defensive-writing/blob/main/SKILL.md) | 学术稿里直接陈述有证据的贡献，清掉写给假想审稿人的辩解。 | [研究主张](decision-rules.md#claim)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 47 | [Adkid-Zephyr/anti-defensive-writing-Skill · anti-defensive-writing](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill/blob/main/skills/anti-defensive-writing/SKILL.md) | 从已有实验中找出最强且有依据的贡献，围绕它组织论文。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 48 | [Adkid-Zephyr/anti-defensive-writing-Skill · anti-defensive-writing-en](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill/blob/main/skills/anti-defensive-writing-en/SKILL.md) | 同仓库的英文入口，覆盖摘要、引言、实验组织和压缩。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 49 | [Boom5426/Nature-Paper-Skills · anti-defensive-writing](https://github.com/Boom5426/Nature-Paper-Skills/blob/main/skills/core/anti-defensive-writing/SKILL.md) | 清理研究稿里混入的自审、开发过程、承诺与防御性解释。 | [科研体例](decision-rules.md#academic)、[长文结构](decision-rules.md#structure) | 按场景 |
| 50 | [Worigin0314/academic-defensive-writing-auditor](https://github.com/Worigin0314/academic-defensive-writing-auditor/blob/main/SKILL.md) | 在真实科学限制之外，标出预先答辩、叠加限定及为结果找借口的句段。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 51 | [shaou77/revise-paper-defensive-writing](https://github.com/shaou77/revise-paper-defensive-writing/blob/main/SKILL.md) | 逐条处理重复局限、免责尾句和二次对冲，支持带修订记录的 Word 稿。 | [限定与防御](decision-rules.md#limit)、[编辑权限](decision-rules.md#scope) | 修订痕迹依交付要求 |
| 52 | [ZhiqianLyu/research-polish](https://github.com/ZhiqianLyu/research-polish/blob/main/SKILL.md) | 同时查预设质疑和上下句是否接得上，适合摘要与讨论。 | [长文结构](decision-rules.md#structure) | 通用 |
| 53 | [hsnyus-09/well-stated](https://github.com/hsnyus-09/well-stated/blob/main/SKILL.md) | 建立一个可检验的核心判断，再分别核对创新性和优越性。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 54 | [Smoothsailing0/anti-defensive-writing-skill · anti-defensive-academic-writing-zh](https://github.com/Smoothsailing0/anti-defensive-writing-skill/blob/main/skills/anti-defensive-academic-writing-zh/SKILL.md) | 面向中文社科论文，把有依据的中心判断提前，删掉空泛的两面平衡。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 55 | [ZF-Utokyo/anti-ai-defensive-writing · anti-ai-defensive-writing](https://github.com/ZF-Utokyo/anti-ai-defensive-writing/blob/main/skills/anti-ai-defensive-writing/SKILL.md) | 核对每个限定的证据依据，也检查 AI 是否擅自添加统计或方法说法。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 56 | [GPI03248/anti-defensiveWriting-of-academicPapers · academic-paper-writing](https://github.com/GPI03248/anti-defensiveWriting-of-academicPapers/blob/main/skills/academic-paper-writing/SKILL.md) | 优先调整结论和限定的放置位置，再修句子，减少重复局限。 | [限定与防御](decision-rules.md#limit)、[长文结构](decision-rules.md#structure) | 通用 |
| 57 | [KkeriaCXC/Gpt-anti-defensive](https://github.com/KkeriaCXC/Gpt-anti-defensive/blob/main/SKILL.md) | 写作前固定概率估计，拆清读者的问题，避免改稿改动原判断强度。 | [事实与归因](decision-rules.md#proof)、[限定与防御](decision-rules.md#limit) | 通用 |
| 58 | [Mseymur/HCI-Academic-Writing · hci-academic-writing](https://github.com/Mseymur/HCI-Academic-Writing/blob/main/skills/hci-academic-writing/SKILL.md) | 人机交互研究里的常规选择直接交代理由，真实限制单独说清。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 59 | [Nixy-pwd/arrephorion-proportionate-writing · proportionate-writing](https://github.com/Nixy-pwd/arrephorion-proportionate-writing/blob/main/skills/proportionate-writing/SKILL.md) | 同一结果给出不同限定程度的三个版本，逐份与材料核对。 | [限定与防御](decision-rules.md#limit)、[读回与交付](decision-rules.md#verify) | 用户要备选时再给多版 |
| 60 | [rainwillchange/dsh-anti-defensive-writing · anti-defensive-writing-en](https://github.com/rainwillchange/dsh-anti-defensive-writing/blob/main/skills/anti-defensive-writing-en/SKILL.md) | 围绕有证据支持的优势组织材料，必要的方法限定留在相关主张旁。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 61 | [rainwillchange/dsh-anti-defensive-writing · anti-defensive-writing](https://github.com/rainwillchange/dsh-anti-defensive-writing/blob/main/skills/anti-defensive-writing/SKILL.md) | 同仓中文入口，覆盖论文、申报、技术方案和报告。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 62 | [justairr/defensive-writing-checker · defensive-writing-checker](https://github.com/justairr/defensive-writing-checker/blob/master/skills/defensive-writing-checker/SKILL.md) | 按论文的中心贡献检查表达是否被假想质疑带偏。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 63 | [Yingch-s/paper-narrative-audit](https://github.com/Yingch-s/paper-narrative-audit/blob/main/SKILL.md) | 同时检查论文主线、内部研究痕迹与防御性段落。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 64 | [helloyangy/anti-defensive-writing](https://github.com/helloyangy/anti-defensive-writing/blob/main/SKILL.md) | 优先写最有依据的发现，减少逐项汇报式叙述。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 65 | [tenaciousMa/defensive-writing](https://github.com/tenaciousMa/defensive-writing/blob/main/SKILL.md) | 把论文主线放在真正成立的优势上，压缩自我辩护。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 66 | [lambert1231/anti-defensive-writing](https://github.com/lambert1231/anti-defensive-writing/blob/main/SKILL.md) | 用最强贡献组织摘要、论证和实验叙述，减少重复免责。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 67 | [mingeric/anti-defensive-writing](https://github.com/mingeric/anti-defensive-writing/blob/main/SKILL.md) | 清理无必要的防御措辞。仓库还带作者个人的视觉配色偏好。 | [工具和偏好的边界](decision-rules.md#tools)、[限定与防御](decision-rules.md#limit) | 仅取限定检查，配色随项目 |
| 68 | [burning5112/anti-defensive-writing](https://github.com/burning5112/anti-defensive-writing/blob/main/SKILL.md) | Kiterlin 近似版本，同样用证据边界判断该保留哪些限定。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 69 | [Yaobin29/humanizer-write](https://github.com/Yaobin29/humanizer-write/blob/main/SKILL.md) | 明确核对删除后是否影响证据、论证或承诺，兼顾作者自己的声音。 | [限定与防御](decision-rules.md#limit)、[作者声音](decision-rules.md#voice) | 通用 |
| 70 | [moismin/Humanizer-en-zh-mixed-for-GPT6.1sol](https://github.com/moismin/Humanizer-en-zh-mixed-for-GPT6.1sol/blob/main/SKILL.md) | 专门处理中英混排中的免责腔与自我辩护，同一段可保留必要术语。 | [双语与地区](decision-rules.md#locale)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 71 | [yihui504/anti-defensive-writing-4cc · anti-defensive-writing](https://github.com/yihui504/anti-defensive-writing-4cc/blob/main/skills/anti-defensive-writing/SKILL.md) | 可去掉多余免责和层层对冲，保留方法、范围等实质限定。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 72 | [yihui504/anti-defensive-writing-4cc · audit](https://github.com/yihui504/anti-defensive-writing-4cc/blob/main/skills/audit/SKILL.md) | 单独的只读入口，把句子分成可删、应换说法和必须保留三档。 | [编辑权限](decision-rules.md#scope)、[限定与防御](decision-rules.md#limit) | 按场景 |
| 73 | [yihui504/anti-defensive-writing-4cc · revise](https://github.com/yihui504/anti-defensive-writing-4cc/blob/main/skills/revise/SKILL.md) | 单独的修订入口，先展示拟改内容，再按确认的范围改稿。 | [编辑权限](decision-rules.md#scope) | 只在要求先审后改时分轮 |
| 74 | [l0oo0ng/anti-defensive-business-writing-Skill · anti-defensive-business-writing](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/blob/main/skills/anti-defensive-business-writing/SKILL.md) | 用真实的市场、产品和验证材料支撑商业论点，削减自我辩护。 | [产品与公众文案](decision-rules.md#copy)、[事实与归因](decision-rules.md#proof) | 按场景 |

## 用普通读者能懂的语言解释（51）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 75 | [ARA-Labs/plain-language-skill · plain-language](https://github.com/ARA-Labs/plain-language-skill/blob/main/skills/plain-language/SKILL.md) | 用第一次接触项目的读者检验术语、句子、数字和证据。 | [读回与交付](decision-rules.md#verify) | 通用 |
| 76 | [ARA-Labs/plain-language-skill · plain-language-zh](https://github.com/ARA-Labs/plain-language-skill/blob/main/skills/plain-language-zh/SKILL.md) | 把仅团队成员知道的简称、代号和自造词换成读者能理解的含义。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 77 | [non-convex/chinese-humanizer](https://github.com/non-convex/chinese-humanizer/blob/main/SKILL.md) | 用具体的主体、动作和因果把意思讲完整，不把信息压成抽象名词。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 78 | [danyuchn/iso-24495-skill](https://github.com/danyuchn/iso-24495-skill/blob/master/SKILL.md) | 依据 ISO 24495-1 的读者导向原则，检查信息能否找到、理解并用起来。 | [读回与交付](decision-rules.md#verify)、[通俗解释](decision-rules.md#plain) | 采纳读者测试，合规需另核 |
| 79 | [olivervvvv/plain-language-skill](https://github.com/olivervvvv/plain-language-skill/blob/main/SKILL.md) | 中文、英文各有写法，用适当的结构拆开一句话里的多个概念。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 80 | [Amasun93/shuorenhua-skill](https://github.com/Amasun93/shuorenhua-skill/blob/master/SKILL.md) | 先判断读者要解决什么问题，再选生活情境解释术语或机制。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 81 | [dzuluaga/claude-skills · explaining-plainly](https://github.com/dzuluaga/claude-skills/blob/main/explaining-plainly/SKILL.md) | 解读 PR、评审和变更记录时交代变化及后果，也能据此起草。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 82 | [arjunprabhulal/agent-skills · plain-language](https://github.com/arjunprabhulal/agent-skills/blob/main/skills/docs/plain-language/SKILL.md) | 把技术内容改写给没有背景的读者，解释术语和密集表述。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 83 | [docwriter-org/plain-writing-skill · plain-writing](https://github.com/docwriter-org/plain-writing-skill/blob/main/skills/plain-writing/SKILL.md) | 尽量用常见词和完整句，控制行话。风格规则也限制类比和破折号。 | [通俗解释](decision-rules.md#plain)、[工具和偏好的边界](decision-rules.md#tools) | 保留必要类比和标点 |
| 84 | [diego-quiroga/plain-writing](https://github.com/diego-quiroga/plain-writing/blob/main/SKILL.md) | 把要点提前，再检查主语、动词、词汇和句子长度。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 85 | [posit-conf-2026/llms · explain](https://github.com/posit-conf-2026/llms/blob/main/.agents/skills/explain/SKILL.md) | 按读者节奏解释代码或概念，把讲解拆成可以逐步理解的内容。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 86 | [davidamitchell/Skills · plain-language](https://github.com/davidamitchell/Skills/blob/main/plain-language/SKILL.md) | 为非专业读者改写密集文本，保留原意和准确度。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 87 | [marketingskills/plain-language-editor](https://github.com/marketingskills/plain-language-editor/blob/main/SKILL.md) | 用青少年也能读懂的词修改偏营销或高度抽象的文案。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 88 | [ryanjmichie-git/ste-explain · ste-explain](https://github.com/ryanjmichie-git/ste-explain/blob/main/skills/ste-explain/SKILL.md) | 用简化技术英语的句法解释专业内容，让外行能顺着读下来。 | [可执行的说明](decision-rules.md#procedure)、[通俗解释](decision-rules.md#plain) | 严格词表随项目 |
| 89 | [newapologydevelopment/orwell](https://github.com/newapologydevelopment/orwell/blob/main/SKILL.md) | 用奥威尔式的具体动词和明确主体处理迂回的英文。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 90 | [obra/the-elements-of-style · writing-clearly-and-concisely](https://github.com/obra/the-elements-of-style/blob/main/skills/writing-clearly-and-concisely/SKILL.md) | 参考 Strunk 的英文写作原则，用主动表达并删掉无用的词。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 91 | [Fenng/tech-doc-style-chinese](https://github.com/Fenng/tech-doc-style-chinese/blob/main/SKILL.md) | 技术说明兼顾可扫读性和操作准确性，保留命令、参数、适用条件。 | [可执行的说明](decision-rules.md#procedure) | 按场景 |
| 92 | [fwqaaq/chinese-tech-writing](https://github.com/fwqaaq/chinese-tech-writing/blob/main/SKILL.md) | 统一中文技术文档的术语、段落结构和中英文混排。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 93 | [openakita/openakita · chinese-writing](https://github.com/openakita/openakita/blob/main/skills/chinese-writing/SKILL.md) | 整理现代中文书面表达，兼顾语气、标点和中英文混排。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 94 | [docker/docs · write](https://github.com/docker/docs/blob/main/.agents/skills/write/SKILL.md) | Docker 文档强调让读者立即明白技术说明和变更。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 95 | [prisma/web · docs-writer](https://github.com/prisma/web/blob/main/.claude/skills/docs-writer/SKILL.md) | 按快速入门、操作指南等不同任务改写开发者文档。 | [可执行的说明](decision-rules.md#procedure) | 按场景 |
| 96 | [cursor/plugins · technical-writing](https://github.com/cursor/plugins/blob/main/pstack/skills/technical-writing/SKILL.md) | 按文档用途组织信息，操作步骤采用简化技术英语规则。 | [可执行的说明](decision-rules.md#procedure)、[工具和偏好的边界](decision-rules.md#tools) | 受控语言按项目执行 |
| 97 | [wondelai/skills · technical-documentation](https://github.com/wondelai/skills/blob/main/technical-documentation/SKILL.md) | 用面向开发者的英文规范审视文档里的结构和表述。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 98 | [jjsnack/technical-language-skill](https://github.com/jjsnack/technical-language-skill/blob/main/SKILL.md) | 清理 README、发布说明和报错中的晦涩表达，保留代码原意。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 99 | [ryanrudd/skills · asd-ste100](https://github.com/ryanrudd/skills/blob/main/skills/asd-ste100/SKILL.md) | 用简化技术英语起草项目说明、变更摘要及工作单。 | [可执行的说明](decision-rules.md#procedure)、[工具和偏好的边界](decision-rules.md#tools) | 受控语言按项目执行 |
| 100 | [lijigang/ljg-skills · ljg-writes](https://github.com/lijigang/ljg-skills/blob/master/skills/ljg-writes/SKILL.md) | 把观点展开成有例子、有反例、可以迁移理解的中文文章。 | [长文结构](decision-rules.md#structure) | 通用 |
| 101 | [unix2dos/skills · feynman-write](https://github.com/unix2dos/skills/blob/main/feynman-write/SKILL.md) | 用追问帮助作者把概念讲清，再整合成中文技术博客。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 102 | [lijigang/ljg-skills · ljg-read](https://github.com/lijigang/ljg-skills/blob/master/skills/ljg-read/SKILL.md) | 从具体情境讲清概念、判断依据及适用条件。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 103 | [JimLiu/Illustrated-Agent-Skills · info-digest](https://github.com/JimLiu/Illustrated-Agent-Skills/blob/main/skills/info-digest/SKILL.md) | 把长篇或外文材料改写成中文资讯，开头给要点，补足必要背景。 | [长文结构](decision-rules.md#structure) | 通用 |
| 104 | [satsilem/claude-skills-pantheon · feynman](https://github.com/satsilem/claude-skills-pantheon/blob/main/skills/feynman/SKILL.md) | 把复杂概念提炼成非专业读者能够复述的解释。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 105 | [The-Interdependency/skill-lib · plain-lens](https://github.com/The-Interdependency/skill-lib/blob/main/plain-lens/SKILL.md) | 为密集原文增加一份通俗的伴读说明，保留原文供核对。 | [通俗解释](decision-rules.md#plain)、[编辑权限](decision-rules.md#scope) | 需要伴读时保留双份 |
| 106 | [Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer/blob/main/SKILL.md) | 借用简化技术英语的部分原则处理 AI 腔，以自然和清楚为目标。 | [可执行的说明](decision-rules.md#procedure)、[工具和偏好的边界](decision-rules.md#tools) | 按场景使用受控句法 |
| 107 | [fayerman-source/deslop](https://github.com/fayerman-source/deslop/blob/main/SKILL.md) | 用主动语态，拉近主语与谓语，改掉古旧法律英语。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 108 | [jgsystemsconsulting/plain-language](https://github.com/jgsystemsconsulting/plain-language/blob/main/SKILL.md) | 用普通语言写作或改稿，仓库提供本地文本检查脚本。 | [工具和偏好的边界](decision-rules.md#tools)、[通俗解释](decision-rules.md#plain) | 取编辑方法，检查脚本可选 |
| 109 | [rpug/plain-language-writing-skill](https://github.com/rpug/plain-language-writing-skill/blob/main/SKILL.md) | 面向公共通知、政策、法规、表单和操作手册组织读者需要的内容。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 110 | [WarutereIan/plain-language-copywriter](https://github.com/WarutereIan/plain-language-copywriter/blob/main/SKILL.md) | 让产品和营销文案的含义以及读者下一步要做什么更明确。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 111 | [Axxon/technical-plain-language](https://github.com/Axxon/technical-plain-language/blob/main/SKILL.md) | 保留完整技术原文，另补一份按读者水平撰写的简短解释。 | [通俗解释](decision-rules.md#plain)、[编辑权限](decision-rules.md#scope) | 需要伴读时保留双份 |
| 112 | [Maryland-Governors-Office-for-Children/us-plain-language](https://github.com/Maryland-Governors-Office-for-Children/us-plain-language/blob/main/SKILL.md) | 面向美国公共服务文字，清楚区分读者的义务、许可和操作。 | [渠道与工作消息](decision-rules.md#channel)、[产品与公众文案](decision-rules.md#copy) | 按场景 |
| 113 | [aviju888/plain-language-changelog](https://github.com/aviju888/plain-language-changelog/blob/main/SKILL.md) | 把已经实现的改动写成非技术读者也能理解的更新日志。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 114 | [Ryuketsukami/ste-plain-writing](https://github.com/Ryuketsukami/ste-plain-writing/blob/main/SKILL.md) | 以简化技术英语起草和审校技术文字，另有措辞检查。 | [可执行的说明](decision-rules.md#procedure) | 严格词表随项目 |
| 115 | [nyamkamunhjin/explaining-in-plain-language](https://github.com/nyamkamunhjin/explaining-in-plain-language/blob/main/SKILL.md) | 向非技术读者解释故障、评审意见、设计决定及其影响。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 116 | [Wujiaowang/plain-language-gate](https://github.com/Wujiaowang/plain-language-gate/blob/main/SKILL.md) | 检查长文有没有外行读不懂的段落，输出放行、复核或改写意见。 | [编辑权限](decision-rules.md#scope)、[读回与交付](decision-rules.md#verify) | 按场景 |
| 117 | [swaylq/shuorenhua-skill](https://github.com/swaylq/shuorenhua-skill/blob/main/SKILL.md) | 用两个模型分别改写，再逐句核对意思。按作者设计需要 OpenRouter。 | [读回与交付](decision-rules.md#verify)、[工具和偏好的边界](decision-rules.md#tools) | 取独立复核方法，外部服务可选 |
| 118 | [kensv1kensv1-rgb/shuo-ren-hua](https://github.com/kensv1kensv1-rgb/shuo-ren-hua/blob/main/SKILL.md) | 用示意图、生活例子和复述问题检验概念是否讲清。 | [通俗解释](decision-rules.md#plain) | 互动与示意图按需 |
| 119 | [robox888/human-readable-chinese-writing](https://github.com/robox888/human-readable-chinese-writing/blob/main/SKILL.md) | 检查中文能否顺畅读懂，同时处理空泛和模板化的表达。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 120 | [heichaowo/jianming-zhongwen · jianming-zhongwen](https://github.com/heichaowo/jianming-zhongwen/blob/main/skills/jianming-zhongwen/SKILL.md) | 说明书先写发生条件，再写操作。新术语首次出现时定义。聊天模式另有篇幅上限。 | [可执行的说明](decision-rules.md#procedure)、[工具和偏好的边界](decision-rules.md#tools) | 保留操作顺序，篇幅按任务 |
| 121 | [AminBlg/SimpleEnglish · simple-english](https://github.com/AminBlg/SimpleEnglish/blob/main/skills/simple-english/SKILL.md) | 面向非专业读者写短句、用主动语态、定义术语，提供普通和严格两种模式。 | [通俗解释](decision-rules.md#plain) | 严格模式依读者需要 |
| 122 | [YoriHan/changelog-humanizer](https://github.com/YoriHan/changelog-humanizer/blob/main/SKILL.md) | 把开发团队的更新记录转成用户能看懂的产品变化。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 123 | [nirjxr26/code-humanizer](https://github.com/nirjxr26/code-humanizer/blob/main/SKILL.md) | 按读者的技术背景选择角度，解释代码库的用途和运行方式。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 124 | [cgartlab/quill](https://github.com/cgartlab/quill/blob/main/SKILL.md) | 帮作者把随手记下的想法组织成读者能追踪的主张、证据和文章结构。 | [长文结构](decision-rules.md#structure) | 通用 |
| 125 | [ThCyber/paper-humanizer](https://github.com/ThCyber/paper-humanizer/blob/main/SKILL.md) | 给非英语母语读者制作交互式论文伴读，按原文结构解释难句。 | [通俗解释](decision-rules.md#plain)、[科研体例](decision-rules.md#academic) | 互动伴读按需 |

## 中文与中英双语去 AI 腔（82）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 126 | [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh/blob/main/SKILL.md) | 去掉文章、评论和说明中的空话、重复与模板句，保持作者原来的确定程度。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 127 | [ninehills/public-skills · deslop-zh](https://github.com/ninehills/public-skills/blob/main/deslop-zh/SKILL.md) | 优先查每段末尾重复小结的习惯，按文体决定该删什么。 | [长文结构](decision-rules.md#structure) | 通用 |
| 128 | [wangyuanchuan2022/humanizer-zh · humanizer-zh-chat](https://github.com/wangyuanchuan2022/humanizer-zh/blob/main/skills/humanizer-zh-chat/SKILL.md) | 把熟人聊天、公开评论和半正式消息分开处理，避免同一种客服口吻。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 129 | [wangyuanchuan2022/humanizer-zh · humanizer-zh-write](https://github.com/wangyuanchuan2022/humanizer-zh/blob/main/skills/humanizer-zh-write/SKILL.md) | 书面稿再区分议论文、说明文和申请类文字。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 130 | [wangyuanchuan2022/humanizer-zh · humanizer](https://github.com/wangyuanchuan2022/humanizer-zh/blob/main/skills/humanizer/SKILL.md) | 按聊天、正式文章和专业文档选用同仓的不同规则。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 131 | [syw2039/humanizer-zh](https://github.com/syw2039/humanizer-zh/blob/main/SKILL.md) | 有作者样本时优先匹配本人的用词和节奏，技术文体保留中性语气。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 132 | [nothing0here/humanizer-zh](https://github.com/nothing0here/humanizer-zh/blob/main/SKILL.md) | 把中式公文套话、欧化句式和客服式开头分开检查，支持样本匹配。 | [双语与地区](decision-rules.md#locale)、[作者声音](decision-rules.md#voice) | 按场景 |
| 133 | [ai-zixun/humanizer-zh](https://github.com/ai-zixun/humanizer-zh/blob/main/SKILL.md) | 优先清理直译腔、空泛大词与机械结构。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 134 | [fy-agent/humanize-chinese-writing](https://github.com/fy-agent/humanize-chinese-writing/blob/main/SKILL.md) | 按材料写长文，检查内容密度，避免教程或讲义腔渗进文章。 | [长文结构](decision-rules.md#structure) | 通用 |
| 135 | [siyuanzhong-root/zh-humanizer](https://github.com/siyuanzhong-root/zh-humanizer/blob/main/SKILL.md) | 技术和调研材料里消除机械罗列，保留术语、事实和治理条件。 | [长文结构](decision-rules.md#structure) | 通用 |
| 136 | [holygeek00/humanizer-zh-cn](https://github.com/holygeek00/humanizer-zh-cn/blob/main/SKILL.md) | 处理中文邮件、报告和技术说明中的模板句，不凭空补案例。 | [事实与归因](decision-rules.md#proof)、[渠道与工作消息](decision-rules.md#channel) | 通用 |
| 137 | [ZeddYu/humanizer_zh](https://github.com/ZeddYu/humanizer_zh/blob/main/SKILL.md) | 先判断作者和读者的关系，再处理宣传腔、报告腔或翻译腔。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 138 | [ksufer/humanizer-zh-skill](https://github.com/ksufer/humanizer-zh-skill/blob/main/SKILL.md) | 按文章体裁识别翻译腔与机械句式。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 139 | [tentenco/shuorenhua-zh-tw](https://github.com/tentenco/shuorenhua-zh-tw/blob/main/SKILL.md) | 将繁体中文对齐台湾用语、标点和出版习惯，也可检查英文。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 140 | [Raymondhou0917/speak-human-tw](https://github.com/Raymondhou0917/speak-human-tw/blob/master/SKILL.md) | 为台湾读者改写邮件、公告和社群文案，兼顾用词和标点。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 141 | [leoluyi/skills · humanizer-zh](https://github.com/leoluyi/skills/blob/main/skills/humanizer-zh/SKILL.md) | 可处理繁中、英文或混排成稿，尽量保留作者习惯。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 142 | [aeopress/writing-skills.TW · humanizer-tw](https://github.com/aeopress/writing-skills.TW/blob/main/humanizer-tw/SKILL.md) | 去掉简转繁残留和空泛收尾，按台湾读者习惯选词。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 143 | [LifelongLazyLearner/qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei/blob/main/SKILL.md) | 为简体中文保留事实、证据强弱、语体和作者声音。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 144 | [baibanbao/qu-ai-wei](https://github.com/baibanbao/qu-ai-wei/blob/main/SKILL.md) | 按作者自用稿或受限改稿选择修改权限，再逐项查惯用套式。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 145 | [MrGeDiao/shuorenhua · shuorenhua](https://github.com/MrGeDiao/shuorenhua/blob/main/skills/shuorenhua/SKILL.md) | 可只标问题，改动时保留原文里的术语和责任主体。 | [编辑权限](decision-rules.md#scope)、[事实与归因](decision-rules.md#proof) | 按场景 |
| 146 | [Hyacehila/humanizer-zh-next](https://github.com/Hyacehila/humanizer-zh-next/blob/main/SKILL.md) | 通用规则配合面向商稿、论文和申报书的单独规则。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 147 | [masterball-w/Master-humanizer-skill](https://github.com/masterball-w/Master-humanizer-skill/blob/main/SKILL.md) | 逐句查假装口语化的写法和强凑的排比、对仗。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 148 | [meikis/remove-ai-flavor-writing-skill](https://github.com/meikis/remove-ai-flavor-writing-skill/blob/main/SKILL.md) | 只修改模板化措辞，保留内容与作者语气。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 149 | [0xtresser/cn-humanizer](https://github.com/0xtresser/cn-humanizer/blob/main/SKILL.md) | 中文成稿清官腔，英译中另查语序和翻译腔。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 150 | [TwilightXQY/humanizer-zh-codex](https://github.com/TwilightXQY/humanizer-zh-codex/blob/main/SKILL.md) | 兼顾自然、直接与原稿的语域。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 151 | [yelban/humanizer.TW](https://github.com/yelban/humanizer.TW/blob/main/SKILL.md) | 清理台湾中文里的时代背景开场、连接词堆叠和结尾套语。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 152 | [deedeekong07-alt/fiction-humanizer-zh](https://github.com/deedeekong07-alt/fiction-humanizer-zh/blob/main/SKILL.md) | 将套话检查落到人物对话、场景与章节衔接。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 153 | [larashero3-dotcom/lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone/blob/main/SKILL.md) | 先用脚本定位，再根据上下文判断，并向作者列出准备修改的范围。 | [工具和偏好的边界](decision-rules.md#tools)、[编辑权限](decision-rules.md#scope) | 取定位和判断，脚本可选 |
| 154 | [allenloves/de-ai-tone](https://github.com/allenloves/de-ai-tone/blob/master/SKILL.md) | 长篇回复、翻译、教材和报告均按繁体中文的行文节奏处理。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 155 | [huangserva/renhua](https://github.com/huangserva/renhua/blob/main/SKILL.md) | 针对 AI 和科技文章，削减产品与模型评测里的行业套话。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 156 | [ismilewolf-eng/sloptrim-zh](https://github.com/ismilewolf-eng/sloptrim-zh/blob/main/SKILL.md) | 既能润色已有中文，也能把事实提纲写成正文，附本地检查脚本。 | [工具和偏好的边界](decision-rules.md#tools)、[事实与归因](decision-rules.md#proof) | 取起草与复核，脚本可选 |
| 157 | [Antony232/zh_de_ai_ify](https://github.com/Antony232/zh_de_ai_ify/blob/main/SKILL.md) | 从公众号、邮件、演讲和产品文案中移除官腔。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 158 | [lambertliu53/humanizer-lanbo-skill](https://github.com/lambertliu53/humanizer-lanbo-skill/blob/main/SKILL.md) | 按公众号、小红书、短视频和销售文案的受众调整语气。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 159 | [marcoaiwithfefe-hub/humanizer-hk](https://github.com/marcoaiwithfefe-hub/humanizer-hk/blob/master/SKILL.md) | 针对香港书面繁体中文，适合清理直译味和机械写法。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 160 | [tangwenwen-md/chinese-de-ai-writing](https://github.com/tangwenwen-md/chinese-de-ai-writing/blob/main/SKILL.md) | 对不同来源的语言特征区别处理，避免见到比喻或设问就删。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 161 | [shirley37/de-ai-writing-skill](https://github.com/shirley37/de-ai-writing-skill/blob/main/SKILL.md) | 减少报幕式过渡、课堂腔和起草时的协作口吻。 | [长文结构](decision-rules.md#structure) | 通用 |
| 162 | [liqinling1994-cloud/qinling-qu-ai-wei](https://github.com/liqinling1994-cloud/qinling-qu-ai-wei/blob/main/SKILL.md) | 按文本选择白描、杂文或书信等写法，适合有发挥空间的稿件。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 163 | [helloLeila/no-ai-tone-skills](https://github.com/helloLeila/no-ai-tone-skills/blob/main/SKILL.md) | 重排笔记或博客时保留观点，删掉无信息量的过渡。 | [长文结构](decision-rules.md#structure) | 通用 |
| 164 | [kuaidaoqingyi/qu-ai-wei](https://github.com/kuaidaoqingyi/qu-ai-wei/blob/main/SKILL.md) | 尽量保留原稿长度和节奏，区分口播、聊天与正式说明。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 165 | [ZZZ234234234/humanize-writing-skill](https://github.com/ZZZ234234234/humanize-writing-skill/blob/main/SKILL.md) | 可从首稿开始避免空话，也可按作者声音改写已有文本。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 166 | [woai3c/humanize-skill](https://github.com/woai3c/humanize-skill/blob/main/SKILL.md) | 同时处理过分口语化、模板句和中英混排中的标点问题。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 167 | [tsaoyunan/shuo-renhua](https://github.com/tsaoyunan/shuo-renhua/blob/main/SKILL.md) | 用偏日常的个人口吻解释事情，适合指定风格的内容。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 168 | [rAIn0x7/shuorenhua](https://github.com/rAIn0x7/shuorenhua/blob/master/SKILL.md) | 自媒体、邮件和 README 先给判断，再用具体材料支撑。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 169 | [HeiGeAi/heige-shuorenhua](https://github.com/HeiGeAi/heige-shuorenhua/blob/main/SKILL.md) | 删掉中文文案里的套话，使用仓库作者偏好的短句和标点。 | [工具和偏好的边界](decision-rules.md#tools)、[句子节奏](decision-rules.md#rhythm) | 取删套话，标点按文体 |
| 170 | [gangtao/de-ai-writing](https://github.com/gangtao/de-ai-writing/blob/main/SKILL.md) | 按工作沟通、正式文档和公开内容切换改写策略。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 171 | [AlexBybye/humanizer-CN](https://github.com/AlexBybye/humanizer-CN/blob/main/SKILL.md) | 清理翻译腔和聊天残留，可从作者样本校准语气。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 172 | [quqxui/context-aware-humanizer](https://github.com/quqxui/context-aware-humanizer/blob/main/SKILL.md) | 中文日常和工作沟通分别处理，另有中英学术演讲场景。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 173 | [neimengboy/humanize-truth](https://github.com/neimengboy/humanize-truth/blob/main/SKILL.md) | 结合事实核对清理套话，避免为了自然制造具体细节。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 174 | [Lanqingsong/humanize-writing](https://github.com/Lanqingsong/humanize-writing/blob/main/SKILL.md) | 首稿就从作者与读者的关系组织正文，避免把最终文章写成对用户的回话。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 175 | [nieyuann99-ship-it/humanize-writing](https://github.com/nieyuann99-ship-it/humanize-writing/blob/main/SKILL.md) | 按中英文原稿清理 AI 惯用写法，保持信息和语气。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 176 | [Oxforce/haning-humanize-writing-skill](https://github.com/Oxforce/haning-humanize-writing-skill/blob/main/SKILL.md) | 以作者样本校准文风，保留术语、引文和个人习惯。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 177 | [woderfulmagic/humanized-chinese-writing-polisher](https://github.com/woderfulmagic/humanized-chinese-writing-polisher/blob/main/SKILL.md) | 润色中文或把文字调整到合适的口语程度。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 178 | [acchuang/zh-tw-humanizer](https://github.com/acchuang/zh-tw-humanizer/blob/main/SKILL.md) | 把繁体中文改成自然的台湾用语，专门检查本地化。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 179 | [Maoziwang725/natural-chinese-protocol](https://github.com/Maoziwang725/natural-chinese-protocol/blob/main/SKILL.md) | 中文稿查模板化叙述，论文另有组织研究叙事的规则。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 180 | [liuliu-66-create/ll-humanizer-zh](https://github.com/liuliu-66-create/ll-humanizer-zh/blob/main/SKILL.md) | 处理中文口播、社交内容和文章里居高临下的说教腔。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 181 | [ruijayfeng/zh-writing-humanizer](https://github.com/ruijayfeng/zh-writing-humanizer/blob/main/SKILL.md) | 借作者样本和发布场景调整中文或以中文为主的文字。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 182 | [KyrieHuang/humanizer_zh](https://github.com/KyrieHuang/humanizer_zh/blob/main/SKILL.md) | 对繁体中文改写和本地化，在通用 Humanizer 基础上增加相应规则。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 183 | [QIU-Guanzong/humanizer-multilingual-writing-skill](https://github.com/QIU-Guanzong/humanizer-multilingual-writing-skill/blob/main/SKILL.md) | 按语言、读者和场景检查文字，按需说明不确定之处。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 184 | [opencare-skillhub/xyb-humanizer](https://github.com/opencare-skillhub/xyb-humanizer/blob/main/SKILL.md) | 保留事实和证据边界，把患者教育材料写得能读懂。 | [通俗解释](decision-rules.md#plain)、[事实与归因](decision-rules.md#proof) | 通用 |
| 185 | [hehuangz/humanizer-enzh](https://github.com/hehuangz/humanizer-enzh/blob/main/SKILL.md) | 为英文和中文分别提供 AI 套式检查，并扩充中文规则。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 186 | [weasleycai56-ctrl/humanize-zh](https://github.com/weasleycai56-ctrl/humanize-zh/blob/main/SKILL.md) | 查找中文里的套式、过度拔高及空泛表态。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 187 | [zray0529-a11y/gov-report-humanizer](https://github.com/zray0529-a11y/gov-report-humanizer/blob/main/SKILL.md) | 面向中文政务汇报、政策简报和发言稿，直接交代工作内容。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 188 | [Red-Sa1t/zh-report-humanizer](https://github.com/Red-Sa1t/zh-report-humanizer/blob/main/SKILL.md) | 处理中文作业、实验和技术报告，兼看正文与图表怎样传达意思。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 189 | [rufushsu9987/humanizer-tw](https://github.com/rufushsu9987/humanizer-tw/blob/main/SKILL.md) | 面向台湾技术团队的日常消息，保留英语术语，按同事交流的语气写。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 190 | [slivenred/humanizer-zh-TW-Pro](https://github.com/slivenred/humanizer-zh-TW-Pro/blob/main/SKILL.md) | 为台湾繁中读者调整文章，保留作者声音及有必要的术语。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 191 | [whatsphone-creator/humanizer-hk](https://github.com/whatsphone-creator/humanizer-hk/blob/main/SKILL.md) | 按交付物选择香港书面语或粤语书写，覆盖短消息及正式文件。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 192 | [yibeitianzhou/zh-copy-humanizer](https://github.com/yibeitianzhou/zh-copy-humanizer/blob/main/SKILL.md) | 改口播或文章里的模板腔，同时维持原有事实范围。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 193 | [dyb061211/humanizer-zh](https://github.com/dyb061211/humanizer-zh/blob/main/SKILL.md) | 找出公文和营销话术，保留专业术语、数字、来源与立场。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 194 | [SYZBZ/fact-locked-humanizer](https://github.com/SYZBZ/fact-locked-humanizer/blob/main/SKILL.md) | 用已经确认的材料写稿，在删减字数前检查事实与作者意图。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 195 | [Jujie-YANG/zh-humanizer-best-practice](https://github.com/Jujie-YANG/zh-humanizer-best-practice/blob/main/SKILL.md) | 先核对事实、术语和语体，再处理助手机械口吻和段落雷同。 | [读回与交付](decision-rules.md#verify) | 通用 |
| 196 | [roy-tong/deck-humanizer](https://github.com/roy-tong/deck-humanizer/blob/main/SKILL.md) | 标题给出结论，正文适合扫读，讲者备注按能念出来的口吻重写。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 197 | [fxw-labs/easy-humanizer-zh](https://github.com/fxw-labs/easy-humanizer-zh/blob/main/SKILL.md) | 可分别按技术博客、公众号、产品和学术写作的口吻改写。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 198 | [softshrimp/Humanizer-zh-HK](https://github.com/softshrimp/Humanizer-zh-HK/blob/main/SKILL.md) | 为香港正式文章、新闻稿等保留原意，采用地道书面语。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 199 | [KyrieHuang/humanizer-zh-speech](https://github.com/KyrieHuang/humanizer-zh-speech/blob/main/SKILL.md) | 把繁体书面稿改成念起来顺的口语，针对朗读检查语气。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 200 | [devin515/bense-humanizer-zh](https://github.com/devin515/bense-humanizer-zh/blob/main/SKILL.md) | 同时支持中文日常回复、成稿轻改和只查问题。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 201 | [gaosen13-byte/zh-unslop](https://github.com/gaosen13-byte/zh-unslop/blob/main/SKILL.md) | 压缩生成式套话，把结论写得具体直接，保留必要术语。 | [直接作答](decision-rules.md#answer) | 通用 |
| 202 | [myne-top/humanize-kit](https://github.com/myne-top/humanize-kit/blob/main/SKILL.md) | 默认交终稿，也可只标问题。按用户示例调整作者口吻。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 203 | [victorpaulee/victorable-shuorenhua](https://github.com/victorpaulee/victorable-shuorenhua/blob/main/SKILL.md) | 将生造隐喻、假对比和导师式口吻换成平实的职场中文。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 204 | [shirley37/qu-ai-wei-skill](https://github.com/shirley37/qu-ai-wei-skill/blob/main/SKILL.md) | 针对简体中文，避免编辑改变证据力度或原来的正式程度。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 205 | [ChuckChouCn/humanizer-stop-slop](https://github.com/ChuckChouCn/humanizer-stop-slop/blob/main/SKILL.md) | 先改生硬的文章结构，再查中文表达与事实保真。 | [长文结构](decision-rules.md#structure) | 通用 |
| 206 | [lukeTheNeuromancer/-_Skill · 说人话skill.md](https://github.com/lukeTheNeuromancer/-_Skill/blob/main/%E8%AF%B4%E4%BA%BA%E8%AF%9Dskill.md) | 用于聊天、状态更新和正式文章，有技能元数据，仓库文件名为“说人话skill.md”。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 207 | [pengong101/ai-humanizer-cn](https://github.com/pengong101/ai-humanizer-cn/blob/main/SKILL.md) | 按原稿和读者需要选择改写强度，作者列明支持中文和英文。 | [编辑权限](decision-rules.md#scope) | 按场景 |

## 英文去 AI 腔与作者文风（53）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 208 | [blader/humanizer](https://github.com/blader/humanizer/blob/main/SKILL.md) | 检查空对比、硬凑三项、销售语气和重复结尾，并保留作者原意。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 209 | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop/blob/main/SKILL.md) | 句子逐条清除铺垫、套式和填充词，适合快改英文稿。 | [直接作答](decision-rules.md#answer) | 通用 |
| 210 | [addyosmani/clarity](https://github.com/addyosmani/clarity/blob/main/SKILL.md) | 支持协写、改稿和只提意见，要求从材料里找具体细节。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 211 | [ccf/humanize · humanize](https://github.com/ccf/humanize/blob/main/skills/humanize/SKILL.md) | 适用于评论、邮件、说明和回复，起草时就检查模板化措辞。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 212 | [Aboudjem/humanizer-skill · humanizer](https://github.com/Aboudjem/humanizer-skill/blob/main/skills/humanizer/SKILL.md) | 多种语气可选，并单列容易误判的个人写作习惯。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 213 | [adewale/anti-slop-writing · anti-slop-writing](https://github.com/adewale/anti-slop-writing/blob/main/skills/anti-slop-writing/SKILL.md) | 既能起草，也能把现有英文稿改紧凑、去模板。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 214 | [xr0zv/no-ai-slop](https://github.com/xr0zv/no-ai-slop/blob/main/SKILL.md) | 清理英文 AI 腔，适合已经有稿、希望少改的人。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 215 | [theclaymethod/unslop](https://github.com/theclaymethod/unslop/blob/main/SKILL.md) | 在重写和只标问题之间选择，检查反复出现的套式。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 216 | [westonhancock/unslop](https://github.com/westonhancock/unslop/blob/main/SKILL.md) | 优先保留作者声音，允许只诊断现有草稿。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 217 | [itstamhn/anti-slop](https://github.com/itstamhn/anti-slop/blob/main/SKILL.md) | 从英文稿里清掉公司套话和公式化表达。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 218 | [Mark-Life/agent-skills · writing-for-readers](https://github.com/Mark-Life/agent-skills/blob/main/skills/communication/writing-for-readers/SKILL.md) | 检查文章里的格言式对句、先否后肯和重复文章主旨的开头。 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 219 | [cloudflare/computer · prose](https://github.com/cloudflare/computer/blob/main/.agents/skills/prose/SKILL.md) | 统一注释、提交说明和 PR 文字的英语表述。 | [变更与代码](decision-rules.md#engineering)、[主语、动作与关系](decision-rules.md#action) | 按场景 |
| 220 | [synthesisengineering/synthesis-skills · synthesis-concise-messaging](https://github.com/synthesisengineering/synthesis-skills/blob/main/skills/synthesis-concise-messaging/SKILL.md) | 压缩邮件和即时消息，默认以五句内表达要点。 | [渠道与工作消息](decision-rules.md#channel)、[工具和偏好的边界](decision-rules.md#tools) | 取短讯写法，篇幅按任务 |
| 221 | [analystacademy/claude-skills · email](https://github.com/analystacademy/claude-skills/blob/main/email/SKILL.md) | 用真实邮件样本确定语气和直接程度。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 222 | [sorawit-w/agent-skills · ghostwriter](https://github.com/sorawit-w/agent-skills/blob/main/skills/ghostwriter/SKILL.md) | 从用户样本中还原其发消息的习惯，不直接套用通用客服声线。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 223 | [aaaronmiller/humanize-writing](https://github.com/aaaronmiller/humanize-writing/blob/main/SKILL.md) | 在长文发布前处理机械节奏，保留原先的信息。 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 224 | [davidcogan/avoid-ai-writing](https://github.com/davidcogan/avoid-ai-writing/blob/main/SKILL.md) | 核对事实、意图和原来的语气，再删除套语。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 225 | [fmschulz/stop-slop-skill](https://github.com/fmschulz/stop-slop-skill/blob/main/SKILL.md) | 除了词汇，还审查冗长解释与无谓的限定。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 226 | [kimhons/humanize](https://github.com/kimhons/humanize/blob/main/SKILL.md) | 将论文、文档、博客和提交说明分开处理。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 227 | [milock/humanizer](https://github.com/milock/humanizer/blob/main/SKILL.md) | 重点是成稿清理，同时保留事实和作者的表达习惯。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 228 | [amanmaqsood/prose-humanizer](https://github.com/amanmaqsood/prose-humanizer/blob/main/SKILL.md) | 用已提供的材料确定作者声线，先判断可以改写的范围。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 229 | [skyzer/deslop-the-copy](https://github.com/skyzer/deslop-the-copy/blob/main/SKILL.md) | 清理照本宣科和过度推销的英文文案，保留原有意思。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 230 | [ExPl0iT-29/deslop](https://github.com/ExPl0iT-29/deslop/blob/main/SKILL.md) | 核对仓库文本里的实际功能，清理 README 中夸张的产品说法。 | [变更与代码](decision-rules.md#engineering)、[产品与公众文案](decision-rules.md#copy) | 按场景 |
| 231 | [jimmygambier/deslop](https://github.com/jimmygambier/deslop/blob/main/SKILL.md) | 清理工作消息里的 AI 腔，默认只交付改好的消息。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 232 | [justincdavis/deslop](https://github.com/justincdavis/deslop/blob/main/SKILL.md) | 把发现的问题写成小而具体的修改，方便作者逐条决定。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 233 | [shessenauer/deslop-ai-lint-skill](https://github.com/shessenauer/deslop-ai-lint-skill/blob/main/SKILL.md) | 专门检查过多限定、低信息量和固定句式。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 234 | [playcations/deslop-skill](https://github.com/playcations/deslop-skill/blob/main/SKILL.md) | 对照实际功能修改界面文字，避免文案承诺超出实现。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 235 | [bhowe/deslopify](https://github.com/bhowe/deslopify/blob/main/SKILL.md) | 交付前检查面向用户的答复和其他成品文字。 | [读回与交付](decision-rules.md#verify) | 通用 |
| 236 | [dianagolduber/anti-slop](https://github.com/dianagolduber/anti-slop/blob/main/SKILL.md) | 删掉清嗓子式开头、空泛限定和故意表演坦诚的短语。 | [直接作答](decision-rules.md#answer) | 通用 |
| 237 | [immeasurablematt/a16z-anti-slop](https://github.com/immeasurablematt/a16z-anti-slop/blob/main/SKILL.md) | 按写作目的检查空洞修辞与辨识度低的作者声音。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 238 | [doctorzorro/humanize-writing](https://github.com/doctorzorro/humanize-writing/blob/main/SKILL.md) | 专门处理简讯、社交短文、产品短句和邮件标题。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 239 | [behzadsp/humanized-writing-skill](https://github.com/behzadsp/humanized-writing-skill/blob/main/SKILL.md) | 用在教程、博客和网站长文，按读者和场景控制语气。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 240 | [AnkitaSontakke/humanize-writing](https://github.com/AnkitaSontakke/humanize-writing/blob/main/SKILL.md) | 以具体作者和目标读者为准，避免套用统一的英文文风。 | [作者声音](decision-rules.md#voice) | 按场景 |
| 241 | [east18047-zmjjkk/humanize-writing](https://github.com/east18047-zmjjkk/humanize-writing/blob/main/SKILL.md) | 同时查英文 AI 套语和无依据的防御性措辞。 | [限定与防御](decision-rules.md#limit) | 通用 |
| 242 | [ordingr/wiki-humanizer](https://github.com/ordingr/wiki-humanizer/blob/main/SKILL.md) | 参考维基百科整理的语言现象，检查反复出现的写作习惯。 | [工具和偏好的边界](decision-rules.md#tools) | 用现象定位，逐处判断 |
| 243 | [Nanako0129/sepia · sepia](https://github.com/Nanako0129/sepia/blob/main/skills/sepia/SKILL.md) | Sepia 同时处理叙事结构和措辞，分别提供只审、轻改和重写入口。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 244 | [ehmo/slopkit · slopbeth](https://github.com/ehmo/slopkit/blob/main/skills/slopbeth/SKILL.md) | slopbeth 面向要交付的文字。同仓 slopgent 面向助手的当场答复。 | [渠道与工作消息](decision-rules.md#channel) | 按场景 |
| 245 | [aeopress/writing-skills.TW · humanizer-en](https://github.com/aeopress/writing-skills.TW/blob/main/humanizer-en/SKILL.md) | 清理英文里的过度拔高、模糊归因和宣传口吻，同仓另有台湾繁中入口。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 246 | [Speedrunlab/no-slop-writing](https://github.com/Speedrunlab/no-slop-writing/blob/main/SKILL.md) | 针对商务文体逐项检查常见 AI 套式。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 247 | [ninehills/public-skills · deslop-en](https://github.com/ninehills/public-skills/blob/main/deslop-en/SKILL.md) | 适用于博客、技术说明、发行说明及科学写作，同仓另有中文规则。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 248 | [haidrrrry/humanize-ai-writing · humanize-ai-writing](https://github.com/haidrrrry/humanize-ai-writing/blob/main/humanize-ai-writing/SKILL.md) | 对正在写和已写完的英文分别检查惯用套话和夸大表述。 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 249 | [cursor/plugins · unslop](https://github.com/cursor/plugins/blob/main/pstack/skills/unslop/SKILL.md) | 按指令对已有文字执行去 AI 腔处理。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 250 | [AvCompDev/humanizer-en](https://github.com/AvCompDev/humanizer-en/blob/main/SKILL.md) | 从既有英文中删除填充语、重复和模板句。 | [直接作答](decision-rules.md#answer) | 通用 |
| 251 | [horiacristescu/humanizer-skill](https://github.com/horiacristescu/humanizer-skill/blob/main/SKILL.md) | 专门剔除文本自我解说、自评重要性和惯例式的最后一段保留意见。 | [长文结构](decision-rules.md#structure) | 通用 |
| 252 | [am0oma/structural-humanizer](https://github.com/am0oma/structural-humanizer/blob/main/SKILL.md) | 从整篇文章的结构处理博客、通讯和文档里的模板感。 | [长文结构](decision-rules.md#structure) | 通用 |
| 253 | [canadapainting-byte/humanizer-80](https://github.com/canadapainting-byte/humanizer-80/blob/main/SKILL.md) | 用接近简化技术英语的写法处理英文，但保留自然的句子。 | [可执行的说明](decision-rules.md#procedure) | 受控词汇按项目 |
| 254 | [Room-to-Grow-LLC/humanizer-narrative-nonfiction](https://github.com/Room-to-Grow-LLC/humanizer-narrative-nonfiction/blob/main/SKILL.md) | 以整篇叙事非虚构作品为单位做发布前的 AI 套式检查。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 255 | [kotopeller/humanizer-ua](https://github.com/kotopeller/humanizer-ua/blob/main/SKILL.md) | 支持英文和乌克兰文，按检测到的文本语言应用对应规则。 | [双语与地区](decision-rules.md#locale) | 采纳英文部分 |
| 256 | [bar148/ben-adam-humanizer](https://github.com/bar148/ben-adam-humanizer/blob/main/SKILL.md) | 分别按英文和希伯来文的语言习惯修改稿件。 | [双语与地区](decision-rules.md#locale) | 采纳英文部分 |
| 257 | [ClydeShen/tech-humanizer-skill](https://github.com/ClydeShen/tech-humanizer-skill/blob/main/SKILL.md) | 在技术说明、PR、邮件及发布说明中清理模板化写法。 | [变更与代码](decision-rules.md#engineering) | 按场景 |
| 258 | [drweber/humanizer-orchestrator](https://github.com/drweber/humanizer-orchestrator/blob/main/SKILL.md) | 按语言调用不同编辑规则，包含专门的英文处理入口。 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 259 | [kadowcreates/Humanizer](https://github.com/kadowcreates/Humanizer/blob/main/SKILL.md) | 按发布渠道和目标语气选择轻改或更大幅度的重写。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 260 | [aierjin/iteration-humanizer](https://github.com/aierjin/iteration-humanizer/blob/main/SKILL.md) | 用学术文本实例参照句子或段落的修改。 | [科研体例](decision-rules.md#academic)、[读回与交付](decision-rules.md#verify) | 按场景 |

## 论文与科研文字（29）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 261 | [junbolian/Academic-Humanizer · academic-humanizer](https://github.com/junbolian/Academic-Humanizer/blob/main/academic-humanizer/SKILL.md) | 稿件可做轻清理或润色，并用配套工具核对数字、公式和引文。 | [读回与交付](decision-rules.md#verify)、[工具和偏好的边界](decision-rules.md#tools) | 保留事实核对，工具可选 |
| 262 | [stephenturner/skill-deslop](https://github.com/stephenturner/skill-deslop/blob/main/SKILL.md) | 清理科学写作里的铺垫和模板结构，也适用于一般英文。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 263 | [jefeerzhang/academic-humanizer-zh](https://github.com/jefeerzhang/academic-humanizer-zh/blob/main/SKILL.md) | 把主张逐条对回数字、图或引用，并为中英文与基金稿选择不同规则。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 264 | [Yila-AI/awesome-research-skills · academic-humanizer](https://github.com/Yila-AI/awesome-research-skills/blob/main/skills/academic-humanizer/SKILL.md) | 改写前固定学术主张、数据、公式和引文，再处理模板化表达。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 265 | [codingrajan/humanizer-skills · academic-humanizer](https://github.com/codingrajan/humanizer-skills/blob/main/skills/academic-humanizer/SKILL.md) | 保留学术文体与必要术语，优先处理没有内容的郑重表态。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 266 | [ashgreat/humanizer](https://github.com/ashgreat/humanizer/blob/main/SKILL.md) | 从复杂或疏远的动词入手，把摘要、方法和结果写得更直接。 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 267 | [dongshuyan/compass-skills · academic-humanizer](https://github.com/dongshuyan/compass-skills/blob/master/skills/academic-humanizer/SKILL.md) | 通篇核对术语身份、逻辑关系以及证据强度，适合最小改动。 | [读回与交付](decision-rules.md#verify) | 通用 |
| 268 | [AIScientists-Dev/academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer/blob/main/SKILL.md) | 论文与基金申请分开处理，结论对证据、计划对可行性。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 269 | [henmuc/codex-academic-humanizer](https://github.com/henmuc/codex-academic-humanizer/blob/main/SKILL.md) | 在润色中文或英文稿时保留事实、术语、引用和逻辑。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 270 | [matsuikentaro1/humanizer_academic](https://github.com/matsuikentaro1/humanizer_academic/blob/main/SKILL.md) | 针对医学论文的语体和措辞清理套语。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 271 | [crabin/paper-humanizer-skill](https://github.com/crabin/paper-humanizer-skill/blob/main/SKILL.md) | 针对中英文研究稿处理模板痕迹，兼顾术语和原有内容。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 272 | [proffitteoy/Mathematician-Humanizer](https://github.com/proffitteoy/Mathematician-Humanizer/blob/main/SKILL.md) | 从定理反向整理证明依赖，区分作者原意与解释者的重建。 | [科研体例](decision-rules.md#academic)、[研究主张](decision-rules.md#claim) | 证明与算例各自核对 |
| 273 | [zkrun/academic-humanizer-zh](https://github.com/zkrun/academic-humanizer-zh/blob/main/SKILL.md) | 按论文类型定位 AI 套式，支持处理单段或整篇论文。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 274 | [mattwang1230/legal-paper-framework-humanizer-zh](https://github.com/mattwang1230/legal-paper-framework-humanizer-zh/blob/main/SKILL.md) | 从题目、框架、论证和术语层面检查中文法学论文的模式化写法。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 275 | [Zeng-xiangkai/humanizer-document-zh](https://github.com/Zeng-xiangkai/humanizer-document-zh/blob/main/SKILL.md) | 在论文和报告中消除机械写法，保留正式文体。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 276 | [atomashevic/deslop](https://github.com/atomashevic/deslop/blob/master/SKILL.md) | 科研项目对外发布的文字和内部记录分开精简，保全各项命题。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 277 | [Fwibo/ml-paper-humanizer](https://github.com/Fwibo/ml-paper-humanizer/blob/main/SKILL.md) | 面向机器学习会议论文的英文正文，写作或审读都能用。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 278 | [XS-dev/anti-ai-writing-skills · academic-writing-optimizer](https://github.com/XS-dev/anti-ai-writing-skills/blob/main/skills/academic-writing-optimizer/SKILL.md) | 同时检查术语负担、概念解释、段落衔接与防御性措辞。 | [通俗解释](decision-rules.md#plain) | 通用 |
| 279 | [XS-dev/anti-ai-writing-skills · scientific-writing-editor](https://github.com/XS-dev/anti-ai-writing-skills/blob/main/skills/scientific-writing-editor/SKILL.md) | 改变论文措辞时复核事实与论证，适合摘要与正文。 | [事实与归因](decision-rules.md#proof) | 通用 |
| 280 | [yllscar728/academic-humanizer-zh](https://github.com/yllscar728/academic-humanizer-zh/blob/main/SKILL.md) | 中文论文和研究报告保留原意、术语和论证，修整机械写法。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 281 | [XuanjinZhu/zh-scientific-humanizer](https://github.com/XuanjinZhu/zh-scientific-humanizer/blob/main/SKILL.md) | 中文科研稿可分别做基础清理、学术润色和风险标注。 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 282 | [Zink-Liu/Academic-Writing-Humanizer](https://github.com/Zink-Liu/Academic-Writing-Humanizer/blob/main/SKILL.md) | 针对摘要和论文段落，确保科学含义与修订后的表达一致。 | [研究主张](decision-rules.md#claim) | 按场景 |
| 283 | [XuyueyangHe/Qualitative-social-science-humanizer](https://github.com/XuyueyangHe/Qualitative-social-science-humanizer/blob/main/SKILL.md) | 针对定性和解释性社会科学论文，按学科文体校正语言。 | [科研体例](decision-rules.md#academic)、[事实与归因](decision-rules.md#proof) | 按场景 |
| 284 | [ecpp/humanize-medical-writing](https://github.com/ecpp/humanize-medical-writing/blob/main/SKILL.md) | 医学与公共卫生研究的英文，保留证据限定和专业文体。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 285 | [Ziyou-os/humanizer-wireless-academic](https://github.com/Ziyou-os/humanizer-wireless-academic/blob/main/SKILL.md) | 依据无线通信论文的专业场景调整自然度。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 286 | [yangchme/humanize-polish-scientific-english](https://github.com/yangchme/humanize-polish-scientific-english/blob/main/SKILL.md) | 科研英译同时核对推理和证据，不因润色而改变主张。 | [研究主张](decision-rules.md#claim)、[双语与地区](decision-rules.md#locale) | 按场景 |
| 287 | [qing54035-design/business-academic-humanizer](https://github.com/qing54035-design/business-academic-humanizer/blob/main/SKILL.md) | 面向商学、经济、金融和管理学中文研究的表述。 | [科研体例](decision-rules.md#academic) | 按场景 |
| 288 | [TashanGKD/scientific-humanization](https://github.com/TashanGKD/scientific-humanization/blob/main/SKILL.md) | 采用中文科研文体，分别处理论文、技术方案与讲稿。 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 289 | [yesaze2077/sjtu-thesis-humanizer](https://github.com/yesaze2077/sjtu-thesis-humanizer/blob/main/SKILL.md) | 按上海交通大学中文学位论文场景处理表达和全文一致性。 | [科研体例](decision-rules.md#academic) | 院校体例依实际要求 |

## 更多有正文依据的写作技能（204）

| 序号 | 来源正文 | 原来源中可采用的做法 | 对应判断 | 使用条件 |
| ---: | --- | --- | --- | --- |
| 290 | [findscripter/everything-skills · humanize-chinese-text](https://github.com/findscripter/everything-skills/blob/main/01-documents/humanize-chinese-text/SKILL.md#L49) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 291 | [sickn33/agentic-awesome-skills · humanize-chinese](https://github.com/sickn33/agentic-awesome-skills/blob/main/plugins/agentic-awesome-skills-claude/skills/humanize-chinese/SKILL.md#L51) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 292 | [cangtianhuang/humanizer-academic-zh](https://github.com/cangtianhuang/humanizer-academic-zh/blob/main/SKILL.md#L113) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 293 | [phoiex/deslop-zh](https://github.com/phoiex/deslop-zh/blob/main/SKILL.md#L49) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 294 | [qi531416/novel-humanize](https://github.com/qi531416/novel-humanize/blob/main/SKILL.md#L20) | 删掉过度华丽的排比和堆叠的景物描写 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 295 | [zlong6943-commits/samehuman-writing](https://github.com/zlong6943-commits/samehuman-writing/blob/main/SKILL.md#L174) | 识别反复出现的模型套语并调整 | [长文结构](decision-rules.md#structure) | 通用 |
| 296 | [nezhazheng/quaiwei-skill](https://github.com/nezhazheng/quaiwei-skill/blob/main/SKILL.md#L50) | 按该项目的中文排版偏好清理英文词两侧的空格 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 297 | [Chenyeppt/humanize-writing-skill](https://github.com/Chenyeppt/humanize-writing-skill/blob/main/SKILL.md#L101) | 识别反复出现的模型套语并调整 | [长文结构](decision-rules.md#structure) | 通用 |
| 298 | [Joozozhao/renhua-skill](https://github.com/Joozozhao/renhua-skill/blob/main/SKILL.md#L132) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 299 | [deedeekong07-alt/humanizer-zh](https://github.com/deedeekong07-alt/humanizer-zh/blob/main/SKILL.md#L36) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 300 | [7247949-art/humanizer-zh-pro](https://github.com/7247949-art/humanizer-zh-pro/blob/main/SKILL.md#L183) | 用具体情境表达感受 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 301 | [rancy-1229/shuo-renhua](https://github.com/rancy-1229/shuo-renhua/blob/main/SKILL.md#L28) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 302 | [Lesterffx/humanizer](https://github.com/Lesterffx/humanizer/blob/main/SKILL.md#L174) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 303 | [Bryce1188/humanizer](https://github.com/Bryce1188/humanizer/blob/main/SKILL.md#L383) | 读者已知的背景可以省去，避免把决定埋在后面 | [直接作答](decision-rules.md#answer) | 通用 |
| 304 | [9gmtv5kkdm-rgb/humanizer-pro](https://github.com/9gmtv5kkdm-rgb/humanizer-pro/blob/main/SKILL.md#L265) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 305 | [zhangjinglsc-alt/a5l-skill-humanizer-zh](https://github.com/zhangjinglsc-alt/a5l-skill-humanizer-zh/blob/main/SKILL.md#L66) | 个人视角合适时可以用第一人称 | [作者声音](decision-rules.md#voice) | 按场景 |
| 306 | [modenicheng/humanizer-yu](https://github.com/modenicheng/humanizer-yu/blob/main/SKILL.md#L42) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 307 | [nightatlas2077/Real-humanizer-zh](https://github.com/nightatlas2077/Real-humanizer-zh/blob/main/SKILL.md#L168) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 308 | [smilexiaobao1992/Humanizer-Skill](https://github.com/smilexiaobao1992/Humanizer-Skill/blob/main/SKILL.md#L99) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 309 | [ght2330/humanizer-zh](https://github.com/ght2330/humanizer-zh/blob/main/SKILL.md#L90) | 结合文体和出现频率判断三段式等信号 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 310 | [davidanan1105/humanizer-agent-skill](https://github.com/davidanan1105/humanizer-agent-skill/blob/main/SKILL.md#L24) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 311 | [jianga0801-ui/humanizer-cn](https://github.com/jianga0801-ui/humanizer-cn/blob/main/SKILL.md#L108) | 朗读改稿，再核对事实、来源和主张是否改变 | [读回与交付](decision-rules.md#verify) | 通用 |
| 312 | [Weijinchen/humanizer-zh](https://github.com/Weijinchen/humanizer-zh/blob/main/SKILL.md#L53) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 313 | [Shinchan-crayon/thinkai-humanizer](https://github.com/Shinchan-crayon/thinkai-humanizer/blob/main/SKILL.md#L91) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 314 | [ddcarolyn/writing-humanizer-zh](https://github.com/ddcarolyn/writing-humanizer-zh/blob/main/SKILL.md#L66) | 按作者口吻决定是否使用第一人称 | [作者声音](decision-rules.md#voice) | 按场景 |
| 315 | [haya-hello/humanizer-cn](https://github.com/haya-hello/humanizer-cn/blob/main/SKILL.md#L48) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 316 | [wxie0815-arch/humanizer-zh](https://github.com/wxie0815-arch/humanizer-zh/blob/main/SKILL.md#L41) | 检查谁做了什么，尽量把主体和动作写清 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 317 | [bobipika2026/humanize](https://github.com/bobipika2026/humanize/blob/main/SKILL.md#L46) | 检查陌生词与行话，按读者背景解释 | [通俗解释](decision-rules.md#plain) | 通用 |
| 318 | [huang-kaibo/content-humanizer](https://github.com/huang-kaibo/content-humanizer/blob/main/SKILL.md#L237) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 319 | [itszuo/mutou-humanizer](https://github.com/itszuo/mutou-humanizer/blob/main/SKILL.md#L89) | 写作样本可用来确定合适的开头方式 | [作者声音](decision-rules.md#voice) | 按场景 |
| 320 | [lijunyu726/humanizer-zh-plus](https://github.com/lijunyu726/humanizer-zh-plus/blob/main/SKILL.md#L80) | 允许使用符合原文身份的第一人称 | [作者声音](decision-rules.md#voice) | 按场景 |
| 321 | [tonyyunyang/humanizer-zh](https://github.com/tonyyunyang/humanizer-zh/blob/main/SKILL.md#L49) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 322 | [lizhengyang-byte/humanizer-zh](https://github.com/lizhengyang-byte/humanizer-zh/blob/main/SKILL.md#L53) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 323 | [wmc837911722-del/humanizer-zh](https://github.com/wmc837911722-del/humanizer-zh/blob/main/SKILL.md#L88) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 324 | [a6828464/yimai-humanizer-v4](https://github.com/a6828464/yimai-humanizer-v4/blob/main/SKILL.md#L85) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 325 | [SAKURAfan1023/humanizer-zh](https://github.com/SAKURAfan1023/humanizer-zh/blob/main/SKILL.md#L44) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 326 | [chy90607002-byte/novel-humanizer-zh](https://github.com/chy90607002-byte/novel-humanizer-zh/blob/main/SKILL.md#L44) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 327 | [focos/anti-ai-writing-humanizer](https://github.com/focos/anti-ai-writing-humanizer/blob/main/SKILL.md#L14) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 328 | [cophQ/humanizer_zh_academic](https://github.com/cophQ/humanizer_zh_academic/blob/main/SKILL.md#L160) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 329 | [dolphinsue319/kd-humanizer](https://github.com/dolphinsue319/kd-humanizer/blob/main/SKILL.md#L75) | 用具体情境表达感受 | [叙事、口播与体裁](decision-rules.md#genre) | 按场景 |
| 330 | [lynote-ai/humanize-text-skill](https://github.com/lynote-ai/humanize-text-skill/blob/main/SKILL.md#L143) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 331 | [nococn/omd-humanize](https://github.com/nococn/omd-humanize/blob/main/SKILL.md#L72) | 按目标语言检查清晰度、节奏和语气 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 332 | [nobrainer-tech/nobrainer-tech-flow · nobrainer-writing](https://github.com/nobrainer-tech/nobrainer-tech-flow/blob/main/skills/nobrainer-writing/SKILL.md#L191) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 333 | [nobodyscode/noaislop](https://github.com/nobodyscode/noaislop/blob/main/SKILL.md#L99) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 334 | [drm-collab/stop-slop](https://github.com/drm-collab/stop-slop/blob/main/SKILL.md#L44) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 通用 |
| 335 | [kjmagnan1s/anti-slop](https://github.com/kjmagnan1s/anti-slop/blob/main/SKILL.md#L22) | 识别反复出现的模型套语并调整 | [长文结构](decision-rules.md#structure) | 通用 |
| 336 | [NVlabs/Skill2Env · stop-slop](https://github.com/NVlabs/Skill2Env/blob/main/SkillHub/skills/stop-slop/SKILL.md#L210) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 337 | [dharmawan-id/anti-ai-slop · anti-slop](https://github.com/dharmawan-id/anti-ai-slop/blob/main/skills/anti-slop/SKILL.md#L14) | 处理像广告一样的形容和宣传用语 | [产品与公众文案](decision-rules.md#copy) | 按场景 |
| 338 | [misbahsy/anti-ai-slop · anti-ai-slop](https://github.com/misbahsy/anti-ai-slop/blob/main/skills/anti-ai-slop/SKILL.md#L213) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 339 | [sankalpsharmaa/claude-config-public · humanizer](https://github.com/sankalpsharmaa/claude-config-public/blob/master/skills/humanizer/SKILL.md#L12) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 340 | [google-gemini/gemini-cli · docs-writer](https://github.com/google-gemini/gemini-cli/blob/main/.gemini/skills/docs-writer/SKILL.md#L25) | 检查谁做了什么，尽量把主体和动作写清 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 341 | [microsoft/devsquad-copilot · documentation-style](https://github.com/microsoft/devsquad-copilot/blob/main/.github/plugins/devsquad/skills/documentation-style/SKILL.md#L25) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 342 | [shawnchee/caveman-skill · caveman](https://github.com/shawnchee/caveman-skill/blob/main/caveman/SKILL.md#L12) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 取删冗词，极短句按需 |
| 343 | [iliagerman/agents · caveman](https://github.com/iliagerman/agents/blob/main/caveman/SKILL.md#L8) | 精简填充词和重复表达 | [长文结构](decision-rules.md#structure) | 取删冗词，极短句按需 |
| 344 | [full-stack-skills/agent-skills · caveman](https://github.com/full-stack-skills/agent-skills/blob/main/skills/caveman/SKILL.md#L11) | 精简填充词和重复表达 | [长文结构](decision-rules.md#structure) | 取删冗词，极短句按需 |
| 345 | [Lesile-Yin/agent-skills · caveman](https://github.com/Lesile-Yin/agent-skills/blob/main/skills/caveman/SKILL.md#L38) | 检查谁做了什么，尽量把主体和动作写清 | [主语、动作与关系](decision-rules.md#action) | 取删冗词，极短句按需 |
| 346 | [infometa/workbuddyskills · caveman](https://github.com/infometa/workbuddyskills/blob/main/skills/caveman/SKILL.md#L20) | 精简填充词和重复表达 | [长文结构](decision-rules.md#structure) | 取删冗词，极短句按需 |
| 347 | [DeadAlmighty/talk-skill](https://github.com/DeadAlmighty/talk-skill/blob/main/SKILL.md#L22) | 精简填充词和重复表达 | [长文结构](decision-rules.md#structure) | 通用 |
| 348 | [hannsxpeter/humanizer](https://github.com/hannsxpeter/humanizer/blob/main/SKILL.md#L206) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 349 | [OussamaHaddouche/skills · humanizer](https://github.com/OussamaHaddouche/skills/blob/main/humanizer/SKILL.md#L65) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 350 | [advisorita/humanize-ai-writing](https://github.com/advisorita/humanize-ai-writing/blob/main/SKILL.md#L197) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 351 | [ryanmaule/humanize](https://github.com/ryanmaule/humanize/blob/main/SKILL.md#L28) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 352 | [mgannotti/humanizer](https://github.com/mgannotti/humanizer/blob/main/SKILL.md#L9) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 通用 |
| 353 | [AshwinSathian/humanize-writing-skill](https://github.com/AshwinSathian/humanize-writing-skill/blob/main/SKILL.md#L78) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 354 | [YaoPan-NJU/Codex-skills-sync · humanizer](https://github.com/YaoPan-NJU/Codex-skills-sync/blob/main/skills/humanizer/SKILL.md#L24) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 355 | [msimchowitz/writing-skills · general-writing](https://github.com/msimchowitz/writing-skills/blob/main/for-agents/general-writing/SKILL.md#L100) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 356 | [maccydee/natural-writing](https://github.com/maccydee/natural-writing/blob/main/SKILL.md#L135) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 357 | [brandonwise/humanizer](https://github.com/brandonwise/humanizer/blob/main/SKILL.md#L45) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 358 | [47thtechcorner/RayCodes_Humanizer](https://github.com/47thtechcorner/RayCodes_Humanizer/blob/master/SKILL.md#L37) | 朗读并核对改稿有没有增减事实 | [读回与交付](decision-rules.md#verify) | 通用 |
| 359 | [pielas-activy/humanizer-pl](https://github.com/pielas-activy/humanizer-pl/blob/main/SKILL.md#L66) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 360 | [thevseprod/humanizer-ru](https://github.com/thevseprod/humanizer-ru/blob/main/SKILL.md#L519) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 361 | [Aaron-Bushnell/humanizer](https://github.com/Aaron-Bushnell/humanizer/blob/master/SKILL.md#L18) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 362 | [chi-feng/humanizer](https://github.com/chi-feng/humanizer/blob/main/SKILL.md#L217) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 363 | [Adeel2208/Humanizer](https://github.com/Adeel2208/Humanizer/blob/main/SKILL.md#L188) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 364 | [WhimseyAI/humanizer-skill](https://github.com/WhimseyAI/humanizer-skill/blob/main/SKILL.md#L200) | 检查句子长度和节奏是否过度一致 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 365 | [maxbotten/humanizer](https://github.com/maxbotten/humanizer/blob/main/SKILL.md#L187) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 366 | [johnakande/AI-Humanizer-Skill](https://github.com/johnakande/AI-Humanizer-Skill/blob/main/SKILL.md#L47) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 367 | [keez97/humanizer](https://github.com/keez97/humanizer/blob/main/SKILL.md#L145) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 368 | [Ilm-Alan/humanizer](https://github.com/Ilm-Alan/humanizer/blob/main/SKILL.md#L232) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 369 | [seulkikaang/writing-deslop](https://github.com/seulkikaang/writing-deslop/blob/main/SKILL.md#L359) | 用写作和复述来检验作者是否想清楚 | [通俗解释](decision-rules.md#plain) | 通用 |
| 370 | [creativedeals/free-claude-skill-deslop](https://github.com/creativedeals/free-claude-skill-deslop/blob/main/SKILL.md#L15) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 371 | [brandon-kaplan/deslop](https://github.com/brandon-kaplan/deslop/blob/main/SKILL.md#L101) | 检查写给假想反对者的辩解和多余限定 | [限定与防御](decision-rules.md#limit) | 通用 |
| 372 | [AHorihuela/deslop](https://github.com/AHorihuela/deslop/blob/main/SKILL.md#L245) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 373 | [ozdemircili/deslop](https://github.com/ozdemircili/deslop/blob/main/SKILL.md#L10) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 374 | [hharshitarora/deslop](https://github.com/hharshitarora/deslop/blob/main/SKILL.md#L60) | 检查固定三项或整齐排比是否增加信息 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 375 | [devv-shayan/deslop](https://github.com/devv-shayan/deslop/blob/main/SKILL.md#L41) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 376 | [jasonericsiegel/deslop-writing](https://github.com/jasonericsiegel/deslop-writing/blob/main/SKILL.md#L86) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 377 | [stephenhillphd/deslop-skill](https://github.com/stephenhillphd/deslop-skill/blob/main/SKILL.md#L110) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 378 | [andrewdex/deslopit-skill](https://github.com/andrewdex/deslopit-skill/blob/main/SKILL.md#L15) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 通用 |
| 379 | [stevenAthompson/deslopify-copy](https://github.com/stevenAthompson/deslopify-copy/blob/main/SKILL.md#L73) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 380 | [aleconf/prose-deslop](https://github.com/aleconf/prose-deslop/blob/main/SKILL.md#L23) | 按严重程度逐句审阅写作问题 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 381 | [paliocha/deslop-wiki](https://github.com/paliocha/deslop-wiki/blob/main/SKILL.md#L78) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 382 | [0xSunSeeker/Ai-Deslop](https://github.com/0xSunSeeker/Ai-Deslop/blob/main/SKILL.md#L37) | 检查连续两句是否机械复用相同的语法骨架 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 383 | [JaimeOrtegaxyz/deslop-copy](https://github.com/JaimeOrtegaxyz/deslop-copy/blob/main/SKILL.md#L163) | 逐段标出 AI 套式并对照修改前后的变化 | [编辑权限](decision-rules.md#scope) | 按场景 |
| 384 | [uniqaiapp/deslop-ru](https://github.com/uniqaiapp/deslop-ru/blob/main/SKILL.md#L85) | 语言为英文时采用英文的写作模式清单 | [双语与地区](decision-rules.md#locale) | 按场景 |
| 385 | [eskayML/anti-slop](https://github.com/eskayML/anti-slop/blob/main/SKILL.md#L40) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 386 | [sanketagarwal/mega-anti-slop](https://github.com/sanketagarwal/mega-anti-slop/blob/main/SKILL.md#L78) | 检查句子长度和节奏是否过度一致 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 387 | [sinadwm1/write-natural](https://github.com/sinadwm1/write-natural/blob/main/SKILL.md#L41) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 388 | [shirley37/humanizer-skill](https://github.com/shirley37/humanizer-skill/blob/main/SKILL.md#L130) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 389 | [jpeggdev/humanize-writing](https://github.com/jpeggdev/humanize-writing/blob/main/SKILL.md#L127) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 390 | [taufiqsun/humanizer-writing-skill](https://github.com/taufiqsun/humanizer-writing-skill/blob/main/SKILL.md#L225) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 391 | [armstoo-dot/humanized-writing](https://github.com/armstoo-dot/humanized-writing/blob/main/SKILL.md#L44) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 392 | [marian-kamenistak/humanize-writing](https://github.com/marian-kamenistak/humanize-writing/blob/master/SKILL.md#L35) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 393 | [dumko2001/humanize-writing](https://github.com/dumko2001/humanize-writing/blob/main/SKILL.md#L35) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 394 | [Nanako0129/sepia · sepia-hemingway](https://github.com/Nanako0129/sepia/blob/main/skills/sepia-hemingway/SKILL.md#L9) | 以同仓 Sepia 为基础，调用海明威风格的小说写作规则 | [叙事、口播与体裁](decision-rules.md#genre) | 仅用于指定的文体练习 |
| 395 | [thekozugroup/humanizer](https://github.com/thekozugroup/humanizer/blob/main/SKILL.md#L106) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 396 | [josemella472-hue/Humanizer](https://github.com/josemella472-hue/Humanizer/blob/claude/instagram-reel-skill-w0r1hq/SKILL.md#L44) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 397 | [Dukeio/humanizer](https://github.com/Dukeio/humanizer/blob/main/SKILL.md#L200) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 398 | [hanzoskill/humanizer](https://github.com/hanzoskill/humanizer/blob/main/SKILL.md#L186) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 399 | [codxt/humanizer](https://github.com/codxt/humanizer/blob/main/SKILL.md#L52) | 使用历史文风档案前确认用户是否要求模仿 | [作者声音](decision-rules.md#voice) | 按场景 |
| 400 | [tatsuroyamaguchi/humanizer](https://github.com/tatsuroyamaguchi/humanizer/blob/main/SKILL.md#L373) | 省去读者已知的背景，避免推迟结论 | [直接作答](decision-rules.md#answer) | 通用 |
| 401 | [vinicq/humanizer](https://github.com/vinicq/humanizer/blob/main/SKILL.md#L104) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 402 | [org42-consulting/humanizer](https://github.com/org42-consulting/humanizer/blob/main/SKILL.md#L245) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 403 | [spuvr/humanizer](https://github.com/spuvr/humanizer/blob/main/SKILL.md#L96) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 404 | [hyper-code-harness/humanizer](https://github.com/hyper-code-harness/humanizer/blob/main/SKILL.md#L25) | 用句长分布和变化检查节奏 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 405 | [Winkey86/humanizer-agent-skill](https://github.com/Winkey86/humanizer-agent-skill/blob/main/SKILL.md#L41) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 406 | [rbaddam/humanizer](https://github.com/rbaddam/humanizer/blob/main/SKILL.md#L32) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 407 | [edmondyv/humanizer](https://github.com/edmondyv/humanizer/blob/main/SKILL.md#L287) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 408 | [BrentPizza/ai-text-humanizer](https://github.com/BrentPizza/ai-text-humanizer/blob/main/SKILL.md#L116) | 按原因报告残留问题及改写到哪一步停止 | [读回与交付](decision-rules.md#verify) | 通用 |
| 409 | [LXSKING/article-humanizer-check](https://github.com/LXSKING/article-humanizer-check/blob/main/SKILL.md#L42) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 410 | [Intern4711/Better_Humanizer](https://github.com/Intern4711/Better_Humanizer/blob/main/SKILL.md#L32) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 411 | [F-DK/humanizer-lite](https://github.com/F-DK/humanizer-lite/blob/main/SKILL.md#L39) | 严格模式按简化技术英语的规则修改 | [可执行的说明](decision-rules.md#procedure) | 严格词表随项目 |
| 412 | [wangxin116/humanizer-install](https://github.com/wangxin116/humanizer-install/blob/main/SKILL.md#L59) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 413 | [Iampattanayak/Claude-Humanizer](https://github.com/Iampattanayak/Claude-Humanizer/blob/main/SKILL.md#L186) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 414 | [fendouai/humanize-skill](https://github.com/fendouai/humanize-skill/blob/main/SKILL.md#L224) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 415 | [rahuljadhav77/humanizer-Skill](https://github.com/rahuljadhav77/humanizer-Skill/blob/main/SKILL.md#L200) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 416 | [ndxtraders/Humanizer-Skill](https://github.com/ndxtraders/Humanizer-Skill/blob/main/SKILL.md#L196) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 417 | [rockyandtom/humanizer-skill](https://github.com/rockyandtom/humanizer-skill/blob/main/SKILL.md#L35) | 将改稿中的事实与来源逐一对照 | [读回与交付](decision-rules.md#verify) | 通用 |
| 418 | [runesleo/humanizer-skill](https://github.com/runesleo/humanizer-skill/blob/main/SKILL.md#L189) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 419 | [Norbert-Brett/humanizer-skill](https://github.com/Norbert-Brett/humanizer-skill/blob/main/SKILL.md#L18) | 避免为模仿人类刻意调乱句长或制造拼写错误 | [作者声音](decision-rules.md#voice) | 按场景 |
| 420 | [cthboss001/humanizer-skill](https://github.com/cthboss001/humanizer-skill/blob/main/SKILL.md#L126) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 421 | [cristiankweber/cue-skill-humanizer](https://github.com/cristiankweber/cue-skill-humanizer/blob/main/SKILL.md#L188) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 422 | [juanman2/humanizer-skill](https://github.com/juanman2/humanizer-skill/blob/main/SKILL.md#L123) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 423 | [porasnagar/humanizer-skill](https://github.com/porasnagar/humanizer-skill/blob/main/SKILL.md#L8) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 424 | [rsynkr/humanizer-skill](https://github.com/rsynkr/humanizer-skill/blob/main/SKILL.md#L90) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 425 | [sajibmiahdv99/AI-Humanizer-Pro](https://github.com/sajibmiahdv99/AI-Humanizer-Pro/blob/main/SKILL.md#L121) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 426 | [modafarshouha/humanizer_skills](https://github.com/modafarshouha/humanizer_skills/blob/master/SKILL.md#L22) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 427 | [sheepyqadir/Humanizer4codex](https://github.com/sheepyqadir/Humanizer4codex/blob/main/SKILL.md#L130) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 428 | [nikhildaswani/Niks_Humanizer](https://github.com/nikhildaswani/Niks_Humanizer/blob/main/SKILL.md#L71) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 429 | [Naberator/humanize-skill](https://github.com/Naberator/humanize-skill/blob/main/SKILL.md#L84) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 430 | [rogue-dev-studio/rogue-humanizer-skill](https://github.com/rogue-dev-studio/rogue-humanizer-skill/blob/main/SKILL.md#L9) | 逐类查找出现在内容、结构及措辞中的惯用套式 | [长文结构](decision-rules.md#structure) | 通用 |
| 431 | [dwaang/anti-slop](https://github.com/dwaang/anti-slop/blob/main/SKILL.md#L15) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 432 | [cc4-marketing/notes-humanizer](https://github.com/cc4-marketing/notes-humanizer/blob/main/SKILL.md#L20) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 433 | [cerealfailure/humanizer-personal](https://github.com/cerealfailure/humanizer-personal/blob/main/SKILL.md#L174) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 434 | [ForgePlan/slopocop-humanizer-en](https://github.com/ForgePlan/slopocop-humanizer-en/blob/master/SKILL.md#L159) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 435 | [riccifra28-pixel/Francesco-Humanizer](https://github.com/riccifra28-pixel/Francesco-Humanizer/blob/main/SKILL.md#L121) | 按该项目指定的个人文风修改 | [作者声音](decision-rules.md#voice) | 按项目明示偏好 |
| 436 | [Christianboat/humanize](https://github.com/Christianboat/humanize/blob/main/SKILL.md#L100) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 437 | [LoubakInnovations/humanizer-linkedin](https://github.com/LoubakInnovations/humanizer-linkedin/blob/main/SKILL.md#L22) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 438 | [sowadalmughni/contextual-humanizer](https://github.com/sowadalmughni/contextual-humanizer/blob/main/SKILL.md#L63) | 检查某句话能否不加修改地套进任何文章 | [长文结构](decision-rules.md#structure) | 通用 |
| 439 | [JohnnyChen1113/sci-humanizer](https://github.com/JohnnyChen1113/sci-humanizer/blob/main/SKILL.md#L209) | 方法部分可保留恰当的被动语态 | [科研体例](decision-rules.md#academic) | 按场景 |
| 440 | [omelyanchuk2593/humanizer-en](https://github.com/omelyanchuk2593/humanizer-en/blob/main/SKILL.md#L318) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 441 | [thejaytang/academic-humanizer](https://github.com/thejaytang/academic-humanizer/blob/main/SKILL.md#L151) | 检查写给假想反对者的辩解和多余限定 | [限定与防御](decision-rules.md#limit) | 通用 |
| 442 | [kush-coder/autopilot-humanizer](https://github.com/kush-coder/autopilot-humanizer/blob/main/SKILL.md#L472) | 在回复中优先写决定，避免重复交代背景 | [直接作答](decision-rules.md#answer) | 通用 |
| 443 | [pikbdesigns/medical-research-humanizer](https://github.com/pikbdesigns/medical-research-humanizer/blob/main/SKILL.md#L83) | 检查连续句子的语法结构是否重复 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 444 | [adrianrivas44/humanizer-personal](https://github.com/adrianrivas44/humanizer-personal/blob/main/SKILL.md#L11) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 445 | [Sixpennvir/Professor-humanizer](https://github.com/Sixpennvir/Professor-humanizer/blob/main/SKILL.md#L25) | 依照原意判断真正有用的平行论证 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 446 | [Ariz0na45/humanizer-template](https://github.com/Ariz0na45/humanizer-template/blob/main/SKILL.md#L8) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 447 | [yostboy6/connor-humanizer](https://github.com/yostboy6/connor-humanizer/blob/main/SKILL.md#L16) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 448 | [victornasar/job-answer-humanizer](https://github.com/victornasar/job-answer-humanizer/blob/main/SKILL.md#L26) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 通用 |
| 449 | [BhashithaSamarasinghe/academic-humanizer](https://github.com/BhashithaSamarasinghe/academic-humanizer/blob/main/SKILL.md#L73) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 450 | [Kevjade/humanizer-pro](https://github.com/Kevjade/humanizer-pro/blob/main/SKILL.md#L108) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 451 | [Secure-Code-Zyloch-Basic/humanizer-pro](https://github.com/Secure-Code-Zyloch-Basic/humanizer-pro/blob/main/SKILL.md#L175) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 452 | [codezeroexe/text-humanizer](https://github.com/codezeroexe/text-humanizer/blob/main/SKILL.md#L19) | 检查句子长度和节奏是否过度一致 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 453 | [DrARaj/ultimate-humanizer](https://github.com/DrARaj/ultimate-humanizer/blob/main/SKILL.md#L331) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 454 | [hurryingauto3/master-humanizer](https://github.com/hurryingauto3/master-humanizer/blob/main/SKILL.md#L176) | 识别作者并不认同的假平衡与假中立 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 455 | [korECM/humanize](https://github.com/korECM/humanize/blob/main/SKILL.md#L24) | 改写时核对原意与材料所给的信息 | [事实与归因](decision-rules.md#proof) | 通用 |
| 456 | [theogenite-coder/humanizer-bh](https://github.com/theogenite-coder/humanizer-bh/blob/main/SKILL.md#L100) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 457 | [bryanmanio/humanizer-compare](https://github.com/bryanmanio/humanizer-compare/blob/main/SKILL.md#L8) | 用改写前后的例子核对如何调整措辞 | [读回与交付](decision-rules.md#verify) | 通用 |
| 458 | [mehulpratapsing/AiHumanizer](https://github.com/mehulpratapsing/AiHumanizer/blob/main/SKILL.md#L183) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 459 | [Skillproofdev/text-humanizer](https://github.com/Skillproofdev/text-humanizer/blob/main/SKILL.md#L53) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 460 | [syaifuddin-saif/humanizer-oxza](https://github.com/syaifuddin-saif/humanizer-oxza/blob/main/SKILL.md#L93) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 461 | [bobsa514/report-humanizer](https://github.com/bobsa514/report-humanizer/blob/main/SKILL.md#L131) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 462 | [Avijit0001/Research-Humanizer-](https://github.com/Avijit0001/Research-Humanizer-/blob/main/SKILL.md#L205) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 463 | [Dex719/humanizer-extended](https://github.com/Dex719/humanizer-extended/blob/main/SKILL.md#L182) | 先交代决定，再给读者需要的理由 | [直接作答](decision-rules.md#answer) | 通用 |
| 464 | [eshaanjain26/no-ai-slop-humanizer](https://github.com/eshaanjain26/no-ai-slop-humanizer/blob/main/SKILL.md#L245) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 465 | [Walid-Idrissi-Labs/SciHumanizer](https://github.com/Walid-Idrissi-Labs/SciHumanizer/blob/main/SKILL.md#L683) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 466 | [marynacleo/humanizer-plus](https://github.com/marynacleo/humanizer-plus/blob/main/SKILL.md#L55) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 467 | [chris-openclaw/voice-match-humanizer](https://github.com/chris-openclaw/voice-match-humanizer/blob/main/SKILL.md#L20) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 468 | [sabirmgd/humanize-plus](https://github.com/sabirmgd/humanize-plus/blob/master/SKILL.md#L68) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 469 | [mscs22019-rgb/Claude-AI-Humanizer-by-MIS](https://github.com/mscs22019-rgb/Claude-AI-Humanizer-by-MIS/blob/main/SKILL.md#L120) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 470 | [Esl1h/humanize-ai-slop](https://github.com/Esl1h/humanize-ai-slop/blob/main/SKILL.md#L76) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 471 | [sarrafgsarraf/humanize-text-pro](https://github.com/sarrafgsarraf/humanize-text-pro/blob/main/SKILL.md#L200) | 检查谁做了什么，尽量把主体和动作写清 | [主语、动作与关系](decision-rules.md#action) | 通用 |
| 472 | [RekaWeb3Design/humanize](https://github.com/RekaWeb3Design/humanize/blob/main/SKILL.md#L71) | 检查开头的铺垫与无信息量的套话 | [直接作答](decision-rules.md#answer) | 通用 |
| 473 | [KittiDon/humanizer](https://github.com/KittiDon/humanizer/blob/main/SKILL.md#L99) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 474 | [K-ai1981/humanizer](https://github.com/K-ai1981/humanizer/blob/main/SKILL.md#L196) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 475 | [IamHarrie-Labs/humanizer-skill](https://github.com/IamHarrie-Labs/humanizer-skill/blob/main/SKILL.md#L205) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 476 | [the-metafactory/humanizer](https://github.com/the-metafactory/humanizer/blob/main/SKILL.md#L188) | 检查段落结尾是否堆有免责话术 | [限定与防御](decision-rules.md#limit) | 通用 |
| 477 | [tjvjk/humanizer](https://github.com/tjvjk/humanizer/blob/main/SKILL.md#L39) | 核对含糊的归因，使读者能看出谁说了什么 | [事实与归因](decision-rules.md#proof) | 通用 |
| 478 | [dm75india/humanizer](https://github.com/dm75india/humanizer/blob/main/SKILL.md#L136) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 479 | [3orionkings/humanizer](https://github.com/3orionkings/humanizer/blob/main/SKILL.md#L41) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 480 | [punith7077-FAA/humanizer](https://github.com/punith7077-FAA/humanizer/blob/main/SKILL.md#L15) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 481 | [maximsmd/Humanizer](https://github.com/maximsmd/Humanizer/blob/main/SKILL.md#L51) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 482 | [cchenzhao/humanizer](https://github.com/cchenzhao/humanizer/blob/main/SKILL.md#L85) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 483 | [Prajhan26/humanizer](https://github.com/Prajhan26/humanizer/blob/main/SKILL.md#L112) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 484 | [timolabs-ai/claude-humanize-skill](https://github.com/timolabs-ai/claude-humanize-skill/blob/main/SKILL.md#L205) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 485 | [nueramator/humanizer](https://github.com/nueramator/humanizer/blob/main/SKILL.md#L131) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 486 | [viniciusiat/humanizer](https://github.com/viniciusiat/humanizer/blob/main/SKILL.md#L190) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 487 | [Oskarhn/humanizer](https://github.com/Oskarhn/humanizer/blob/main/SKILL.md#L89) | 检查句子长度和节奏是否过度一致 | [句子节奏](decision-rules.md#rhythm) | 通用 |
| 488 | [HafidIdrissi/humanizer](https://github.com/HafidIdrissi/humanizer/blob/master/SKILL.md#L308) | 依据作者已有的语气或样本修改 | [作者声音](decision-rules.md#voice) | 按场景 |
| 489 | [rob-ard/humanizer](https://github.com/rob-ard/humanizer/blob/main/SKILL.md#L29) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 490 | [bhushanasati25/humanizer](https://github.com/bhushanasati25/humanizer/blob/main/SKILL.md#L28) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 491 | [Aparnabuilds/humanizer](https://github.com/Aparnabuilds/humanizer/blob/main/SKILL.md#L249) | 把读者要找的答案提到前面 | [直接作答](decision-rules.md#answer) | 通用 |
| 492 | [imMamdouhaboammar/humanizer](https://github.com/imMamdouhaboammar/humanizer/blob/main/SKILL.md#L130) | 检查为强调而硬凑的否定对比 | [否定、反例与排比](decision-rules.md#contrast) | 通用 |
| 493 | [skk-hub/humanizer](https://github.com/skk-hub/humanizer/blob/main/SKILL.md#L41) | 朗读全文，再检查改写过程中增添的信息 | [读回与交付](decision-rules.md#verify) | 通用 |
