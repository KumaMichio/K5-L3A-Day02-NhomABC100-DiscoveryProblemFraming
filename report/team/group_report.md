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

**Cách đã dùng:** Phỏng vấn sâu **5 học viên** + khảo sát nhanh (micro-survey) mở rộng tổng cộng **8 học viên** thuộc các **nhóm 4 người khác nhau trong lớp L3A** (theo đúng 3 luật của *The Mom Test*: chỉ hỏi về tình huống thật vừa xảy ra sáng nay/tối qua khi làm Lab trên Zalo nhóm + GitHub chung, cách họ đang tự xoay xở và thời gian mất thật; không hỏi câu giả định *"Bạn có muốn..."*), kết hợp đối chiếu log tin nhắn Zalo/Discord và lịch sử commit GitHub thực tế.
*(Bảng dữ liệu chi tiết 8 học viên được lưu tại [`report/assets/cp4-survey-and-interviews.md`](../assets/cp4-survey-and-interviews.md)).*

**Câu hỏi khung nhóm đã dùng (tuân thủ The Mom Test):**
1. *"Trong nhóm 4 người lớp L3A của bạn, nhóm đang trao đổi công việc chính qua kênh nào (Zalo nhóm + GitHub chung / Discord / Bàn trực tiếp tại lớp)?"*
2. *"Lần gần nhất sáng nay hoặc tối qua khi chia việc CP3–CP6 và merge file lên GitHub, bạn có phải kéo lại chat Zalo/Discord để xem ai nhận mục nào hoặc nhóm chốt đề tài nào không? Mất khoảng bao nhiêu phút?"*
3. *"Lúc đó bạn đã tìm lại bằng cách nào (cuộn lại chat, gõ từ khóa tìm kiếm, xem tin nhắn Ghim hay hỏi lại nhóm) và gặp trục trặc gì?"*

#### Interview Snapshot #1 (HV01)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhóm trưởng một nhóm 4 người lớp L3A (dùng Zalo nhóm + GitHub chung) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Tìm bằng từ khóa trên Zalo chỉ ra một đống tin nhắn có chữ CP4 thôi, chứ muốn biết cuối cùng chốt ai làm mục nào thì vẫn phải ngồi kéo đọc lại cả đoạn dài vì lúc đầu bàn một kiểu, 15 phút sau lại đổi."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Lúc chia việc CP3–CP6 và merge file lên GitHub: phải kéo lại hơn 150 tin nhắn Zalo xem cuối cùng nhóm chốt đề tài nào trong 12 ý tưởng và ai nhận mục số mấy trong `group_report.md`. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng ô tìm kiếm từ khóa trên Zalo rồi cuộn lên cuộn xuống đọc dò lại cả đoạn hội thoại; nếu lười tìm thì nhắn hỏi lại thẳng vào nhóm chờ các bạn trả lời. |
| Mất bao lâu, bao lần? | Khoảng 10–12 phút/lần tự lục tìm; một tuần gặp khoảng 5 lần (nhất là lúc ghép bài nhóm). |
| Insight / opportunity rút ra | Tìm kiếm từ khóa (keyword search) không giải quyết được bài toán vì **quyết định cuối cùng phụ thuộc vào ngữ cảnh cả đoạn hội thoại** (ai đồng ý, ai đổi phần việc). |

#### Interview Snapshot #2 (HV02)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Thành viên một nhóm 4 người lớp L3A (dùng Zalo nhóm + Discord + GitHub chung) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Trên Zalo nhắn câu cụt lủn 'bạn làm phần 4 nhé', đến lúc mở file `group_report.md` ra thì CP4 lại nằm ở Mục 3, thế là làm nhầm sang Mục 4 mất 15 phút phải khôi phục lại."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Sáng nay khi nhận việc làm báo cáo nhóm: trên chat Zalo chỉ nhắn ngắn gọn *"làm phần 4 nhé"*, người nhận hiểu thành Mục 4 (Quy trình trước/sau — CP5) trong khi ý nhóm là Checkpoint 4 (Mục 3 trong file), dẫn đến viết nhầm mục và phải kéo lại chat đối chiếu để khôi phục. |
| Hiện đang xử lý bằng cách nào (workaround)? | Kéo cuộn lại tin nhắn Zalo để đối chiếu xem lúc nãy nhóm bàn theo số Checkpoint (`CP4`) hay số Mục (`Mục 4`) trong file báo cáo rồi nhắn hỏi lại. |
| Mất bao lâu, bao lần? | Mất 10–15 phút đọc lại và sửa lại file; 4 lần/tuần khi chia các mục nhỏ trong nhóm 4 người. |
| Insight / opportunity rút ra | Khi trao đổi nhanh trên chat, các thành viên dùng từ viết tắt/ngắn gọn (*"phần 4" vs "CP4"*), nếu không có bảng chốt ghi rõ **Tên Checkpoint + Mục số mấy trong file + Người làm** thì rất dễ làm nhầm phần của nhau. |

