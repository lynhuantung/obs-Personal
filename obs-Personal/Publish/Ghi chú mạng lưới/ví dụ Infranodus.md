---
dg-publish: true
dg-home: false
---
Sử dụng một tình huống đơn giản và quen thuộc: phân tích một bài viết ngắn về "Thói quen buổi sáng". Tôi sẽ trình bày từng bước để bạn thấy rõ cách công cụ này trích xuất từ khóa, xây dựng mạng lưới, tìm lỗ hổng và gợi ý mở rộng.

---

### Ví dụ: Phân tích "Thói quen buổi sáng" với InfraNodus

#### **Văn bản mẫu**
"Mỗi sáng, tôi thường dậy sớm để tập thể dục và uống một cốc nước chanh. Tập thể dục giúp tôi cảm thấy tràn đầy năng lượng cho cả ngày. Nước chanh hỗ trợ tiêu hóa và cung cấp vitamin C. Sau đó, tôi ăn sáng nhẹ với bánh mì và đọc sách để bắt đầu ngày mới một cách tích cực."

#### **Bước 1: Trích xuất từ khóa**
InfraNodus quét văn bản và chọn ra các từ khóa quan trọng (từ khóa sẽ [[Đưa về từ gốc]]) dựa trên tần suất và ý nghĩa:
- Dậy sớm , Tập thể dục, Nước chanh, Năng lượng, Tiêu hóa, Vitamin C, Ăn sáng, Bánh mì,  Đọc sách, Tích cực

#### **Bước 2: Xây dựng mạng lưới từ khóa**
InfraNodus tạo đồ thị dựa trên sự đồng xuất hiện của các từ khóa trong văn bản:
- **"Dậy sớm"** nối với **"tập thể dục"** và **"nước chanh"** (thói quen buổi sáng).
- **"Tập thể dục"** liên kết với **"năng lượng"** (vì nó mang lại năng lượng).
- **"Nước chanh"** nối với **"tiêu hóa"** và **"vitamin C"** (lợi ích của nước chanh).
- **"Ăn sáng"** liên kết với **"bánh mì"** (món ăn cụ thể).
- **"Đọc sách"** nối với **"tích cực"** (cách bắt đầu ngày mới).

**Hình dung đồ thị**:  
![[Pasted image 20250316083434.png]]
- "Dậy sớm" là trung tâm, kết nối với các hoạt động chính: "tập thể dục", "nước chanh", "ăn sáng", "đọc sách".  
- Các từ khóa phụ như "năng lượng", "tiêu hóa", "vitamin C" là nhánh phụ, giải thích lợi ích.

#### **Bước 3: Phân tích và tìm lỗ hổng thông tin**
InfraNodus kiểm tra mạng lưới để tìm các khu vực thiếu kết nối hoặc chưa được khai thác:
- **Nút cô lập**: "Bánh mì" chỉ nối với "ăn sáng" mà không có thêm lợi ích hay chi tiết nào (ví dụ: dinh dưỡng của bánh mì).  
- **Khoảng cách giữa cụm**: "Tập thể dục" và "nước chanh" đều là thói quen tốt nhưng không có liên kết trực tiếp với nhau trong văn bản (ví dụ: nước chanh có thể hỗ trợ tập thể dục không?).  
- **Từ khóa thiếu**: Văn bản chưa đề cập đến các thói quen phổ biến khác như "thiền" hoặc "cà phê" – những thứ thường xuất hiện trong chủ đề buổi sáng.

**Kết luận lỗ hổng**:  
- Thiếu thông tin về lợi ích cụ thể của "bánh mì" (ví dụ: năng lượng từ tinh bột).  
- Chưa kết nối "nước chanh" với "tập thể dục" (ví dụ: hydrat hóa cơ thể).  
- Thiếu các thói quen khác như "thiền" để tăng sự tích cực.

#### **Bước 4: Gợi ý mở rộng nội dung**
InfraNodus đề xuất các ý tưởng để làm nội dung phong phú hơn:
- **Thêm lợi ích của bánh mì**: "Bánh mì cung cấp tinh bột, duy trì năng lượng lâu dài."  
- **Kết nối nước chanh và tập thể dục**: "Nước chanh giúp bù nước sau khi tập thể dục."  
- **Bổ sung thói quen mới**:  
  - "Thiền 5 phút để tăng sự tập trung và tích cực."  
  - "Uống cà phê để kích thích tỉnh táo."  
