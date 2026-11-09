# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: QƯERTY
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

Bài của nhóm nằm ở ô: Độ phức tạp cao × Độ mơ hồ trung bình.
Vì sao:
    - Độ phức tạp cao: Một thao tác trên giao diện có thể đi qua nhiều tầng xử lý như Controller, Service, Repository, Model và Database. Intern phải lần theo nhiều file, hàm gọi chéo và quan hệ dữ liệu mới hiểu được toàn bộ luồng nghiệp vụ.
    - Độ mơ hồ trung bình: Cấu trúc code và tên hàm có thể được xác định thông qua tìm kiếm, nhưng các quy tắc ngầm của nhóm như quy ước xử lý lỗi, phân quyền, đặt tên và nghiệp vụ đặc thù thường không được ghi đầy đủ trong tài liệu.
    - Không thể chỉ dùng quy tắc cố định: Cùng một yêu cầu nghiệp vụ nhưng mỗi tính năng có thể có cấu trúc code và đường đi dữ liệu khác nhau. Cần khả năng đọc ngữ cảnh và tổng hợp thông tin từ nhiều file.
Kết luận: Bài toán phù hợp với Workflow có AI hỗ trợ phân tích ngữ cảnh, kết hợp Rule để truy xuất cấu trúc code và tài liệu dự án.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) |Viết ARCHITECTURE_MAP.md, tạo mẫu Intern tự ghi 3 dòng kế hoạch sửa code và gửi Mentor xác nhận.|Dự án nhỏ, ít luồng nghiệp vụ, tài liệu kiến trúc được cập nhật thường xuyên.|Tài liệu nhanh lỗi thời khi code thay đổi; không bao phủ được từng API và hàm trong codebase lớn.|Không chọn làm giải pháp chính|
| **Rule** |Tìm kiếm theo tên route, API, hàm; quét cây thư mục và hiển thị các file có liên quan theo cấu trúc Controller → Service → Repository → Model.|Tên hàm, route và cấu trúc dự án rõ ràng, có quy ước nhất quán.|Không hiểu được ngữ cảnh nghiệp vụ, hàm gọi chéo phức tạp và quy tắc ngầm không được ghi thành quy tắc cố định.|Không chọn làm giải pháp chính|
| **Workflow** |Kết hợp Rule và AI: nhận yêu cầu/tên thao tác → truy xuất file liên quan → AI phân tích chuỗi gọi hàm và tài liệu CONVENTIONS.md → tạo sơ đồ luồng dữ liệu, tóm tắt quy tắc liên quan và dẫn chứng vị trí code. Intern kiểm tra lại và Mentor xác nhận.|Codebase có thể truy xuất, có tài liệu hoặc code để đối chiếu; đầu ra được con người kiểm tra trước khi sử dụng.|AI có thể bỏ sót hàm gọi chéo, suy diễn sai quan hệ dữ liệu hoặc trình bày quy tắc chưa được xác thực như sự thật.|Chọn|
| **Agent** |AI tự động đọc toàn bộ dự án, chủ động tìm hiểu nghiệp vụ, cập nhật sơ đồ kiến trúc và đề xuất hoặc thực hiện thay đổi code.|Có hệ thống kiểm soát quyền truy cập, kiểm thử tự động, giám sát và cơ chế phê duyệt chặt chẽ.|Phạm vi quá rộng, tốn chi phí, nguy cơ đọc sai nghiệp vụ, cập nhật sai tài liệu hoặc tự ý tác động đến code.|Không chọn|

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:** 
    - Không chọn No AI: Tài liệu kiến trúc tĩnh chỉ mô tả được các luồng chính, không thể bao phủ hàng trăm thư mục và các luồng xử lý cụ thể trong từng ticket. Intern vẫn phải tự mở 10–15 file để lần theo dữ liệu.
    - Không chọn Rule: Rule có thể tìm được file và hàm dựa trên tên gọi, nhưng chưa đủ khả năng tổng hợp mối quan hệ giữa nhiều tầng xử lý, hiểu ngữ cảnh nghiệp vụ và diễn giải các quy tắc được ghi rải rác.
    - Workflow phù hợp hơn: Có thể kết hợp khả năng truy xuất chính xác của Rule với khả năng đọc hiểu, tổng hợp và giải thích của AI. Đồng thời vẫn giữ Intern và Mentor trong quy trình xác nhận.
    - Không chọn Agent: Tự động hóa toàn bộ quá trình là chưa cần thiết. Bài toán hiện tại chỉ cần giúp Intern hiểu code nhanh hơn, không cần AI tự sửa code hoặc tự ra quyết định.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? |AI nhận ticket hoặc tên thao tác trên giao diện, phân tích codebase để tạo sơ đồ luồng dữ liệu từ UI → API Route → Controller → Service → Repository → Model → Database. Đồng thời tóm tắt các quy tắc nghiệp vụ và quy ước nhóm có liên quan.|
