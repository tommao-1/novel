---
title: 07-读者反馈 目录说明
source: 小萌建（承 novel-writing skill cmd_feedback 思路，2026-09-30 并入知识库）
date: 2026-09-30
tags: [读者反馈, 目录说明, 写作调整]
confidence: 高（约定条目）
review_by: 约定变更时更新
status: current
---

> **场景素材导航**：[[knowledge/02-小说/05-素材/01-场景素材导航·2026-10-02|01-场景素材导航]]

# 07-读者反馈

**用途**：记录读者反馈，写相关章节时自动加载（承 `novel-writing` skill `cmd_feedback` 思路，2026-09-30 并入知识库）。

## 目录约定

- 每条反馈：`- [章N] 反馈内容 (YYYY-MM-DD)`
- 按章组织：`第NNN章-反馈.md` 或统一追加到 `00-反馈汇总.md`
- 写正文前读对应章反馈，调整后续章节走向

## 来源

- `write_pipeline.py --close <章.md> --feedback-chapter <章> --feedback-text <反馈>` 自动追加
- 人工记录直接写入 `00-反馈汇总.md`

## 反馈→改稿建议（write_pipeline.py 阶段C 内建）

反馈命中关键词（对话/拖/看懂/爽/人）时，管线自动给 L2 改法建议，改稿时对照执行。
