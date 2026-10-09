# Retail Receipt Intelligence — Case Study

公开作品集页面，展示一个植根日本本土零售运营的参考案例：以微信小程序、小票 OCR 与会员运营，把访日中国消费者的线下消费转为可使用的 CRM 数据。

它面向希望进入日本市场的中国团队，以及需要理解中国消费者触点的英语圈/国际团队。重点不是复用某一段私有代码，而是参考一套可分阶段落地的业务、运营与技术治理方法。

默认页为日语，并提供独立重写的中文与英文版本：`index.html`、`zh.html`、`en.html`。

## 本地预览

直接在浏览器打开 `index.html`。

## 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库，例如 `retail-receipt-intelligence-case`。
2. 上传下列公开文件，并保留目录结构：
   - `index.html`
   - `zh.html`
   - `en.html`
   - `README.md`
   - `assets/`（整个文件夹）
   - `skill/japan-inbound-retail-crm/`（整个文件夹）
3. **不要上传** `skill/retail-crm-case-study/`。这是案例制作工作流，不是本案例希望对外分享的内容。
4. 在仓库 `Settings → Pages` 中选择 `Deploy from a branch`，分支选择 `main` 和 `/(root)`。
5. 保存后，GitHub 会提供公开链接。

页面不包含源码、后台截图、原始运营数据、云账号或供应商信息。

## Reusable Skill

`skill/retail-crm-case-study/` 是案例制作 Skill：它将“资料核验、结果与计划的区分、技术治理叙事、三语本地化、公开内容检查”固化为流程。它保留在本地工作目录，不随本案例公开。

`skill/japan-inbound-retail-crm/` 是项目方法论 Skill：它把这个小程序所代表的日本本土零售运营模式——访日中国客群、WeChat 触点、购物凭证、OCR、权益与 CRM 闭环、分阶段系统连接、供应商治理——整理成可供其他团队参考的蓝图。它不包含私有源代码或可直接部署的生产系统。
