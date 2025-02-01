---
dg-publish: true
dg-home: false
---
# Các ghi chú
---

## Danh sách các ghi chú
```dataview
table without id replace(file.folder, "Publish/", "") as "Thư Mục", file.name as "Tên File"
from "Publish"
sort file.folder asc, file.name asc

```
