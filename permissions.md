---
description: Permission Set
---

# Permissions

### 

### Permission Groups

| Can | User | Authenticated | Editors | Staff |
| :--- | :--- | :--- | :--- | :--- |
| View | x | x | x | x |
| Clap |  | x | x | x |
| Comment |  | x | x | x |
| Create |  |  | x | x |
| Revise |  |  | x | x |
| Apply Rev |  |  | x | x |
| Delete |  |  |  | x |
| Admin Panel |  |  |  | X |

## Flows \(Current\)

1. Created \(Editors\)
2. Applied \(Editors\)
3. Revised \(Editors\)

## Future: Flow \(Create\)

1. Suggested \(Authenticated, Editors\)
2. Approve \(Editor\)

Requires: "Submission Status", "Approval Backlog", "Suggestion UI"

## Future: Flow \(Revise\)

1. Revision \(Authenticated: 1 Pending Max, Editors: No Limit\)
2. Approve \(Editors\)

