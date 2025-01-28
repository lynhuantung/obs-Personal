---
dg-publish: true
dg-home: false
dg-show-local-graph: "true"
dg-home-link: "true"
dg-show-backlinks: "true"
dg-show-toc: "true"
dg-show-inline-title: "true"
dg-show-file-tree: "true"
dg-enable-search: "true"
dg-link-preview: "true"
dg-show-tags: "true"
dg-pass-frontmatter: "true"
---

[[Simple-Page]]

---

# Các tính năng hỗ trợ trong Digital Garden

## Cài đặt ghi chú

Bạn có thể kích hoạt các tính năng sau trong **cài đặt ghi chú**:  
(Xem hướng dẫn tại: [note settings](https://dg-docs.ole.dev/getting-started/03-note-settings/))

- **Local Graph** (Biểu đồ liên kết cục bộ)
- **Global Graph** (Biểu đồ liên kết toàn cầu)
- **Backlinks** (Liên kết ngược)
- **Table Of Content** (Mục lục)
- **Filetree navigation** (Duyệt file theo cây thư mục)
- **Link preview** (Xem trước liên kết)
- **Search** (Tìm kiếm)
- **Frontmatter tags** (Thẻ frontmatter)

Ngoài ra, Digital Garden còn hỗ trợ nhiều định dạng nội dung khác nhau trong ghi chú.

---

## **Liên kết Wikilink**

Dùng cú pháp `[[Wikilink]]` để liên kết các ghi chú với nhau giống như trong Obsidian.

### **Liên kết tiêu đề**

Liên kết đến một tiêu đề cụ thể trong ghi chú:

```
[[Tên ghi chú#Tiêu đề ghi chú]]
```

### **Liên kết đến một đoạn cụ thể**

Liên kết đến một khối nội dung cụ thể trong ghi chú:

```
[[Tên ghi chú#^123abc]]
```

### **Thay đổi tên hiển thị của liên kết**

Có thể thay đổi nội dung hiển thị cho liên kết Wikilink giống như trong Obsidian.  
(Xem ví dụ hình: ![Hình ảnh](https://dg-docs.ole.dev/img/user/img/CleanShot%202023-01-10%20at%2018.07.56@2x.png))

---

## **Khối mã Code Blocks**

Bạn có thể chèn code vào ghi chú bằng cách sử dụng các khối mã:

```javascript
let a = 5;
```

(Xem ví dụ hình: ![Hình ảnh](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2015.34.59@2x.png))

---

## **Truy vấn Dataview**

```dataview
list from "Advanced"
```

Một số tài liệu tham khảo:

- [Adding custom components](https://dg-docs.ole.dev/advanced/adding-custom-components/)
- [CSS Customization](https://dg-docs.ole.dev/advanced/css-customization/)
- [Dataview queries](https://dg-docs.ole.dev/advanced/dataview-queries/)
- [Fine grained access token](https://dg-docs.ole.dev/advanced/fine-grained-access-token/)

(Xem thêm tại: [Dataview queries](https://dg-docs.ole.dev/advanced/dataview-queries/))

---

## **Callouts (Khối nhấn mạnh)**

Ví dụ về **Ghi chú**:

```
> [!NOTE] Tiêu đề ghi chú
> Đây là nội dung ghi chú.
```

📌 **Kết quả hiển thị:**

> [!NOTE] Tiêu đề ghi chú  
> Đây là nội dung ghi chú.

---

Ví dụ về **Cảnh báo**:

```
> [!WARNING] Một cảnh báo
> Đây là một thông báo cảnh báo.
```

📌 **Kết quả hiển thị:**

> [!WARNING] Một cảnh báo  
> Đây là một thông báo cảnh báo.

---

**Callout có thể thu gọn**:

```
> [!NOTE]+ Mở mặc định
> Callout có thể thu gọn/mở rộng.
```

📌 **Kết quả hiển thị:**

> [!NOTE]+ Mở mặc định  
> Callout có thể thu gọn/mở rộng.

---

## **Hỗ trợ công thức toán học (MathJax / LaTex)**

```
$\frac{1}{0} = \infty$
```

📌 **Hiển thị:**  
10=∞\frac{1}{0} = \infty

(Xem thêm hướng dẫn: [MathJax Reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference))

---

## **Thẻ (Tags)**

Nhấp vào thẻ bên dưới để xem các trang khác có cùng thẻ.

`#exampletag`

---

## **Hình ảnh nhúng / Transcluded Images**

📌 Ví dụ hình ảnh nhúng:  
![Hình ảnh](https://dg-docs.ole.dev/img/user/img/obsidianlogo.png)

---

## **Tài liệu nhúng (Transcluded documents)**

Có thể nhúng toàn bộ file hoặc chỉ một phần nội dung vào một ghi chú khác.

(Xem ví dụ hình: ![Hình ảnh](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.24.50@2x.png))

(Xem thêm về transclusion: [Content Customization#Tranclusions](https://dg-docs.ole.dev/advanced/content-customization/#tranclusions))

---

## **Hỗ trợ Excalidraw**

📌 **Lưu ý:** Hiện tại chưa hỗ trợ liên kết đến các ghi chú khác bên trong bản vẽ Excalidraw.

(Xem ví dụ hình: ![Hình ảnh](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.25.34@2x.png))

---

## **Sơ đồ Mermaid**

📌 Mermaid hỗ trợ tạo sơ đồ như **Gantt Chart**, **Flowchart**, **State Diagram**, v.v.

(Xem ví dụ hình: ![Hình ảnh](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.26.47@2x.png))

---

## **Sơ đồ PlantUML**

📌 Ví dụ sơ đồ UML:  
![UML Diagram](https://www.plantuml.com/plantuml/svg/jLHTRzem57tthxWAhnjBCsWx52AwJdkRLAsR-a1vkCGtmIAn8zk8TjF--wuXq9HHrZqiaHBhVfvphks9ysZzggx4PB_oobS4jwRmQxIyU7IUQdWBrqPxL9gi4wAYmeCtO5Mvy22LfTmheuLmIwKRj5Z3Jm7W5YZDMkaI2gmSiGMjDUlFNEbM_I0uYzaagS1LvR_HWx-gLAbhqXvo_f1bxzfYSwUaNq0IX-WQ7xwGSrXIMo4MluHOA4d0E2qP_zXG5qU0XhgiA4rtdBQK-f_GunmTPTa6x4VCbwKrAoslJMKiz0RlBwKSiYVWRMt5vWdHnagohJMXy-H3Y6pJBQl4U1dP4uw6XJCwJRyxiYzrZ2y7oSNyDHtZOKB3ysSDNYPwH_EhfgbKZc58_vEksBA4Q3mEFEzrwdXAexCuczviFBFqNR1a4UoLG0TXnRcCYESAqS7UkzVJ0yiif3ydsR9wakDcMwq3_4XARx1vZYNkLJYH5YJOgHuuiz3GKRfBVtzwkWhyRKuipScGm_wx7VslZJiduS-MEsSORnWKzAUzYpYyR_n2vKlDnt6SpFhPQQmmWYZDWw2ZDZtZQYuIfxDUsso7yaYRhuJIGM5D3QWbtoZAa-FRAn8Jqd9p-Mt_lm40)

---

## **Danh sách công việc (Checkboxes)**

```
- [ ] Chưa hoàn thành
- [x] Đã hoàn thành
```

📌 **Hiển thị:**

- [ ]  Chưa hoàn thành
- [x]  Đã hoàn thành

---

Bản dịch trên đã giữ nguyên các liên kết gốc và thuật ngữ quan trọng. Nếu cần thêm chỉnh sửa, hãy cho mình biết nhé! 😊