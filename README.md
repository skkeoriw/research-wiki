# research-wiki

多源研究知识库 — YouTube/Arxiv/Web 等内容 → NotebookLM 分析 → 知识图谱 wiki → TG 通知。

由本机 `agent-brain-plugins/youtube-wiki` SOP pipeline 驱动。

## Pipeline

```
raw/youtube-links/   → Stage A: youtube-fetch
raw/youtube-metadata/ → Stage B: notebooklm-research
raw/notebooklm-analysis/ → Stage C: wiki-build
index.md             → Stage D: tg-notify
```

详见根目录 `sop.yaml`。
