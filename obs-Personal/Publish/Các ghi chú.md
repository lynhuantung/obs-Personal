---
dg-publish: true
dg-home: false
---
# Danh sách các ghi chú
```dataview
table replace(file.folder, "Publish/", "") as "Thư Mục"
from "Publish"
sort file.folder asc, file.name asc

```