#### Interview Snapshot #3 (HV03)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Thành viên phụ trách ghép bài của một nhóm 4 người lớp L3A (dùng Zalo nhóm + GitHub chung) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Sợ nhất là một bạn nhắn báo đã điền `TEAM.md` chỉ 1 câu ngắn rồi bị 20 tin nhắn bàn CP3 trôi đè lên, bạn sau không đọc kịp cứ thế push đè lên làm mất luôn phần của bạn trước."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi 4 thành viên cùng sửa chung repo nhóm: thành viên A vừa cập nhật mục cá nhân vào `TEAM.md` và nhắn báo trên Zalo, nhưng tin nhắn bị trôi; thành viên B sửa trên bản cũ rồi push lên ghi đè làm mất phần khai báo trong `TEAM.md` của thành viên A. |
| Hiện đang xử lý bằng cách nào (workaround)? | Mở lịch sử `git log` đối chiếu với giờ nhắn tin trên Zalo rồi nhắn hỏi lại từng người và khôi phục lại đoạn bị mất. |
| Mất bao lâu, bao lần? | Mất 12–15 phút rà lại chat và lịch sử commit; 4–5 lần/tuần. |
| Insight / opportunity rút ra | Nỗi đau không chỉ là tìm "quyết định đã chốt" mà còn là **nắm được trạng thái cập nhật mới nhất của 4 thành viên và các blocker/lỗi quyền Git (như lỗi 403 chưa accept lời mời)** bị trôi trong luồng chat. |

#### Interview Snapshot #4 (HV04) *(Tín hiệu phản bác)*

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Thành viên một nhóm 4 người ngồi cùng bàn trên lớp L3A (trao đổi trực tiếp tại bàn + GitHub) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nhóm mình 4 người ngồi sát nhau cùng bàn trên lớp, bàn gì nói miệng 2 phút rồi gõ thẳng vào file `TEAM.md` trên GitHub luôn, trên Zalo chỉ nhắn vài câu gửi link nên không mất công lục tìm."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Sáng nay khi chia việc CP3–CP6, cả 4 người ngồi cùng bàn, thống nhất miệng và 1 người điền thẳng tên người phụ trách từng Checkpoint vào bảng phân công trong `TEAM.md`. |
| Hiện đang xử lý bằng cách nào (workaround)? | Bàn trực tiếp tại bàn và ghi thẳng vào bảng phân công duy nhất trong file Markdown (`TEAM.md`), hầu như không bàn dài dòng qua tin nhắn Zalo. |
| Mất bao lâu, bao lần? | Chỉ mất 1–2 phút mở file `TEAM.md` hoặc kéo vài tin nhắn Zalo. |
| Insight / opportunity rút ra | **Tín hiệu phản bác rất rõ:** Với nhóm 4 người ngồi trực tiếp cùng bàn trên lớp (co-located) và ít nhắn tin (< 20 tin nhắn/ngày), phương án **No AI (ghi thẳng vào bảng `TEAM.md`) là hoàn toàn đủ**, không cần công cụ tóm tắt chat. |

#### Interview Snapshot #5 (HV05)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhóm trưởng một nhóm 4 người lớp L3A (làm việc kết hợp buổi tối qua Zalo + Google Meet) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nếu có bản tóm tắt thì mình vẫn phải nhìn được câu gốc bạn ấy nhắn là gì, chứ công cụ mà tự suy diễn rồi ghi 'bạn A nhận làm phần 5' trong khi bạn ấy mới chỉ hỏi 'phần 5 làm thế nào?' là làm trùng việc ngay."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối hôm trước khi chốt phân công làm bài lab: thử copy một đoạn chat Zalo dài dán vào ChatGPT nhờ tóm tắt việc cần làm; ChatGPT thấy một bạn hỏi về mục C liền ghi luôn bạn đó phụ trách mục C, may mà nhóm trưởng đọc lại phát hiện kịp. |
| Hiện đang xử lý bằng cách nào (workaround)? | Khi nhờ AI tóm tắt đoạn chat dài, nhóm trưởng vẫn phải tự cuộn Zalo dò lại từng tên người với đoạn chat gốc trước khi gửi lên nhóm. |
| Mất bao lâu, bao lần? | Dán vào AI mất 1 phút nhưng dò lại mất 5–7 phút vì AI không trích dẫn dòng tin nhắn gốc; làm 3–4 lần/tuần. |
| Insight / opportunity rút ra | Người dùng muốn **được hỗ trợ (augment)** chứ không giao phó hoàn toàn; bản tóm tắt **bắt buộc phải kèm trích dẫn nguyên văn câu chat gốc** để người duyệt kiểm tra trong 1–2 phút và tránh lỗi "gán nhầm việc". |

