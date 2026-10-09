# Retail Receipt Intelligence

**日本市場の小売 CRM 運用リファレンス**  
WeChat、レシート OCR、特典運用を通じて、訪日中国人顧客の店頭購買を継続的に活用できる顧客データへつなぐケーススタディです。

[日本語](#日本語) · [中文](#中文) · [English](#english)

---

## 日本語

### このリポジトリについて

日本の小売現場で、訪日中国人顧客の一回限りの購買を、会員・購買証憑・特典・CRM の運用ループへ変えるための公開リファレンスです。

主題は特定の小程序コードを公開することではありません。POS の全面連携を待たずに、顧客自身のレシート登録を入口として、実購買データ、OCR の品質管理、例外審査、特典付与、次の CRM 活用をどう段階的に成立させるかを示します。

### ケースで扱うこと

- 日本の店舗運営を前提にした、訪日中国人顧客向け WeChat 接点
- レシート画像を実購買の証憑として扱うデータ取得設計
- OCR、金額照合、重複・例外処理、人手審査を含む運用モデル
- 会員 ID、ポイント、ギフト、分析を結ぶ CRM ループ
- POS・EC・既存会員基盤への将来連携を見据えた段階設計
- ベンダー開発における事業側の要件定義、受入基準、運用・技術判断

### 公開ケースページ

GitHub Pages では、日本語を初期表示とし、中国語・英語の独立した説明も提供します。

- `index.html` — 日本語
- `zh.html` — 中文
- `en.html` — English

### 再利用できる方法論

[`skill/japan-inbound-retail-crm/`](skill/japan-inbound-retail-crm/) には、この事例から抽出した日本市場向けの小売 CRM 運用設計 Skill を格納しています。私有ソースコードではなく、要件整理、統合方針、OCR の品質・審査設計、ベンダーガバナンスに利用する方法論です。

### 公開範囲

本リポジトリには、私有ソースコード、顧客情報、原票、実在するクラウド識別子、API 情報、または取引先固有の情報は含めていません。ページの数値は公開用に丸めています。Traceable GMV は顧客 ID と紐付けて捕捉した購買額であり、施策による増分売上ではありません。

---

## 中文

### 这个仓库是什么

这是一个面向日本零售场景的公开参考案例：如何以 WeChat、小票 OCR 和权益运营为入口，把访日中国消费者的一次线下购买变成可被 CRM 使用的顾客数据。

它不公开某个供应商交付的小程序源码。它公开的是方法：当 POS 或既有会员系统暂时无法直接连接时，如何先通过顾客上传购物凭证，验证真实消费数据、审核机制、权益激励和运营闭环，再逐步扩展到更深的数据连接。

### 你能从中参考什么

- 面向访日中国消费者的 WeChat 触点与本地零售运营结合方式
- 以小票作为真实购买凭证的数据采集方法
- OCR、金额校验、重复凭证、异常处理与人工审核的业务规则
- 会员 ID、积分、礼券与分析输出之间的 CRM 闭环
- 从小范围验证到 POS、EC、会员系统连接的分阶段路径
- 非技术业务负责人如何参与供应商方案、验收标准、运营设计与技术判断

### 案例页面

GitHub Pages 默认打开日语版，同时提供独立重写的中文和英文版本：

- `index.html` — 日本語
- `zh.html` — 中文
- `en.html` — English

### 可复用 Skill

[`skill/japan-inbound-retail-crm/`](skill/japan-inbound-retail-crm/) 是本项目的方法论资产。它不是可直接部署的私有生产系统，而是一套可用于调研、方案设计、供应商比较、OCR 审核规则和公开案例整理的日本市场零售 CRM 蓝图。

### 公开边界

仓库不包含私有源代码、客户信息、原始小票、真实云资源标识、接口信息或供应商专有内容。页面数据均为公开展示而做了范围化处理。Traceable GMV 是已关联顾客 ID 的捕获消费金额，不代表活动直接创造的增量销售。

---

## English

### What this repository is

This is a public operating reference for Japan retail teams serving Chinese visitors. It shows how a WeChat touchpoint, receipt evidence, OCR, and rewards can turn a one-time store purchase into customer intelligence that a CRM team can use.

It does not publish a supplier-delivered Mini Program codebase. It publishes the operating logic: when direct POS or loyalty-platform integration is not yet practical, use customer-submitted receipt evidence to validate real purchase data, review controls, incentives, and an operating loop before committing to deeper integration.

### What the reference covers

- A WeChat customer touchpoint designed for Chinese shoppers in Japan
- Receipt-led capture of verifiable in-store purchase evidence
- OCR quality controls, reconciliation, duplicate/anomaly handling, and manual review
- A CRM loop spanning member identity, points, gifts, and analysis outputs
- A phased route from proof of value toward POS, e-commerce, and loyalty integration
- Business-side product ownership: vendor evaluation, acceptance criteria, operating design, and technical governance

### Case-study pages

GitHub Pages defaults to Japanese and offers independently written Chinese and English pages:

- `index.html` — Japanese
- `zh.html` — Chinese
- `en.html` — English

### Reusable method Skill

[`skill/japan-inbound-retail-crm/`](skill/japan-inbound-retail-crm/) packages the domain method from this project. It is not a deployable private system; it is a blueprint for discovery, solution design, vendor comparison, OCR review rules, and public case-study work in the Japan retail context.

### Public scope

This repository excludes private source code, customer data, raw receipts, real cloud identifiers, API details, and supplier-specific materials. Metrics are rounded for public presentation. Traceable GMV means captured spend linked to customer identity; it is not campaign-attributed or incremental revenue.
