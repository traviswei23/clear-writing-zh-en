# clear-writing-zh-en

给 Codex 用的中英文写作技能。它可以起草、轻改、重写、只做审校，或把一段话讲给不同背景的读者。比如同一份导出测试记录写着 CSV 通过、PDF 测试超时，工作消息可以直接写“CSV 导出已通过测试。PDF 测试超时，导出结果仍待核对。”一次超时还不足以断定 PDF 功能损坏。

## 安装与更新

第一次安装时，把这行发给 Codex。

```text
$skill-installer 请安装 https://github.com/traviswei23/clear-writing-zh-en/tree/main/skills/clear-writing-zh-en
```

安装后，从下一轮对话起可以直接调用。其他人使用同一公开地址即可安装。手动安装也可以，把仓库里的 `skills/clear-writing-zh-en` 整个目录复制到个人 Codex 技能目录（默认是 `~/.codex/skills/`）。更新已有安装时，先保留自己的修改，再把新版入口和整个 `references/` 同步进去。安装器遇到同名目录会停止。

## 怎么用

```text
$clear-writing-zh-en 轻改下面这封客户邮件。保留道歉、日期和退款条件。只给可直接发送的正文。
```

```text
$clear-writing-zh-en 把这个 PR 分别写成维护注释和用户能看懂的发布说明。按差异和测试记录写。
```

```text
$clear-writing-zh-en Edit the Results paragraph for a journal. Preserve the denominators, follow-up period and uncertainty. Flag substantive errors separately.
```

For English output, give the skill the source text, the intended reader and the kind of edit you want. Ask for comments only if you want a review instead of a revised draft.

希望本机 Codex 平常也按这套习惯回复，可以在个人 `~/.codex/AGENTS.md` 现有指令中加入下面这段。在另一台电脑上，用同样的安装方式和个人指令。其他能读取文件的助手可把同一份入口及所需手册作为项目资料，按任务引用。

> 中英文回复和文件都先回答读者实际需要知道的问题。保留事实、作者声音、证据强度和影响行动的条件。起草或修订长文、技术文档、维护注释、复杂解释和论文时，使用 clear-writing-zh-en 并按任务选读参考手册。简单问题说清就停。

## 需要细看时读哪一篇

| 你要做的事 | 从哪里开始 |
| --- | --- |
| 判断用户要的是轻改、重写、翻译还是审校 | [技能入口与六步工作法](skills/clear-writing-zh-en/SKILL.md) |
| 找出具体哪句有问题，判断该删、该修还是应保留 | [中英文改稿手册与七个实例](skills/clear-writing-zh-en/references/editing-playbook.md) |
| 写回复、估算时间、讲机制、写操作文档、接口说明、错误提示、PR 和维护注释 | [读者沟通与技术写作](skills/clear-writing-zh-en/references/reader-and-technical.md) |
| 组织论文各章节，分清相关与因果、人数与次数、百分点与百分比 | [科研表达与事实核对](skills/clear-writing-zh-en/references/research-and-revision.md) |
| 处理规则冲突，例如简洁与完整、直接表达与必要限定 | [21 个判断方法和取舍实例](skills/clear-writing-zh-en/references/decision-rules.md) |
| 查某个 GitHub 技能贡献了什么 | [493 个入口与采用条件](skills/clear-writing-zh-en/references/source-map.md) |

## 怎样检验改稿有没有改错

给技能一份含有容易误读信息的原稿，再按验收条件查看它的实际输出。下列记录是虚构的测试输入。

| 输入 | 合格的结果 |
| --- | --- |
| 群消息。服务 10:20 恢复，网页下单验证成功，移动端未测。写给接班同事。 | 保留时间、已测范围和待办。读者不会误以为移动端发生了故障。 |
| 英译中。Only an owner can select `Export history` after approval. | 保留审批条件、唯一被授权的角色、手动操作和可在界面中找到的标签。 |
| 只审公告。材料注明“仅管理员可下载已结算账单”。草稿说“每位用户可下载全部账单”。 | 分别指出权限和账单范围这两个问题，交付批注。 |
| 润色结果。历史对照组 60 人中 12 人至少投诉一次，本期 64 人中 15 人至少投诉一次。作者写“新方案导致多 3 次投诉”。 | 指出材料统计的是人数，两组分母不同，历史比较也不足以认定因果。只准轻改时将实质问题单列给作者。 |
| 写注释。项目给超时设定传毫秒，传输层接口接收秒。 | 说明跨接口单位约定。标识符、可执行代码和返回行为保持一致。 |

这份手册整合了本次调研收录的 475 个公开仓库、493 个技能入口。相同建议合并使用，有冲突的做法按读者、体裁和证据决定取舍。来源表随技能分发，日常写作只需读取与任务有关的章节。
