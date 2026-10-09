---
name: japan-wechat-retail-crm
description: Design or review a Japan-market retail customer-intelligence operating model for WeChat users using receipt evidence, OCR, rewards, and CRM. Use when a phased integration strategy and vendor-governed operating model are needed rather than a generic OCR demo.
---

# Japan WeChat Retail CRM Blueprint

## Scope

Use this Skill for Japan retail teams serving WeChat users. It is a domain method derived from a receipt-to-CRM operating pattern, not a private Mini Program codebase or a deployable product template.

## Core loop

Customer identity → receipt evidence → OCR extraction → reconciliation and anomaly checks → automated or manual review → points/gift issuance → CRM record → segmentation and next action.

## Design decisions

- Treat the receipt as purchase evidence, not the product itself.
- Compare POS/loyalty integration, staff entry, registration-only, and customer-submitted receipts against speed, data quality, operating load, and future integration cost.
- Use receipt-led capture as a staged option when full integration is not yet practical; do not claim it is universally superior.
- Evaluate OCR on business usability: total, tax where applicable, item data where available, time, duplicate checks, reconciliation, and exception handling.
- Name an operator or rule for every exception, reward decision, and override.

## Technical governance

Keep customer experience, operations console, business services, and run layer distinct. A business owner who does not write code can still define acceptance criteria, decide operational fallback, evaluate vendor scope/cost, and preserve integration boundaries for future POS or e-commerce connections.

## Public positioning

Describe the work as a Japan-market retail operating reference for WeChat users. Do not claim it is the first, only, or standard solution without independent proof.
