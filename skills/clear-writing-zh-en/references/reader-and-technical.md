# 面向读者的写法

## 回答与进度

先找出对方真正要判断的事。问题有明确答案就先答。报告故障时从现象和影响开始，把证实的原因和仍待排查的原因分开。需要对方采取行动时指出具体动作。普通进度消息只在有变化时增加信息。被纠正后更新结论和受影响的稿件，保留仍有用的依据。

例：只知道“旧版浏览器的兼容测试尚未运行”。汇报写“新版浏览器的测试已通过”需要另有记录。只凭当前材料，写“旧版浏览器的兼容性还没测。”读者如果正等发布决定，再交代这项缺口对决定的影响。

English example. The test log shows that export passed for CSV and the PDF test timed out. A useful update is “CSV export passed. The PDF test timed out, so PDF export still needs verification.” Calling PDF export broken would confuse the test outcome with a confirmed product defect.

## 解释与工作文稿

第一次接触某个概念的人，往往先需要知道它解决什么问题。给出一个完整的小例子，再用术语对上例子中的动作。专家读者则可以从术语和新发现开始。给同事的邮件把所需决定和时间放在容易找到的位置，只使用材料给出的截止日期。涉及产品或公共服务时，说明读者能做什么以及条件是什么。

中文例：“推进报表权限能力建设”没有交代谁能做什么。如果实际变更是“财务人员现在可以查看本部门报表”，就直接写后一句。如果只知道正在调整权限，就保留进行中的状态。不要猜角色和功能。

English example. When the interface and its behavior are known, replace “The user can leverage the configuration functionality to enable alerts” with “Turn on alerts in Settings.” Keep the interface label exactly as it appears in the product.

需要朗读的讲稿按说话时自然停顿的地方分句。简报标题可以表达发现，图表标签和单位要便于对照。公开文章保留作者已有的情绪与节奏。中文版按指定地区使用简体、台湾繁体或香港书面语。英文采用目标读者熟悉的搭配，合理使用主动或被动。中英混排时使用同一术语对应同一对象，保留标识符大小写和产品名。

## 技术文档、报错和注释

- 操作文档写清前提、动作和预期结果。用户需要逐字输入的命令、配置键、路径、代码和报错原文按原样保留。在某种条件下会覆盖数据或改变结果时，把这个条件放在操作旁边。
- README、发布说明、PR 和进度消息的读者不同。发布说明写用户能观察到的变化。PR 说明写为什么改、怎么验证，以及评审要关注的选择。只把实际运行过的检查称为已验证。
- 给未来的维护者写注释。解释从代码难以推断的约束、顺序、边界、单位或取舍。代码已经清楚表达的动作通常可以省去注释。修改现有注释时对照实现；历史原因需要有材料支持。
- 例：已知输入时间以毫秒计、下游接口以秒计。中文注释可写“接口按秒接收超时时间，配置值的单位是毫秒。”英文可写 “The API expects seconds. The configured timeout is in milliseconds.” 对代码 `seconds = timeout_ms / 1000` 逐字解说除法，对维护者帮助较小。