| **Judgment** — con người cân nhắc, quyết định gì? |Intern kiểm tra các file, hàm, bảng dữ liệu và vị trí code mà AI dẫn chứng trên IDE; đánh giá thông tin có đúng với yêu cầu ticket không. Mentor xác nhận các quy tắc nghiệp vụ quan trọng và kế hoạch sửa code.|
| **Action** — hành động cuối cùng là gì, ai làm? |Intern tự viết kế hoạch sửa code 3 dòng, gửi Mentor xác nhận rồi mới thực hiện chỉnh sửa. AI không tự động sửa hoặc commit code.|
| **Outcome** — đo kết quả bằng gì? |(1) Thời gian xác định danh sách file/hàm/bảng DB giảm từ 75 phút xuống dưới 20 phút/task. (2) Số lần hỏi Mentor về luồng dữ liệu cơ bản giảm từ 4–5 lần/tuần xuống ≤ 1 lần/tuần.|
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |Ticket mô tả yêu cầu, tên thao tác hoặc màn hình, mã nguồn dự án (Controller, Service, Repository, Model...), cấu trúc thư mục, schema Database và tài liệu CONVENTIONS.md. Phần lớn đã có trong repository; tài liệu quy tắc ngầm cần được Mentor bổ sung hoặc xác nhận nếu chưa tồn tại.|
| **Feedback** — lấy phản hồi ở đâu để cải thiện? |Intern đánh dấu file/hàm AI tìm sai hoặc bỏ sót; Mentor xác nhận hoặc chỉnh sửa sơ đồ luồng và quy tắc nghiệp vụ. Ghi nhận thời gian hoàn thành task và số lần phải hỏi lại Mentor để đánh giá chất lượng qua từng lần sử dụng.|

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
    Chọn Augment (AI hỗ trợ con người), không chọn Automate (AI tự động làm thay).  
    * Bằng chứng:
        - Intern cần hiểu kiến trúc dự án để có thể tự xử lý những ticket tương tự trong tương lai, chứ không chỉ cần AI chỉ sẵn file để sửa.
        - Việc hiểu các quy tắc nghiệp vụ và quy ước ngầm đòi hỏi kinh nghiệm của Mentor và kiến thức thực tế của nhóm.
        - AI chỉ đưa ra sơ đồ luồng code, vị trí file/hàm và các quy tắc liên quan để Intern tham khảo.
        - Intern bắt buộc tự kiểm tra trên IDE và viết kế hoạch sửa code 3 dòng gửi Mentor xác nhận (HITL).

- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:
    Bỏ sót (False Negative) là rủi ro nghiêm trọng hơn trong bài toán này.
    * Vì:
        - Nếu AI bỏ sót một file hoặc hàm quan trọng, Intern có thể hiểu sai luồng xử lý và sửa thiếu thành phần liên quan.
        - Nếu AI báo nhầm một file không liên quan, Intern vẫn có thể kiểm tra và loại bỏ thông tin đó trên IDE.
        - Tuy nhiên, cả hai loại lỗi đều cần được kiểm soát vì thông tin sai có thể dẫn đến thay đổi code không an toàn.

    * Phương án xử lý:
        - AI phải cung cấp đường dẫn file, tên hàm và vị trí code làm bằng chứng cho từng nhận định.
        - Phân biệt rõ thông tin tìm thấy trong code với giả thuyết AI suy luận.
        - Khi không đủ bằng chứng, AI phải ghi rõ Chưa xác minh thay vì tự khẳng định.
        - Hiển thị các điểm chưa chắc chắn và cảnh báo những tầng xử lý chưa truy xuất được.
        - Intern tự kiểm tra trên IDE, Mentor xác nhận trước khi sửa code.
