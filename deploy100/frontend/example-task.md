---
project: deploy100
type: task
status: in-progress
priority: high
version: 1.0
tags: [#frontend, #ui]
created: 2026-04-14
---

# 例：フロントエンド実装タスク

## 概要
このはサンプルタスクです。このフォーマットを参考にして、実際のタスクを作成してください。

## フロントマッターの説明

| フィールド | 説明 | 例 |
|-----------|------|-----|
| `project` | プロジェクト名 | deploy100 |
| `type` | ノートの種類 | task |
| `status` | 進捗状況 | pending / in-progress / done |
| `priority` | 優先度 | low / medium / high |
| `version` | バージョン | 1.0, 1.1, etc. |
| `tags` | タグ（複数可） | [#frontend, #ui] |
| `created` | 作成日 | YYYY-MM-DD |

## 使い方

1. **新しいタスクを作成**
   - `deploy100/frontend/` または `deploy100/backend/` に `.md` ファイルを追加

2. **フロントマッターを設定**
   - 上記のテンプレートをコピーして修正

3. **[[deploy100/tasks|タスク一覧]]を確認**
   - Dataview が自動的に集約した表を表示

## サンプルタスク構成

```
---
project: deploy100
type: task
status: [pending/in-progress/done]
priority: [low/medium/high]
version: 1.0
tags: [#xxx, #yyy]
created: YYYY-MM-DD
---

# タスク名

## 概要
何をするか簡潔に説明

## 詳細
- 詳しい説明
- 要件
- チェックリスト

## 参考資料
関連ノートへのリンク
```

このファイルは削除しても構いませんが、参考として残しておきます。😊
