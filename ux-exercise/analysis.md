# 💰 Phân tích & Đề xuất Tính năng Quản lý Chi tiêu

---

## 📌 Path 1: Tự động phân tích chi tiêu
**Mô tả:**  
Hệ thống tự động dựa vào các giao dịch như *"Mua sắm, Ăn uống, Di chuyển"* để phân loại và đưa ra các gợi ý chi tiêu.

**Đánh giá:**  
✅ Đúng nếu sử dụng thanh toán từ MoMo  
⚠️ Có thể sai nếu dữ liệu đầu vào không rõ ràng

---

## 📌 Path 2: Truy vấn bằng ngôn ngữ tự nhiên
**Mô tả:**  
Người dùng có thể hỏi như:  
> "Tháng này tôi đã chi tiêu cho việc đi siêu thị là bao nhiêu?"

**Đánh giá:**  
⚠️ Không ổn định  
- AI có thể hiểu sai từ khóa  
- Phụ thuộc vào việc ghi chú giao dịch có rõ ràng hay không  

---

## 📌 Path 3: Thiết lập hạn mức chi tiêu
**Mô tả:**  
Cho phép người dùng đặt giới hạn chi tiêu và cảnh báo khi vượt mức.

**Đánh giá:**  
✅ Hữu ích  
- Giúp giữ kỷ luật tài chính  
- Phù hợp với người dễ chi tiêu quá tay  

---

## 📌 Path 4: Báo cáo hàng tháng
**Mô tả:**  
Cung cấp báo cáo chi tiêu theo tháng dưới dạng trực quan.

**Đánh giá:**  
✅ Rất tốt  
- Dễ hiểu  
- Giúp theo dõi xu hướng chi tiêu  

---

## 🔄 Sketch To-Be vs As-Is

### 🧩 As-Is (Hiện tại)
- Người dùng phải bấm vào từng giao dịch  
- Tự nhóm các khoản chi tiêu thủ công  

### 🚀 To-Be (Đề xuất)
- Thêm tính năng **Batch Edit** để chỉnh sửa hàng loạt  
- Ứng dụng AI để tự động phân loại & cập nhật thông tin giao dịch  

---

## 🧠 Gợi ý cải tiến thêm
- Thêm confidence score cho phân loại AI  
- Cho phép user "correct" để AI học dần (feedback loop)  
- Highlight các khoản chi bất thường (anomaly detection)  