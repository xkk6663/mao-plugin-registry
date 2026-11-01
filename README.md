# mao-plugin-registry · 精选插件索引

Mao 插件市场的**精选清单**（混合索引的"官方推荐"一侧）。主索引是 GitHub topic
`mao-plugin-market` 自动发现、零人工维护；本仓库是可选叠加，收录经人工过目的插件。

## 收录规则（PR 评审制）

1. 插件仓库根有合法 `mao-plugin.json`（schema 1），远程安装预览不报错；
2. PR 里附仓库地址 + 一句话说明；维护者过目清单字段与仓库内容后合入；
3. 条目格式：`{"repo": "owner/repo", "id": "...", "name": "...", "category": "...", "author": "...", "note": "..."}`。
