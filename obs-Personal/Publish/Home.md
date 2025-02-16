---
dg-publish: true
dg-home: true
title:
---
# Liên kết
---
- [Node Link Mobile](https://m-nodelink.netlify.app/)
- [[MOC]]
- [[0 - Books|Sách]]


# 🚀 Getting Started
---

Digital Garden là cách bạn tổ chức và chia sẻ kiến thức một cách tự nhiên, liên kết các ý tưởng lại với nhau để tạo thành một hệ sinh thái thông tin phong phú. Nếu bạn mới bắt đầu, đây là hướng dẫn để giúp bạn thiết lập và sử dụng Digital Garden một cách hiệu quả! 🌱

## 🔹 1. Digital Garden là gì?

Digital Garden là một mô hình ghi chú mở rộng, nơi bạn không chỉ ghi chép mà còn xây dựng một hệ thống liên kết giữa các ý tưởng. Khác với blog truyền thống, Digital Garden không cần sự hoàn hảo – bạn có thể cập nhật, mở rộng, và phát triển các ghi chú theo thời gian.

🔹 **Lợi ích của Digital Garden**:

- Kết nối ghi chú một cách linh hoạt, giúp bạn khám phá mối liên hệ giữa các ý tưởng.
- Không cần bài viết hoàn hảo ngay từ đầu – bạn có thể cải thiện ghi chú dần dần.
- Dễ dàng tìm kiếm và tái sử dụng kiến thức đã có.

## 🔹 2. Cách sử dụng

Để bắt đầu với Digital Garden trong Obsidian, bạn cần:

✅ **Cài đặt Plugin Digital Garden**: Vào `Settings > Community Plugins` và tìm **Digital Garden**. ✅ **Cấu hình cơ bản**: Trong phần `Digital Garden Settings`, hãy đảm bảo bạn đã đặt URL và các tùy chỉnh phù hợp. ✅ **Viết ghi chú và đặt liên kết**: Sử dụng cú pháp `[Tên ghi chú](Tên file.md)` để liên kết giữa các ghi chú. ✅ **Publish ghi chú**: Chỉ cần thêm `dg-publish: true` vào metadata của tệp để xuất bản nó lên web.

## 🔹 3. Tạo ghi chú đầu tiên

Bắt đầu bằng cách tạo một tệp mới trong Obsidian:

```yaml
---
dg-publish: true
dg-home: false
dg-show-toc: true
---
```

Viết nội dung của bạn như bình thường và lưu lại. Khi muốn xuất bản, hãy vào `Command Palette` và chọn `Digital Garden: Publish Notes`.

## 🔹 4. Liên kết và mạng lưới ghi chú

Digital Garden hoạt động tốt nhất khi bạn liên kết ghi chú với nhau. Một số cách để làm điều này:

- Sử dụng `[[Tên ghi chú]]` để liên kết nội bộ giữa các ghi chú trong Obsidian.
- Dùng **Graph View** (`Ctrl+G`) để xem mạng lưới ghi chú của bạn.
![[Pasted image 20250201083611.png]]
- Gắn tag hoặc danh mục để tổ chức nội dung tốt hơn (`#concept #project`).

## 🔹 5. Cấu hình hiển thị Digital Garden

Bạn có thể tùy chỉnh cách hiển thị ghi chú trên Digital Garden bằng cách sử dụng các property như:

|Property|Mô tả|
|---|---|
|`dg-home: true`|Đặt ghi chú này làm trang chủ.|
|`dg-show-toc: true`|Hiển thị mục lục tự động.|
|`dg-enable-search: true`|Cho phép tìm kiếm trong Digital Garden.|
|`dg-show-tags: true`|Hiển thị các tag của ghi chú.|

Sau khi tùy chỉnh, bạn có thể cập nhật Digital Garden bằng cách chạy `Publish Notes`.
