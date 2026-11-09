# Báo cáo cá nhân — 2A202603365_NguyenTienHung


## 1. Thông tin học viên

- Họ tên: Nguyễn Tiến Hưng
- MSSV: 2A202603365
- Email trường (không bắt buộc, repo có thể để public):26ai.hungnt9@vinuni.edu.vn
- Tên nhóm: QWERTY
- Link repo nhóm:https://github.com/Khoaitay51/K5-L3A-Day02-QWERTY-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi mở một repo lab mới (README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION…), tôi muốn biết nhanh mình phải nộp gì, ở đâu, theo tên nào, để không mất điểm vì sai cấu trúc | Học viên K5 (tôi + các bạn cùng lớp) | Đề Day02 có 9 file hướng dẫn, ~16.000 từ (đếm bằng `wc -w`). Tôi mất 15–30 phút đọc đến khi rõ phải nộp gì; 1–2 lab/tuần → 15–60 phút/tuần |
| 2 | Lặp lại | Khi bắt đầu mỗi lab nhóm, tôi muốn fork và đặt tên repo, tạo file báo cáo đúng cú pháp, để cả nhóm không bị trừ điểm vì sai tên | Nhóm trưởng và thành viên | Lặp lại 1–2 lần/tuần. Bằng chứng: repo nhóm hôm nay đang đặt `Day02` thay vì `DAY02` theo mẫu → rủi ro trừ 5đ (RUBRIC, quy tắc chấm) |
| 3 | Pain từ người khác | Khi có thông báo deadline/gia hạn từ coach, tôi muốn thấy nó ở một chỗ, để không phải hỏi lại trong group chat | Cả lớp, coach | Ước lượng ~5 câu hỏi lặp về deadline/tuần trong group lớp; coach phải trả lời lại ~2 lần/tuần |
| 4 | Lặp lại | Khi nhóm làm chung một repo, tôi muốn biết ai đang sửa file nào, để không bị conflict khi push | Thành viên nhóm | Đã gặp 1–2 lần conflict/ghi đè khi push trong các lab nhóm trước |
| 5 | Tốn thời gian | Khi điền báo cáo Markdown nhiều bảng, tôi muốn kiểm tra còn sót mục nào trước khi nộp, để không bị trừ điểm vì thiếu field | Học viên | Soát lại mất 10–20 phút/lab, 1–2 lab/tuần. Template cá nhân Day02 có 70+ dòng bảng cần điền |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Claude gợi ý 8 problem từ bối cảnh học viên K5. Tôi giữ 5 problem trên vì đúng trải nghiệm của tôi và tôi ước lượng được số liệu (thời gian đọc đề, soát bài, số lần conflict). Tôi bỏ 3 ý: "tìm lại câu trả lời cũ trong group chat", "gom ghi chú ôn tập nhiều nguồn" và "bạn cùng nhóm hỏi lại phân công", vì tôi không có số liệu thật cho các ý này.


## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 Đọc nhiều file hướng dẫn lab để biết phải nộp gì | Lặp lại mỗi lab, ai trong lớp cũng gặp, sai thì mất điểm rõ ràng | Các bạn khác có thật sự mất nhiều thời gian không, hay chỉ mình tôi đọc chậm |
| 2 | #5 Soát báo cáo thiếu mục trước khi nộp | Bottleneck rõ (bước tự đối chiếu checklist), metric đo được (số mục thiếu) | Một checklist tĩnh có đủ giải quyết không |
| 3 | #3 Thông báo deadline rải rác, phải hỏi lại | Có bằng chứng dễ thu (đếm tin nhắn), ảnh hưởng nhiều người | Có phải do kênh thông báo (vấn đề tổ chức) chứ không phải do người đọc |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi mở một repo lab mới, tôi muốn biết nhanh mình phải nộp gì, ở đâu, đặt tên thế nào, để không mất điểm vì sai cấu trúc |
| Actor | Học viên K5 · L3A, làm lab hằng ngày theo repo GitHub |
| Thời điểm / bối cảnh | Đầu mỗi buổi lab, và lần nữa trước deadline khi soát bài |
| Quy trình hiện tại (3–7 bước) | 1. Mở README → 2. Mở RULES, CHECKPOINTS → 3. Mở RUBRIC để biết cách chấm → 4. Mở SUBMISSION để biết tên repo/file → 5. Tự ghi chú lại "phải nộp gì" → 6. Hỏi lại nhóm/coach chỗ chưa rõ |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: đối chiếu RUBRIC với SUBMISSION và template để ra danh sách việc phải làm, ~10 phút |
| Impact (nếu không giải thì sao) | Sai tên repo/file bị trừ 5đ; đọc đề mất 15–30 phút trong khi lịch lab chỉ dành 15' cho CP0 |
| Success metric (baseline → target) | Thời gian từ lúc mở repo đến lúc có danh sách "phải nộp gì": ~25 phút → ≤ 10 phút (tự bấm giờ ở lab sau); số lỗi tên repo/file khi nộp: 1 (lab này) → 0 |
| Phương án không dùng AI | Đề xuất coach thêm một mục "TL;DR phải nộp gì" (1 bảng) đầu README; nhóm dùng chung một checklist |
| Giả thuyết về AI (nếu có) | AI đọc các file .md và trích ra checklist nộp bài kèm link tới dòng nguồn — nhưng nếu repo đã có SUBMISSION checklist thì có thể không cần |
| Cảm nhận nhanh | No AI / **Rule** (checklist cố định) — Workflow chỉ khi format đề mỗi lab khác nhau nhiều |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~25 phút/lab

