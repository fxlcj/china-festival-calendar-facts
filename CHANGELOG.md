# Changelog

## 2026-11-14 — DB backfill

- 22 entries appended from the site's curated `verified_facts` (source URLs already re-checked against official pages at DB ingest). Append-only, deduped by claim+source.

## 2026-11-13 — incremental sync from published articles

- 1 entries added from official-source sentences in newly published articles; 0 candidates skipped (unreachable/non-official/duplicate source).

## 2026-11-11 — expanded with official-source facts

- 3 entries added directly from official Chinese government sources (rail: NRA/PSB Announcement No.1 items catalogue; food: Anti-Food-Waste Law; payment: Interim Regulation on Express Delivery; festival: holiday-decision amendment). Total now 34.

## 2026-11-10
- 建仓：从 culture 主题 8 篇已发布英文文章的官方外链句 / FAQ 数字句 / 官方源直采（国务院办公厅 2026/2027 年度节假日安排、《全国年节及纪念日放假办法》国务院令第795号、国务院《通用规范汉字表》通知、UNESCO 中国书法与制茶技艺名录、二十四节气与春节的非遗列入）中，逐条 curl 验证官方源后收录 31 条事实。
- 口径：与铁路/食品仓一致——可引用资产，不计外链成绩、不进三个数、不推广。
- 官方源变更时按月度维护任务（每月 10 日 09:30）重核 source_url；国务院年度放假安排发布即当次更新本仓（不等月度）。
