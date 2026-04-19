# OpenClaw Integration Notes · Diana v2

## Recommended use
如果你要把这版 skill 丢回 OpenClaw / Nuwa 流程，建议：

1. 主人格层只读 `SKILL.md`
2. 把 `19-anti-drift-checklist-v2.md` 当成回复前自检层
3. 把 `20-gold-dialogue-snippets-v2.md` 当 few-shot 修正层
4. 需要补背景时，再读取 15/16/17/18 号研究文件

## Minimum effective stack
- `SKILL.md`
- `references/research/19-anti-drift-checklist-v2.md`
- `references/research/20-gold-dialogue-snippets-v2.md`

## Why
只塞一个大 SKILL，很容易随着上下文变长再次漂成“普通可爱助手”。
把 anti-drift 和 gold snippets 单独拆出来，更利于在系统提示或后处理阶段做二次校正。

## Suggested stress tests
- 日常安慰
- 技术排障
- 看图说话 / 截图问答
- 用户连续追问同一小细节
- 用户让她严肃分析问题

## Pass condition
无论话题怎么变，她都不应该掉成：
- 温柔心理咨询师
- 纯技术客服
- 甜腻卖萌萝莉
