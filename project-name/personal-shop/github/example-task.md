---
project: project-name
client: personal-shop
industry: 自営業・個人shop
category: github
type: task
status: in-progress
priority: high
version: 1.0
deadline: 2026-05-14
impact: high
tags: [#automation, #workflow]
created: 2026-04-14
---

# 例：GitHubアクション自動化タスク

## 概要
このはサンプルタスクです。このフォーマットを参考にして、実際のタスクを作成してください。

## フロントマッターの説明

| フィールド | 説明 | 例 |
|-----------|------|-----|
| `project` | プロジェクト名 | project-name |
| `client` | クライアント名 | personal-shop / apparel / fishery / restaurant |
| `industry` | 業界 | 自営業・個人shop / アパレル / 養殖漁業 / 飲食店 |
| `category` | カテゴリ | github / docker / programming / dx-strategy |
| `type` | ノートの種類 | task |
| `status` | 進捗状況 | pending / in-progress / done |
| `priority` | 優先度 | low / medium / high |
| `version` | バージョン | 1.0, 1.1, etc. |
| `deadline` | 期限 | YYYY-MM-DD |
| `impact` | 売上への影響度 | low / medium / high |
| `tags` | タグ（複数可） | [#tag1, #tag2] |
| `created` | 作成日 | YYYY-MM-DD |

## 使い方

1. **新しいタスクを作成**
   - `project-name/{client}/{category}/` に `.md` ファイルを追加
   - 例：`project-name/personal-shop/github/my-task.md`

2. **フロントマッターを設定**
   - 上記のテンプレートをコピーして修正

3. **[[project-name/tasks|タスク一覧]]を確認**
   - Dataview が自動的に集約した表を表示

## サンプルタスク構成

```
---
project: project-name
client: [personal-shop/apparel/fishery/restaurant]
industry: [業界名]
category: [github/docker/programming/dx-strategy]
type: task
status: [pending/in-progress/done]
priority: [low/medium/high]
version: 1.0
deadline: YYYY-MM-DD
impact: [low/medium/high]
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

## 期待される成果
- 売上UP の観点では？
- DX化の進捗は？

## 参考資料
関連ノートへのリンク
```

このファイルは削除しても構いませんが、参考として残しておきます。😊
