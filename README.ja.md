# GEO SEO リソース

[English](./README.md) | [简体中文](./README.zh-CN.md) | [繁體中文](./README.zh-Hant.md) | [日本語](./README.ja.md)

<div align="center">
  <a href="./assets/branding/README.md" title="ブランドアセットとリポジトリ用マーク">
    <img
      src="./assets/branding/social-preview.svg"
      alt="GEO SEO リソース — 再利用可能な SEO / GEO スキルライブラリ（1280×640 バナー）"
      width="920"
      height="460"
      style="max-width: 100%; height: auto;"
      decoding="async" />
  </a>
</div>

発見されやすく AI からも読み取りやすい、参考ドキュメント型サイト向けの第三者 SEO / GEO リソース集です。

このリポジトリには、公開可能なサンプル、GEO ノート、`llms.txt` パターン、スキーマ参照、監査レポートのサンプル、そして再利用可能な SEO / GEO スキルライブラリが含まれています。例示 URL には予約ドメイン `example.org` を使います。実運用では自サイトのドメインとパスに置き換えてください。

## 言語と形式

- **README**: 英語・簡体字中国語・繁体字中国語・日本語で同じ構成。上部のリンクで切り替えます。
- **本文ドキュメント**: `docs/` の多くは英語で、ツール横断でリンクを安定させるためです。
- **エージェント向けスキル**: ディレクトリ名と `SKILL.md` は英語中心（Cursor / Codex / Claude Code の慣習に合わせるため）。
- **ライセンス**: [`LICENSE`](LICENSE)（MIT）。著作権者: **Elser AI Limited**。GitHub 連絡先: [@wchklaus97](https://github.com/wchklaus97)。

## 軽量な品質チェック（CI/CD ではない）

アプリの**ビルド・リリース・デプロイのパイプラインはありません**。ドキュメントとスキルが主です。

あるのは次だけです。

- 小さな **GitHub Actions** ワークフロー（[`.github/workflows/ci.yml`](.github/workflows/ci.yml)）: push / PR で Markdown リント、一部パスのリンク確認、`reports/` のサンプル JSON 検証。
- 同じチェックはローカルでも実行可能です（[`docs/ci-and-quality.md`](docs/ci-and-quality.md)）。

## このリポジトリの見方

- **第三者の参考資料**: 特定ベンダーから独立して保守される教育・参照コンテンツです。
- **非公式**: いかなる製品・商標の公式・認可・提携リポジトリでもありません。
- **スナップショットは陳腐化しうる**: ルートや指標は本番サイトの変更でずれることがあります。重要な点はリンク先で確認してください。
- **現状提供**: サンプルとスキルに保証はありません（研究・運用ワークフロー向け）。

## 位置付け

- これは第三者のリソースリポジトリです。
- いかなる単一ベンダー／製品の公式資産、認可済み資産、提携資産でもありません。
- 目的は、公開リファレンスサイトを SEO、GEO、AI 可読性の観点でどう構成できるかを、リサーチャー、運用担当者、コンテンツチームが理解できるようにすることです。

## 主要な例示ルート（プレースホルダ）

以下は文書用プレースホルダ（`example.org`）です。実際の利用時は自サイトに差し替えてください。

- [Guides hub](https://www.example.org/guides?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Prompt templates hub](https://www.example.org/prompt-templates?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Product overview guide](https://www.example.org/guides/product-overview?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Advanced prompt techniques](https://www.example.org/prompt-templates/advanced-prompt-tips?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Illustrative `llms.txt`](https://www.example.org/llms.txt?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)

## このリポジトリに含まれるもの

- `docs/llms-txt-guide.md`: 参考サイトが AI 可読コンテンツインデックスをどう構成できるか
- `docs/schema-examples.md`: 公開可能なスキーマ案とマッピングメモ
- `docs/citability-checklist.md`: guide ページと prompt-template ページの AI 引用準備度を高める方法
- `docs/reference-site-examples.md`: 最初に訴求するルートの整理マップ（例示 URL）
- `docs/report-samples.md`: GEO 監査レポートのサンプルと読み方
- `docs/measurement-plan.md`: GitHub referral UTM ルールと計測メモ
- `docs/skills-index.md`: Cursor、Codex、Claude Code 向けのミラー技能カタログ
- `docs/skill-route-inventory.md`: 旧ワークスペース名・汎用技能・例示 slug の対応表
- `docs/repository-overview.md`: リポジトリ概要、構成、次のアクション
- `docs/ci-and-quality.md`: CI 範囲、品質チェック、ローカル確認方法
- `.cursor/skills/agent-skills-index.md`: リポジトリ内 canonical 技能インデックス
- `examples/reference-route-map.md`: パス単位の情報設計マップ（UTM や README 配置ルールは含めない）
- `reports/reference-geo-audit-sample.md`: 公開可能な GEO サマリー
- `reports/reference-geo-audit-sample.json`: 構造化された監査サンプルデータ

## GEO の現状スナップショット

これらのサンプル指標は、典型的なリファレンスサイト GEO スナップショットの形を示すデモ用の値です。

- `llms.txt`: 存在し、有効
- `llms.txt` links: `57`
- guide overview citability: `40.6 / 100`
- prompt-template citability: `34.0 / 100`

要約された解釈は [`reports/reference-geo-audit-sample.md`](reports/reference-geo-audit-sample.md) を参照してください。

## このリポジトリの目的

このリポジトリは、検索で発見されるリソースレイヤーとして機能します。

- GitHub ユーザーに役立つ GEO / SEO の実例を提供する
- ルートマップやサンプルレポートなどの証拠資産を提供する
- 興味を持った読者をまず情報密度の高いドキュメントページへ導く（fork では実ドメインに置換）
- 商用リンクや運営主体の自己紹介リンクを明確に二次的な位置に置く

## 汎用スキルライブラリ

このリポジトリには、以下に対応した再利用可能なスキルライブラリも追加されています。

- `Cursor`
- `Codex`
- `Claude Code`

canonical 版は `.cursor/skills/` にあり、`codex/skills/` と `.claude/skills/` には薄いアダプタを配置しています。

現在実装済みの汎用スキルは主に次の領域です。

- ブラウザ発見と SEO 分析
- サイト構造と landing page SEO 分析
- 参考サイト分析
- capability ページのワークフロー
- site SEO verify-to-generate ワークフロー
- SEO 成長と追跡のワークフロー
- capabilities、guides、prompt templates の route cluster スキル
- OG プレビュー画像生成
- referral トラフィック分析
- video-to-story ワークフロー

## 安全なリンク方針

主要な外部リンクは、実際に分析・訴求する公開ドキュメントサイトを指すべきです。既定の例は特定の本番資産に固定しません。

運営主体に関する二次リンクは、以下のような中立的な配置であれば掲載できます。

- `About the team`
- `More tools by our team`
- `Contact our team`

これらは特定ベンダー製品ワークフローの自然な次の一歩として表現すべきではありません。

## 関連サイト（背景として）

- **[example.org](https://www.example.org/)** — IETF 予約のドキュメント用プレースホルダドメイン。例示 URL 専用で、本リポジトリのワークフローと実プロダクトサイトを結びつけるものではありません。
- **[elser.ai](https://www.elser.ai/?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources_identity)** — 保守側に関連する広いツール群。任意の補足であり、ここでのサンプルを読む**前提ではありません**。

推奨や保証を意味するものではありません。

## メンテナー

GitHub 上の主な連絡先: [@wchklaus97](https://github.com/wchklaus97)。SEO、GEO、AI 可読コンテンツシステムに関する文脈で保守しています。二次的な背景リンクは上の **関連サイト** を参照してください。

## 次に読むもの

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