---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** |Thực tập sinh (Intern Developer) mới tham gia dự án trong 3–4 tuần đầu và Mentor/Senior Developer chịu trách nhiệm hướng dẫn.|
| **Quy trình** |Intern đọc ticket → mở màn hình giao diện → tìm API Route → lần theo Controller, Service, Repository, Model → kiểm tra Database → tìm quy tắc ngầm trong code cũ/PR → hỏi Mentor nếu chưa hiểu → lập kế hoạch sửa code.|
| **Bottleneck** |Bước lần theo luồng dữ liệu qua 10–15 file mất khoảng 35 phút; tìm quy tắc ngầm trong code cũ và PR mất khoảng 15 phút. Tổng thời gian tìm hiểu và xác nhận luồng khoảng 75 phút/task.|
| **Impact** |Intern mất 60–90 phút mò mẫm cho mỗi task mới trong giai đoạn đầu; Mentor bị gián đoạn 4–5 lần/tuần, mỗi lần 15–20 phút. Nguy cơ sửa thiếu file, sai luồng dữ liệu hoặc vi phạm quy ước dự án.|
| **Success Metric** (baseline → target, cách đo) |(1) Thời gian xác định danh sách file/hàm/bảng DB cần chạm tới: 75 phút → dưới 20 phút/task. Đo bằng thời gian từ lúc bắt đầu đọc ticket đến khi hoàn thành danh sách và kế hoạch sửa. (2) Số lần hỏi Mentor về luồng dữ liệu cơ bản: 4–5 lần/tuần → ≤ 1 lần/tuần. Đo bằng nhật ký câu hỏi của Intern trong giai đoạn pilot.|
| **Boundary** |AI chỉ phân tích, truy xuất và giải thích luồng code; không tự sửa, xóa, tạo hoặc commit code. Không tự khẳng định các quy tắc nghiệp vụ chưa có bằng chứng. Intern phải tự kiểm tra trên IDE và Mentor xác nhận kế hoạch sửa trước khi thực hiện.|
| **AI intervention point** |Can thiệp sau khi Intern cung cấp ticket và thao tác/màn hình cần tìm hiểu. AI truy xuất các file liên quan, lần theo quan hệ gọi hàm, đối chiếu tài liệu quy ước và tạo sơ đồ luồng dữ liệu kèm dẫn chứng.|
| **Mức chọn** | Workflow – kết hợp Rule để tìm kiếm và truy xuất code với AI để phân tích, tổng hợp và giải thích ngữ cảnh.|
| **Rủi ro & người kiểm tra** |AI có thể bỏ sót file, suy diễn sai quan hệ gọi hàm hoặc hiểu nhầm quy tắc nghiệp vụ. Intern kiểm tra vị trí code trên IDE; Mentor/Senior xác nhận các quy tắc nghiệp vụ và kế hoạch sửa.|

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
|Bottleneck|Mô tả chung là mất thời gian mò mẫm giữa các thư mục.|Tách rõ 35 phút lần theo 10–15 file và 15 phút tìm quy tắc ngầm; tổng quy trình khoảng 75 phút/task.|Xác định chính xác điểm cần AI can thiệp, tránh giải quyết sai vấn đề.|
|Success Metric|Intern hòa nhập nhanh hơn, giảm ngại hỏi Mentor.|Thời gian xác định file/hàm/bảng DB giảm từ 75 phút xuống dưới 20 phút/task; số lần hỏi Mentor giảm từ 4–5 xuống ≤ 1 lần/tuần.|Chuyển từ cảm nhận định tính sang chỉ số có thể đo lường.|
|Giả thuyết AI|AI đọc code và tóm tắt luồng nghiệp vụ.|Kết hợp Rule truy xuất code và Workflow dùng AI phân tích chuỗi file, hàm, Database và tài liệu quy ước.|Làm rõ cách AI hoạt động thay vì chỉ nêu ý tưởng chung.|
|Boundary|Chưa quy định rõ quyền hạn của AI.|AI chỉ đưa ra sơ đồ và dẫn chứng; Intern tự kiểm tra IDE, viết kế hoạch sửa 3 dòng và gửi Mentor xác nhận.|Tránh Intern phụ thuộc vào AI, copy-paste mà không hiểu kiến trúc dự án.|
|Mức can thiệp|Chưa phân biệt rõ giữa Workflow và Agent.|Chọn Workflow, không cho AI tự sửa code hoặc tự quyết định nghiệp vụ.|Giảm rủi ro và giữ con người kiểm soát các quyết định quan trọng.|
|Rủi ro|Chưa phân tích rõ lỗi AI có thể gây ra.|Bổ sung kiểm soát báo nhầm, bỏ sót, dẫn chứng code và nhãn Chưa xác minh.|Đảm bảo Intern có thể kiểm tra lại đầu ra trước khi sử dụng.|

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 |Độ chính xác của luồng dữ liệu|Các bước từ UI → API → Controller → Service → Repository → Database được xác định đúng và có thể kiểm tra trên IDE.|Chỉ sai hoặc bỏ sót một thành phần quan trọng khiến Intern hiểu sai luồng nghiệp vụ.|
| 2 |Độ đầy đủ của file/hàm liên quan|Liệt kê được các file và hàm quan trọng liên quan trực tiếp đến ticket, có giải thích vai trò từng thành phần.|Bỏ sót file/hàm quan trọng hoặc đưa quá nhiều file không liên quan mà không giải thích.|
| 3 |Độ tin cậy của quy tắc nghiệp vụ|Mỗi quy tắc được trích dẫn từ code, tài liệu hoặc PR có thể kiểm chứng; thông tin chưa rõ được đánh dấu Chưa xác minh.|AI tự suy diễn quy tắc ngầm hoặc trình bày giả thuyết như một sự thật.|
| 4 |Khả năng giải thích và sử dụng|Intern đọc được sơ đồ, hiểu vai trò các file/hàm và tự xác định được nơi cần kiểm tra tiếp.|Đầu ra quá chung chung, khó hiểu hoặc không có đường dẫn đến code gốc.|
| 5 |Hiệu quả thời gian|Intern hoàn thành danh sách file/hàm/bảng DB cần kiểm tra trong dưới 20 phút/task.|Thời gian vẫn từ 20 phút trở lên hoặc phải mất thêm nhiều thời gian sửa lại thông tin AI cung cấp.|

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? |Trung Bình|Intern mất 60–90 phút tìm hiểu mỗi task và phải hỏi Mentor 4–5 lần/tuần. Đây là nhu cầu có dấu hiệu thực tế. Tuy nhiên, cần kiểm chứng thêm xem Intern có sẵn sàng sử dụng công cụ mới thay vì tiếp tục tìm kiếm trực tiếp trên IDE hay không.|
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |Trung Bình|Sơ đồ luồng code và danh sách file có thể giúp Intern dễ hiểu hơn. Tuy nhiên, người mới vẫn cần biết cách đọc code, kiểm tra đường dẫn và phân biệt thông tin AI suy luận với thông tin có bằng chứng.|
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? |Trung Bình|Có thể tận dụng mã nguồn, cấu trúc thư mục, API, schema Database và tài liệu hiện tại. Tuy nhiên, việc truy xuất chính xác hàm gọi chéo, xử lý nhiều module và cập nhật khi code thay đổi là thách thức kỹ thuật cần thử nghiệm.|
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? |Trung Bình|Có thể tiết kiệm thời gian Intern và Mentor, nhưng cần tính chi phí API/LLM, tài nguyên phân tích code và bảo mật mã nguồn. Nhóm phát triển công cụ chịu trách nhiệm vận hành; Mentor/Senior phụ trách xác nhận tài liệu và quy tắc nghiệp vụ.|

