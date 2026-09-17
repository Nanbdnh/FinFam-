# FinFam

## Mô tả
FinFam là ứng dụng quản lý chi tiêu gia đình, giúp các thành viên trong gia đình ghi chép lại các chi phí sinh hoạt như tiền điện, tiền nước, ăn uống, mua sắm, giáo dục,.. Ứng dụng tổng kết lịch sử chi tiêu theo tháng, so sánh mức chi tiêu hàng tháng và lập biểu đồ để gia đình biết tháng này mình chủ yêu tiêu vào việc gì 

## Vì sao chọn stack này

- **Frontend: React + Vite** — vì app có nhiều màn hình tương tác (nhập chi phí, xem lịch sử, xem số dư từng người), React giúp quản lý trạng thái giao diện dễ dàng hơn HTML/JS thuần. Vite được chọn thay vì Create React App vì tốc độ khởi động và build nhanh hơn nhiều).
- **Backend: Node.js + Express** — vì cú pháp gần giống JavaScript ở Frontend, giúp không phải học thêm ngôn ngữ mới, và có thể viết CRUD API nhanh mà vẫn tự tay kiểm soát logic (khác với dùng backend dựng sẵn như Supabase).
- **Database: PostgreSQL** — vì dữ liệu của app có quan hệ rõ ràng giữacác bảng (thành viên, khoản chi, ai chi cho ai), phù hợp với cơ sở dữ liệu quan hệ hơn là NoSQL. Postgres cũng miễn phí và dễ deploy trên Render.

## Cách chạy local


## Deploy
