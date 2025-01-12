---
dg-publish: true
dg-home: true
---
# Getting started
---

## 01 Bắt đầu

- [[Các ghi chú|Danh sách các ghi chú]] 

Việc thiết lập ban đầu chỉ mất vài phút, nhưng sau khi hoàn tất, bạn sẽ có một "digital garden" (vườn kỹ thuật số) mà bạn hoàn toàn kiểm soát và có thể tùy chỉnh theo ý muốn. Đây là điều làm cho digital garden trở nên thú vị.

1. Tải xuống và cài đặt plugin cộng đồng [Digital Garden](obsidian://show-plugin?id=digitalgarden) trong Obsidian.

---

2. Tiếp theo, bạn cần một tài khoản GitHub. Nếu chưa có, tạo tài khoản [tại đây](https://github.com/signup).

---

3. Bạn cũng cần một tài khoản Vercel. Đăng ký bằng tài khoản GitHub [tại đây](https://vercel.com/signup).

---

4. Mở [repo này](https://github.com/oleeskild/digitalgarden), và nhấn vào nút màu xanh "Deploy to Vercel".

![CleanShot 2023-01-22 at 23.38.57@2x.png](https://dg-docs.ole.dev/img/user/img/CleanShot%202023-01-22%20at%2023.38.57@2x.png)  
Điều này sẽ mở Vercel và tạo một bản sao của repository này trong tài khoản GitHub của bạn. Đặt một tên phù hợp, chẳng hạn như 'my-digital-garden'. Thực hiện theo các bước trong Vercel để xuất bản trang web của bạn lên internet.

---

5. Tiếp theo, bạn cần tạo một mã truy cập (access token) cho tài khoản GitHub của mình. Mã này giống như mật khẩu để plugin có thể thêm các ghi chú mới vào repository GitHub của bạn. Truy cập [trang này](https://github.com/settings/tokens/new?scopes=repo) trong khi đã đăng nhập vào GitHub. Các cài đặt đúng đã được áp dụng sẵn. (Nếu bạn không muốn tạo mã này lại mỗi vài tháng, chọn tùy chọn "No expiration"). Nhấn vào nút "Generate token", và sao chép mã xuất hiện ở trang tiếp theo.

**Lựa chọn bảo mật hơn**

GitHub gần đây đã giới thiệu một tính năng beta mới, cho phép bạn giới hạn mã truy cập chỉ đến các repository cụ thể. Đây là cách an toàn nhất để sử dụng plugin. Xem chi tiết tại [Fine grained access token](https://dg-docs.ole.dev/advanced/fine-grained-access-token/).

---

6. Mở Obsidian, vào phần cài đặt "Digital Garden", và điền tên người dùng GitHub, tên của repository chứa ghi chú mà bạn đã tạo ở bước 3, và cuối cùng dán mã truy cập của bạn vào.

![CleanShot 2023-10-12 at 17.06.27@2x.png](https://dg-docs.ole.dev/img/user/CleanShot%202023-10-12%20at%2017.06.27@2x.png)

---

7. Bây giờ, hãy xuất bản ghi chú đầu tiên của bạn! Tạo một ghi chú mới trong Obsidian. Sau đó thêm hai thuộc tính mới vào ghi chú.

**Cách thêm thuộc tính vào ghi chú**

- Một hộp kiểm tên `dg-publish`.
- Một hộp kiểm tên `dg-home`.  
  Chuyển cả hai hộp kiểm sang trạng thái "đã chọn".  
  Nó sẽ trông giống như sau:  
  ![CleanShot 2023-10-12 at 16.59.10@2x.png](https://dg-docs.ole.dev/img/user/CleanShot%202023-10-12%20at%2016.59.10@2x.png)

**Điều này có hai tác dụng:**

- Cài đặt `dg-home` cho plugin biết rằng đây là trang chủ hoặc trang vào "digital garden" của bạn. (Chỉ cần thêm thuộc tính này vào một ghi chú duy nhất, không cần thêm vào tất cả các ghi chú bạn xuất bản).

- Cài đặt `dg-publish` cho plugin biết rằng ghi chú này cần được xuất bản lên "digital garden" của bạn. Các ghi chú không có thuộc tính này sẽ không được xuất bản. (Nói cách khác: Mỗi ghi chú bạn muốn xuất bản đều cần thuộc tính này).

---

8. Mở bảng lệnh (Command Palette) bằng cách nhấn CTRL+P trên Windows/Linux (CMD+P trên Mac) và tìm lệnh "Digital Garden: Publish Single Note". Nhấn Enter.

---

9. Truy cập URL trang web của bạn, bạn có thể tìm thấy URL này trên [Vercel](https://vercel.com/dashboard). Nếu chưa thấy gì, đợi một chút và làm mới trang. Ghi chú của bạn sẽ xuất hiện.

---

**Chúc mừng!** Bạn đã có một phần internet cá nhân của riêng mình dưới dạng "digital garden", hoàn toàn miễn phí 🎉.

Giờ đây, bạn có thể bắt đầu thêm liên kết như thông thường trong Obsidian, với dấu ngoặc vuông kép, vào ghi chú bạn vừa xuất bản.

Nhớ rằng bạn cũng cần xuất bản các ghi chú mà bạn đang liên kết đến vì việc này sẽ không được thực hiện tự động. Đây là thiết kế có chủ đích. Bạn luôn kiểm soát ghi chú nào bạn muốn xuất bản. Nếu bạn không xuất bản ghi chú được liên kết, liên kết đó sẽ dẫn đến một trang thông báo rằng ghi chú này không tồn tại.

Nếu bạn muốn gỡ bỏ ghi chú khỏi "digital garden" mà không xóa nó khỏi vault, chỉ cần bỏ chọn hoặc xóa thuộc tính `dg-publish` trong ghi chú, mở [publication center](https://dg-docs.ole.dev/getting-started/02-commands/#open-publication-center), và nhấn nút "Delete notes from garden".

Khi bạn đã sẵn sàng, bạn có thể xem các [lệnh có sẵn](https://dg-docs.ole.dev/getting-started/02-commands/) hoặc các [cài đặt ghi chú](https://dg-docs.ole.dev/getting-started/03-note-settings/). Hoặc bạn có thể muốn [thay đổi giao diện](https://dg-docs.ole.dev/getting-started/04-appearance-settings/).