### 8.2. Kết luận

**Quyết định:** Not Yet

**Lý do:** Nhóm xác định được vấn đề thực tế của Intern Developer khi mới tham gia dự án: mất 60–90 phút mỗi task để tìm hiểu luồng code, đồng thời phải hỏi Mentor 4–5 lần/tuần.
* Tuy nhiên, nhóm chưa nên triển khai Workflow AI ngay vì còn một số điểm chưa được kiểm chứng:
    - Chưa xác minh đầy đủ dữ liệu đầu vào: Chưa chắc repository hiện tại có đủ thông tin để AI truy xuất chính xác luồng từ UI → API → Controller → Service → Repository → Database.
    - Chưa giải quyết được quy tắc ngầm: Nhiều quy tắc nghiệp vụ chỉ tồn tại trong kinh nghiệm của Mentor, chưa được ghi lại trong CONVENTIONS.md. AI không thể tự suy ra chính xác những thông tin này.
    - Chưa kiểm chứng độ chính xác: Chưa có thử nghiệm thực tế để biết AI có bỏ sót file, hàm gọi chéo hoặc nhầm lẫn quan hệ dữ liệu hay không.
    - Chưa có bằng chứng về hiệu quả: Mục tiêu giảm thời gian từ 75 phút xuống dưới 20 phút/task hiện mới là giả thuyết, chưa có kết quả pilot.
    - Chưa đánh giá đầy đủ tính khả thi: Cần xác định phương án truy xuất code, chi phí sử dụng LLM và yêu cầu bảo mật mã nguồn của dự án.
