# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: QWERTY
- Candidate problem nhóm chọn (1 câu): #4 — Thực tập sinh mới mất nhiều thời gian lần theo luồng dữ liệu và tìm quy ước của nhóm khi nhận ticket sửa tính năng có sẵn.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Phạm Trường Chinh | 2A202603426 | Quy trình trước/sau + Problem Statement v0 (CP5) | *(bổ sung)* |
| 2 | Hoàng Bảo Nguyên | 2A202603384 | Hội tụ nhóm: pitch, cluster, cây OST, bảng chấm điểm (CP3) | Stormaka |
| 3 | Nguyễn Quang Trung | 2A202603389 | Mức can thiệp AI + Problem Statement v1 + quyết định (CP6) | *(bổ sung)* |
| 4 | Nguyễn Tiến Hưng | 2A202603365 | Kiểm chứng: phỏng vấn/survey + assumption map (CP4) | *(bổ sung)* |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

> Phân công chốt ngày 09/11/2026. Dòng "CP4 — Research" giao Quang Trung để chạy song song với phần phỏng vấn của Tiến Hưng (phỏng vấn không được dùng AI, research được dùng AI) và làm input trực tiếp cho CP6 của Trung; nhóm có thể chỉnh khi họp.

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Hoàng Bảo Nguyên | Cả nhóm (mỗi người pitch top 3 + phản biện) | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Nguyễn Tiến Hưng | Hoàng Bảo Nguyên, Phạm Trường Chinh | Assumption map, snapshot hoặc survey |
| CP4 — Research | Nguyễn Quang Trung | Nguyễn Tiến Hưng | Bảng research có link |
| CP5 — Quy trình trước/sau | Phạm Trường Chinh | Hoàng Bảo Nguyên | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Phạm Trường Chinh | Cả nhóm | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Quang Trung | Cả nhóm | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Nguyễn Quang Trung | Cả nhóm | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### HoVaTen-MSSV

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-

### PhamTruongChinh-2A202603426

**Phần việc phụ trách**

- Phụ trách CP5, gồm quy trình trước/sau, bảng so sánh và Problem Statement v0.
- Hỗ trợ Nguyễn Tiến Hưng ở CP4 bằng dữ liệu ban đầu từ Problem Card để đối chiếu các giả định kiểm chứng.

**Đóng góp cụ thể**

- Vẽ quy trình hiện tại khi Intern nhận ticket sửa tính năng có sẵn. Ghi actor, đầu vào, đầu ra và thời gian từng bước. Chỉ ra hai điểm nghẽn là lần theo luồng qua 10–15 file (35 phút) và tìm quy ước của nhóm (15 phút).
- Đề xuất quy trình sau can thiệp. Intern đối chiếu trên IDE và ghi phiếu xác nhận 4 dòng để Mentor duyệt. Khi bản tóm tắt AI sai, Intern quay về cây phụ thuộc và phiếu xác nhận thủ công. Lập bảng so sánh trước/sau.
- Soạn Problem Statement v0 với mốc ban đầu 75 phút/task, mục tiêu dưới 20 phút/task, cách đo và phạm vi AI được phép hỗ trợ.
- Cung cấp trải nghiệm thực tập làm cơ sở đặt giả định CP4 về thời gian lần theo luồng, vị trí nghẽn và tần suất hỏi Mentor.

**Bằng chứng**

- CP5 nằm ở mục 4–5 của [báo cáo nhóm](report/team/group_report.md), commit `5b10b07`.
- Nguồn cho các giả định CP4 nằm ở Problem Card #1 trong [báo cáo cá nhân](report/individual/2A0202603426_PhamTruongChinh.md).

**Điều mình học được từ phần nhóm**

- Khi vẽ quy trình ở CP5, mình thấy câu “mất nhiều thời gian đọc code” quá chung. Tách thời gian theo từng bước giúp mình chỉ ra hai chỗ cần cải thiện trước là lần theo các file liên quan và tìm quy ước của nhóm.
- Khi đặt mục tiêu dưới 20 phút mỗi ticket, mình nhận ra làm nhanh chỉ có ý nghĩa nếu Intern vẫn xác định đúng các file, hàm và bảng cần sửa. Vì vậy mình giữ bước đối chiếu trên IDE và để Mentor duyệt phiếu xác nhận trước khi sửa code.
- Khi dùng Problem Card của mình để hỗ trợ CP4, mình học được cách phân biệt số liệu từ trải nghiệm cá nhân với bằng chứng cho cả nhóm người dùng. Mốc 75 phút mỗi ticket giúp mình đặt câu hỏi kiểm chứng cụ thể hơn.
