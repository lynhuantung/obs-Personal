---
dg-publish: true
dg-home: false
---
# Danh sách các ghi chú
```dataview
table without id replace(file.folder, "Publish/", "") as "Thư Mục", file.name as "Tên File"
from "Publish"
sort file.folder asc, file.name asc

```
