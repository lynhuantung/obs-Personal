---
dg-publish: true
dg-home: false
dg-show-local-graph: "false"
dg-home-link: "false"
dg-show-backlinks: "false"
dg-show-toc: "false"
dg-show-inline-title: "false"
dg-show-file-tree: "false"
dg-enable-search: "false"
dg-link-preview: "false"
dg-show-tags: "false"
dg-pass-frontmatter: "false"
---

[[Getting started|AllFeature]]


Một trang mà đồ thị cục bộ, tìm kiếm, liên kết ngược, cây tệp, liên kết trang chủ và bảng nội dung bị vô hiệu hóa.

Lý tưởng để sử dụng nếu bạn muốn có giải pháp chia sẻ ghi chú dễ dàng mà không cần tất cả các tính năng rườm rà.


> [!NOTE] Obsidian properties
> Sau khi giới thiệu các thuộc tính, Obsidian không đặt rõ ràng giá trị "false" cần thiết trên các thuộc tính hộp kiểm khi chúng không được chọn. Hiện tại, bạn sẽ cần sử dụng các thuộc tính dưới dạng kiểu văn bản khi muốn tắt cài đặt trên một ghi chú cụ thể. Các thuộc tính của ghi chú này trông như thế này:
> ![[Pasted image 20250125072456.png]]

Dưới đây là bảng giải thích ý nghĩa của từng property trong Obsidian Digital Garden:

| Property                 | Giá trị | Ý nghĩa ngắn gọn                                               |
| ------------------------ | ------- | -------------------------------------------------------------- |
| **dg-publish**           | `true`  | Ghi chú này sẽ được public lên web (Digital Garden).           |
| **dg-home**              | `false` | Không đặt ghi chú này làm trang chủ của Digital Garden.        |
| **dg-show-local-graph**  | `false` | Không hiển thị biểu đồ cục bộ (Local Graph) cho ghi chú này.   |
| **dg-home-link**         | `false` | Không hiển thị link về trang chủ từ ghi chú này.               |
| **dg-show-backlinks**    | `false` | Không hiển thị các liên kết ngược (backlinks) của ghi chú này. |
| **dg-show-toc**          | `false` | Không hiển thị mục lục (Table of Contents) cho ghi chú này.    |
| **dg-show-inline-title** | `false` | Không hiển thị tiêu đề của ghi chú ngay trong nội dung.        |
| **dg-show-file-tree**    | `false` | Không hiển thị cây thư mục của Digital Garden.                 |
| **dg-enable-search**     | `false` | Vô hiệu hóa chức năng tìm kiếm trong Digital Garden.           |
| **dg-link-preview**      | `false` | Không hiển thị preview của các liên kết khi di chuột vào.      |
| **dg-show-tags**         | `false` | Không hiển thị các tags của ghi chú này.                       |
| **dg-pass-frontmatter**  | `false` | Không truyền dữ liệu frontmatter (phần metadata) khi publish.  |

Bảng này giúp bạn dễ hình dung hơn về cách các property ảnh hưởng đến hiển thị của ghi chú trong Digital Garden. 🚀 Nếu muốn bật/tắt tính năng nào, chỉ cần thay đổi giá trị `true` hoặc `false` tương ứng.