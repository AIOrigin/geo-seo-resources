# GEO SEO 資源庫

[English](./README.md) | [简体中文](./README.zh-CN.md) | [繁體中文](./README.zh-Hant.md) | [日本語](./README.ja.md)

<div align="center">
  <a href="./assets/branding/README.md" title="品牌資源與倉庫識別檔案">
    <img
      src="./assets/branding/social-preview.svg"
      alt="GEO SEO 資源庫 — 可重用的 SEO 與 GEO 技能庫（1280×640 橫幅）"
      width="920"
      height="460"
      style="max-width: 100%; height: auto;"
      decoding="async" />
  </a>
</div>

面向可發現、AI 可讀的參考文件類站點的第三方 SEO 與 GEO 資源集合。

本倉庫整理了可公開分享的範例、GEO 筆記、`llms.txt` 模式、結構化資料參考、示例審計輸出，以及一套可重用的 SEO / GEO 技能庫。示例 URL 使用保留域名 `example.org`，落地時請替換為你自己的線上站點。

## 語言與格式

- **README**：英文、簡體中文、繁體中文、日文版本結構一致，可透過頁首連結切換。
- **正文文件**：`docs/` 下多數長期文件以英文撰寫，便於跨工具保持連結穩定。
- **Agent 技能**：目錄名與 `SKILL.md` 正文以英文為主，以貼合 Cursor、Codex、Claude Code 的常見約定。
- **授權**：見 [`LICENSE`](LICENSE)（MIT）。著作權人：**Elser AI Limited**。GitHub 聯絡：[@wchklaus97](https://github.com/wchklaus97)。

## 輕量品質檢查（非 CI/CD）

本倉庫以**文件與技能**為主，**沒有**應用建置、發佈流水線或部署管道。

現有機制：

- 小型 **GitHub Actions** 工作流程（[`.github/workflows/ci.yml`](.github/workflows/ci.yml)）：在 push / PR 時執行 Markdown 檢查、對部分路徑的連結檢查，以及 `reports/` 下範例 JSON 的驗證。
- 本地可執行相同檢查；見 [`docs/ci-and-quality.md`](docs/ci-and-quality.md)。

## 如何理解本倉庫

- **第三方視角**：內容為獨立維護的教學與參考材料，與任何單一產品廠商無隸屬關係。
- **非官方**：不是任何特定商標或產品的官方、授權或合作倉庫。
- **快照會過時**：路徑、指標與範例可能隨線上站點變化；重要請以目標站點為準。
- **按現狀提供**：範例與技能僅供研究與營運工作流參考，不作擔保。

## 定位

- 這是一個第三方資源倉庫。
- 它不是任何單一廠商或產品的官方、授權或合作資產。
- 它的目標是幫助研究者、營運人員與內容團隊理解公共參考文件站點應如何為 SEO、GEO 與 AI 可讀發現進行組織。

## 主要示例入口（占位域名）

以下連結僅作文檔占位（`example.org`），請在實際使用時替換為你的域名與路徑：

- [Guides hub](https://www.example.org/guides?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Prompt templates hub](https://www.example.org/prompt-templates?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Product overview guide](https://www.example.org/guides/product-overview?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Advanced prompt techniques](https://www.example.org/prompt-templates/advanced-prompt-tips?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Illustrative `llms.txt`](https://www.example.org/llms.txt?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)

## 倉庫內容

- `docs/llms-txt-guide.md`：說明參考站點如何組織其 AI 可讀內容索引
- `docs/schema-examples.md`：可公開使用的結構化資料思路與映射說明
- `docs/citability-checklist.md`：提升 guide 與 prompt-template 頁面 AI 引用準備度的方法
- `docs/reference-site-examples.md`：首批重點推廣路徑的整理地圖（示例 URL）
- `docs/report-samples.md`：GEO 審計輸出範例及其解讀方式
- `docs/measurement-plan.md`：GitHub referral UTM 規則與測量說明
- `docs/skills-index.md`：面向 Cursor、Codex 和 Claude Code 的鏡像技能目錄
- `docs/skill-route-inventory.md`：舊工作區技能名、通用技能與示例 slug 對照表
- `docs/repository-overview.md`：倉庫整體概覽、結構與下一步建議
- `docs/ci-and-quality.md`：CI 範圍、品質檢查與本地驗證說明
- `.cursor/skills/agent-skills-index.md`：倉庫內 canonical 技能索引
- `examples/reference-route-map.md`：頁面路徑級資訊架構圖（不含 UTM 或 README 擺放規則）
- `reports/reference-geo-audit-sample.md`：可公開分享的 GEO 摘要
- `reports/reference-geo-audit-sample.json`：結構化示例審計資料

## GEO 線上快照

以下示例訊號為典型參考文件站 GEO 快照的形態示例（演示用指標）：

- `llms.txt`：已存在且有效
- `llms.txt` links：`57`
- guide overview citability：`40.6 / 100`
- prompt-template citability：`34.0 / 100`

摘要解讀見 [`reports/reference-geo-audit-sample.md`](reports/reference-geo-audit-sample.md)。

## 倉庫存在的意義

這個倉庫作為一個可被搜尋發現的資源層，承擔以下作用：

- 為 GitHub 使用者提供有用的 GEO 與 SEO 範例
- 提供路徑地圖和樣例報告等證明材料
- 優先將感興趣的讀者導向資訊密度高的文件頁（在 fork 中替換為真實域名）
- 將商業化或主體身份相關連結保持在次要位置

## 通用技能庫

這個倉庫現在也包含一層可重用的技能庫，分別適配：

- `Cursor`
- `Codex`
- `Claude Code`

canonical 版本位於 `.cursor/skills/`，`codex/skills/` 和 `.claude/skills/` 保存對應的薄適配層。

目前已經實作的通用技能主要包括：

- 瀏覽器發現與 SEO 分析
- 網站結構與 landing page SEO 分析
- 參考站分析
- capability 頁面工作流
- site SEO verify-to-generate 工作流
- SEO 增長與追蹤工作流
- capabilities、guides、prompt templates 的 route cluster 技能
- OG 預覽圖生成
- referral 流量分析
- video-to-story 工作流

## 安全連結策略

主連結應指向你實際分析或推廣的公共文件站點；本倉庫預設示例不綁定單一線上資產。

主體相關的次級連結可以出現在中性位置，例如：

- `About the team`
- `More tools by our team`
- `Contact our team`

這些連結不應被表述為某一廠商產品工作流的自然下一步。

## 相關站點（背景資訊）

- **[example.org](https://www.example.org/)** — IETF 保留的文件占位域名，僅用於示例 URL，不代表與本倉庫工作流綁定的真實產品站點。
- **[elser.ai](https://www.elser.ai/?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources_identity)** — 維護方相關的更廣工具與系統，可作可選背景了解，**不是**閱讀本倉庫範例的前置步驟。

以上僅為便於理解占位連結語義或相鄰工具語境，不構成背書。

## 維護者

GitHub 主要聯絡：[@wchklaus97](https://github.com/wchklaus97)。本倉庫在 SEO、GEO 與 AI 可讀內容系統相關語境下維護。次級背景連結見上文 **相關站點**。

## 延伸閱讀

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
