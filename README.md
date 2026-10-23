# Demo · Danh sách báo giá — Thiết bị mầm non Việt Mỹ

Bản đề xuất trang `/danh-sach-bao-gia/` của site đang dựng (website-demo-02.thcmedia.vn), theo 7 dòng feedback 201–207
tab "Review tổng thể website" (đọc 23/10/2026):

- 201 form gọn 2 cột, lọt 1 màn hình 1440×900 (695px, trước 1.002px) · bỏ H2 "Thông tin nhận báo giá"
- 202 mô tả dưới H1: 1 mốc 15–30 phút + giờ làm việc (nháp, chờ SEO duyệt)
- 203 SP giá liên hệ hết "0đ": dòng "Giá: Liên hệ", ô tổng tách nhóm có giá / giá liên hệ / chưa chọn mẫu, email "Đơn giá: Liên hệ"
- 204 lưu mẫu mã + số lượng, đổi mẫu ngay trong dòng, "+ Thêm mẫu khác"
- 205 bỏ trần 3 SP (trần kỹ thuật 100 dòng, báo bằng toast của site)
- 206 nút gửi luôn bấm được, lỗi hiện tại chỗ, ô đồng ý 20px tick đỏ, chặn gửi khi danh sách trống
- 207 label `for`/`id`, ô ghi chú có `name` + `aria-label`, chữ 14px

Bảng demo (góc dưới trái): đổi kịch bản danh sách, bật/tắt khung đánh dấu (số = dòng sheet), xem ghi chú DEV + nội dung email.
Form **không gửi đi đâu** (đã gỡ Contact Form 7). File dựng bằng `build.py` (thư mục nguyên liệu, không nằm trong repo).
