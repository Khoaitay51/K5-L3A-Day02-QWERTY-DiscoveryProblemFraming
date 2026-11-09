# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: QWERTY
- Candidate problem nhóm chọn (1 câu): 
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | | | Assumption map, snapshot hoặc survey |
| CP4 — Research | | | Bảng research có link |
| CP5 — Quy trình trước/sau | | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | | | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | | | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenQuangTrung - 2A202603389

**Phần việc phụ trách:**
        - CP6 — Mức can thiệp AI và Problem Statement v1: phân tích mức độ phù hợp của AI đối với candidate problem #4, xây dựng phương án can thiệp, xác định phạm vi AI được phép thực hiện và hoàn thiện Problem Statement v1.

        - CP6 — Quyết định: tổng hợp các rủi ro, đánh giá mức độ sẵn sàng của giải pháp và đề xuất quyết định cuối cùng cho nhóm.
-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

        - Xây dựng phần mức can thiệp AI trong CP6, phân biệt phần việc có thể hỗ trợ bằng AI với những bước cần giữ sự kiểm tra và xác nhận của con người. Mục tiêu là tránh để AI tự suy đoán hoặc đưa ra kết luận sai về cấu trúc và quy ước của dự án.
        - Hoàn thiện Problem Statement v1 dựa trên Problem Statement v0 và các nội dung phân tích ở những checkpoint trước. Làm rõ người gặp vấn đề, bối cảnh nhận ticket, khó khăn khi lần theo luồng dữ liệu và tìm quy ước, đồng thời xác định phạm vi hỗ trợ của AI.
        - Tổng hợp và phân tích 4 nhóm rủi ro trước khi triển khai, xem xét các vấn đề như AI xác định sai file hoặc luồng dữ liệu, giải thích không chính xác, thiếu ngữ cảnh về quy ước dự án và việc thực tập sinh quá phụ thuộc vào kết quả AI.
        - Đề xuất quyết định Not Yet vì nhóm chưa có đủ bằng chứng kiểm chứng để khẳng định giải pháp thực sự cải thiện thời gian xử lý ticket mà vẫn đảm bảo độ chính xác. Cần bổ sung dữ liệu và đánh giá kết quả trước khi quyết định triển khai.
-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

        - group_report.md — phần CP6, bao gồm mức can thiệp AI, Problem Statement v1 và quyết định cuối cùng.
        - Các nguồn research và đường dẫn tham khảo được tổng hợp trong phần CP4 Research của báo cáo nhóm.
        - Phần AI Canvas, ma trận mức can thiệp AI và nội dung đánh giá rủi ro trong phần CP6 của báo cáo nhóm.
        - Problem Statement v1 và kết quả đánh giá Go / Not Yet / No-Go trong phần CP6.
        - Commit: 255f5be5465eec8f94b9e69128a68e080eaad808, 923566846136ab629a663e0bf400868d26bbae96, 924cf60753866a7a5c7bbb45c65801be1d81a475, 3d7ef49ee9ae7505949107e9b39be82d1a326cbf, cf73db6bddebcf42b39094b5930d7587f6325816, f64005b00cf8c9131c668c8cbba6f9f73001e586
-

**Điều mình học được từ phần nhóm:**
        - Qua quá trình thực hiện CP6, mình học được cách đánh giá một vấn đề dựa trên research, bằng chứng và tính khả thi thay vì chỉ dựa vào ý tưởng cá nhân. Mình cũng hiểu rằng AI chỉ nên hỗ trợ những công việc phù hợp, còn kết quả vẫn cần được con người kiểm tra và xác nhận. Đặc biệt, quyết định Not Yet giúp mình nhận ra rằng không nên vội triển khai một giải pháp khi chưa có đủ dữ liệu chứng minh hiệu quả và cách kiểm soát rủi ro.
-