- **Mở rộng chủ đề**: Thêm "lập kế hoạch ngày mới" như một thói quen hữu ích.

#### **Kết quả cuối cùng**
Sau khi áp dụng gợi ý, văn bản mở rộng có thể là:  

"Việc **dậy sớm** mang lại nhiều lợi ích tích cực, giúp bắt đầu ngày mới một cách chủ động và hiệu quả. Khi thức dậy sớm, bạn có thể **tập thể dục** để rèn luyện sức khỏe, kết hợp **uống nước chanh** giúp thanh lọc cơ thể. Sau đó, một bữa **ăn sáng** đầy đủ dinh dưỡng sẽ giúp duy trì năng lượng suốt cả ngày.

Ngoài ra, buổi sáng là thời điểm lý tưởng để **đọc sách**, giúp nâng cao kiến thức và phát triển tư duy. Việc thực hành **thiền** sẽ giúp tâm trí thư thái hơn, từ đó cải thiện khả năng **tập trung** và duy trì trạng thái **tích cực**. Những thói quen này không chỉ giúp bạn làm việc hiệu quả hơn mà còn góp phần tạo nên một lối sống lành mạnh và cân bằng.

Bên cạnh đó, thực phẩm như **bánh mì** cũng đóng vai trò quan trọng trong việc cung cấp **năng lượng** cần thiết cho cơ thể. Chọn những thực phẩm phù hợp sẽ giúp bạn duy trì sức bền và tinh thần sảng khoái trong cả ngày."

**Đồ thị mới**:  
![[Pasted image 20250316084207.png]]
- "Dậy sớm" nối với "tập thể dục", "nước chanh", "thiền", "ăn sáng", "đọc sách".  
- "Nước chanh" liên kết thêm với "tập thể dục" (bù nước).  
- "Bánh mì" nối với "năng lượng".  
- "Thiền" liên kết với "tích cực" và "tập trung".

#### **Kết quả trước và sau khi tái tạo văn bản**
---
![[Pasted image 20250316085451.png]]
Nhận xét về sự khác biệt giữa **trước** và **sau** như sau:
##### **Trước**

- Mô hình ban đầu có một số cụm ý tưởng tách biệt, chưa có sự kết nối rõ ràng.
- **Dậy sớm** liên kết với **tập thể dục**, từ đó dẫn đến **năng lượng**.
- **Nước chanh** có hai nhánh: **tiêu hóa** và **vitamin C**.
- **Bánh mì** chỉ kết nối với **ăn sáng**, không liên quan đến các yếu tố khác.
- **Đọc sách** đứng riêng lẻ, chỉ kết nối với **tích cực** mà không có sự liên kết với **dậy sớm**.

##### **Sau**

- Mạng lưới sau khi chỉnh sửa có tính liên kết chặt chẽ hơn, giúp tạo mối quan hệ logic giữa các yếu tố.
- **Dậy sớm** trở thành trung tâm, kết nối với nhiều yếu tố hơn: **đọc sách, ăn sáng, tập thể dục, nước chanh**.
- **Thiền** xuất hiện và tạo mối liên kết với **tập trung** và **tích cực**, giúp hệ thống hóa lợi ích của việc rèn luyện tinh thần.
- **Bánh mì** được gắn với **năng lượng**, giúp thể hiện rõ ràng vai trò của nó trong chuỗi hoạt động buổi sáng.
- **Nước chanh** không còn liên kết với **tiêu hóa** và **vitamin C**, mà thay vào đó, kết nối trực tiếp với **dậy sớm**, nhấn mạnh vai trò của nó trong việc khởi đầu ngày mới.

##### **Nhận xét tổng quan**

- **Mô hình sau hợp lý hơn**, thể hiện rõ **mối quan hệ nhân - quả** giữa các thói quen buổi sáng.
- **Trước**: Các yếu tố có vẻ rời rạc, chưa có sự kết nối mạnh mẽ.
- **Sau**: Mạng lưới trở nên chặt chẽ hơn, các yếu tố có mối liên hệ rõ ràng hơn, giúp người đọc dễ dàng hiểu được mối quan hệ giữa chúng.


---
InfraNodus giúp bạn thấy rõ cách các ý tưởng liên kết với nhau và bổ sung những gì còn thiếu để câu chuyện trở nên trọn vẹn hơn. Xem thêm ví dụ [[1.Quả Táo]]

