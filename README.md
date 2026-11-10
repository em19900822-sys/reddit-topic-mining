# reddit-topic-mining

Reddit 搜帖与选题入库 Skill：通过 Reddit 公开 RSS 搜索帖子，按项目里的筛选方法初筛、打分，并把精选帖和评分卡存到指定目录。

- `SKILL.md`：Skill 配方（Grok Bot / Cursor / Claude Code 等可读的 SKILL.md 格式）
- `USAGE.md`：调用例句和怎么改默认值

## 用法示例

```
按搜帖 Skill，只找促排不顺的人，精选5条，完整打分并入库。
按搜帖 Skill，这次只初筛，不打分。
```

项目自己的默认值（子版、关键词、条数等）写在项目目录里的 `搜帖配置.md`，不在本仓库中。
