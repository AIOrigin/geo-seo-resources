# GEO SEO 资源库

[English](./README.md) | [简体中文](./README.zh-CN.md) | [繁體中文](./README.zh-Hant.md) | [日本語](./README.ja.md)

<div align="center">
  <a href="./assets/branding/README.md" title="品牌资源与仓库标识文件">
    <img
      src="./assets/branding/social-preview.svg"
      alt="GEO SEO 资源库 — 可复用的 SEO 与 GEO 技能库（1280×640 横幅）"
      width="920"
      height="460"
      style="max-width: 100%; height: auto;"
      decoding="async" />
  </a>
</div>

面向可发现、AI 可读的参考文档类站点的第三方 SEO 与 GEO 资源集合。

本仓库整理了可公开分享的示例、GEO 笔记、`llms.txt` 模式、结构化数据参考、示例审计输出，以及一套可复用的 SEO / GEO 技能库。示例 URL 使用保留域名 `example.org`，落地时请替换为你自己的线上站点。

## 语言与格式

- **README**：英语、简体中文、繁体中文、日文版本结构一致，可通过页首链接切换。
- **正文文档**：`docs/` 下多数长期文档以英文撰写，便于跨工具保持链接稳定。
- **Agent 技能**：目录名与 `SKILL.md` 正文以英文为主，以贴合 Cursor、Codex、Claude Code 的常见约定。
- **许可**：见 [`LICENSE`](LICENSE)（MIT）。著作权人：**Elser AI Limited**。GitHub 联络：[@wchklaus97](https://github.com/wchklaus97)。

## 轻量质量检查（非 CI/CD）

本仓库以**文档与技能**为主，**没有**应用构建、发布流水线或部署管道。

现有机制：

- 小型 **GitHub Actions** 工作流（[`.github/workflows/ci.yml`](.github/workflows/ci.yml)）：在 push / PR 时运行 Markdown 校验、对部分路径的链接检查，以及 `reports/` 下示例 JSON 的校验。
- 本地可运行相同检查；见 [`docs/ci-and-quality.md`](docs/ci-and-quality.md)。

## 如何理解本仓库

- **第三方视角**：内容为独立维护的教学与参考材料，与任何单一产品厂商无隶属关系。
- **非官方**：不是任何特定商标或产品的官方、授权或合作仓库。
- **快照会过时**：路径、指标与示例可能随线上站点变化；重要请以目标站点为准。
- **按原样提供**：示例与技能仅供研究与运营工作流参考，不作担保。

## 定位

- 这是一个第三方资源仓库。
- 它不是任何单一厂商或产品的官方、授权或合作资产。
- 它的目标是帮助研究者、运营人员和内容团队理解公共参考文档站点应如何为 SEO、GEO 与 AI 可读发现进行组织。

## 主要示例入口（占位域名）

以下链接仅作文档占位（`example.org`），请在实际使用时替换为你的域名与路径：

- [Guides hub](https://www.example.org/guides?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Prompt templates hub](https://www.example.org/prompt-templates?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Product overview guide](https://www.example.org/guides/product-overview?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Advanced prompt techniques](https://www.example.org/prompt-templates/advanced-prompt-tips?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Illustrative `llms.txt`](https://www.example.org/llms.txt?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)

## 仓库内容

- `docs/llms-txt-guide.md`：说明参考站点如何组织其 AI 可读内容索引
- `docs/schema-examples.md`：可公开使用的结构化数据思路与映射说明
- `docs/citability-checklist.md`：提升 guide 与 prompt-template 页面 AI 引用准备度的方法
- `docs/reference-site-examples.md`：首批重点推广路径的整理地图（示例 URL）
- `docs/report-samples.md`：GEO 审计输出示例及其解读方式
- `docs/measurement-plan.md`：GitHub referral UTM 规则与测量说明
- `docs/skills-index.md`：面向 Cursor、Codex 和 Claude Code 的镜像技能目录
- `docs/skill-route-inventory.md`：旧工作区技能名、通用技能与示例 slug 对照表
- `docs/repository-overview.md`：仓库整体概览、结构与下一步建议
- `docs/ci-and-quality.md`：CI 范围、质量检查和本地验证说明
- `.cursor/skills/agent-skills-index.md`：仓库内 canonical 技能索引
- `examples/reference-route-map.md`：页面路径级信息架构图（不含 UTM 或 README 摆放规则）
- `reports/reference-geo-audit-sample.md`：可公开分享的 GEO 摘要
- `reports/reference-geo-audit-sample.json`：结构化示例审计数据

## GEO 在线快照

以下示例信号为典型参考文档站 GEO 快照的形态示例（演示用指标）：

- `llms.txt`：已存在且有效
- `llms.txt` links：`57`
- guide overview citability：`40.6 / 100`
- prompt-template citability：`34.0 / 100`

摘要解读见 [`reports/reference-geo-audit-sample.md`](reports/reference-geo-audit-sample.md)。

## 仓库存在的意义

这个仓库作为一个可被搜索发现的资源层，承担以下作用：

- 为 GitHub 用户提供有用的 GEO 与 SEO 示例
- 提供路径地图和样例报告等证明材料
- 优先将感兴趣的读者导向信息密度高的文档页（在 fork 中替换为真实域名）
- 将商业化或主体身份相关链接保持在次要位置

## 通用技能库

这个仓库现在也包含一层可复用的技能库，分别适配：

- `Cursor`
- `Codex`
- `Claude Code`

canonical 版本位于 `.cursor/skills/`，`codex/skills/` 和 `.claude/skills/` 保存对应的薄适配层。

当前已经实现的通用技能主要包括：

- 浏览器发现与 SEO 分析
- 网站结构与 landing page SEO 分析
- 参考站分析
- capability 页面工作流
- site SEO verify-to-generate 工作流
- SEO 增长与追踪工作流
- capabilities、guides、prompt templates 的 route cluster 技能
- OG 预览图生成
- referral 流量分析
- video-to-story 工作流

## 安全链接策略

主链接应指向你实际分析或推广的公共文档站点；本仓库默认示例不绑定单一线上资产。

主体相关的次级链接可以出现在中性位置，例如：

- `About the team`
- `More tools by our team`
- `Contact our team`

这些链接不应被表述为某一厂商产品工作流的自然下一步。

## 相关站点（背景信息）

- **[example.org](https://www.example.org/)** — IETF 保留的文档占位域名，仅用于示例 URL，不代表与本仓库工作流绑定的真实产品站点。
- **[elser.ai](https://www.elser.ai/?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources_identity)** — 维护方相关的更广工具与系统，可作可选背景了解，**不是**阅读本仓库示例的前置步骤。

以上仅为便于理解占位链接语义或相邻工具语境，不构成背书。

## 维护者

GitHub 主要联络：[@wchklaus97](https://github.com/wchklaus97)。本仓库在 SEO、GEO 与 AI 可读内容系统相关语境下维护。次级背景链接见上文 **相关站点**。

## 延伸阅读

- [LLMS.txt guide](docs/llms-txt-guide.md)
- [Citability checklist](docs/citability-checklist.md)
- [Schema examples](docs/schema-examples.md)
- [Reference site route examples](docs/reference-site-examples.md)
- [Report samples](docs/report-samples.md)
- [Measurement plan](docs/measurement-plan.md)
- [Skills index](docs/skills-index.md)
- [Skill and route inventory](docs/skill-route-inventory.md)
- [Repository overview](docs/repository-overview.md)
- [CI and quality](docs/ci-and-quality.md)
