# Hồ Sơ Đồ Án Hệ Thống Quản Lý Thư Viện Trường
## Phần 1: Phân tích lỗi
1. **Lỗi Auto TOC hiển thị rỗng:** Các tiêu đề đang dùng định dạng thủ công trên nền `Normal` thay vì `Heading Styles`. Word chỉ quét mục lục tự động qua hệ thống `Heading 1, 2, 3`.
2. **Nhầm cấp Heading ('2.1.1. Tiểu ban Kỹ thuật'):** Gán nhầm từ `Heading 3` thành `Heading 2` làm sai lệch độ thụt đầu dòng, phá vỡ cấu trúc phân cấp logic của tài liệu.
## Phần 2: Sửa lỗi & Nghiệm thu
3. **Các bước sửa Heading:**
   * **Heading 1** (Tên chương): Nhấn `Ctrl + Alt + 1`
   * **Heading 2** (Mục con): Nhấn `Ctrl + Alt + 2`
   * **Heading 3** (Chi tiết nhỏ): Nhấn `Ctrl + Alt + 3`
   * Vào **References** > **Table of Contents** để tạo lại mục lục.
4. **Cập nhật số trang (Bẫy dữ liệu):** Khi nội dung thay đổi số trang, mục lục cũ không tự cập nhật.
   * **Khắc phục:** Click vào bảng mục lục > Chọn **Update Table** (hoặc nhấn **`F9`**) > Chọn **Update entire table** > Bấm `OK`
## Thông tin nộp bài
* **Tên Repository:** `B26DTCN097_IT108_Session11_Bai7` (Public trên GitHub)
