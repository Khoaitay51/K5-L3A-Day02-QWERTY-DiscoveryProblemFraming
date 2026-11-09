# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

> Phụ trách CP4: Nguyễn Tiến Hưng (2A202603365). Bộ câu hỏi phỏng vấn: [cp4-interview-guide.md](../assets/cp4-interview-guide.md).

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| A1 | Intern mới mất ≥ 60 phút/task để xác định đúng các file, hàm, bảng DB cần sửa trong 3–4 tuần đầu | Value | 5 | 2 (mới có trải nghiệm của 1 thành viên) | **Có** |
| A2 | Mentor bị Intern hỏi về luồng dữ liệu cơ bản 4–5 lần/tuần, mỗi lần 15–20 phút | Value | 4 | 1 (chưa hỏi Mentor nào) | **Có** |
| A3 | Bước nghẽn là lần theo luồng qua 10–15 file và tìm quy tắc ngầm, không phải hiểu nghiệp vụ trong ticket | Value | 5 | 1 | **Có** |
| A4 | Quy tắc ngầm của nhóm có thể viết ra thành tài liệu (vd. `CONVENTIONS.md`) và giữ được cập nhật | Feasibility | 4 | 2 (research: có công cụ gắn tài liệu với code, xem 3.3) | Sau |
| A5 | Công ty cho phép đưa source code vào công cụ AI/dịch vụ bên ngoài | Viability | 5 | 1 | Có (hỏi câu 9) |
| A6 | Intern sẽ tự mở IDE kiểm lại sơ đồ thay vì chép máy móc | Usability | 3 | 1 | Sau |

Giả định nhóm kiểm chứng trong buổi này: **A1, A2, A3** (quan trọng cao, bằng chứng thấp), cộng thêm A5 bằng câu hỏi số 9.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn 2–3 người ngoài nhóm theo The Mom Test (câu hỏi tại [cp4-interview-guide.md](../assets/cp4-interview-guide.md)).

> ⚠️ CHƯA PHỎNG VẤN — các bảng dưới chỉ điền sau khi đã hỏi người thật. Không điền trước. Bịa kết quả → C7 = 0 cho cả nhóm.

### Interview snapshot #1 — Ví dụ giả định

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Lập trình viên mới tham gia một dự án, chưa quen với cấu trúc codebase. |
| Câu nói đáng nhớ nhất (nguyên văn) | “Em hiểu chức năng cần sửa, nhưng đôi khi không biết nên bắt đầu tìm từ file nào và dữ liệu được xử lý qua những hàm nào.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi được giao chỉnh sửa một chức năng có sẵn, người này mất thời gian tìm file liên quan và lần theo luồng dữ liệu trước khi hiểu được vị trí cần thay đổi. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tìm kiếm từ khóa trong IDE, đọc README và tài liệu dự án, xem lịch sử commit hoặc hỏi thành viên có kinh nghiệm. |
| Mất bao lâu, bao lần? | Chưa có dữ liệu thực tế. Cần hỏi người được phỏng vấn về thời gian của lần gần nhất và tần suất gặp vấn đề. |
| Insight / opportunity rút ra | Người mới có thể gặp khó khăn khi xác định file, hàm và luồng dữ liệu liên quan đến một chức năng. Có cơ hội cải thiện khả năng điều hướng codebase và cung cấp hướng dẫn ban đầu, đồng thời vẫn giữ vai trò trao đổi chuyên môn của Mentor. |



### Interview snapshot #2

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Developer mới tham gia dự án phần mềm, có kinh nghiệm học lập trình nhưng chưa quen codebase của nhóm |
| Câu nói đáng nhớ nhất (nguyên văn) | Ví dụ minh họa: "Có những lúc em biết chức năng cần sửa nhưng không biết dữ liệu bắt đầu từ file nào và đi qua những hàm nào." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Ví dụ minh họa: Khi được giao sửa một chức năng có sẵn, người mới chưa xác định được file xử lý chính và phải tìm hiểu mối liên hệ giữa nhiều hàm trước khi bắt đầu chỉnh sửa. |
| Hiện đang xử lý bằng cách nào (workaround)? | Ví dụ minh họa: Tìm kiếm tên hàm trong IDE, đọc README và tài liệu dự án, xem lại các commit cũ hoặc hỏi thành viên có kinh nghiệm. |
| Mất bao lâu, bao lần? | Chưa có số liệu thực tế. Cần hỏi người được phỏng vấn về thời gian của lần gần nhất và tần suất gặp tình huống tương tự. |
| Insight / opportunity rút ra | Có thể tồn tại khó khăn trong việc xác định mối liên hệ giữa các file, hàm và luồng dữ liệu. Cơ hội là hỗ trợ developer mới định hướng codebase và tìm đúng vị trí cần đọc mà không thay thế việc trao đổi chuyên môn với Mentor. |

