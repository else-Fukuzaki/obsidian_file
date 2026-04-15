---
project: deploy100
type: tasks
version: 1.0
---

# タスク管理

## 進捗中のタスク

```dataview
TABLE status, priority, version, tags
FROM "deploy100"
WHERE status = "in-progress"
SORT priority DESC
```

## 完了したタスク

```dataview
TABLE status, priority, version, completed-date
FROM "deploy100"
WHERE status = "done"
SORT completed-date DESC
```

## すべてのタスク

```dataview
TABLE status, priority, version, tags
FROM "deploy100"
WHERE type != "tasks" AND type != "changelog" AND type != "decisions"
SORT priority DESC, status ASC
```