* Kết luận: Vấn đề đáng giải quyết và hướng Workflow có tiềm năng, nhưng cần kiểm chứng dữ liệu, độ chính xác và nhu cầu thực tế trước khi quyết định đầu tư xây dựng công cụ AI.

**Nếu Go — pilot nhỏ nhất:** Chưa triển khai ở giai đoạn hiện tại. Sau khi hoàn thành các điều kiện kiểm chứng ở phần dưới, nhóm có thể thực hiện pilot nhỏ:
    - Chọn 1 repository và 3–5 luồng nghiệp vụ thực tế.
    - Thử nghiệm với 2–3 Intern và 1 Mentor.
    - Sử dụng Workflow AI để truy xuất file, hàm, bảng Database và quy tắc nghiệp vụ.
    - Bắt buộc Intern kiểm tra trên IDE và Mentor xác nhận.
    - Đo thời gian hoàn thành, độ chính xác và số lần hỏi Mentor.

**Nếu Not Yet — cần kiểm chứng gì trước:** 
    1. Kiểm chứng vấn đề: Phỏng vấn ít nhất 3 Intern và 1–2 Mentor để xác nhận thời gian 60–90 phút/task, tần suất hỏi Mentor và những khó khăn thực tế.
    2. Kiểm chứng dữ liệu: Chọn một repository mẫu, kiểm tra khả năng truy xuất route, Controller, Service, Repository, Model và Database.
    3. Kiểm chứng quy tắc ngầm: Phỏng vấn Mentor, thu thập các quy ước hiện có và thử chuẩn hóa thành CONVENTIONS.md.
    4. Kiểm chứng khả năng AI: Thử nghiệm trên 3 luồng nghiệp vụ, đối chiếu kết quả AI với luồng code do Mentor xác nhận để phát hiện file bị bỏ sót, đường dẫn sai và suy luận không có căn cứ.
    5. Kiểm chứng bảo mật và chi phí: Xác định dữ liệu nào được phép đưa vào LLM, phương án bảo vệ mã nguồn và chi phí dự kiến khi sử dụng.
    
    Chỉ chuyển sang Go khi nhóm có đủ dữ liệu đầu vào, AI truy xuất được luồng code với độ chính xác chấp nhận được và Mentor xác nhận giải pháp có giá trị thực tế.

**Nếu No-Go — nên làm gì thay AI:** Nếu sau kiểm chứng, AI không thể truy xuất luồng code đủ chính xác hoặc chi phí triển khai không phù hợp, nhóm chuyển sang giải pháp No AI kết hợp Rule:
- Xây dựng tài liệu ARCHITECTURE_MAP.md mô tả các luồng nghiệp vụ chính.
- Chuẩn hóa tài liệu CONVENTIONS.md ghi lại quy tắc ngầm của nhóm.
- Xây dựng checklist onboarding cho Intern.
- Áp dụng mẫu xác nhận luồng 3 dòng trước khi sửa code.
- Sử dụng chức năng tìm kiếm có sẵn trong IDE để hỗ trợ truy xuất file và hàm.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):
- Nếu AI bỏ sót các file/hàm quan trọng hoặc cung cấp đường dẫn không chính xác ở mức khiến Mentor phải sửa lại thường xuyên → dừng mở rộng AI, quay về Rule.
- Nếu không thể chuẩn hóa các quy tắc nghiệp vụ thành tài liệu có thể kiểm chứng → chưa triển khai chức năng giải thích quy tắc ngầm.
- Nếu thời gian xác định luồng code không giảm đáng kể so với cách làm hiện tại → đánh giá lại tính cần thiết của AI.
- Nếu không đảm bảo bảo mật mã nguồn → không đưa repository lên dịch vụ AI bên ngoài.
---

