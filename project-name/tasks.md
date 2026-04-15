---
project: project-name
type: tasks
version: 1.0
---

# クライアント DX化・売上UP タスク管理

## 進捗中のタスク

```dataview
TABLE client, category, priority, deadline, impact
FROM "project-name"
WHERE status = "in-progress"
SORT priority DESC, deadline ASC
```

## クライアント別進捗

```dataview
TABLE client, category, status, impact
FROM "project-name"
WHERE type != "tasks" AND type != "changelog" AND type != "decisions"
SORT client, status
```

## 期限間近のタスク

```dataview
TABLE client, category, deadline, priority, impact
FROM "project-name"
WHERE status != "done" AND deadline
SORT deadline ASC
```

## 完了したタスク

```dataview
TABLE client, category, impact
FROM "project-name"
WHERE status = "done"
SORT completed-date DESC
```
