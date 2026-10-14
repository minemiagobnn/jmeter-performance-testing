# BÁO CÁO BÀI TẬP KIỂM THỬ HIỆU NĂNG VỚI APACHE JMETER

## 1. Thông tin bài tập
* **Công cụ sử dụng:** Apache JMeter.
* **Mục tiêu:** Kiểm tra tải và đánh giá hiệu năng của API với 10 người dùng ảo đồng thời.

---

## 2. Cấu hình kịch bản kiểm thử (Test Plan)
* **Number of Threads (Users):** 10
* **Ramp-up Period:** 5 giây
* **Loop Count:** 1

---

## 3. Kết quả thực hiện và Minh họa

### 3.1. Chi tiết các request (View Results Tree)
Các request gửi đi đều thành công (trạng thái màu xanh):

<img width="1917" height="1020" alt="view_results_tree" src="https://github.com/user-attachments/assets/c726489a-cc13-4868-9317-461f5edb7660" />


### 3.2. Thống kê tổng hợp (Aggregate Report)
Bảng tổng hợp các chỉ số hiệu năng thu được:

<img width="1917" height="1017" alt="aggregate_report" src="https://github.com/user-attachments/assets/6f0d41e0-110c-4247-b3c0-8a6ee6f06b40" />


---

## 4. Đánh giá và Kết luận
* **Tỷ lệ lỗi (Error %):** 0.00% (Hệ thống chạy ổn định, không có request nào bị lỗi).
* **Thời gian phản hồi trung bình (Average):** ~256 ms.
* **Lưu lượng xử lý (Throughput):** 2.2 requests/sec.
* **Kết luận chung:** Hệ thống đáp ứng tốt ở mức tải kiểm thử ban đầu, thời gian phản hồi nhanh và an toàn.
