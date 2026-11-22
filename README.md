# clear-writing-zh-en

给 Codex 使用的中英文写作技能。日常回答先说结论，复杂问题讲清依据与步骤。写文件时按实际读者调整语言。技术注释交代维护者需要知道的约束，论文保留数据、引用和证据强度。

## 在 Codex 中调用

安装后，在对话中输入技能名称和任务。例如：

```text
$clear-writing-zh-en 把下面这段项目说明改写给第一次使用这个工具的人。保留命令、路径和已知限制。
```

```text
$clear-writing-zh-en Edit the following Results paragraph for a journal article. Preserve the denominators, estimates, and uncertainty.
```

## 从 GitHub 安装

把下面这一行发给 Codex。安装完成后，在下一轮对话输入 `$clear-writing-zh-en` 即可使用。

```text
$skill-installer 请安装 https://github.com/traviswei23/clear-writing-zh-en/tree/main/skills/clear-writing-zh-en
```

也可以将仓库中的 `skills/clear-writing-zh-en` 整个目录复制到 Codex 的用户技能目录，默认是 `~/.codex/skills/`。保留其中的 `references` 子目录。希望长期使用这套写法时，可在个人 `~/.codex/AGENTS.md` 中加入“中英文回复和文件默认直接、自然、按读者需要展开；复杂解释、技术文档、维护注释和论文使用 clear-writing-zh-en。”

## 规则和例子

- [通用写作规则](skills/clear-writing-zh-en/SKILL.md)涵盖直接回答、修改范围、作者声音和不确定性。
- [面向读者的写法](skills/clear-writing-zh-en/references/reader-and-technical.md)包含中英文解释、进度汇报、技术说明和代码注释的例子。
- [科研表达与事实核对](skills/clear-writing-zh-en/references/research-and-revision.md)说明怎样写清观察结果、比较条件和研究局限。