### Tổng hợp

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | Chưa thực hiện phỏng vấn thực tế | Chưa có dữ liệu thực tế để xác nhận vấn đề từ người dùng. Cần phỏng vấn 2–3 lập trình viên mới để tìm hiểu trải nghiệm gần đây. | Chưa có dữ liệu phản bác từ phỏng vấn. |
| Research (3.3) | 3 nguồn | Đã có công cụ thương mại giải quyết các vấn đề như lần theo luồng code và phát hiện tài liệu lỗi thời. Điều này cho thấy đây là những nhu cầu đã được nhận diện trên thị trường. | Nghiên cứu onboarding tại Microsoft cho thấy các nhiệm vụ thực tế còn giúp developer mới xây dựng sự tự tin và hòa nhập với nhóm. Vì vậy, giảm số lần hỏi Mentor không nhất thiết là điều tốt. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- Từ research (đề xuất, chờ nhóm duyệt): đổi metric "số lần hỏi Mentor ≤ 1 lần/tuần" thành "số câu hỏi **về luồng dữ liệu cơ bản** (file/hàm/bảng nào) ≤ 1 lần/tuần", vẫn giữ các câu hỏi về nghiệp vụ và quyết định thiết kế, vì tương tác với người hướng dẫn có giá trị hòa nhập (Ju et al., 2021).
- Từ research: câu hỏi "làm sao giữ tài liệu không lỗi thời" đã có hướng giải ở công cụ có sẵn (gắn tài liệu với code, kiểm tra trong CI) → nhóm không cần tự phát minh cơ chế này.
- Từ phỏng vấn: (điền sau khi có kết quả)

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Swimm** — tài liệu gắn với code (code-coupled docs) | [docs.swimm.io — Benefits of code-coupled documentation](https://docs.swimm.io/new-to-swimm/benefits-of-code-coupled-documentation) | Bước 4 (tìm quy tắc ngầm) và rủi ro "tài liệu lỗi thời" | Tài liệu nhúng đoạn code/tên hàm thật; Auto-sync cập nhật đoạn code khi code đổi; nếu thay đổi lớn thì kiểm tra thất bại và tài liệu bị đánh dấu "có thể đã lỗi thời"; có tích hợp CI để kiểm trên mỗi PR | Vẫn cần người viết tài liệu ban đầu; công cụ trả phí; số liệu giảm thời gian onboarding chỉ có trong case study của chính Swimm, không phải nghiên cứu độc lập | Trả lời đúng điều nhóm còn chưa chắc: muốn tài liệu không lỗi thời thì phải gắn nó với code và kiểm trong CI. Bản No AI/Rule có thể bắt chước: để `CONVENTIONS.md` trong repo + thêm mục kiểm vào PR template |
| **DeepWiki** (Cognition / Devin) — tự sinh wiki cho repo | [docs.devin.ai — DeepWiki](https://docs.devin.ai/work-with-devin/deepwiki) | Bước 2–3 (dò từ giao diện xuống route, lần theo luồng qua nhiều file) | Tự index repo, sinh wiki có sơ đồ kiến trúc, link tới source, tóm tắt codebase; có hỏi đáp trên wiki | Bản miễn phí chỉ cho repo public; repo lớn có thể bị bỏ sót thư mục; tài liệu không mô tả cơ chế tự cập nhật (phải sinh lại); không biết quy tắc ngầm chưa ai viết ra; phải đưa code cho bên thứ ba → vướng A5 | Phần "tóm tắt luồng dữ liệu" đã có công cụ sẵn → nhóm **không nên tự xây**. Giá trị còn lại nằm ở quy tắc ngầm và bước Mentor xác nhận |
| **Nghiên cứu: Ju, Sajnani, Kelly, Herzig (ICSE 2021)** — *A Case Study of Onboarding in Software Teams: Tasks and Strategies* | [arXiv:2103.05055](https://arxiv.org/abs/2103.05055) | Không giải bước cụ thể — cho bối cảnh về onboarding qua task | Dữ liệu thật ở Microsoft: phỏng vấn 32 dev chuyển nhóm và 15 quản lý, khảo sát 189 dev và 37 quản lý; onboarding chủ yếu qua task kỹ thuật nhỏ (sửa bug, tính năng nhỏ); task ảnh hưởng tới việc học, sự tự tin và sự hòa nhập | Bối cảnh công ty lớn, không riêng Intern; phần abstract không nói cụ thể về Mentor hay cách đọc codebase, cần đọc bản đầy đủ | Bối cảnh card (Intern nhận ticket sửa tính năng có sẵn) khớp với cách onboarding phổ biến. Không nên đặt mục tiêu "cắt hẳn việc hỏi Mentor"; nên giữ bước Mentor xác nhận (HITL) |

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

- Ju, A., Sajnani, H., Kelly, S., Herzig, K. (2021). *A Case Study of Onboarding in Software Teams: Tasks and Strategies*. ICSE 2021. https://arxiv.org/abs/2103.05055
- Swimm. *Benefits of code-coupled documentation*. https://docs.swimm.io/new-to-swimm/benefits-of-code-coupled-documentation
- Cognition. *DeepWiki* (Devin docs). https://docs.devin.ai/work-with-devin/deepwiki
