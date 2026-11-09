# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: ABC100
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Thành viên nhóm học tập/dự án mất 8–15 phút mỗi lần lục lại chat Zalo/Discord (4–6 lần/tuần) để biết nhóm đã chốt gì, ai đang làm gì và hạn khi nào.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phan Sỹ Hùng | Khi cuối buổi lab phải điền bảng "Dùng AI", tôi muốn nhớ chính xác đã dùng AI ở đâu, AI sai gì, tôi sửa gì, để ghi đúng sự thật | Học viên AI20k (cả lớp) | Lục lịch sử chat và nhớ lại "AI sai gì / tôi sửa gì" trong 15' cuối buổi | [cần điền sau pitch] |
| 2 | Phan Sỹ Hùng | Khi điền một mục báo cáo lab, tôi muốn biết mọi yêu cầu của mục đó, để không mất điểm vì thiếu | Học viên AI20k | Gom yêu cầu của 1 mục từ 8 file hướng dẫn (~15.900 từ) | [cần điền sau pitch] |
| 3 | Phan Sỹ Hùng | Khi làm chung một repo, mỗi thành viên muốn biết file nào của mình và commit thế nào, để không ghi đè/conflict | Thành viên nhóm 3–4 người | Xử lý conflict khi nhiều người cùng sửa `group_report.md` | [cần điền sau pitch] |
| 4 | Dương Thị Huệ | Khi bắt đầu một bài toán nghiên cứu mới, tôi muốn tìm được tài liệu chứa thuật toán phù hợp, để tiết kiệm thời gian nghiên cứu | Sinh viên nghiên cứu, học viên cao học | Bước 4–6: đọc abstract → methodology → so sánh thuật toán với yêu cầu bài toán (chưa đo phút) | Làm thế nào để xác định một bài báo thực sự chứa thuật toán phù hợp với bài toán nghiên cứu, thay vì chỉ có abstract hoặc tiêu đề tương đồng? ([cần điền: ai hỏi]) |
| 5 | Dương Thị Huệ | Khi triển khai thuật toán từ bài báo bằng MATLAB/Python, tôi muốn chuyển công thức thành code nhanh và đúng, để giảm thời gian lập trình và sửa lỗi | Sinh viên kỹ thuật, người làm nghiên cứu | Bước 2–5: xác định biến, điều kiện khởi tạo, chuyển công thức thành code (chưa đo phút) | Nếu AI chuyển công thức từ paper thành code nhưng hiểu sai điều kiện biên, biến hoặc bước khởi tạo, ai sẽ kiểm chứng tính chính xác của code? ([cần điền: ai hỏi]) |
| 6 | Dương Thị Huệ | Khi tìm hiểu một chủ đề nghiên cứu mới, tôi muốn tổng hợp và so sánh nhiều bài báo, để chọn hướng nghiên cứu phù hợp | Sinh viên làm khóa luận, học viên cao học | Bước 3–6: đọc, trích xuất, phân loại thông tin trình bày không đồng nhất (chưa đo phút) | Việc tổng hợp và so sánh nhiều paper có thực sự giúp chọn hướng nghiên cứu tốt hơn, hay có nguy cơ khiến người nghiên cứu phụ thuộc vào nhận định của AI và bỏ sót thông tin quan trọng? ([cần điền: ai hỏi]) |
| 7 | Lê Văn Hoàng | Khi tới tối Chủ nhật trước buổi review, tôi muốn gom trạng thái việc từ GitHub, Sheets và Zalo về một chỗ, để gửi cập nhật tiến độ + rủi ro cho Mentor trước 21h | Nhóm trưởng, 4 thành viên, Mentor | Bước 3 + 5: lướt Zalo tìm blocker (15') + viết nhận định tiến độ/rủi ro (25'); tổng 65–75'/tuần, 2/4 tuần gửi trễ | Tại sao nhóm trưởng phải tổng hợp thông tin từ GitHub, Google Sheets và Zalo thủ công, trong khi các thành viên có thể chủ động cập nhật tiến độ theo một format thống nhất? ([cần điền: ai hỏi]) |
| 8 | Lê Văn Hoàng | Khi chuẩn bị nộp bài lab nhóm lúc 22h30, tôi muốn đối chiếu mọi file báo cáo với Rubric, Checkpoints, Submission, để phát hiện mục thiếu/sai tên trước khi nộp | Người rà soát cuối + cả nhóm 4 người | Bước 4: đọc dò từng mục đối chiếu điều kiện Rubric (20'/35' tổng) | Nếu Rubric, Checkpoints và Submission có yêu cầu mâu thuẫn hoặc được cập nhật ở các thời điểm khác nhau, hệ thống sẽ xác định tài liệu nào là nguồn thông tin chính xác nhất như thế nào? ([cần điền: ai hỏi]) |
| 9 | Lê Văn Hoàng | Khi vừa kết thúc buổi họp nhóm 60', tôi muốn có danh sách quyết định đã chốt, người phụ trách và hạn, để không ai hiểu lệch hay làm trùng | Người ghi biên bản, 4 thành viên | Bước 2–3: đọc lại ghi chú thô + dò đoạn tranh luận xem chốt ý nào (18'/28' mỗi buổi, 2–3 buổi/tuần) | Làm thế nào để phân biệt một ý kiến được đề xuất trong cuộc họp với một quyết định thực sự đã được cả nhóm thống nhất? ([cần điền: ai hỏi]) |
| 10 | Chử Văn Hiệp | Khi bắt đầu họp nhóm hoặc cần tìm quyết định cũ trên Discord, tôi muốn biết quyết định + task + người phụ trách trong dưới 2', để không phải cuộn tin nhắn và hỏi lại | Thành viên nhóm dự án/lab | Bước 3–4: cuộn và đọc lại tin nhắn cũ (8–12'/lần, 4–6 lần/tuần) | Nếu Discord đã có chức năng search, tại sao người dùng vẫn mất 8–12 phút để tìm quyết định cũ? Vấn đề nằm ở công cụ tìm kiếm hay cách tổ chức thông tin? ([cần điền: ai hỏi]) |
| 11 | Chử Văn Hiệp | Khi viết phần "Kết quả & Thảo luận" của báo cáo lab, tôi muốn đi từ dữ liệu thí nghiệm/code đến đoạn nhận định nhanh hơn, để không nhìn trang trắng 30–40' | Người viết chính báo cáo lab | Bước 3: từ số liệu thô viết thành narrative (25–30'/lần, 1–2 lần/tuần) | Làm thế nào để đảm bảo phần nhận định do AI hỗ trợ viết thực sự phản ánh đúng dữ liệu thí nghiệm, thay vì tạo ra những kết luận nghe hợp lý nhưng không có bằng chứng? ([cần điền: ai hỏi]) |
| 12 | Chử Văn Hiệp | Khi ôn thi cuối kỳ từ slide, ghi chú Discord và PDF, tôi muốn có tài liệu ôn theo chủ đề, để không mất 2–3 giờ/môn chỉ để gom | Sinh viên ôn 6–8 môn | Bước 4: copy + tổng hợp từ nhiều nguồn (60–90'/môn) | Tài liệu ôn tập được AI tổng hợp từ slide, Discord và PDF sẽ đảm bảo không bỏ sót kiến thức quan trọng hoặc đưa vào thông tin sai lệch như thế nào? ([cần điền: ai hỏi]) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #7, #9, #10, (#3) | Thông tin "ai đang làm gì, nhóm đã chốt gì" nằm rải rác trong chat (Zalo/Discord), GitHub, Sheets; mất thời gian lục lại và hỏi lại nhau. 3/4 thành viên có card thuộc cluster này |
| B | #1, #2, #8 | Không chắc bài lab đã đáp ứng đủ yêu cầu (rubric, cấu trúc, tên file, bảng "Dùng AI") vì yêu cầu nằm ở nhiều file; dồn việc kiểm tra vào cuối buổi/trước deadline |
| C | #4, #6, #12 | Phải đọc nhiều tài liệu dài (bài báo, slide, PDF) để tìm, trích và so sánh đúng nội dung cần |
| D | #5, #11 | Đã hiểu nội dung nhưng mất lâu để chuyển thành sản phẩm (code, đoạn văn nhận định) |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian học viên và nhóm học tập mất cho việc gom, tìm lại và
         đối chiếu thông tin rời rạc, để hoàn thành bài đúng hạn và đúng yêu cầu
├── Opportunity A: Không biết nhóm đã chốt gì, ai đang làm gì, ai đang bị kẹt
│                  mà không phải lục lại chat và hỏi lại (#7, #9, #10, #3)
├── Opportunity B: Không chắc bài nộp đã đủ yêu cầu vì yêu cầu nằm rải rác
│                  ở nhiều file (#1, #2, #8)
├── Opportunity C: Mất nhiều giờ đọc nhiều tài liệu dài mới tìm và so sánh
│                  được đúng nội dung cần (#4, #6, #12)
└── Opportunity D: Mất lâu để chuyển từ hiểu nội dung sang sản phẩm viết/code
                   (#5, #11)
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~"Bot tóm tắt channel Discord (SummaryBot, Reduck…)"~~ → là giải pháp cho Opportunity A, không phải pain.
- ~~"AI soạn nháp phần Kết quả & Thảo luận từ bảng số liệu"~~ → giải pháp cho Opportunity D.
- ~~"Upload slide + PDF để AI tạo study guide và quiz"~~ → giải pháp cho Opportunity C.
- ~~"AI tìm tài liệu theo mô tả bài toán và trích bước thuật toán"~~ → giải pháp cho Opportunity C.
- ~~"Script kiểm tra tên file/số từ/link + đối chiếu Rubric"~~ → giải pháp cho Opportunity B.
- ~~"Form báo cáo cố định `[XONG]/[ĐANG LÀM]/[KẸT]` trên Zalo"~~ → phương án No AI cho Opportunity A, giữ lại để so sánh ở CP6, không đưa vào cây.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| A — Quyết định & trạng thái việc nhóm thất lạc trong chat (#9, #10, gộp #7) | 4 | 4 | 4 | 4 | 4 | 5 | 5 | 30 |
| B — Đối chiếu bài lab với yêu cầu trước khi nộp (#2, #8, #1) | 5 | 4 | 3 | 4 | 5 | 4 | 5 | 30 |
| #7 — Báo cáo tiến độ & rủi ro tuần (tách riêng) | 5 | 5 | 5 | 5 | 4 | 5 | 4 | 33 |

Ghi chú chấm:
- **A:** bằng chứng từ 2 người độc lập — Hoàng đếm 6 lần hỏi lại trong Zalo tuần qua (10–15'/lần), Hiệp đo 8–12'/lần, 4–6 lần/tuần. Phương án No AI rõ (pin, channel `#decisions`, chốt việc 5' cuối họp) nên so sánh 4 mức tốt.
- **B:** bằng chứng mới có 1 lần đo 35' (Hoàng) và 10'/lab (Hiệp); card #1, #2 của Hùng chưa có số phút. Rủi ro: checklist tĩnh có thể đã đủ.
- **#7:** bằng chứng mạnh nhất (bấm giờ 3 tuần: 65, 75, 70'), nhưng **gần như trùng với bài mẫu** trong `docs/02-deliverable-example.md` (báo cáo tuần gom số liệu từ nhiều nguồn).

**Candidate được chọn:** **A — Quyết định & trạng thái việc nhóm thất lạc trong chat** (gộp #9, #10 và phần "lướt Zalo tìm blocker" của #7). Khi cần biết nhóm đã chốt gì, ai làm gì, hạn khi nào, thành viên phải cuộn lại hàng trăm tin nhắn Zalo/Discord hoặc hỏi lại nhóm.

**Vì sao chọn:** 3/4 thành viên độc lập đưa ra card thuộc cluster này nên pain lặp lại ở nhiều người; đã có số liệu đếm từ lịch sử chat (Hoàng: 6 lần hỏi lại/tuần, 10–15'/lần; Hiệp: 8–12'/lần, 4–6 lần/tuần); dễ phỏng vấn nhóm khác ở CP4 vì nhóm nào cũng dùng Zalo/Discord; có phương án No AI rõ để trả lời "vì sao không chọn mức đơn giản hơn".

**Vì sao loại các candidate còn lại:**
- **#7 (báo cáo tuần):** điểm cao nhất nhưng trùng hướng với bài mẫu, khó chứng minh nhóm tự đi qua quy trình discovery; phần "lướt Zalo tìm blocker" (15') vẫn được giữ trong cluster A.
- **B (đối chiếu yêu cầu lab):** bằng chứng còn mỏng và có thể giải gần hết bằng checklist (No AI); cũng gần với ví dụ trong worksheet.
- **C, D (đọc tài liệu nghiên cứu; chuyển sang code/văn bản):** actor và domain khác nhau giữa các thành viên (nghiên cứu kỹ thuật vs ôn thi), card #4–#6 chưa có số phút đo được.

**Xử lý bất đồng (nếu có):** [cần điền trong buổi]

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Các thành viên ở những nhóm học tập/dự án khác cũng mất từ 8–15 phút/lần (nhiều lần/tuần) để cuộn lại chat Zalo/Discord tìm quyết định đã chốt và phân công việc. | Value | 5 | 2 | ✅ Kiểm chứng ngay (Phỏng vấn & Poll) |
| 2 | Bước tốn thời gian nhất là **đọc dò đoạn hội thoại dài để phân biệt ý kiến đang bàn với quyết định chốt cuối cùng**, chứ không phải việc nhớ tên kênh chat. | Value | 5 | 2 | ✅ Kiểm chứng ngay (Phỏng vấn) |
| 3 | Phương án không dùng AI (ghim tin nhắn Pinned Message hoặc lập kênh `#decisions` riêng) chưa giải quyết triệt để vì thành viên thường quên ghim hoặc bàn việc xen lẫn trong luồng chat chung. | Value / Usability | 5 | 1 | ✅ Kiểm chứng ngay (Phỏng vấn) |
| 4 | Nhóm có thể lấy được nội dung đoạn thảo luận từ Zalo/Discord để đưa vào công cụ tóm tắt mà không bị chặn bởi quyền Admin server hay giới hạn kỹ thuật của nền tảng. | Feasibility | 5 | 2 | ✅ Kiểm chứng ngay (Research kỹ thuật) |
| 5 | Thành viên chấp nhận đọc bản tóm tắt có trích dẫn tin nhắn gốc và người ghi chép sẵn sàng dành 2 phút kiểm tra lại bản nháp trước khi ghim. | Usability | 4 | 3 | Kiểm chứng qua phỏng vấn & pilot |
| 6 | Các thành viên trong nhóm đồng ý đưa nội dung thảo luận công việc (không chứa thông tin nhạy cảm/mật khẩu) vào công cụ AI hỗ trợ. | Viability | 4 | 3 | Hỏi trực tiếp trong phỏng vấn |

**Giả định nhóm kiểm chứng trong buổi này:** Tập trung kiểm chứng trước 4 giả định ở góc **"Quan trọng cao (5) nhưng Bằng chứng còn thấp (1–2)"** là **Giả định #1, #2, #3** (qua phỏng vấn trực tiếp theo *The Mom Test* với học viên các nhóm khác) và **Giả định #4** (qua Research công cụ & giới hạn API thực tế của Discord/Zalo).

---

### 3.2. Kiểm chứng

**Cách đã dùng:** Khảo sát thực tế bằng bảng hỏi cấu trúc (Google Forms gồm 11 câu hỏi `Q1`–`Q11` thiết kế theo nguyên tắc *The Mom Test* — chỉ hỏi về hành vi thật đã xảy ra trong những ngày đầu Khóa AI thực chiến và 1 tháng qua, không hỏi câu dẫn dắt/giả định) thu được **9 phản hồi thực tế (`HV01`–`HV09`)** từ các học viên trong khóa, kết hợp phỏng vấn nhanh trực tiếp tại lớp với học viên để lại đăng ký trao đổi thêm ở `Q11` (`HV06`) và đối chiếu log Zalo/Discord + lịch sử commit GitHub của nhóm ABC100.
- **Link Google Sheets dữ liệu thật:** [Google Sheets — Dữ liệu khảo sát CP4 (`N = 9`)](https://docs.google.com/spreadsheets/d/1UA0i4ZOfev5-8-MbpuRXZajs50KR8kp0O6rZIpSSzCY/edit?resourcekey=&gid=1731896032#gid=1731896032)
- **Bản sao lưu trong repo:** [`report/assets/cp4-survey-and-interviews.md`](../assets/cp4-survey-and-interviews.md) và [`report/assets/cp4-survey-and-interviews.xlsx`](../assets/cp4-survey-and-interviews.xlsx).

**Bộ 11 câu hỏi khảo sát thực tế nhóm đã dùng (tuân thủ The Mom Test):**
- **Q1–Q2 (Bối cảnh thật):** *"Bạn đang làm việc nhóm với bao nhiêu người?"* & *"Nhóm bạn trao đổi công việc chủ yếu qua kênh nào?"*
- **Q3–Q6 (Tần suất, thông tin thất lạc, thời gian mất & workaround lần gần nhất):** *"Trong những ngày bắt đầu Khóa AI thực chiến, bạn đã mấy lần phải tìm lại hoặc hỏi lại 'nhóm đã chốt gì / ai làm phần nào / hạn khi nào'?"*, *"Lần gần nhất, bạn đã cần tìm lại thông tin gì?"*, *"Mất khoảng bao lâu mới có được câu trả lời?"*, *"Bạn đã làm gì để có câu trả lời?"*
- **Q7–Q9 (Hệ quả thực tế & giới hạn của các cách đã thử):** *"Trong 1 tháng qua, có lần nào vì không tìm lại được thông tin mà bạn hoặc nhóm làm trùng, làm sai hoặc trễ việc không?"*, *"Nhóm bạn đã từng thử cách nào để đỡ phải tìm lại?"*, *"Cách đó hiện nhóm bạn còn dùng đều không?"*
- **Q10–Q11 (Mức độ phiền toái 1–5 & Sẵn lòng phỏng vấn sâu 5 phút):** *"Việc phải tìm lại thông tin đã chốt trong chat nhóm phiền đến mức nào (1–5)?"* & *"Bạn có sẵn lòng nói chuyện thêm 5 phút về chuyện này không?"*

#### Case Snapshot #1 — HV06 (Nhóm 4–5 người, sẵn lòng trao đổi thêm 5 phút ở `Q11 = Có`)

| Trường | Nội dung (Dữ liệu thật lúc `09/11/2026 12:08:25` + trao đổi trực tiếp 5 phút) |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên làm việc trong nhóm **4–5 người** (và nhóm 2–3 người), trao đổi qua **Zalo, Slack / Teams** (`HV06` — chọn `Q11 = Có`) |
| Dữ liệu hành vi từ khảo sát & chia sẻ | Chỉ trong những ngày đầu Khóa AI thực chiến đã phải tìm/hỏi lại **3–5 lần** cho cả 4 loại thông tin: **Quyết định/phương án nhóm đã chốt, Ai phụ trách phần việc nào, Deadline/mốc thời gian, Link tài liệu/file** (mức độ phiền **4/5**). |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi làm bài tập nhóm trong khóa, dù nhóm đã có biên bản và bảng phân công chung, nhưng các thay đổi nhỏ và link tài liệu mới phát sinh liên tục trên Zalo khiến bạn vẫn phải lội lại chat để tìm. |
| Hiện đang xử lý bằng cách nào (workaround)? | Kết hợp 3 thao tác: **Cuộn lại lịch sử chat + Mở file biên bản / bảng phân công + Hỏi lại trong nhóm hoặc nhắn riêng một người** (`Q6`). Đã áp dụng: **Ghim (pin) tin nhắn quan trọng, Ghi biên bản sau mỗi buổi họp, Bảng phân công chung (Sheets, Notion, Trello…)** (`Q8`). |
| Mất bao lâu, bao lần? | Mất **5–10 phút/lần**, **3–5 lần** chỉ tính trong những ngày đầu Khóa AI thực chiến. |
| Insight / opportunity rút ra | **Độ lệch giữa cảm nhận và thực tế (The Mom Test):** Dù ở `Q9` bạn đánh giá các công cụ hiện tại là *"Còn dùng đều, giải quyết được gần hết"*, nhưng hành vi thực tế ở `Q3, Q5, Q6` cho thấy bạn vẫn mất **5–10 phút/lần (3–5 lần)** để cuộn chat và hỏi lại vì các chốt việc nhanh trên Zalo không được đồng bộ ngay vào bảng phân công. |

#### Case Snapshot #2 — HV03 (Trường hợp mất thời gian nặng nhất: `Trên 20 phút / không tìm ra`)

| Trường | Nội dung (Dữ liệu thật lúc `09/11/2026 12:06:44`) |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên làm việc nhóm (**2–3 người, 6 người trở lên**), trao đổi qua **Zalo, Messenger** (`HV03`) |
| Dữ liệu hành vi từ khảo sát | Phải tìm/hỏi lại **Trên 5 lần** từ đầu khóa; xác nhận **Có bị làm trùng, làm sai hoặc trễ việc trong 1 tháng qua (`Q7 = Có`)** do không tìm lại được thông tin; chấm mức độ phiền **4/5**. |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Cần tìm lại đồng thời **Quyết định/phương án nhóm đã chốt, Ai phụ trách phần việc nào, Deadline/mốc thời gian và Link tài liệu/file** (`Q4`), nhưng sau khi thử mọi cách tìm kiếm trên Zalo/Messenger vẫn mất **Trên 20 phút / không tìm ra** (`Q5`). |
| Hiện đang xử lý bằng cách nào (workaround)? | Đã làm cả 4 bước: **Cuộn lại lịch sử chat + Dùng ô tìm kiếm trong app chat + Xem tin nhắn đã ghim (pin) + Hỏi lại trong nhóm hoặc nhắn riêng một người** (`Q6`). |
| Mất bao lâu, bao lần? | **Trên 20 phút / không tìm ra** ở lần gần nhất; lặp lại **Trên 5 lần** trong những ngày đầu khóa. |
| Insight / opportunity rút ra | Khi nhóm trao đổi qua **Zalo/Messenger**, ngay cả khi đã thử **ô tìm kiếm (Search)** và **xem tin nhắn ghim (Pin)**, người dùng vẫn có thể mất **trên 20 phút mà không tìm ra** quyết định và link file cũ, dẫn trực tiếp đến hậu quả **làm trùng, làm sai hoặc trễ việc (`Q7 = Có`)**. |

#### Case Snapshot #3 — HV01 & HV05 (Bằng chứng vì sao phương án No AI thất bại: `"Còn dùng nhưng hay quên cập nhật"`)

| Trường | Nội dung (Dữ liệu thật lúc `12:04:17` và `12:08:13`) |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Hai học viên làm việc nhóm **4–5 người** (`HV01`) và **2–3 người** (`HV05`), trao đổi chính qua **Zalo, Messenger** |
| Dữ liệu hành vi từ khảo sát | Cả hai đều xác nhận ở `Q9`: **`"Còn dùng nhưng hay quên cập nhật"`** và đều xác nhận ở `Q7`: **`"Có"` (đã từng làm trùng, làm sai hoặc trễ việc trong 1 tháng qua vì không tìm lại được thông tin)**. |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Cả hai đều cần tìm lại đủ 4 mục: **Quyết định nhóm đã chốt, Ai phụ trách phần việc nào, Deadline, Link tài liệu/file** (`Q4`). Dù nhóm đã lập đủ **Ghim (pin) tin nhắn + Biên bản họp + Bảng phân công chung (Sheets/Notion/Trello)** (`Q8`), nhưng khi thảo luận nhanh trên chat thì quên cập nhật vào bảng/pin. |
| Hiện đang xử lý bằng cách nào (workaround)? | Phải làm đồng thời cả 5 thao tác: **Cuộn lại lịch sử chat + Dùng ô tìm kiếm + Xem tin nhắn đã ghim + Mở file biên bản/bảng phân công + Hỏi lại trong nhóm/nhắn riêng** (`Q6`). |
| Mất bao lâu, bao lần? | `HV01`: **2–5 phút/lần**, **3–5 lần** từ đầu khóa; `HV05`: **10–20 phút/lần**, **Trên 5 lần** từ đầu khóa. |
| Insight / opportunity rút ra | **Xác nhận Giả định #3:** Phương án No AI (Pin tin nhắn, Biên bản, Bảng phân công Sheets/Notion) đã được **88.9% học viên thử dùng**, nhưng **55.6% (5/9 người) thất bại ở bước duy trì vì "hay quên cập nhật"**, khiến thành viên phải mở cùng lúc cả chat, pin lẫn file bảng phân công mà vẫn bị làm sai/trễ việc. |

#### Case Snapshot #4 — HV07 *(Tín hiệu phản bác một phần về thời gian tìm kiếm: chỉ mất `Dưới 2 phút`)*

| Trường | Nội dung (Dữ liệu thật lúc `09/11/2026 12:09:03`) |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên làm việc trong nhóm **4–5 người**, trao đổi qua **Zalo, Discord** (`HV07`) |
| Dữ liệu hành vi từ khảo sát | Chỉ phải tìm lại **1–2 lần** từ đầu khóa (`Q3`), lần gần nhất chỉ tìm **Ai phụ trách phần việc nào** (`Q4`) và chỉ mất **Dưới 2 phút** (`Q5`) bằng cách **Dùng ô tìm kiếm trong app chat** (`Q6`). |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tuy tìm nhanh dưới 2 phút ở lần gần nhất, nhưng ở `Q7` bạn vẫn xác nhận **Có bị làm trùng, làm sai hoặc trễ việc trong 1 tháng qua**, ở `Q9` xác nhận **Ghim (pin) tin nhắn quan trọng: "Còn dùng nhưng hay quên cập nhật"**, và chấm mức độ phiền **4/5** (`Q10`). |
| Hiện đang xử lý bằng cách nào (workaround)? | Gõ từ khóa vào ô tìm kiếm trong app chat Zalo/Discord và xem tin nhắn ghim (nhưng tin ghim hay quên cập nhật). |
| Mất bao lâu, bao lần? | **Dưới 2 phút/lần**, **1–2 lần** từ đầu khóa. |
| Insight / opportunity rút ra | **Tín hiệu phản bác giúp hiệu chỉnh bài toán:** Không phải mọi lần tìm kiếm đều mất 8–15 phút (có **1/9 người mất < 2 phút** và **2/9 người mất 2–5 phút** khi chỉ tra cứu nhanh 1 thông tin đơn lẻ). Tuy nhiên, ngay cả khi tra cứu nhanh, việc **quên cập nhật tin nhắn Pin khi đổi phân công** vẫn gây ra **làm trùng/làm sai việc (`Q7 = Có`)**. Do đó giá trị cốt lõi không chỉ là giảm số phút cuộn chat, mà là **chống sót/nhầm việc khi phân công thay đổi**. |

#### Case Snapshot #5 — HV09 & HV02 *(Đã thử `Bot / tính năng tóm tắt tự động` trên Discord & Phản bác về hậu quả làm sai)*

| Trường | Nội dung (Dữ liệu thật lúc `12:16:33` và `12:05:09`) |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Hai học viên làm việc trong nhóm **4–5 người** dùng **Discord** (`HV09`) và đa kênh **Zalo, Discord, Messenger, Slack/Teams** (`HV02`) |
| Dữ liệu hành vi từ khảo sát | Cả hai đều phải tìm lại **Trên 5 lần** từ đầu khóa (`Q3`) và đều mất **5–10 phút/lần** (`Q5`), độ phiền **4/5** (`HV09`) và **5/5** (`HV02`). Đặc biệt: `HV09` đã thử dùng **Bot / tính năng tóm tắt tự động** (`Q8`) nhưng đánh giá **`"Còn dùng nhưng hay quên cập nhật"`** (`Q9`); còn `HV02` là người duy nhất chọn **`Q7 = Không`** (chưa bị làm trùng/sai/trễ). |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | `HV09` cần tìm lại **Deadline / mốc thời gian và Link tài liệu, file** (`Q4`) trên Discord; dù nhóm từng thử Bot/tóm tắt tự động nhưng không duy trì cập nhật đều nên vẫn phải tự cuộn lịch sử chat và dùng ô tìm kiếm mất 5–10 phút. |
| Hiện đang xử lý bằng cách nào (workaround)? | Cuộn lại lịch sử chat + Dùng ô tìm kiếm trong app chat (`HV09`); kết hợp hỏi lại nhóm và mở bảng phân công để kiểm tra chéo nên không bị làm sai (`HV02`). |
| Mất bao lâu, bao lần? | Mất **5–10 phút/lần**, lặp lại **Trên 5 lần** chỉ trong những ngày đầu Khóa AI thực chiến. |
| Insight / opportunity rút ra | (1) **Bài học từ `HV09`:** Ngay cả khi có **Bot / tính năng tóm tắt tự động**, nếu đầu ra không trích xuất đúng các trường hay bị thất lạc nhất (**Deadline 88.9%, Link tài liệu/file 77.8%, Người phụ trách 77.8%, Quyết định chốt 77.8%**) và không gắn vào nhịp chốt việc của nhóm thì vẫn bị bỏ quên. <br>(2) **Tín hiệu phản bác từ `HV02`:** Có thể tránh làm sai (`Q7 = Không`) nếu chấp nhận bỏ ra **5–10 phút/lần (> 5 lần)** kiểm tra đủ mọi nguồn, nhưng cái giá phải trả là sự phiền toái ở mức tối đa (**5/5**). |

#### Tổng hợp kết quả kiểm chứng (`N = 9` học viên thực tế từ Google Sheets)

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận (Confirming Signals) | Tín hiệu phản bác / Điều chỉnh (Disconfirming Signals) |
|---|---:|---|---|
| **Khảo sát thực tế trên Google Forms/Sheets** ([Link Google Sheets](https://docs.google.com/spreadsheets/d/1UA0i4ZOfev5-8-MbpuRXZajs50KR8kp0O6rZIpSSzCY/edit?resourcekey=&gid=1731896032#gid=1731896032), bản lưu [`cp4-survey-and-interviews.md`](../assets/cp4-survey-and-interviews.md) & [`.xlsx`](../assets/cp4-survey-and-interviews.xlsx)) + trao đổi thêm với `HV06` (`Q11 = Có`) | **9 học viên** trong Khóa AI thực chiến (**7/9 = 77.8%** thuộc nhóm **4–5 người**; **77.8% dùng Zalo**, **44.4% dùng Discord**) | - **Tần suất cao (`Q3`):** **7/9 học viên (77.8%)** đã phải tìm/hỏi lại từ **3–5 lần (33.3%)** đến **Trên 5 lần (44.4%)** chỉ trong những ngày đầu khóa.<br>- **Thời gian mất (`Q5`):** **6/9 học viên (66.7%)** mất từ **5–10 phút (44.4%)**, **10–20 phút (11.1%)** đến **Trên 20 phút / không tìm ra (11.1%)**.<br>- **Hậu quả thật (`Q7`):** **5/9 học viên (55.6%)** xác nhận **Có** làm trùng, làm sai hoặc trễ việc trong 1 tháng qua.<br>- **Giới hạn của No AI (`Q8, Q9`):** Dù **88.9%** đã dùng Pin và **55.6%** đã lập Bảng phân công/Biên bản, nhưng **55.6% (5/9) thất bại vì `"Còn dùng nhưng hay quên cập nhật"`**.<br>- **Độ phiền (`Q10`):** Trung bình **3.89/5**, với **77.8% chấm mức 4–5/5**. | - **Thời gian tìm kiếm ngắn hơn ở một số trường hợp (`Q5`):** Có **1/9 học viên (`HV07` — 11.1%)** chỉ mất **Dưới 2 phút** và **2/9 học viên (`HV01, HV04` — 22.2%)** mất **2–5 phút** (nên con số giả định ban đầu `8–15 phút` cần được điều chỉnh lại thành phổ biến nhất là **`5–10 phút`**, dải rộng từ `2–5 phút` đến `> 20 phút`).<br>- **Cảm nhận về cách hiện tại (`Q9`):** Có **3/9 học viên (`HV03, HV06, HV08`)** chọn *"Còn dùng đều, giải quyết được gần hết"*, dù dữ liệu chéo ở `Q5, Q7` cho thấy cả 3 vẫn mất 5–20+ phút tìm lại và 2/3 vẫn bị làm sai/trễ.<br>- **Hậu quả (`Q7`):** **1/9 học viên (`HV02`)** xác nhận **Không** bị làm trùng/sai/trễ (nhưng mất 5–10'/lần, >5 lần và chấm độ phiền 5/5). |
| **Đối chiếu lịch sử chat & Git log thực tế của nhóm ABC100 (4 thành viên)** | 2 kênh (Zalo/Discord + Git log của nhóm 4 người) | Đếm thực tế có **6 lần hỏi lại** quyết định/link trên Zalo, **4–6 lần/tuần** cuộn tìm trên Discord, và **1 lần ghi đè `TEAM.md` + 1 lần hiểu nhầm "Phần 4" vs "CP4"** ngay trong buổi làm bài do thông tin chốt trôi trong chat. | Với các câu hỏi đơn lẻ chỉ tra cứu 1 từ khóa ngắn thì gõ ô tìm kiếm mất dưới 2 phút là đủ (`HV07`). |

**Nhóm đã sửa problem thế nào sau kiểm chứng (dựa trên dữ liệu thật `N = 9`):**
1. **Hiệu chỉnh lại số đo Thời gian & Tần suất sát thực tế khảo sát (`Q3, Q5`):** Thay vì giả định cứng mọi người đều mất `8–15 phút/lần`, nhóm cập nhật lại theo phân bố thật: **66.7% học viên mất từ 5–20+ phút/lần (phổ biến nhất là 5–10 phút/lần, chiếm 44.4%; nặng nhất là > 20 phút không tìm ra)** và **77.8% phải tìm lại từ 3 đến > 5 lần chỉ trong vài ngày đầu khóa học**, dẫn tới **55.6% từng bị làm trùng, làm sai hoặc trễ việc**.
2. **Bổ sung trường thông tin bị thất lạc nhiều nhất từ `Q4` ("Link tài liệu, file" — 77.8%):** Trước kiểm chứng, nhóm chỉ tập trung vào *Quyết định + Người làm + Deadline*. Dữ liệu thật ở `Q4` cho thấy **88.9% cần tìm Deadline**, **77.8% cần tìm Ai phụ trách**, **77.8% cần tìm Quyết định đã chốt**, và đặc biệt **77.8% (7/9 học viên) cần tìm lại "Link tài liệu, file"** (link repo GitHub, Google Sheets, tài liệu bài tập). Vì vậy, đầu ra của giải pháp bắt buộc phải trích xuất đủ **4 trường: (1) Quyết định đã chốt, (2) Đầu việc & Người phụ trách, (3) Deadline/mốc thời gian, (4) Link tài liệu/file đính kèm**.
3. **Chuyển trọng tâm từ "thay thế Pin/Bảng phân công" sang "chống quên cập nhật" (`Q8, Q9`):** Vì **88.9% học viên đã biết dùng Pin** và **55.6% đã có Bảng phân công**, nhưng **55.6% thất bại vì `"Còn dùng nhưng hay quên cập nhật"`** (kể cả `HV09` khi dùng Bot tự động), quy trình mới ở CP5 không bắt nhóm lập thêm bảng phức tạp mà phải **hỗ trợ gom nhanh đoạn chat cuối buổi thảo luận thành bản chốt 4 mục chuẩn hóa trong < 2 phút** để người phụ trách duyệt và ghim ngay.

---

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **1. Tính năng có sẵn của Discord: Search Filters (`from:`, `in:`, `has:`) & Pinned Messages** | https://support.discord.com/hc/en-us/articles/115000468588-Using-Search <br>và<br> https://support.discord.com/hc/en-us/articles/220403608-Pinned-Messages | **Bước tìm kiếm & lưu trữ thủ công:** Lọc tin nhắn theo người gửi/ngày/kênh và ghim các tin nhắn chốt quan trọng lên đầu kênh. | Có sẵn miễn phí 100%, không cần cài đặt thêm, truy cập ngay trong ứng dụng. | Chỉ tìm theo từ khóa chính xác (keyword matching); không tự tổng hợp được khi một quyết định nằm rải rác qua 10–15 tin nhắn tranh luận; phụ thuộc hoàn toàn vào việc thành viên nhớ bấm Pin (thực tế phỏng vấn cho thấy hay quên khi bàn khuya). | Tận dụng **Pinned Message làm nơi đăng bản chốt cuối cùng** (đầu ra), nhưng không thể chỉ dựa vào tìm kiếm từ khóa để giải quyết bước đọc hiểu ngữ cảnh. |
| **2. Slack AI (Channel Recaps & Thread Summaries)** | https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack | **Bước đọc & tóm tắt hội thoại:** Tự động tóm tắt các kênh chat và luồng thảo luận (thread) theo khoảng thời gian, nêu các ý chính và bước tiếp theo. | Tích hợp gốc ngay trong giao diện chat, có gắn link nhảy tới tin nhắn nguồn (citation). | Chỉ hoạt động trên nền tảng Slack và **yêu cầu gói trả phí (Pro / Business+ / Enterprise)**; các nhóm sinh viên Việt Nam chủ yếu dùng **Zalo và Discord miễn phí** nên không áp dụng trực tiếp được. | Học **mẫu thiết kế đầu ra của Slack AI**: bản tóm tắt tốt phải ngắn gọn theo cấu trúc cố định và **có dẫn chứng về tin nhắn gốc** để người đọc kiểm chứng. |
| **3. n8n Workflow (Discord Node + LLM Summarization)** | https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.discord/ <br>và<br> https://n8n.io/workflows/ | **Bước gom tin nhắn tự động → AI tóm tắt → Đăng lại lên kênh:** Tự động lấy tin nhắn mới trong kênh Discord theo lịch, đưa qua mô hình ngôn ngữ lớn để tóm tắt. | Tự động hóa theo đúng kiến trúc **Workflow** (các bước cố định, AI chỉ làm bước tóm tắt văn bản). | (1) Đòi hỏi quyền **Admin server** để tạo Bot Token cấp quyền đọc lịch sử tin nhắn (sinh viên thường không có quyền Admin trên server chung của lớp); (2) **Zalo cá nhân không cung cấp API mở** để đọc tin nhắn nhóm; (3) Nếu để workflow tự đăng thẳng mà không có người duyệt dễ gây hiểu lầm khi AI tóm tắt sai. | **Không tự xây Bot phức tạp đòi hỏi quyền Admin/API Zalo** (tránh rủi ro Feasibility & Viability). Thay vào đó dùng cách lấy đoạn chat đơn giản (copy/export đoạn thảo luận) kết hợp bước **con người duyệt (HITL)** trước khi ghim. |
| **4. Google NotebookLM / Prompt chuẩn với dữ liệu hội thoại dán vào** | https://support.google.com/notebooklm | **Bước phân tích ngữ cảnh & trích xuất có dẫn nguồn:** Người dùng dán đoạn lịch sử chat hoặc ghi chú họp vào làm nguồn (source), yêu cầu trích xuất bảng Quyết định – Task – Blocker. | Miễn phí, dùng được ngay cho cả **Zalo lẫn Discord** mà không cần quyền cài Bot/API; NotebookLM tự động đánh số **trích dẫn (inline citations)** trỏ về đúng câu chữ trong đoạn chat gốc, chống bịa (hallucination) rất tốt. | Bước đưa đoạn chat vào vẫn cần thao tác copy/paste thủ công (mất khoảng 30–60 giây); nếu không có prompt quy định cấu trúc đầu ra chuẩn thì mỗi lần trả lời một kiểu. | Giải pháp vừa sức, khả thi nhất cho nhóm ngay hôm nay là thiết kế một **Workflow bán tự động**: Quy ước gắn nhãn nhanh trên chat → Copy đoạn thảo luận vào **Prompt chuẩn / NotebookLM** (yêu cầu trích dẫn câu gốc) → Người ghi chép duyệt trong 2 phút → Ghim bản chốt lên Pinned Message. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):
**Sơ đồ quy trình hiện tại:**
```text
HIỆN TẠI — 8 bước, chưa có tổng thời gian đo đầy đủ, 8/8 bước thủ công

[1 Phát sinh nhu cầu tìm lại thông tin]
→ [2 Mở Zalo / Discord / Messenger]
→ [3 Tìm từ khóa hoặc cuộn lịch sử chat]
→ [4 Đọc nhiều tin nhắn để tìm đoạn thảo luận liên quan] ← BOTTLENECK
→ [5 Phân biệt ý kiến đang bàn và quyết định đã chốt]
→ [6 Đối chiếu tin ghim / biên bản / bảng phân công]
→ [7 Hỏi lại thành viên nếu thông tin thiếu hoặc mâu thuẫn]
→ [8 Xác nhận quyết định + người phụ trách + deadline + link tài liệu]
```

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[1 Copy đoạn chat / ghi chú cần chốt: 1']
→ [2 Đưa nội dung vào Prompt chuẩn / NotebookLM: 0.5']
→ [3 Trích xuất 4 trường thông tin + dẫn chứng nguồn: 0.5'] ← AI
→ [4 Người phụ trách kiểm tra và sửa bản nháp: tối đa 2']
→ [5 Xác nhận và đăng bản chốt lên tin ghim / bảng chung: 1'] ← CON NGƯỜI
→ [6 Thành viên tra cứu bản chốt khi cần]
```
BOUNDARY:
AI chỉ trích xuất bản nháp từ nội dung được cung cấp; không tự kết luận ý kiến là quyết định đã chốt, không tự gán người phụ trách/deadline, không tự đăng bản chốt. Thông tin chưa rõ phải ghi "Chưa xác định" hoặc "Cần xác nhận". Người phụ trách kiểm tra và xác nhận trước khi sử dụng.

PHƯƠNG ÁN QUAY VỀ:
Nếu AI tóm tắt sai, thiếu dẫn chứng hoặc nhầm quyết định → bỏ bản nháp, đối chiếu chat gốc và lập bản chốt thủ công theo template 4 trường. Nếu công cụ AI không hoạt động → tiếp tục dùng tin ghim, biên bản và bảng phân công như quy trình hiện tại.

**Ghi chú về thời gian:** CP4 đo thời gian tìm kiếm ở lần gần nhất, chưa đo tổng thời gian của toàn bộ quy trình. Mức 4–5 phút ở quy trình tương lai là ước tính thiết kế ban đầu (copy, nhập liệu, AI xử lý, kiểm tra và đăng bản chốt), cần bấm giờ trong pilot để xác nhận.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 8 | 6 | Gộp thao tác tìm kiếm và đối chiếu thành workflow chuẩn hóa. |
| Tổng thời gian | Phổ biến 5–10 phút/lần tìm kiếm; có trường hợp trên 20 phút | Khoảng 4–5 phút | Target ban đầu; cần đo thực tế trong pilot. |
| Bước thủ công | 8/8 | 3/6 | Copy đoạn chat, kiểm tra bản nháp, xác nhận và đăng bản chốt. |
| Bottleneck | Đọc dò nhiều tin nhắn, phân biệt ý kiến và quyết định cuối cùng | Người phụ trách kiểm tra và xác nhận bản nháp | Bottleneck chuyển sang bước kiểm soát chất lượng, chấp nhận được để tránh AI chốt sai. |
| Rủi ro mới | Thất lạc thông tin, quên cập nhật, dùng nhầm thông tin cũ | AI trích xuất sai, thiếu ngữ cảnh hoặc bản chốt không được cập nhật | Xử lý bằng dẫn chứng nguồn, boundary và Human-in-the-loop. |

Số bước thủ công 3/6 tính theo các thao tác con người trực tiếp thực hiện trong workflow: copy dữ liệu, kiểm tra bản nháp, xác nhận/đăng bản chốt. Bước tra cứu ở cuối là thao tác sử dụng kết quả, không tính vào thời gian tạo bản chốt.
---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Thành viên nhóm học tập/dự án khoảng 2–6 người, thường xuyên trao đổi công việc qua Zalo, Discord, Messenger hoặc Slack/Teams. |
| **Quy trình** | Khi cần tìm lại thông tin, thành viên mở ứng dụng chat, tìm từ khóa/cuộn lịch sử, đọc lại thảo luận, phân biệt ý kiến và quyết định đã chốt, đối chiếu tin ghim/biên bản/bảng phân công và hỏi lại nếu cần. |
| **Bottleneck** | Đọc dò nhiều tin nhắn để xác định quyết định cuối cùng và đối chiếu 4 trường thông tin: quyết định, người phụ trách, deadline, link tài liệu. Thông tin thường phân tán và các cách lưu hiện tại dễ bị quên cập nhật. |
| **Impact** | 7/9 học viên (77,8%) phải tìm/hỏi lại từ 3 đến trên 5 lần trong những ngày đầu khóa; 6/9 (66,7%) mất từ 5 phút trở lên ở lần tìm gần nhất; 5/9 (55,6%) từng gặp tình trạng làm trùng, làm sai hoặc trễ việc trong tháng qua. |
| **Success Metric** | Giảm thời gian tìm lại bản chốt từ mức phổ biến 5–10 phút/lần xuống mục tiêu dưới 2 phút; thời gian tạo và xác nhận bản chốt mới mục tiêu khoảng 4–5 phút. Đo bằng cách bấm giờ trong pilot 2 tuần, đồng thời theo dõi độ chính xác của 4 trường thông tin và số lần phải hỏi lại. |
| **Boundary** | AI chỉ trích xuất bản nháp từ đoạn chat được cung cấp, phải có dẫn chứng nguồn; không tự kết luận quyết định, không tự gán người phụ trách/deadline, không tự đăng. Người phụ trách phải kiểm tra và xác nhận trước khi ghim/lưu. |

**Phản biện nhận được / câu hỏi nhóm cần tự kiểm tra:** Quy trình mới có thực sự tiết kiệm thời gian không, hay lại tạo thêm thao tác copy/paste và kiểm tra bản nháp? Nhóm đồng ý đây là rủi ro cần kiểm chứng. Vì vậy, ngoài metric thời gian tìm kiếm, nhóm bổ sung metric **thời gian tạo bản chốt, độ chính xác của 4 trường thông tin và tỷ lệ bản nháp được người phụ trách xác nhận mà không cần sửa lớn**. Nếu workflow nhanh hơn nhưng thường xuyên trích xuất sai hoặc bị bỏ quên cập nhật thì chưa thể xem là giải pháp thành công.

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô:** Độ mơ hồ cao × Độ phức tạp thấp đến trung bình.

**Vì sao:**

Vấn đề của nhóm là tìm lại những quyết định đã chốt, người phụ trách, deadline và trạng thái công việc trong các đoạn chat Zalo/Discord dài.

- **Độ mơ hồ cao:** Các thành viên thường trao đổi bằng ngôn ngữ tự nhiên, sử dụng từ viết tắt hoặc thay đổi ý kiến trong quá trình thảo luận. Ví dụ, câu "bạn làm phần 4 nhé" có thể bị hiểu nhầm giữa CP4 và Mục 4 trong báo cáo. AI cũng có thể nhầm câu hỏi hoặc đề xuất thành quyết định cuối cùng.
- **Độ phức tạp thấp đến trung bình:** Quy trình xử lý tương đối cố định, gồm lấy đoạn chat, trích xuất thông tin, kiểm tra, xác nhận và lưu lại kết quả. Không cần AI tự lập kế hoạch hoặc thực hiện nhiều hành động phức tạp.

Vì vậy, nhóm có thể sử dụng AI để xử lý phần ngôn ngữ khó xác định bằng quy tắc cố định, nhưng vẫn cần con người kiểm tra trước khi sử dụng kết quả.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Thống nhất 5 phút cuối mỗi buổi họp, ghi quyết định, người phụ trách và deadline trực tiếp vào `TEAM.md`; ghim thông báo quan trọng. | Nhóm ít trao đổi qua chat, dưới 20 tin nhắn/ngày, thường xuyên làm việc trực tiếp. | Thành viên quên cập nhật hoặc thông tin ghim không còn mới khi có thay đổi. | Không chọn làm phương án chính; giữ làm phương án dự phòng. |
| **Rule** | Sử dụng nhãn `[CHỐT]`, `[TASK]`, `[KẸT]` và biểu mẫu cố định; có thể dùng script để lọc tin nhắn đã gắn nhãn. | Các thành viên tuân thủ quy ước và thông tin đã được ghi rõ ràng. | Không hiểu được ngữ cảnh, khó xử lý tin nhắn thiếu nhãn hoặc quyết định bị thay đổi. | Không chọn làm mức chính; kết hợp vào Workflow. |
| **Workflow** | Người dùng copy đoạn chat → AI trích xuất quyết định, task, owner, deadline, blocker và câu dẫn chứng → người phụ trách kiểm tra → cập nhật file chung và ghim bản chốt. | Nhóm trao đổi trực tuyến nhiều, có các đoạn thảo luận dài và cần tổng hợp thông tin từ nhiều tin nhắn. | AI có thể tóm tắt sai, bỏ sót thông tin hoặc gán nhầm việc; cần kiểm tra thủ công. | **Chọn để pilot.** |
| **Agent** | AI tự theo dõi Zalo/Discord, phát hiện quyết định, cập nhật task và gửi nhắc việc tự động. | Có quyền truy cập dữ liệu, API phù hợp, sự đồng ý của thành viên và nhu cầu tự động hóa liên tục. | Khó lấy dữ liệu từ Zalo, phụ thuộc quyền Admin Discord, rủi ro quyền riêng tư và tự hành động sai. | Không chọn. |

**Mức chọn:** Workflow bán tự động, kết hợp Rule và Human-in-the-loop (HITL).

**Vì sao không chọn mức đơn giản hơn:**

Qua kiểm chứng, 7/8 học viên được hỏi cho biết thường mất 8–15 phút để tìm lại quyết định hoặc phân công công việc trong nhóm chat. Với những cuộc thảo luận dài, chức năng tìm kiếm từ khóa hoặc ghim tin nhắn chưa giải quyết hoàn toàn vấn đề vì một quyết định có thể bị thay đổi sau nhiều lượt trao đổi.

Rule có thể hỗ trợ chuẩn hóa cách ghi thông tin nhưng không đủ khả năng phân biệt ngữ cảnh phức tạp nếu thành viên không ghi đúng quy ước. Workflow phù hợp hơn vì AI có thể hỗ trợ đọc hiểu và trích xuất nội dung, trong khi con người vẫn kiểm soát quyết định cuối cùng.

Tuy nhiên, với nhóm ít tin nhắn và đã cập nhật công việc trực tiếp vào file chung, No AI vẫn là phương án phù hợp và không cần triển khai AI.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | AI trích xuất bản tóm tắt có cấu trúc gồm quyết định đã chốt, task, người phụ trách, deadline, trạng thái file và blocker. Mỗi thông tin phải kèm câu chat gốc làm bằng chứng; nội dung chưa rõ được đánh dấu "Cần xác nhận". |
| **Judgment** — con người cân nhắc, quyết định gì? | Nhóm trưởng hoặc người ghi chép đối chiếu kết quả với tin nhắn gốc, xác định đâu là quyết định cuối cùng và kiểm tra việc phân công có chính xác hay không. |
| **Action** — hành động cuối cùng là gì, ai làm? | Người được phân công kiểm tra, chỉnh sửa và xác nhận bản tóm tắt, sau đó cập nhật `TEAM.md` hoặc bảng công việc và ghim thông báo lên nhóm chat. AI không tự đăng hoặc thay đổi phân công. |
| **Outcome** — đo kết quả bằng gì? | Thời gian tìm lại quyết định từ 8–15 phút xuống dưới 2 phút/lần; giảm số lần hỏi lại; không có trường hợp gán nhầm người phụ trách; hạn chế bỏ sót quyết định và blocker quan trọng. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Đoạn chat Zalo/Discord được thành viên sao chép hoặc xuất thủ công, tốt nhất có người gửi, thời gian và nội dung đầy đủ. Dữ liệu có sẵn trong nhóm nhưng cần kiểm tra tính đầy đủ và quyền chia sẻ trước khi đưa vào AI. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Lấy từ người duyệt và các thành viên sử dụng bản tóm tắt: thông tin nào đúng, sai, bị bỏ sót, mất bao lâu để kiểm tra và có phải hỏi lại hay không. Ghi lỗi để điều chỉnh prompt và quy tắc xử lý. |

### 6.4. Hai câu hỏi của Google PAIR

**Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**

Nhóm lựa chọn **augment**, tức AI hỗ trợ tổng hợp thông tin chứ không thay thế hoàn toàn con người.

Bằng chứng là trong quá trình phỏng vấn, học viên HV05 đã thử dùng ChatGPT tóm tắt đoạn chat nhưng AI gán nhầm công việc cho một thành viên chỉ đang đặt câu hỏi. Người dùng vẫn cần đối chiếu với tin nhắn gốc trước khi xác nhận bản tóm tắt.

Vì vậy, AI chỉ tạo bản nháp, còn quyền quyết định, phân công và công bố thông tin thuộc về nhóm trưởng hoặc người được giao nhiệm vụ.

**AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót? Vì sao, và thiết kế đã xử lý thế nào:**

Trong bài toán này, **báo nhầm quyết định hoặc gán nhầm người phụ trách là lỗi đặc biệt nghiêm trọng** vì có thể khiến thành viên làm sai việc, làm trùng hoặc bỏ lỡ deadline. Tuy nhiên, bỏ sót blocker quan trọng cũng có thể làm chậm tiến độ nhóm.

Để hạn chế hai loại lỗi, nhóm đề xuất:

1. Mọi quyết định và phân công do AI trích xuất phải có dẫn chứng từ chat gốc.
2. Không tự suy diễn người phụ trách hoặc deadline khi chưa có thông tin rõ ràng.
3. Những trường hợp chưa chắc chắn phải được đánh dấu "Cần xác nhận".
4. Người phụ trách kiểm tra bản tóm tắt, đặc biệt là quyết định, phân công và blocker, trước khi ghim lên nhóm.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Thành viên hoặc nhóm trưởng của nhóm học tập/dự án khoảng 4 người, thường xuyên trao đổi công việc trực tuyến qua Zalo/Discord và làm việc trên GitHub chung, với các buổi thảo luận có trên 50 tin nhắn. |
| **Quy trình** | 1. Mở Zalo/Discord → 2. Tìm đoạn chat liên quan → 3. Cuộn và đọc lại các tin nhắn → 4. Xác định quyết định cuối cùng, task, owner, deadline và blocker → 5. Hỏi lại nếu chưa rõ → 6. Ghi vào file chung. |
| **Bottleneck** | Bước 3–4: phải đọc nhiều tin nhắn để phân biệt ý kiến đang thảo luận với quyết định đã chốt và xác định chính xác người phụ trách. Hiện mất khoảng 8–15 phút/lần. |
| **Impact** | Mất thời gian tìm kiếm lặp lại 3–5 lần/tuần theo khảo sát; có thể dẫn đến hỏi lại nhiều lần, làm trùng việc, hiểu nhầm CP4 với Mục 4 hoặc bỏ sót thông báo cập nhật file và blocker. |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian tìm thông tin: 8–15 phút → dưới 2 phút/lần, bấm giờ từ khi bắt đầu tra cứu đến khi tìm được câu trả lời đúng. (2) Số lần gán nhầm người phụ trách: mục tiêu 0 trong pilot. (3) Tỷ lệ trích xuất đúng và đủ quyết định quan trọng: mục tiêu ≥ 90%, đối chiếu với bản chốt do nhóm xác nhận. (4) 100% thông tin được công bố phải có nguồn kiểm tra. Các target là mục tiêu đề xuất, chưa phải kết quả đã đạt. |
| **Boundary** | AI không tự quyết định, không tự phân công hoặc thay đổi deadline, không được suy diễn khi thiếu bằng chứng, không tự đăng bản chốt. Chỉ xử lý nội dung được phép chia sẻ và phải có người duyệt trước khi sử dụng. |
| **AI intervention point** | Sau khi người dùng lấy đoạn chat và trước khi lập bảng tổng hợp. AI hỗ trợ đọc hiểu, phân loại và trích xuất thông tin theo mẫu cố định, kèm dẫn chứng. |
| **Mức chọn** | **Workflow bán tự động (Rule + AI + HITL).** |
| **Rủi ro & người kiểm tra** | Rủi ro chính là AI hiểu sai ngữ cảnh, gán nhầm việc, bỏ sót blocker hoặc xử lý dữ liệu chưa được phép chia sẻ. Nhóm trưởng hoặc người ghi chép chịu trách nhiệm kiểm tra từng quyết định và phân công trước khi công bố. |

**Thay đổi so với v0 và lý do:**

*Lưu ý: Phần Problem Statement v0 trong file nhóm hiện chưa được điền. Bảng dưới đây dùng nội dung candidate ban đầu ở CP3 làm mốc so sánh với v1, không phải một bản v0 đã hoàn thành.*

| Trường | v0 (ý tưởng ban đầu) | v1 | Vì sao đổi |
|---|---|---|---|
| **Actor** | Các thành viên nhóm học tập/dự án nói chung. | Nhóm khoảng 4 người, trao đổi trực tuyến nhiều, trên 50 tin nhắn/buổi. | HV04 cho thấy nhóm làm trực tiếp và ít chat có thể giải quyết bằng No AI. |
| **Bottleneck** | Mất thời gian tìm lại tin nhắn cũ. | Khó phân biệt quyết định cuối cùng với ý kiến đang bàn; khó xác định task, owner, deadline. | Phỏng vấn cho thấy tìm kiếm từ khóa không giải quyết được vấn đề ngữ cảnh. |
| **Output** | Tóm tắt những thông tin quan trọng trong chat. | Bảng quyết định, task, owner, deadline, blocker và trạng thái file, kèm nguồn gốc. | Tránh hiểu nhầm phân công, bỏ sót trạng thái công việc. |
| **Success Metric** | Giảm thời gian tìm kiếm từ 8–15 phút xuống dưới 2 phút. | Giữ metric thời gian, bổ sung độ chính xác, tính đầy đủ và dẫn chứng nguồn. | Tìm nhanh nhưng sai vẫn gây ảnh hưởng tới công việc nhóm. |
| **Boundary** | Chưa xác định đầy đủ. | Không tự gán việc, không tự công bố và bắt buộc người duyệt kiểm tra. | HV05 ghi nhận trường hợp AI nhầm câu hỏi thành phân công công việc. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | **Đúng quyết định cuối cùng** | Trích xuất đúng quyết định đã được nhóm xác nhận, không lấy ý kiến cũ đã bị thay đổi. | Nhầm đề xuất, câu hỏi hoặc quyết định đã hủy thành quyết định cuối cùng. |
| 2 | **Đúng người và đầu việc** | Task, mã CP, số Mục, owner và deadline khớp bằng chứng; trường chưa rõ ghi "Cần xác nhận". | Tự gán người, tự đặt deadline hoặc nhầm CP4 với Mục 4. |
| 3 | **Đầy đủ thông tin quan trọng** | Trích xuất được ≥ 90% quyết định/task cần có và không bỏ sót blocker quan trọng trong bộ kiểm thử. | Bỏ sót blocker quan trọng hoặc tỷ lệ bao phủ dưới 90%. |
| 4 | **Có thể kiểm chứng** | 100% quyết định và phân công trong bản công bố có trích dẫn chính xác từ dữ liệu chat gốc. | Dẫn chứng thiếu, sai hoặc không tìm thấy trong nguồn. |
| 5 | **Hiệu quả thời gian** | Thời gian tra cứu bản đã được xác nhận dưới 2 phút; thời gian người duyệt kiểm tra bản nháp mục tiêu ≤ 2 phút/đoạn. | Tra cứu vẫn mất từ 2 phút trở lên hoặc phải kiểm tra lại quá lâu khiến Workflow không hiệu quả hơn No AI/Rule. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Thấp** | 7/8 học viên được khảo sát gặp vấn đề, mất 8–15 phút/lần; tuy nhiên mẫu mới có 8 người và một trường hợp cho thấy No AI là đủ. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **TB** | Copy đoạn chat và sử dụng prompt tương đối đơn giản, nhưng AI từng gán nhầm việc. Cần nguồn trích dẫn và người kiểm tra trước khi sử dụng. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **TB** | Có thể dùng đoạn chat copy thủ công và công cụ AI sẵn có, không cần tự xây bot. Tuy nhiên cần kiểm tra khả năng lấy dữ liệu đầy đủ, thời gian xử lý và chất lượng trích xuất. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **TB** | Có thể thử nghiệm với công cụ miễn phí hoặc sẵn có. Rủi ro chính là quyền riêng tư và việc đưa dữ liệu chat lên công cụ bên ngoài. Nhóm trưởng quản lý quy trình, người ghi chép vận hành; cần sự đồng ý của các thành viên và loại bỏ thông tin nhạy cảm. |

### 8.2. Kết luận

**Quyết định đề xuất: Go — thực hiện pilot nhỏ có kiểm soát, chưa triển khai tự động toàn bộ.**

**Lý do:**

Nhóm đã có bằng chứng cho thấy vấn đề xảy ra thực tế, ảnh hưởng đến nhiều người và có thể đo lường bằng thời gian tìm lại thông tin. Phương án Workflow bán tự động phù hợp vì có thể sử dụng những công cụ sẵn có, không cần phát triển hệ thống phức tạp hoặc xin quyền Admin để tích hợp bot.

Tuy nhiên, AI chưa được kiểm chứng đầy đủ về độ chính xác và hiệu quả so với No AI/Rule. Vì vậy, Go ở đây chỉ có nghĩa là đủ cơ sở để thử nghiệm nhỏ, không phải triển khai chính thức.

**Nếu Go — pilot nhỏ nhất:**

Thử nghiệm trên nhóm ABC100 với 3 đoạn hội thoại Zalo/Discord đã được phép sử dụng, mỗi đoạn có trên 50 tin nhắn và có quyết định hoặc phân công công việc.

Quy trình:

1. Người ghi chép chuẩn bị đoạn chat, loại bỏ dữ liệu nhạy cảm và lập bản đáp án chuẩn bằng cách đối chiếu với các thành viên.
2. Thử phương án No AI/Rule để có số liệu so sánh trên cùng loại nhiệm vụ.
3. Đưa đoạn chat vào Workflow sử dụng prompt chuẩn, yêu cầu AI trích xuất quyết định, task, owner, deadline và blocker kèm dẫn chứng.
4. Người ghi chép kiểm tra, chỉnh sửa và ghim bản đã xác nhận.
5. Cho các thành viên thực hiện các câu hỏi tra cứu thực tế, bấm giờ, đếm lỗi và so sánh kết quả hai phương án.

**Mục tiêu pilot:** Thời gian tìm thông tin dưới 2 phút/lần, không có trường hợp gán nhầm owner, không bỏ sót blocker quan trọng và đạt ít nhất 90% thông tin cần trích xuất chính xác, đầy đủ.

**Nếu Not Yet — cần kiểm chứng gì trước:**

Nếu pilot chưa đáp ứng các tiêu chí, nhóm cần kiểm tra thêm khả năng cung cấp dữ liệu chat, mức độ chính xác khi phân biệt quyết định với đề xuất, thời gian duyệt của con người và hiệu quả thực tế so với quy trình No AI/Rule.

**Nếu No-Go — nên làm gì thay AI:**

Áp dụng một bảng phân công thống nhất trong `TEAM.md`, sử dụng quy ước `[CHỐT]`, `[TASK]`, `[KẸT]`, dành 5 phút cuối buổi họp để xác nhận quyết định và ghim thông báo đã chốt. Chỉ định một người chịu trách nhiệm cập nhật khi có thay đổi.

**Ngưỡng dừng:**

Sau 3 đoạn hội thoại pilot, nếu xuất hiện bất kỳ trường hợp AI gán nhầm người phụ trách hoặc quyết định sai mà người duyệt không phát hiện, bỏ sót blocker quan trọng, tỷ lệ thông tin đúng và đủ dưới 90%, hoặc thời gian sử dụng không tốt hơn phương án No AI/Rule, nhóm sẽ dừng mở rộng Workflow và quay về quy trình ghi chép thủ công có cấu trúc.

Chỉ tiếp tục triển khai khi kết quả cho thấy tiết kiệm thời gian thực tế và đảm bảo tính chính xác, khả năng kiểm chứng cũng như quyền kiểm soát của con người.

### 8.2. Kết luận

**Quyết định:** **Go — triển khai pilot nhỏ có kiểm soát, chưa triển khai chính thức.**

**Lý do:**

Kết quả kiểm chứng cho thấy 7/8 học viên gặp khó khăn khi tìm lại quyết định và phân công công việc trên Zalo/Discord, thường mất 8–15 phút/lần. Vấn đề xảy ra nhiều lần trong tuần, gây lãng phí thời gian và có nguy cơ làm trùng hoặc bỏ sót công việc.

Nhóm lựa chọn Workflow bán tự động vì có thể tận dụng công cụ AI sẵn có để hỗ trợ tổng hợp thông tin mà không cần xây dựng Agent phức tạp. Tuy nhiên, AI vẫn có khả năng hiểu sai ngữ cảnh hoặc gán nhầm người phụ trách. Vì vậy, cần thử nghiệm nhỏ và có con người kiểm tra trước khi quyết định triển khai rộng hơn.

**Nếu Go — pilot nhỏ nhất:**

Thử nghiệm trên nhóm ABC100 với 3 đoạn hội thoại Zalo/Discord, mỗi đoạn trên 50 tin nhắn và có nội dung quyết định, phân công công việc hoặc blocker.

Quy trình thử nghiệm:

1. Người phụ trách chuẩn bị đoạn chat đã được phép sử dụng và xác nhận các quyết định đúng làm dữ liệu đối chiếu.
2. Đo thời gian tìm kiếm bằng phương án No AI/Rule.
3. Sử dụng AI với prompt chuẩn để trích xuất quyết định, task, owner, deadline và blocker kèm dẫn chứng.
4. Người ghi chép kiểm tra, chỉnh sửa và xác nhận kết quả.
5. So sánh thời gian và độ chính xác giữa hai phương án.

Mục tiêu: Giảm thời gian tìm kiếm xuống dưới 2 phút/lần, tỷ lệ thông tin đúng và đầy đủ đạt ít nhất 90%, không gán nhầm người phụ trách và không bỏ sót blocker quan trọng.

**Nếu Not Yet — cần kiểm chứng gì trước:**

Cần kiểm tra thêm khả năng lấy dữ liệu chat đầy đủ, mức độ chính xác của AI khi phân biệt quyết định cuối cùng với ý kiến đang thảo luận, thời gian con người cần để kiểm tra kết quả và hiệu quả thực tế so với No AI/Rule. Đồng thời, cần xác nhận sự đồng ý của các thành viên khi sử dụng dữ liệu hội thoại với công cụ AI.

**Nếu No-Go — nên làm gì thay AI:**

Áp dụng quy trình ghi chép thống nhất: sử dụng nhãn `[CHỐT]`, `[TASK]`, `[KẸT]`, dành 5 phút cuối buổi họp để xác nhận phân công, cập nhật trực tiếp vào `TEAM.md` và ghim thông báo quan trọng. Phân công một người chịu trách nhiệm duy trì thông tin mới nhất.

**Ngưỡng dừng:**

Nếu sau 3 đoạn hội thoại thử nghiệm, AI vẫn gán nhầm người phụ trách hoặc quyết định cuối cùng mà người duyệt không phát hiện, bỏ sót blocker quan trọng, tỷ lệ trích xuất đúng và đủ dưới 90%, hoặc tổng thời gian xử lý không tốt hơn No AI/Rule, nhóm sẽ dừng mở rộng Workflow và quay về quy trình ghi chép thủ công có cấu trúc.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- Mẫu kiểm chứng còn nhỏ, mới gồm 8 học viên thuộc các nhóm trong lớp L3A nên chưa thể đại diện cho tất cả nhóm học tập hoặc dự án.
- Dữ liệu thời gian chủ yếu dựa trên phỏng vấn, khảo sát và một số lần quan sát thực tế; chưa có thử nghiệm đối chứng đủ lớn để khẳng định mức tiết kiệm thời gian.
- Không phải nhóm nào cũng cần AI. Nhóm ít thành viên, trao đổi trực tiếp và cập nhật công việc thường xuyên có thể giải quyết tốt bằng No AI.
- AI có nguy cơ hiểu sai ngữ cảnh, nhầm đề xuất thành quyết định hoặc bỏ sót thông tin. Việc kiểm tra thủ công vẫn cần thiết.
- Khả năng tích hợp trực tiếp với Zalo/Discord còn hạn chế bởi quyền truy cập, API và yêu cầu bảo vệ dữ liệu hội thoại.
- Nhóm chưa hoàn thành pilot để đánh giá độ chính xác, chi phí và tính ổn định của Workflow trong sử dụng thực tế.

**Hướng tiếp theo:**

1. Hoàn thiện prompt chuẩn với đầu ra cố định gồm quyết định, task, owner, deadline, blocker và dẫn chứng từ tin nhắn gốc.
2. Thử nghiệm với 3 đoạn hội thoại thực tế, đồng thời đo thời gian xử lý, số lỗi và tỷ lệ thông tin được trích xuất chính xác.
3. So sánh Workflow với phương án No AI/Rule để xác định AI có thực sự tạo thêm giá trị hay không.
4. Thu thập phản hồi từ thành viên, đặc biệt về các trường hợp AI hiểu sai, bỏ sót hoặc cần người kiểm tra quá lâu.
5. Nếu pilot đạt mục tiêu, mở rộng thử nghiệm sang một số nhóm có tần suất trao đổi trực tuyến cao; nếu không đạt, cải thiện quy trình ghi chép thủ công trước khi cân nhắc ứng dụng AI tiếp.

---

## 10. Tài liệu tham khảo

1. **Báo cáo kiểm chứng CP4 của nhóm ABC100.** Kết quả phỏng vấn và khảo sát 8 học viên về thời gian tìm lại quyết định, phân công công việc trong nhóm chat.  
   File nội bộ: `report/assets/cp4-survey-and-interviews.md`

2. **Discord Support — Using Search.** Hướng dẫn sử dụng chức năng tìm kiếm và bộ lọc tin nhắn trên Discord.  
   https://support.discord.com/hc/en-us/articles/115000468588-Using-Search

3. **Discord Support — Pinned Messages.** Hướng dẫn ghim và quản lý tin nhắn quan trọng trong Discord.  
   https://support.discord.com/hc/en-us/articles/220403608-Pinned-Messages

4. **Slack Help Center — Guide to AI features in Slack.** Tham khảo cách AI tóm tắt hội thoại, tổng hợp thông tin và dẫn về nguồn tin nhắn.  
   https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack

5. **n8n Documentation — Discord Node.** Tham khảo khả năng xây dựng quy trình tự động hóa liên quan đến Discord.  
   https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.discord/

6. **Google — NotebookLM Help.** Tham khảo công cụ hỗ trợ tổng hợp thông tin từ tài liệu nguồn và trích dẫn để kiểm chứng nội dung.  
   https://support.google.com/notebooklm

7. **Báo cáo nhóm ABC100 — Day 02 Discovery & Problem Framing.** Nguồn tổng hợp kết quả CP3–CP6, Assumption Map, kiểm chứng và so sánh các phương án giải quyết.  
   File nội bộ: `report/team/group_report.md`