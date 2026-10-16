# 维护来源与本地取舍

仅用于维护和溯源，不是运行时必读文件。适用版本：v0.1.4；来源记录沿用此前核查，本次未重新审计上游许可。

来源核查日期：2026-08-30。下列链接固定到已核读的提交；文件日期按Asia/Shanghai显示，依据Git提交者时间。固定版本可复核，不代表自动跟随上游最新版本。采用前涉及接口、脚本或宿主适配的部分仍须重验。

## 已确认内容何时可以重新修改

来源：[JUNERDD/skills — receiving-code-review](https://github.com/JUNERDD/skills/blob/7bc44add6e04acf5152e85da23b44da1e4de4cc6/skills/receiving-code-review/SKILL.md)，文件最后修改2026-07-11。

- 借鉴：已处理的决定需要具体变化才可重开；有意如此必须有用户、要求或设计批准依据，不能仅凭现有代码推断。
- 本地写法：以用户本次要求为准；证据与保留项冲突时说明冲突，不自行扩大授权。用户已明确改变旧要求时，不重复求批准。
- 不采用：完整执行链台账、强制多代理、处置矩阵、持久审查报告和16步流程。

## 保护原文与局部修复误改

来源：[tw93/Waza — write](https://github.com/tw93/Waza/blob/9fbf0ab2e33e26e4b77eac57f4c53170a2b15186/skills/write/SKILL.md)，文件最后修改2026-08-16。

- 借鉴：保护自然清楚的原句与作者声音，核对是否误改作者原话；连续返工不靠不断增加修辞解决。
- 本地补强：仅修复能够定位的本轮误改，保留后续独立编辑；不整体回退、不清理旧版本。这个多次编辑保护边界是本地适配，不声称是上游原文。
- 不采用：个人文风规则、标点脚本或对全文的自动修改授权。

## 修改前后比较与停止无收益的重复

来源：[research-paper-lifecycle-skills — reflect-and-improve](https://github.com/ShaishavMaisuria/research-paper-lifecycle-skills/blob/f9a0ed8f0f1770fb0321c5b022d55ed34c939927/skills/reflect-and-improve/SKILL.md)，文件最后修改2026-06-21。

- 借鉴：围绕同一目标比较前后、识别退步、停止无收益的重复。
- 本地写法：有新证据或可验证的新修法时，在原授权内继续；没有时说明未解决项，不把自评分提高当成用户体验改善。
- 不采用：固定三轮、论文记忆创建/追加/裁剪、自动整份回退，也不宣称已复现上游的自动循环效果。

## 已有验收原则的交叉参考

[obra/superpowers — verification-before-completion](https://github.com/obra/superpowers/blob/b36e0829c6d0140e93cfef2ca599b1b07d4a7797/skills/verification-before-completion/SKILL.md)，文件最后修改2026-07-24。用于交叉核对已有的“证据支持到哪一层，就只声称到哪一层”，不重复增加一套门禁或必读依赖。

## 证据限度

这里记录的是方法来源与本地重新表述，没有复制上游代码或整段流程，没有安装、执行上游Skill及其脚本。源码存在并不证明实际效果；结构检查、合成案例和真实用户验收应分别报告。
