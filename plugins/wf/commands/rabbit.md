---
name: rabbit
description: CodeRabbitの指摘に対応
model: sonnet
disable-model-invocation: true
---

現在のPR Commentのうち @coderabbitai によるコメントのうちresolveではないものを全て取得します。
それぞれのコメントに対してparallelで以下を進めます。
1. その指摘の再現可能性を動作確認を通して確認する
2. 修正が妥当な場合、Prompt for AI Agents の内容を元に 新たなsubtaskを作成して修正する
