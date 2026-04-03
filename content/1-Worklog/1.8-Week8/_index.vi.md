---
title: "Worklog Tuần 8"
date: 2026-03-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8

- Deploy FE lên S3 và CloudFront.

### Các công việc cần triển khai trong tuần này

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|-----|-----------|--------------|-----------------|----------------|
| 1 | - Chuẩn bị build config FE và biến môi trường.<br>- Kiểm tra build output tại môi trường local. | 02/03/2026 | 02/03/2026 | Tài liệu nội bộ |
| 2 | - Tạo S3 bucket và upload artifact.<br>- Cấu hình cache và metadata đúng. | 03/03/2026 | 03/03/2026 | Tài liệu AWS |
| 3 | - Cấu hình CloudFront distribution và HTTPS.<br>- Thiết lập cache behaviors và invalidation. | 04/03/2026 | 05/03/2026 | Tài liệu AWS |
| 4 | - Smoke test sau deploy.<br>- Fix lỗi routing/CORS nếu có. | 05/03/2026 | 06/03/2026 | Tài liệu nội bộ |

### Kết quả đạt được tuần 8

- Pipeline build FE ổn định.
- FE được deploy lên S3 và CloudFront.
- Cấu hình HTTPS và caching cho production.
- Xử lý các lỗi sau deploy.
