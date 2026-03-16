# Quang

## bai_tap_bai_doc_04

# Báo cáo Kiểm thử Hiệu năng với JMeter

---

## 1. Thông tin chung

- Website kiểm thử: t1.fan / t1a.gg
- Công cụ: Apache JMeter
- Môi trường: Java 1.8.0_401

---

## 2. Kịch bản kiểm thử (Thread Groups)

| Kịch bản | Số lượng Threads | Ramp-up | Thời gian/Lặp | Hành vi |
|--------|--------|--------|--------|--------|
| Basic_Test | 10 | 1s | 5 loops | Truy cập trang chủ |
| Load_Test | 50 | 30s | 1 loop | Truy cập trang chủ |
| Custom_Test | 20 | 1s | 60s | Truy cập Membership & Content |

---

## 3. Kết quả kiểm thử

- Tổng số mẫu (Samples): 120
- Thời gian phản hồi trung bình: 315 ms
- Thời gian phản hồi lâu nhất: 1323 ms
- Tỉ lệ lỗi: 0.00%
- Thông lượng: 3.5 requests/sec

---

## 4. Phân tích và kết luận

- Website hoạt động ổn định khi có nhiều người dùng truy cập.
- Thời gian phản hồi trung bình ở mức tốt.
- Không phát hiện lỗi trong quá trình kiểm thử.

---


