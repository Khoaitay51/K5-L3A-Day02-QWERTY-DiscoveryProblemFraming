# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: QWERTY
- Thành viên: Hoàng Bảo Nguyên
- Candidate problem được chọn (1 câu): *(chốt trong buổi CP3)*
- Quyết định cuối: Go / Not Yet / No-Go *(chốt sau CP6)*

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Hoàng Bảo Nguyên | Gom đủ đề cương, slide, bài tập ôn thi ĐSTT vào một nơi duy nhất | Sinh viên tự ôn thi | Lục nhóm Zalo ~10'/lần, trong quy trình 7 bước ~50' | |
| 2 | Hoàng Bảo Nguyên | Tổng hợp 4 loại nguồn thành một bộ ôn tập | Sinh viên trước kỳ thi | Xếp công thức/dạng bài ~30–60', trong 60–120'/lần | |
| 3 | Hoàng Bảo Nguyên | Tự học và làm bài tập ngay sau buổi học | Sinh viên sau buổi học | Mò phần chưa hiểu ~30–45', trong 60–90'/buổi | |
| 4 | Phạm Trường Chính | Hiểu luồng dữ liệu + quy tắc ngầm khi hòa nhập codebase | Intern Dev (kèm Mentor bị ngắt quãng) | Dò 10–15 file theo luồng: 50'/task (tổng 75'/task) | |
| 5 | Phạm Trường Chính | So sánh 2–3 thư viện theo đúng kiến trúc dự án | Intern Dev làm research | Đọc blog lan man + lọc sai tiêu chí: 135'/lần (tổng 210') | |
| 6 | Phạm Trường Chính | Biết việc nào đang chặn đồng đội khi 3 đầu việc cùng lúc | Intern Dev đa nhiệm | Không thấy được việc nào chặn ai; 2–3 ngày/tuần bị phân tán | |
| 7 | Nguyễn Quang Trung | Ghi biên bản họp: quyết định + phân công | Người tham dự/thư ký họp | Lọc ý + soạn biên bản 15–30'/họp *(ước tính, cần xác minh)* | |
| 8 | Nguyễn Quang Trung | Nắm nội dung chính của tài liệu dài | Người đọc tài liệu | Đọc + tự lọc ý chính 1–3 giờ/tài liệu *(ước tính, cần xác minh)* | |
| 9 | Nguyễn Quang Trung | Trả lời nhanh câu hỏi khách hàng lặp lại | Nhân viên CSKH | 50–100 câu/ngày *(giả thuyết, chưa có bằng chứng)* | |
| 10 | Nguyễn Tiến Hưng | Biết phải nộp gì, nộp ở đâu khi bắt đầu lab | Học viên K5 | Đối chiếu RUBRIC ↔ SUBMISSION ↔ template ~10', trong ~25'/lab | |
| 11 | Nguyễn Tiến Hưng | Soát báo cáo còn thiếu mục nào trước deadline | Học viên trước giờ nộp | Dò từng field bằng tay ~8', trong ~15'/lần | |
| 12 | Nguyễn Tiến Hưng | Xem được mọi deadline/thông báo ở một chỗ | Học viên, cả lớp | ~5 câu hỏi lặp/tuần trong group lớp *(ước lượng)* | |


### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Thông tin cần dùng nằm rải rác nhiều nơi | #1, #4, #10 | Phải tự lục/gom từ nhiều nguồn rời rạc mới bắt đầu làm được việc |
| B — Đọc nhiều nguồn rồi tự tổng hợp có cấu trúc | #2, #3, #5, #8 | Phải đọc nhiều nguồn và tự xếp thành sản phẩm (bộ ôn, bảng so sánh, tóm tắt) |
| C — Ghi chép, tổng hợp lại sau sự kiện | #7 | Sau họp phải tự nhớ, lọc và viết lại đủ ý |
| D — Tự soát theo checklist trước khi nộp | #11 | Dò tay từng mục/field để không bị trừ điểm |
| E — Cùng thông tin bị hỏi/đáp lại nhiều lần | #9, #12 | Không có chỗ tra chung nên lặp lại hỏi–đáp |
| F — Xếp ưu tiên việc đang chặn người khác | #6 | Quá tải, không thấy việc mình làm đang chặn ai |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian mỗi thành viên dành để gom và tổng hợp thông tin rải rác trong học/làm việc hằng tuần, mà vẫn nắm đúng và đủ ý chính.
├── Opportunity A: Thông tin cần dùng nằm rải rác nhiều nơi, không có một chỗ chung để tìm
├── Opportunity B: Phải đọc nhiều nguồn rồi tự xếp lại thành sản phẩm có cấu trúc
├── Opportunity C: Sau mỗi buổi họp phải tự ngồi nhớ và viết lại đủ ý
├── Opportunity D: Trước khi nộp phải tự dò từng mục theo checklist chấm
├── Opportunity E: Cùng một thông tin bị hỏi lại nhiều lần vì không có chỗ tra chung
└── Opportunity F: Không biết việc mình đang làm có đang chặn ai
```

### 2.4. Chấm điểm shortlist (1–5)

Shortlist lấy **3 candidate từ file của Phạm Trường Chính** — bộ bằng chứng định lượng chi tiết nhất nhóm hiện có (số phút theo từng bước, tần suất đếm được, sự việc cụ thể kèm hệ quả). **Điểm dưới là đề xuất của người chuẩn bị — nhóm xác nhận và chấm lại trong buổi**; 12 candidate vẫn pitch đủ ở bảng 2.1 và nhóm có quyền đưa candidate khác vào nếu tranh luận ra điều ngược lại.

| Candidate (từ file Trường Chính) | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #4 Dò luồng dữ liệu + quy tắc ngầm codebase | 5 | 5 | 5 | 5 | 3 | 5 | 2 | 30 |
| #5 So sánh thư viện theo kiến trúc dự án | 5 | 5 | 5 | 4 | 4 | 5 | 4 | **32** |
| #6 Ưu tiên việc đang chặn đồng đội | 5 | 3 | 4 | 4 | 3 | 3 | 3 | 25 |

Ghi chú chấm (theo dữ liệu trong file Trường Chính): #4 có bằng chứng và impact mạnh nhất (75'/task đo theo bước; Mentor bị ngắt 4–5 lần/tuần × 15–20') nhưng "vừa sức lab" 3 (cần codebase thật để thử, khó phỏng vấn thêm intern trong buổi) và "nhóm hiểu domain" 2 (chỉ 1/4 thành viên đang thực tập); #5 thử được ngay trong lab bằng Template 6 tiêu chí với 2–3 thư viện thật, ai từng làm đồ án cũng hiểu domain nên 4; #6 card chưa vẽ quy trình chi tiết và chính chủ card nghi "quy tắc phân loại cố định (No AI/Rule) là đủ" nên thấp ở "quy trình rõ" và "so 4 mức".

**Candidate được chọn:** *(đề xuất: #5 — So sánh thư viện theo kiến trúc dự án; nhóm chốt trong buổi)*

**Vì sao chọn:** bằng chứng định lượng (210'/lần, 1/2 lần phải làm lại thêm 90'), quy trình 6 bước có số phút, so sánh trực tiếp được No AI (Template 6 tiêu chí + công cụ tra số liệu) với Workflow (AI đối chiếu tài liệu thư viện theo template), và kiểm chứng CP4 làm được ngay trong lab: phỏng vấn 2–3 bạn từng research thư viện cho đồ án + thử template trên 2–3 thư viện thật.

**Vì sao loại các candidate còn lại:** #4 (30) — bằng chứng và impact mạnh nhất nhóm nhưng chỉ 1/4 thành viên thật sự gặp; kiểm chứng CP4 khó trong buổi (cần bạn đang thực tập thật để phỏng vấn); giữ làm hướng tiếp theo nếu nhóm ưu tiên impact hơn tính kiểm chứng được. #6 (25) — chưa vẽ được quy trình chi tiết; chính card ghi nghi vấn "quy tắc phân loại cố định là đủ" — nếu đúng, bài dừng sớm ở mức can thiệp. #1 (Nguyên — gom tài liệu ôn thi) — số liệu toàn ước lượng hồi tưởng, chưa bấm giờ và chưa xác nhận người khác cùng pain. #10 (Hưng) — một phần nghiệm thuộc coach sửa đề, ngoài quyền nhóm. #7–#9 (Trung) — chưa có dấu hiệu thật (toàn "ước tính/giả thuyết, cần xác minh").

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