## 9. Hạn chế và hướng tiếp theo

* Hạn chế:
    - Thiếu dữ liệu kiểm chứng: Các số liệu về thời gian tìm hiểu code và tần suất hỏi Mentor hiện chủ yếu là baseline ban đầu, cần xác minh qua phỏng vấn và quan sát thực tế.
    - Phụ thuộc chất lượng repository: Code thiếu comment, tên hàm không rõ ràng hoặc cấu trúc không nhất quán có thể khiến AI truy xuất sai luồng dữ liệu.
    - Khó xác định quy tắc ngầm: Những quy tắc chỉ tồn tại trong kinh nghiệm của Mentor không thể được AI xác định chính xác nếu chưa được ghi lại.
    - Nguy cơ kết quả lỗi thời: Khi code thay đổi liên tục, sơ đồ luồng dữ liệu được tạo trước đó có thể không còn chính xác.
    - Chưa chứng minh hiệu quả Workflow: Chưa có kết quả thực nghiệm chứng minh AI giúp giảm thời gian xuống dưới 20 phút/task và giảm số lần hỏi Mentor xuống ≤ 1 lần/tuần.
    - Chưa đánh giá chi phí và bảo mật: Chưa xác định đầy đủ chi phí LLM, phương án xử lý mã nguồn nội bộ và quyền truy cập repository.
* Hướng tiếp theo:
    1. Giai đoạn 1 – Khảo sát: Phỏng vấn Intern và Mentor, xác minh các số liệu baseline và xác định những luồng nghiệp vụ thường gặp.
    2. Giai đoạn 2 – Chuẩn hóa dữ liệu: Chọn một repository mẫu, xây dựng ARCHITECTURE_MAP.md và CONVENTIONS.md với sự xác nhận của Mentor.
    3. Giai đoạn 3 – Kiểm chứng kỹ thuật: Thử nghiệm khả năng truy xuất file, hàm, API và Database bằng Rule trước; sau đó đánh giá khả năng AI tổng hợp và giải thích luồng code.
    4. Giai đoạn 4 – Đánh giá Workflow: So sánh kết quả AI với sơ đồ luồng do Mentor xác nhận, ghi nhận các trường hợp báo nhầm, bỏ sót và suy luận sai.
    5. Giai đoạn 5 – Ra quyết định: Nếu kết quả đủ tin cậy, chi phí phù hợp và đáp ứng nhu cầu thực tế, chuyển sang Go để xây dựng MVP Workflow. Nếu không, duy trì giải pháp No AI kết hợp Rule.

## 10. Tài liệu tham khảo
1. Google PAIR – People + AI Guidebook: Tài liệu tham khảo về thiết kế sản phẩm AI lấy con người làm trung tâm, phân chia trách nhiệm giữa AI và con người, kiểm soát sai sót và thiết kế tương tác.
- Google People + AI Guidebook.
2. Repository và tài liệu kiến trúc dự án: Mã nguồn, cấu trúc thư mục, API, Database Schema và các tài liệu kỹ thuật của dự án được lựa chọn để kiểm chứng.
3. Tài liệu quy ước nhóm: CONVENTIONS.md, Coding Conventions, các quy tắc nghiệp vụ và Pull Request đã được Mentor xác nhận.
4. Dữ liệu khảo sát người dùng: Kết quả phỏng vấn Intern Developer và Mentor về thời gian tìm hiểu code, số lần hỏi đáp và khó khăn trong quá trình onboarding.
5. Dữ liệu kiểm chứng Workflow: Kết quả thử nghiệm trên 3 luồng nghiệp vụ, bao gồm danh sách file/hàm AI truy xuất, mức độ chính xác, phản hồi của Mentor và thời gian hoàn thành task.