#### Tổng hợp kết quả kiểm chứng (8 học viên từ các nhóm 4 người lớp L3A)

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu & Khảo sát nhanh (theo *The Mom Test*, chi tiết tại [`cp4-survey-and-interviews.md`](../assets/cp4-survey-and-interviews.md)) | **8 học viên** (thuộc các nhóm 4 người khác nhau trong lớp L3A) | **7/8 học viên** xác nhận mất **8–15 phút/lần** (3–5 lần/tuần) để cuộn lại chat Zalo/Discord tìm quyết định chốt, phân công mục bài làm (`CP4` vs `Mục 4`) và trạng thái merge GitHub; xác nhận việc ghim tin nhắn (Pin) thủ công vẫn bị lệch khi 2 thành viên đổi việc cho nhau ở dưới luồng chat mà quên ghim lại (HV08). | **1/8 học viên (HV04)** (nhóm 4 người ngồi sát cùng bàn trên lớp, < 20 tin nhắn/ngày) cho biết không gặp pain này vì nói miệng 2 phút và điền thẳng vào `TEAM.md` là đủ. **1/8 học viên (HV05)** cảnh báo AI dễ nhầm "câu hỏi đang bàn" thành "quyết định đã chốt" nếu không trích dẫn câu gốc. |
| Đối chiếu lịch sử chat & Git log thực tế của nhóm ABC100 (4 thành viên) | 2 kênh (Zalo/Discord + Git log của nhóm 4 người) | Đếm thực tế có **6 lần hỏi lại** quyết định/link trên Zalo (10–15'/lần), **4–6 lần/tuần** cuộn tìm trên Discord (8–12'/lần), và **1 lần ghi đè `TEAM.md` + 1 lần hiểu nhầm "Phần 4" vs "CP4"** ngay trong buổi làm bài do thông tin chốt trôi trong chat. | Với các thông báo ngắn dưới 15 tin nhắn thì đọc lướt mắt thường trong 1 phút nhanh hơn dùng công cụ. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
1. **Thu hẹp Actor và bối cảnh (nhờ tín hiệu phản bác ở HV04):** Không phát biểu bài toán cho "mọi nhóm học tập" chung chung, mà thu hẹp rõ vào: **"Nhóm học tập/dự án 4 người trao đổi công việc trực tuyến qua Zalo/Discord kết hợp GitHub chung với lượng tin nhắn lớn (> 50 tin nhắn/buổi thảo luận)"**. Với nhóm 4 người ngồi trực tiếp cùng bàn trên lớp và ít nhắn tin (< 20 tin/ngày), nhóm khuyến nghị dùng thẳng **No AI** (điền trực tiếp vào `TEAM.md`).
2. **Làm sắc nét Bottleneck & Đầu ra cần có (nhờ HV01, HV02, HV03):** Đổi từ "tìm lại tin nhắn cũ" sang **"rút trích 3 thông tin cốt lõi: (1) Quyết định đã chốt, (2) Đầu việc (ghi rõ cả mã Checkpoint và số Mục trong file) – Người nhận – Hạn, (3) Trạng thái file dùng chung (`TEAM.md`/`group_report.md`) & Blocker đang chờ hỗ trợ — kèm câu trích dẫn nguyên văn từ đoạn chat"**.
3. **Bổ sung điều kiện Boundary & Metric chất lượng (nhờ HV05, HV08):** Bắt buộc bản tóm tắt phải đính kèm trích dẫn câu gốc để người duyệt kiểm tra trong 2 phút, và tuyệt đối không tự gán người phụ trách khi câu chat chỉ đang hỏi hoặc đề xuất.

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