[Đọc README: 5'] → [RULES + CHECKPOINTS: 5'] → [RUBRIC: 3']
→ [Đối chiếu RUBRIC ↔ SUBMISSION ↔ template: 10'] ← BOTTLENECK
→ [Ghi checklist riêng: 1'] → [Hỏi lại nhóm/coach: 1']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp lab trước deadline, tôi muốn biết báo cáo còn thiếu mục/field nào, để không bị trừ điểm vì thiếu |
| Actor | Học viên K5, tự soát báo cáo cá nhân và báo cáo nhóm |
| Thời điểm / bối cảnh | 30–60 phút trước deadline, thường buổi tối |
| Quy trình hiện tại (3–7 bước) | 1. Mở RUBRIC → 2. Mở file báo cáo → 3. Dò từng mục xem đã điền chưa → 4. Kiểm tên file, tên repo → 5. Commit & push → 6. Kiểm trên GitHub |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: dò từng bảng/field (ô trống, thiếu số phút, thiếu số từ reflection), ~8 phút |
| Impact (nếu không giải thì sao) | Thiếu field bị trừ theo rubric (vd. thiếu dấu hiệu thật quá nửa → C1 tối đa 4/8) |
| Success metric (baseline → target) | Thời gian soát: ~15 phút (10–20') → ≤ 5 phút; số mục thiếu bị phát hiện sau khi nộp → 0 (đếm bằng số dòng trừ điểm trong kết quả chấm) |
| Phương án không dùng AI | Script/regex đếm ô trống trong bảng Markdown, đếm số từ mục 6, kiểm tên file theo mẫu `MSSV_HoTen.md` |
| Giả thuyết về AI (nếu có) | AI chỉ cần cho phần định tính (vd. "dấu hiệu thật có đo được không", "Job Story có phải solution trá hình không") |
| Cảm nhận nhanh | **Rule** cho phần định lượng; Workflow cho phần định tính |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~15 phút/lần nộp

[Mở RUBRIC: 2'] → [Mở báo cáo: 1']
→ [Dò từng bảng, ô trống, số từ: 8'] ← BOTTLENECK
→ [Kiểm tên file/repo: 1'] → [Commit + push: 2'] → [Kiểm trên GitHub: 1']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi coach thông báo deadline hoặc gia hạn, tôi muốn thấy thông tin đó ở một chỗ cố định, để không phải hỏi lại trong group chat |
| Actor | Học viên (người hỏi) và coach/TA (người trả lời lặp lại) |
| Thời điểm / bối cảnh | Cuối buổi lab và tối trước deadline |
| Quy trình hiện tại (3–7 bước) | 1. Nhớ mang máng có thông báo → 2. Cuộn group chat → 3. Kiểm LMS → 4. Không chắc → hỏi lại trong group → 5. Chờ coach/bạn trả lời |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2: cuộn group chat tìm thông báo, dưới 5 phút/lần (đã hạ từ ước lượng ban đầu sau phản biện của nhóm) |
| Impact (nếu không giải thì sao) | Coach trả lời lặp lại 2 lần/tuần; có nguy cơ nộp muộn vì nhớ sai mốc (lab sáng 23h59 vs lab chiều 11h59 hôm sau) |
| Success metric (baseline → target) | Số câu hỏi lặp về deadline trong group/tuần: 5 → ≤ 1 |
| Phương án không dùng AI | Ghim tin nhắn deadline; một trang LMS/Google Sheet duy nhất cho mọi deadline |
| Giả thuyết về AI (nếu có) | Gần như không cần AI — đây là vấn đề kênh thông tin |
| Cảm nhận nhanh | **Rule** (ban đầu nghĩ Workflow; nhóm phản biện là quá cao → hạ xuống Rule, vd. ghim + gắn tag #deadline) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~8 phút/lần

[Nhớ có thông báo: 0'] → [Cuộn group chat: 3'] ← BOTTLENECK
→ [Kiểm LMS: 2'] → [Hỏi lại: 1'] → [Chờ trả lời: 2'+]
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Bottleneck là một bước cụ thể (dò ô trống/field), metric đo được, và so sánh rõ được No AI / Rule / Workflow — phần định lượng làm bằng Rule, chỉ phần định tính mới cần AI.
- Câu hỏi muốn nhóm phản biện: Một checklist tĩnh + script đếm ô trống đã đủ chưa, hay phần "dấu hiệu thật có đo được không" thật sự cần AI?

### AI đã phản biện card thế nào

(Prompt: "Đóng vai PM hoài nghi, chỉ ra điểm yếu" — Claude, 2026-11-09)

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: repo đã có SUBMISSION.md checklist sẵn — có thể pain là "không đọc checklist" chứ không phải thiếu thông tin | Đồng ý một phần | Hạ cảm nhận từ Workflow xuống Rule/No AI; thêm "Điều còn chưa chắc" |
| Card #2: actor "học viên" quá rộng; bottleneck có thể ở bước kiểm định tính chứ không phải đếm ô trống | Đồng ý | Tách metric thành phần định lượng (Rule) và định tính (Workflow) |
| Card #3: đây là vấn đề tổ chức kênh thông báo, AI không giải quyết gốc | Đồng ý | Bỏ ý Workflow; nghiêng về No AI/Rule (nhóm cũng phản biện tương tự) |
| Cả 3 card: baseline phút chưa có số đo thật; card #1 có target (≤10') lớn hơn baseline (5') là vô lý | Đồng ý | Thay bằng số tự ước lượng: đọc đề 15–30', soát bài 10–20'; sửa baseline card #1 thành ~25'; ghi chú sẽ bấm giờ thật ở lab sau |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch top 3 card với nhóm, trong đó có card #3 (tìm lại thông báo/deadline trong group chat) | Problem của tôi không trùng với 3 bạn còn lại → góp thêm một hướng mới vào danh sách candidate |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (bổ sung sau khi nhóm chốt) | (bổ sung sau khi nhóm chốt) |
| Nhận phản biện | Câu hỏi tôi nhận được: thời gian lướt tìm thông báo có thật sự tới 5 phút không, và bài này có cần tới mức Workflow không? | Tôi đã sửa gì: đồng ý với thành viên nhóm — hạ thời gian bottleneck xuống dưới 5 phút và hạ mức can thiệp từ Workflow xuống Rule |
| Gom cluster / cây OST | (bổ sung sau khi nhóm chốt) | (bổ sung sau khi nhóm chốt) |
| Chọn candidate problem | Cùng nhóm so sánh các card đã pitch; đồng ý chọn card #1 của bạn Phạm Trường Chinh: *Intern mới vào dự án phải tự tìm hiểu luồng dữ liệu (file, hàm, bảng DB) và quy tắc ngầm*. Card của tôi (#3 tìm thông báo deadline) không được chọn vì sau phản biện chỉ cần Rule/No AI, bottleneck dưới 5 phút | Nhóm chốt candidate có actor rõ (Intern & Mentor), lặp lại ở mọi task tháng đầu, tốn 1–1,5h/ngày của Intern và ngắt quãng Mentor 4–5 lần/tuần. Điều còn chưa chắc: làm sao giữ sơ đồ/tóm tắt luồng dữ liệu không lỗi thời khi code thay đổi liên tục |
| Kiểm chứng / research | (bổ sung sau khi nhóm chốt) | (bổ sung sau khi nhóm chốt) |
| Quy trình nhóm | Cùng nhóm thống nhất làm lần lượt từng giai đoạn (scan → pitch → hội tụ) thay vì nhảy vào giải pháp | Giảm tình trạng solution-first khi nhóm vội ra quyết định |
| Problem Statement | (bổ sung sau khi nhóm chốt) | (bổ sung sau khi nhóm chốt) |
| Mức can thiệp AI | Với card của tôi: chấp nhận hạ từ Workflow xuống Rule sau phản biện | Bài nhóm: (bổ sung sau khi nhóm chốt) |
| Quyết định | (bổ sung sau khi nhóm chốt) | (bổ sung sau khi nhóm chốt) |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Claude gợi ý 8 problem theo 4 lăng kính từ bối cảnh học viên K5 | Phủ đủ 4 lăng kính, viết đúng dạng Job Story | Không có dấu hiệu thật — AI không biết tôi mất bao nhiêu phút | Tự điền số liệu (đọc đề 15–30', soát bài 10–20', 1–2 conflict); bỏ 3 problem không có số liệu, giữ 5 |
| CP2 Problem Card | Claude dựng nháp 3 card + phản biện kiểu PM hoài nghi | Chỉ ra card #3 là vấn đề tổ chức, không cần AI | Quy trình là quy trình "điển hình", chưa chắc là quy trình thật của tôi; số phút ban đầu tôi điền không khớp nhau | Tự chia số phút từng bước cho khớp tổng thời gian tôi ước lượng; sửa target card #1 |
| CP4 Research | (nhóm chưa tới bước này) | | | |
| CP5 Quy trình | (nhóm chưa tới bước này) | | | |
| CP5–6 Problem Statement | (nhóm chưa tới bước này) | | | |
| CP6 Mức can thiệp / quyết định | (nhóm chưa tới bước này) | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi khá ấn tượng với các problem của 3 bạn còn lại và ấn tượng bởi problem về việc tốn thời gian trong việc cuộn đọc thông tin từ group chung của cộng đồng. Problem của tôi thì không trùng với của thành viên nào trong nhóm.
<!-- Gợi ý tự soi: Problem nào của bạn khác làm bạn bất ngờ? Problem nào trùng pattern với của bạn? Ai viết bottleneck cụ thể hơn bạn, cụ thể ở điểm nào? -->


**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có đôi lúc nhóm gặp tình trạng solution-first khi quá vội để suy nghĩ cách giải quyết và đưa ra quyết định luôn. Khi đó nhóm đã chọn ngồi lại hoàn thành từng giai đoạn một.
<!-- Gợi ý: Có ai nói "làm chatbot/agent…" trước khi vẽ quy trình không? Ai phát hiện ra? Cây OST đã gạch bỏ ý nào vì là solution? -->


**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã có thay đổi ý định một lần về thời gian hoàn thành của việc lướt tìm thông báo không lên tới 5 phút, và mức Workflow đang hơi cao nên hạ xuống Rule; tôi đồng ý với thành viên của nhóm tôi.
<!-- Gợi ý: Card #2 của bạn ban đầu nghĩ cần Workflow — sau phản biện có hạ xuống Rule không? Ai hỏi câu gì khiến bạn đổi? -->


**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

<!-- Gợi ý: Người được hỏi có mất nhiều thời gian như nhóm giả định không? Tín hiệu phản bác là gì? Công cụ có sẵn đã giải được bước nào? -->


**6.5. Điều khó nhất khi viết Problem Statement là gì?**

<!-- Gợi ý: Khó nhất là chọn baseline, viết metric đo được, hay viết boundary? Bản v0 bị phản biện ở trường nào? -->


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

<!-- Gợi ý: Bạn có bấm giờ thật thay vì ước lượng không? Có điểm nào bạn thấy chưa chặt nhưng không nói ra? -->


**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- [docs/01-worksheet.md](../../docs/01-worksheet.md) — template, 4 lăng kính, prompt phản biện
- [RUBRIC.md](../../RUBRIC.md), [SUBMISSION.md](../../SUBMISSION.md) — dùng làm bằng chứng cho Card #1, #2
- Jobs-to-be-Done / Job Story (Intercom), xem [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md)
