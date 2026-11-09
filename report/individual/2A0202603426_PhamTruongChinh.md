# Báo cáo cá nhân — 2A0202603426_PhamTruongChinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Trường Chinh
- MSSV:2A202603426
- Email trường (không bắt buộc, repo có thể để public):26ai.chinhpt@vinuni.edu.vn
- Tên nhóm:QWERTY
- Link repo nhóm:https://github.com/Khoaitay51/K5-L3A-Day02-QWERTY-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi mới vào nhóm dự án và được giao sửa một luồng nghiệp vụ có sẵn, tôi muốn biết một thao tác trên màn hình sẽ đi qua những file, hàm và bảng dữ liệu nào kèm các quy tắc ngầm của nhóm, để hòa nhập nhanh mà không phải hỏi anh Mentor những câu cơ bản lặp đi lặp lại. | Thực tập sinh (Intern Dev), Mentor / Senior Dev | Trong 3 tuần đầu thực tập, mỗi ngày mất 1–1.5 tiếng mò mẫm giữa các thư mục; mỗi tuần vẫn phải hỏi anh Mentor 4–5 lần về luồng dữ liệu, mỗi lần làm ngắt quãng 15–20 phút của cả hai. |
| 2 | Lặp lại | Khi chuẩn bị gửi Pull Request lên cho các anh chị trong nhóm duyệt, tôi muốn rà soát xem đoạn code mình (kết hợp công cụ gợi ý code) vừa viết có vi phạm các quy ước ngầm của dự án (cách bọc lỗi, ghi log, đặt tên, phân quyền) hay không, để không bị trả về sửa lại nhiều vòng. | Intern Dev (3 người), Senior Reviewer (2 người) | Mất 30 phút tự dò lại code trước mỗi PR; thống kê 5 PR gần nhất vẫn nhận trung bình 12–15 comments nhắc sửa các lỗi quy ước nội bộ (convention) vì công cụ gợi ý code viết theo kiểu mặc định chứ không theo chuẩn riêng của nhóm. |
| 3 | Lặp lại | Khi đến giờ báo cáo hằng ngày (Daily Standup) hoặc viết báo cáo thực tập cuối tuần, tôi muốn gom lại các việc mình đã làm (các commit, các lỗi đã gỡ, tài liệu đã đọc) thành bản tóm tắt ngắn gọn đúng trọng tâm kết quả, để anh Mentor nắm được tiến độ thật và góp ý kịp thời. | Intern Dev, Mentor, Quản lý thực tập | Mất 15–20 phút mỗi sáng và 45 phút chiều thứ Sáu để ngồi nhớ lại lịch sử làm việc; 3 lần trong tháng đầu báo cáo lan man khiến Mentor tưởng là đang không có đầu ra cụ thể. |
| 4 | Tốn thời gian | Khi dùng công cụ hỗ trợ sinh code (Cursor/Copilot) để viết nhanh một tính năng chạm tới nhiều file, tôi muốn kiểm tra và hiểu rõ từng nhánh logic vừa được sinh ra có làm hỏng luồng dữ liệu cũ hay không, để tự tin giải thích được code của mình khi anh Mentor hỏi. | Intern Dev, Mentor / Senior Dev | Mất 40–60 phút đọc dò lại code do công cụ sinh ra cho mỗi task; 3–4 lần/tuần; tuần trước có 2 lần bị anh Mentor hỏi "vì sao thêm điều kiện kiểm tra này?" trong PR mà tôi lúng túng không giải thích được ngay. |
| 5 | Tốn thời gian | Khi nhận một tài liệu yêu cầu (Spec) dài hoặc một ticket lớn trên hệ thống mà chưa quen hết codebase, tôi muốn tách nhỏ yêu cầu đó thành các bước thực hiện tuần tự và xác định rõ những chỗ mình chưa hiểu để hỏi ngay từ đầu, để không bị ngợp và không làm sai hướng. | Intern Dev, Mentor, BA/PM | Mất 2–3 tiếng ngồi đọc tài liệu và mở hàng chục tab code mà không biết bắt đầu từ đâu; tháng trước có 2 task vì ngại hỏi sớm nên tự làm mò mất 1.5 ngày mới phát hiện hiểu sai yêu cầu phải viết lại. |
| 6 | Tốn thời gian | Khi được anh Mentor giao tìm hiểu 2–3 thư viện hoặc giải pháp kỹ thuật mới để áp dụng vào dự án, tôi muốn biết cần so sánh theo những tiêu chí kỹ thuật nào sát với hệ thống hiện tại (độ tương thích, dung lượng, bảo trì), để không bị lạc trong hàng chục bài viết quảng cáo trên mạng. | Intern Dev, Mentor / Tech Lead | Mất 3–4 tiếng đọc tài liệu tiếng Anh cho mỗi lần tìm hiểu; 2 lần/tháng; lần trước gửi bảng tổng hợp dài 5 trang nhưng phải làm lại vì thiếu phần đánh giá rủi ro khi ghép vào kiến trúc hiện tại của nhóm. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi chạy thử tính năng mới hoặc cập nhật thư viện mà màn hình terminal/Docker bắn ra hàng trăm dòng log báo lỗi (stack trace) nối tiếp nhau, tôi muốn tách ra được dòng nào là nguyên nhân gốc ở code của mình và dòng nào chỉ là lỗi dây chuyền của thư viện, để không mất hàng giờ sửa sai chỗ. | Intern Dev, Mentor hỗ trợ | Mất 45–90 phút/lần tra cứu mỗi khi gặp lỗi build/runtime lạ; 3–4 lần/tuần; từng copy nhầm dòng log cuối cùng (hệ quả) lên mạng tìm kiếm mất hơn 1 tiếng không ra, trong khi lỗi thật nằm ở dòng cấu hình phía trên. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi tham gia buổi họp gỡ lỗi (debug) hoặc họp thiết kế kỹ thuật cùng các anh Senior, tôi muốn gom lại được đoạn log lỗi đang bàn, nguyên nhân các anh vừa chốt và các bước cụ thể giao cho tôi làm tiếp theo, để sau cuộc họp không bị sót việc hoặc hiểu sai ý. | Intern Dev, Tech Lead, các thành viên trong buổi họp | Mất 30 phút sau mỗi buổi họp để ngồi dịch lại ghi chú rời rạc và các đoạn log gửi trong khung chat; 2 buổi/tuần; tuần trước hiểu nhầm 1 yêu cầu xử lý lỗi trong cuộc họp dẫn đến phải sửa lại code mất nửa ngày. |
| 9 | Cần đọc, tổng hợp nhiều thông tin | Khi cùng một lúc vừa phải code task mới trong sprint, vừa nhận hàng chục bình luận yêu cầu sửa ở PR cũ, vừa được gọi vào kiểm tra một lỗi mới phát sinh trên nhóm chat, tôi muốn biết việc nào đang chặn (block) người khác để làm trước, để không bị quá tải và không làm trễ việc của đồng đội. | Intern Dev, các thành viên phụ thuộc vào task của Intern | Trung bình 2–3 ngày/tuần bị phân tán giữa 3 đầu việc cùng lúc; tuần trước vì mải sửa các bình luận đổi tên biến ở PR cũ mà làm chậm API đang chặn bạn Frontend, khiến bạn phải chờ cả buổi chiều. |
| 10 | Pain từ người khác | Khi thực tập sinh nhắn tin hỏi về một lỗi đang bị kẹt, anh Mentor muốn tin nhắn đó có sẵn thông báo lỗi chính xác, đoạn code liên quan và những cách thực tập sinh đã tự thử, để anh có thể chỉ hướng giải quyết ngay trong 2 phút thay vì phải hỏi vặn lại từng câu. | Mentor / Senior Dev, Intern Dev | Trung bình 4–5 lần/tuần trên nhóm chat có tin nhắn hỏi lỗi thiếu ngữ cảnh; mỗi lần như vậy hai anh em phải nhắn tin hỏi đáp qua lại 15–20 phút mới xác định được đang chạy lệnh gì, ở nhánh nào và lỗi ở dòng log nào. |
| 11 | Pain từ người khác | Khi anh Senior/Mentor nhận một Pull Request dài hàng trăm dòng từ thực tập sinh (được viết nhanh nhờ công cụ hỗ trợ sinh code), anh Mentor muốn biết ngay phần nào thực tập sinh đã tự kiểm thử kỹ và phần nào là code sinh tự động dễ sai điều kiện biên, để không phải đọc dò từng dòng từ đầu. | Senior Dev / Mentor, Intern Dev | Mentor mất 40–50 phút để duyệt 1 PR lớn của thực tập sinh; thời gian chờ duyệt PR trung bình kéo dài 15–24 tiếng vì Mentor ngại mở các PR dài vào giữa ngày. |
| 12 | Pain từ người khác | Khi bản code mới đẩy lên môi trường dùng chung (Dev/Staging) trả về lỗi `500`, các bạn làm giao diện (Frontend) và kiểm thử (QA) muốn biết ngay lỗi đó do truyền sai dữ liệu đầu vào hay do lỗi code phía server, để không phải nhắn tin chờ người viết API mở file log hàng nghìn dòng ra tra hộ. | Frontend Dev, QA, Backend Intern/Dev | 6–8 lần/tuần trong kênh chat chung có tin nhắn báo lỗi `500` kèm câu "Check log giúp mình với"; mỗi lần chờ mở server đọc log và đối chiếu thời gian mất 20–30 phút chờ đợi của cả hai phía. |
| 13 | Pain từ người khác | Khi kiểm thử viên (QA) nhận một ticket vừa được thực tập sinh chuyển sang trạng thái sẵn sàng kiểm thử, QA muốn các trường hợp cơ bản và phạm vi các màn hình bị ảnh hưởng đã được tự kiểm tra trước, để không mất công tạo phiếu báo lỗi cho những lỗi hiển nhiên ngay lần bấm đầu tiên. | QA Engineer (2 người), Intern Dev, Mentor | 4/10 ticket của thực tập sinh trong tháng qua bị QA trả về (`Reopened`) chỉ sau 5 phút kiểm thử vì lỗi thiếu kiểm tra dữ liệu rỗng (`null`) hoặc làm lệch giao diện màn hình bên cạnh; mất 30 phút/vòng chuyển trạng thái qua lại. |
| 14 | Pain từ người khác | Khi người quản lý (PM/Mentor) tạo một ticket giao việc cho thực tập sinh nhưng chỉ viết 1–2 dòng mô tả tóm tắt vì bận, thực tập sinh muốn biết rõ kết quả đầu ra mong đợi (input/output mẫu, màn hình tham chiếu, điều kiện nghiệm thu), để không phải tự đoán mò rồi làm sai. | Intern Dev, PM / BA / Mentor | Trong 10 ticket gần nhất giao cho thực tập sinh, có tới 6 ticket phần mô tả dưới 30 từ; dẫn đến phải nhắn hỏi bổ sung trung bình 3 lần/ticket hoặc làm sai phải sửa lại mất 3–4 tiếng/ticket. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Quá trình thực hiện:** Sau khi tự liệt kê 8 vấn đề từ trải nghiệm thực tập của bản thân (các ý #1, #2, #3, #4, #5, #7, #8, #9 — xoay quanh việc hòa nhập codebase, bị ngợp bởi tài liệu/log lỗi và kiểm soát code khi dùng công cụ hỗ trợ sinh code), tôi nhờ AI gợi ý thêm góc nhìn ở lăng kính **"Pain từ người khác"** khi làm việc cùng thực tập sinh.
- **Ý giữ lại và viết lại theo trải nghiệm thật:** Tôi giữ lại các ý **#6, #10, #11, #12, #13, #14** (góc nhìn của anh Mentor khi review PR dài hoặc khi nhận câu hỏi thiếu ngữ cảnh, góc nhìn của QA và bạn Frontend khi chờ check log `500` trên Staging) vì đây là những tình huống thực tế đã xảy ra trong nhóm dự án của tôi; tôi đã tự viết lại câu chữ và gắn số phút, tần suất thật của nhóm mình.
- **Ý loại bỏ và lý do:**
  1. Bỏ gợi ý *"Xây dựng trợ lý AI tự động đọc log trên server và tự sửa code đẩy lên nhánh chính"* vì đây là **solution trá hình** (nhảy vào giải pháp trước khi hiểu vấn đề) và vi phạm ranh giới an toàn hệ thống.
  2. Bỏ gợi ý *"Hệ thống AI tự động đánh giá năng lực thực tập sinh hằng tuần"* vì phạm vi quá rộng, thiên về quản trị nhân sự và không có quy trình thao tác cụ thể để đo baseline trong một buổi lab.


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | **#1 — Tìm hiểu luồng dữ liệu (file, hàm, bảng DB) và quy tắc ngầm khi mới hòa nhập dự án** | Actor rõ (Intern & Mentor), lặp lại ở mọi task trong tháng đầu, tốn 1–1.5h/ngày của Intern và làm ngắt quãng Mentor 4–5 lần/tuần | Làm sao giữ cho sơ đồ/bản tóm tắt luồng dữ liệu không bị lỗi thời khi các anh chị trong nhóm sửa code liên tục? |
| 2 | **#6 — Tìm hiểu và so sánh 2–3 thư viện/giải pháp kỹ thuật mới theo đúng kiến trúc dự án** | Quy trình rõ ràng, mỗi lần làm mất 3–4 tiếng mà dễ bị chệch trọng tâm phải làm lại; rất hợp để so sánh giữa Template (`No AI`) và `Workflow` | Làm sao kiểm chứng được các giới hạn ngầm (như xung đột phiên bản hoặc dung lượng thực tế) mà không cần cài thử cả 3 thư viện vào dự án? |
| 3 | **#9 — Xác định thứ tự ưu tiên việc nào đang chặn (block) đồng đội khi bị dồn 3 đầu việc cùng lúc** | Nỗi đau quá tải (overwhelmed) rất thật của Intern mỗi tuần, gây ảnh hưởng trực tiếp tới đồng đội (như bạn Frontend phải chờ API) | Liệu bài toán này chỉ cần một quy tắc phân loại cố định (`No AI` / `Rule`) với Mentor là đã giải quyết xong mà không cần tới AI? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi mới vào nhóm dự án và được giao sửa một luồng nghiệp vụ có sẵn, tôi muốn biết một thao tác trên màn hình sẽ đi qua những file, hàm và bảng dữ liệu nào kèm các quy tắc ngầm của nhóm, để hòa nhập nhanh mà không phải hỏi anh Mentor những câu cơ bản lặp đi lặp lại. |
| Actor | Thực tập sinh (Intern Dev) mới vào dự án (người thực hiện task) và Mentor / Senior Dev (người hướng dẫn). |
| Thời điểm / bối cảnh | Trong 3–4 tuần đầu thực tập, mỗi khi Intern nhận một ticket yêu cầu chỉnh sửa hoặc thêm trường dữ liệu vào một tính năng đã có sẵn. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc mô tả ticket và mở màn hình giao diện tương ứng · 2. Tìm từ khóa trên IDE để dò từ giao diện xuống API route · 3. Mở lần lượt 10–15 file (Controller, Service, Repository, Model) để lần theo đường đi của dữ liệu · 4. Đọc lịch sử commit/PR cũ xem có quy tắc ngầm nào của nhóm không · 5. Bị rối giữa các hàm gọi chéo nên nhắn tin hỏi anh Mentor · 6. Chờ anh Mentor rảnh chỉ lại luồng rồi mới bắt đầu sửa code. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 3 & Bước 4 (Lần mò đường đi của dữ liệu qua 10–15 file và tìm quy tắc ngầm của nhóm):** Mất **50 phút/task** (35' mở đọc từng file gọi chéo nhau + 15' lục tìm quy ước cũ mà vẫn sợ sót). |
| Impact (nếu không giải thì sao) | Intern mất 60–90 phút mò mẫm cho mỗi task mới trong 3 tuần đầu; Mentor bị ngắt quãng công việc 4–5 lần/tuần (mỗi lần 15–20 phút) để giải thích lại luồng dữ liệu cơ bản; Intern dễ sửa thiếu file hoặc vi phạm quy tắc ngầm của dự án. |
| Success metric (baseline → target) | (1) Thời gian Intern xác định xong danh sách các file, hàm, bảng DB cần chạm tới trước khi code giảm từ **75 phút xuống dưới 20 phút/task**; (2) Số lần phải nhắn hỏi Mentor về luồng đi của dữ liệu cơ bản giảm từ **4–5 lần/tuần xuống ≤ 1 lần/tuần**. |
| Phương án không dùng AI | Bổ sung tài liệu `ARCHITECTURE_MAP.md` vẽ sơ đồ luồng chính + áp dụng mẫu **"Xác nhận luồng 4 dòng"** (Intern ghi danh sách file dự kiến sửa gửi Mentor duyệt nhanh trong 2 phút). *Hạn chế:* Tài liệu tĩnh chỉ vẽ được 2–3 luồng lớn, không bao phủ được từng API cụ thể trong hơn 100 thư mục. |
| Giả thuyết về AI (nếu có) | Kết hợp `Rule` (cây thư mục + tìm kiếm theo tên route/hàm) và `Workflow` (AI đọc chuỗi file từ route đến model kèm file quy ước `CONVENTIONS.md` để tóm tắt sơ đồ luồng dữ liệu và nhắc các quy tắc ngầm liên quan); Intern kiểm tra lại trên IDE rồi gửi Mentor xác nhận nhanh. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~75 phút/lần tìm hiểu luồng cho task mới

[1. Đọc ticket & mở màn hình giao diện: 5']
  → [2. Tìm từ khóa từ giao diện xuống API route: 10']
  → [3. Mở 10-15 file lần theo luồng Controller → Service → DB: 35'] ← BOTTLENECK 1
  → [4. Lục tìm quy tắc ngầm trong code cũ / PR cũ: 15']             ← BOTTLENECK 2
  → [5. Bị rối, nhắn hỏi & chờ Mentor giải thích lại luồng: 10']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi được anh Mentor giao tìm hiểu 2–3 thư viện hoặc giải pháp kỹ thuật mới để áp dụng vào dự án, tôi muốn biết cần so sánh theo những tiêu chí kỹ thuật nào sát với hệ thống hiện tại (độ tương thích, dung lượng, bảo trì), để không bị lạc trong hàng chục bài viết quảng cáo trên mạng. |
| Actor | Thực tập sinh (Intern Dev — người được giao research) và Mentor / Tech Lead (người duyệt chọn thư viện). |
| Thời điểm / bối cảnh | Khi nhóm chuẩn bị làm một tính năng mới (như xuất PDF, xử lý hàng đợi, xác thực) và Mentor giao cho Intern tìm hiểu 2–3 thư viện ứng viên để báo cáo trước buổi họp kỹ thuật. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận yêu cầu tìm hiểu từ Mentor (chỉ có tên bài toán hoặc tên 2–3 thư viện) · 2. Lên Google đọc hàng chục bài blog so sánh và trang chủ của từng thư viện · 3. Copy các tính năng nổi bật vào một file tài liệu dài · 4. Tự viết bảng so sánh theo cảm tính (vì chưa biết tiêu chí nào quan trọng với dự án) · 5. Gửi báo cáo cho Mentor duyệt · 6. Bị Mentor yêu cầu làm lại vì thiếu đánh giá độ tương thích với phiên bản framework hiện tại của nhóm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 2 & Bước 4 (Đọc hàng chục trang tài liệu tiếng Anh và lọc ra các giới hạn kỹ thuật sát với hệ thống hiện tại):** Mất **135 phút/lần** (90' đọc lan man các bài blog quảng cáo + 45' tổng hợp mà vẫn sót tiêu chí cốt lõi). |
| Impact (nếu không giải thì sao) | Tốn 3–4 tiếng (180–240 phút) cho mỗi bài tìm hiểu; 1/2 lần báo cáo trong tháng qua phải làm lại vòng 2 (mất thêm 90 phút) vì chỉ chép lại tính năng quảng cáo mà quên kiểm tra xung đột phiên bản và giấy phép (license). |
| Success metric (baseline → target) | (1) Thời gian hoàn thành 1 bản báo cáo so sánh thư viện giảm từ **210 phút xuống dưới 60 phút/lần**; (2) Bản báo cáo vượt qua đủ **100% (6/6) tiêu chí bắt buộc của nhóm** ngay từ vòng duyệt đầu tiên mà không phải làm lại. |
| Phương án không dùng AI | Tạo **Template đánh giá thư viện cố định 6 tiêu chí** (1. Phiên bản Node/Python tương thích; 2. Lần cập nhật gần nhất & số issue mở; 3. Kích thước gói; 4. License; 5. Chi phí/giới hạn; 6. Rủi ro khi tích hợp) kèm công cụ `npmtrends`/`bundlephobia`. |
| Giả thuyết về AI (nếu có) | Dùng `Rule`/công cụ tra cứu lấy số liệu cứng từ GitHub/`package.json` của dự án → Dùng `Workflow` (AI đối chiếu tài liệu chính thức của 2–3 thư viện với cấu hình `package.json`/`requirements.txt` hiện tại của nhóm theo đúng 6 tiêu chí trong Template) → Intern kiểm tra lại link nguồn trước khi gửi Mentor. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~210 phút/lần tìm hiểu (chưa tính 90' làm lại nếu lạc đề)

[1. Nhận đề bài tìm hiểu 2-3 thư viện từ Mentor: 10']
  → [2. Đọc 15-20 bài blog & docs tiếng Anh trên mạng: 90']       ← BOTTLENECK 1
  → [3. Ghi chép tính năng vào file nháp (dài nhưng thiếu ý): 30']
  → [4. Lập bảng so sánh nhưng thiếu tiêu chí tương thích dự án: 45'] ← BOTTLENECK 2
  → [5. Mentor đọc, chỉ ra chỗ thiếu & yêu cầu về tra cứu lại: 35']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cùng một lúc vừa phải code task mới trong sprint, vừa nhận hàng chục bình luận yêu cầu sửa ở PR cũ, vừa được gọi vào kiểm tra một lỗi mới phát sinh trên nhóm chat, tôi muốn biết việc nào đang chặn (block) người khác để làm trước, để không bị quá tải và không làm trễ việc của đồng đội. |
| Actor | Thực tập sinh (Intern Dev) và các thành viên phụ thuộc vào đầu ra của Intern (Frontend Dev, QA, Mentor). |
| Thời điểm / bối cảnh | Giữa hoặc cuối Sprint (2–3 ngày/tuần), khi thông báo từ GitHub PR, Jira ticket và tin nhắn Slack/Zalo dồn đến cùng một buổi chiều. |
| Quy trình hiện tại (3–7 bước) | 1. Đang viết code dở cho task mới trong sprint thì thấy thông báo có 12 bình luận trên PR cũ và tin nhắn nhờ kiểm tra lỗi trên nhóm chat · 2. Mở đọc lần lượt từng bình luận PR và tin nhắn chat · 3. Bị cuống nên chọn làm việc nào trông "dễ và nhanh" trước (như ngồi sửa tên biến ở PR cũ) · 4. Chuyển qua chuyển lại giữa 3 nhánh git (context switching) làm rối code · 5. Cuối buổi chiều bạn Frontend nhắn hỏi mới nhớ ra API bạn ấy đang chờ vẫn chưa làm xong. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 2 & Bước 3 (Đọc thông báo rời rạc ở 3 nơi và tự phán đoán sai thứ tự ưu tiên do không nhìn thấy ai đang bị chặn):** Mất **35 phút** lúng túng chuyển ngữ cảnh và dẫn đến **2–3 tiếng** làm việc ngược thứ tự ưu tiên. |
| Impact (nếu không giải thì sao) | 2–3 ngày/tuần Intern rơi vào trạng thái quá tải, hiệu suất giảm do đổi nhánh git liên tục; tuần trước làm bạn Frontend phải ngồi chờ API mất 3 tiếng buổi chiều vì Intern mải sửa các bình luận format nhỏ ở PR cũ. |
| Success metric (baseline → target) | (1) Thời gian phân loại và chốt thứ tự làm việc khi có nhiều việc dồn cùng lúc giảm từ **35 phút lúng túng xuống dưới 5 phút**; (2) Số lần làm chậm việc đang chặn (blocker) của đồng đội trong tuần giảm từ **2 lần/tuần xuống 0 lần/tuần**. |
| Phương án không dùng AI | Áp dụng **Ma trận ưu tiên 3 mức cố định (`No AI` / `Rule`)**: *(Ưu tiên 1: Lỗi hoặc API đang chặn trực tiếp người khác làm việc → Ưu tiên 2: Sửa lỗi logic trên PR để kịp merge → Ưu tiên 3: Sửa góp ý đặt tên/format và code task mới chưa gấp)*, kèm 1 tin nhắn 3 dòng báo thứ tự ưu tiên trên Slack cho Mentor/nhóm biết. |
| Giả thuyết về AI (nếu có) | Thực chất bài toán này nguyên nhân gốc là thiếu quy tắc phân loại ưu tiên và thiếu giao tiếp trạng thái với nhóm; giải pháp `No AI` (Quy tắc 3 mức + nhắn xác nhận 1 câu với Mentor) hoặc `Rule` (gắn nhãn `[BLOCKER]` trên kênh chat/Jira) đã giải quyết được 80–90% mà chưa cần dùng tới AI. |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 35 phút rối loạn chuyển ngữ cảnh + làm đồng đội chờ 3 tiếng

[1. Đang code task mới thì nổ thông báo từ PR cũ & nhóm chat: 5']
  → [2. Mở đọc 12 comments PR + lội tin nhắn chat ở nhiều tab: 20'] ← BOTTLENECK 1
  → [3. Chọn làm việc dễ trước (sửa tên biến PR) vì không rõ cái nào chặn ai: 15'] ← BOTTLENECK 2
  → [4. Ngồi sửa việc phụ + đổi nhánh git qua lại: 120']
  → [5. Bạn Frontend nhắn giục mới phát hiện làm trễ việc đang chặn đồng đội: 10']
```

### Card muốn pitch nhất

- **Card số:** **Problem Card #1** (*Tìm hiểu luồng dữ liệu file, hàm, bảng DB và quy tắc ngầm khi mới hòa nhập dự án*).
- **Vì sao:** Đây là nỗi đau lặp lại hàng ngày với bất kỳ thực tập sinh hoặc thành viên mới nào khi đứng trước một codebase lớn; có quy trình 5 bước rất rõ ràng; vừa giải quyết được sự quá tải của Intern vừa giảm thời gian bị ngắt quãng của Mentor; đồng thời rất dễ so sánh cả 4 mức can thiệp từ `No AI` (Tài liệu sơ đồ + mẫu xác nhận), `Rule` (Lọc cây thư mục/route) đến `Workflow` (Tóm tắt luồng code kèm quy ước ngầm).
- **Câu hỏi muốn nhóm phản biện:** *"Giữa việc dùng công cụ hỗ trợ tóm tắt luồng code (`Workflow`) và việc bắt buộc Intern tự vẽ luồng ra giấy 4 dòng rồi gửi Mentor duyệt trong 2 phút (`No AI`), cách nào thực sự giúp Intern nhớ kiến trúc dự án lâu hơn mà không bị phụ thuộc vào công cụ?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| **Ở Card #1 (#1):** Nếu công cụ vẽ sẵn toàn bộ luồng code và chỉ sẵn chỗ cần sửa, Intern sẽ copy-paste theo máy móc mà không thực sự hiểu kiến trúc dự án, dẫn đến khi Mentor hỏi lại vẫn không trả lời được. | Đồng ý | Sửa lại giả thuyết và thêm **Boundary**: Bước hỗ trợ chỉ chỉ ra sơ đồ các file/hàm liên quan và nhắc quy tắc ngầm; Intern bắt buộc phải tự mở IDE kiểm tra lại và tự viết 3 dòng "Kế hoạch sửa" gửi Mentor xác nhận (HITL). |
| **Ở Card #1 (#1):** Success metric ban đầu chỉ ghi "Intern hòa nhập nhanh hơn và đỡ ngại hỏi" — đây là cảm nhận định tính, không đo được trong buổi lab. | Đồng ý | Đổi sang 2 chỉ số đo được cụ thể: *"Thời gian xác định danh sách file/bảng cần sửa giảm từ 75 phút xuống dưới 20 phút/task"* và *"Số lần hỏi lại Mentor về luồng dữ liệu cơ bản giảm từ 4–5 lần/tuần xuống ≤ 1 lần/tuần"*. |
| **Ở Card #2 (#6):** AI gợi ý nên làm một Agent tự động lên mạng tìm thư viện, tự tải về cài vào dự án và tự chạy benchmark. | Không đồng ý | Bác bỏ vì việc tự ý tải và chạy gói thư viện lạ có rủi ro bảo mật (supply-chain attack) và quá phức tạp. Giữ ở mức **Workflow**: đối chiếu tài liệu chính thức của các thư viện ứng viên với file `package.json` hiện tại theo đúng **Template 6 tiêu chí cố định**. |
| **Ở Card #3 (#9):** Khi đóng vai PM hoài nghi, AI chỉ ra tôi đang cố nghĩ cách dùng AI đọc tin nhắn và PR để sắp xếp việc, trong khi nguyên nhân gốc chỉ là Intern chưa có quy tắc phân biệt việc nào là `Blocker` (đang chặn người khác). | Đồng ý hoàn toàn | Đổi "Cảm nhận nhanh" của Card #3 từ `Workflow` về **`No AI`** (áp dụng Quy tắc ưu tiên 3 mức cố định + gắn nhãn `[BLOCKER]` và hỏi Mentor 1 câu xác nhận trong 2 phút là đã giải quyết triệt để). |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
