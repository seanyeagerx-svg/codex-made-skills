# 我们在 Codex 里做的 Skills

把日常协作中反复遇到的问题，整理成可复用的 Skill。这份合集收录 **4 项已确认由本项目编写或自建封装的 Skill**，与[小龙虾合集](https://github.com/seanyeagerx-svg/lobster-made-skills)分开维护。

[下载 4 项合集 ZIP](https://github.com/seanyeagerx-svg/codex-made-skills/archive/refs/tags/v0.1.0-review.zip) · [来源与版本](SOURCE.md) · [审查范围](AUDIT.md)

## 有哪些

| Skill | 用途 | 单项版本 |
|---|---|---|
| [request-restate](skills/request-restate/SKILL.md) | 在会改变结果的关键歧义处核对要求，清楚请求直接处理 | 0.2.2 |
| [rework-diagnosis](skills/rework-diagnosis/SKILL.md) | 返工时找准问题，保留已确认内容，按授权修正并复验 | 0.1.4 |
| [pinterest-search-links](skills/pinterest-search-links/SKILL.md) | 把参考需求变成有差异的英文 Pinterest 搜索入口 | 1.6.0 |
| [research-curator](skills/research-curator/SKILL.md) | 对资料、参考或方案去重、核验和筛选，报告实际覆盖范围 | 0.1.0 |

前三项继续保留各自独立仓库；本合集固定版本，便于一起下载。资料筛选器有原项目创建、交付和安装副本记录。名称表示我们在 Codex 中完成的项目成果，不是 Codex 官方 Skill，也不表示发明了其中引用的全部方法。

## 怎么用

1. 下载并解压，按需选择 `skills/` 下的单个 Skill 文件夹，保留其参考文件、界面元数据和许可证。
2. 本地项目试用可复制到 `<你的项目>/.agents/skills/<名称>/`。已有同名文件夹时先比较版本和独立改动，避免混装或直接覆盖。
3. 在 Codex 中用 `$request-restate`、`$rework-diagnosis`、`$pinterest-search-links` 或 `$research-curator` 显式调用，核对实际加载位置。未发现更新时重启 Codex。

安装路径和加载机制对照了 [OpenAI 官方 Skills 文档](https://learn.chatgpt.com/docs/build-skills)。本合集采用直接目录形式供本地试用，未制作或验收插件市场安装包；自动选择和其他 Agent 的兼容性也需单独验证。

## 收录边界

不收录视频生产 SOP、第三方 Skill 包、来源尚未核清的 Skill、真实对话、账号配置、客户素材或运行日志。Pinterest 文件夹中的 `SOP.md` 是该搜索入口的用户说明，属于同一自制功能，不是视频 SOP。

源文件与公开副本的对照、检查内容和未验收项见 [VALIDATION.md](VALIDATION.md)。外部方法出处见 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)，本项目文本按 [MIT](LICENSE) 分发。
