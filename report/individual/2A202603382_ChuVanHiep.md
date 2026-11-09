# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên:Chử Văn Hiệp
- MSSV:2A202603382
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:ABC100
- Link repository:https://github.com/KumaMichio/K5-L3-Day02-NhomABC100-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.


| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng + link) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi tới hạn nộp lab/báo cáo nhóm, tôi muốn biết bài mình còn thiếu mục nào và đã đúng cấu trúc chưa, để không bị trừ điểm vì sai format |Bản thân + nhóm| Bản thân mỗi lab mất 10 phút kiểm checklist; 1-2 lab/ngày.|
| 2 | Lặp lại | Khi bắt đầu buổi họp nhóm trên Discord, tôi muốn có sẵn tóm tắt quyết định và task của lần họp trước, để không phải hỏi lại “hôm trước mình chốt gì?” | Bản thân + nhóm họp | Mỗi họp mất 5-10 phút để mọi người nhớ lại; 2-3 họp/tuần.|
| 3 | Tốn thời gian | Khi cần viết phần “Kết quả & Thảo luận” của báo cáo, tôi muốn có bản nháp từ dữ liệu thí nghiệm/code, để không ngồi nhìn trang trắng 30–40 phút | Bản thân | 35–50 phút/lần viết phần này; 1–2 lần/tuần. University of Calgary ước lượng 1 báo cáo lab “đủ tốt” mất khoảng 2 giờ tổng ([link](https://www.chem.ucalgary.ca/courses/351/laboratory/reports.html)). |
| 4 | Tốn thời gian | Khi ôn thi cuối kỳ từ nhiều slide + ghi chú Discord + tài liệu PDF, tôi muốn có bản tóm tắt theo chủ đề, để không phải mở 10 tab cùng lúc | Bản thân | Mỗi môn mất 2–3 giờ gom tài liệu; 6-8 môn/học kỳ.|
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm lại câu trả lời cũ trong Discord của nhóm hoặc class, tôi muốn tìm đúng thread trong dưới 2 phút, để không phải cuộn hàng trăm tin nhắn | Bản thân | Mỗi lần tìm mất 8–10 phút; 4–6 lần/tuần.|
| 6 | Pain từ người khác | Khi thành viên mới vào nhóm hoặc mới nhận task, họ muốn hiểu rõ yêu cầu và deadline ngay, để không phải hỏi lại nhiều lần | Thành viên mới + leader | Thành viên hỏi lại 2–3 lần/task (đếm từ Discord). |


---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tìm lại thông tin (#2) | Quy trình rõ, tần suất cao, có số liệu đo được, so sánh được 4 mức AI | Quyền truy cập server Discord của nhóm có đủ không? |
| 2 | Viết phần Kết quả & Thảo luận lab/báo cáo (#3) | Bottleneck rõ (trang trắng), impact trực tiếp điểm số, vừa sức lab | “Nháp đủ tốt” đo thế nào? |
| 3 | Ôn thi từ nhiều nguồn rời rạc (#4) | Pain rộng, nhiều người gặp, có tool sẵn (Gemini Notebook) | Phạm vi dễ quá rộng nếu không thu hẹp actor |

### Problem Card #1 — Tìm lại thông tin & tóm tắt Discord nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu buổi họp nhóm hoặc cần tìm quyết định cũ trên Discord, tôi muốn có bản tóm tắt quyết định + task + người phụ trách trong dưới 2 phút, để không mất 8–10 phút cuộn tin nhắn và hỏi lại |
| Actor | Sinh viên, thành viên nhóm dự án/lab |
| Thời điểm / bối cảnh | Trước và trong buổi họp nhóm (2 lần/tuần), hoặc khi cần tra cứu giữa tuần |
| Quy trình hiện tại | 1. Mở Discord → 2. Tìm channel/thread → 3. Cuộn tin nhắn cũ → 4. Đọc lại để nhớ quyết định → 5. Hỏi lại nhóm nếu không chắc → 6. Ghi chú thủ công |
| Bottleneck | Bước 3–4: cuộn và đọc lại tin nhắn (8–10 phút/lần) |
| Impact | 4–6 lần/tuần × 10 phút ≈ 40–90 phút/tuần/người; cả nhóm 4–5 người → 3–7 giờ/tuần |
| Success metric | Thời gian tìm từ 8–10 phút → dưới 2 phút/lần; số lần hỏi lại trong họp giảm |
| Phương án không dùng AI | Pin message quan trọng + tạo channel “#decisions” + checklist họp |
| Giả thuyết về AI | AI tóm tắt thread/channel theo cấu trúc (quyết định – task – owner – deadline) từ tin nhắn đã có |
| Cảm nhận nhanh | Workflow |

```text
HIỆN TẠI — khoảng 10–15 phút/lần

[1 Mở Discord: 1'] → [2 Tìm channel/thread: 2'] → [3 Cuộn + đọc tin cũ: 8–12'] ← BOTTLENECK
→ [4 Hỏi lại nhóm nếu cần: 2–5'] → [5 Ghi chú: 1']
```
---


### Problem Card #2 — Viết phần Kết quả & Thảo luận

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần viết phần “Kết quả & Thảo luận” của báo cáo lab, tôi muốn có bản nháp từ dữ liệu thí nghiệm/code đã có, để không ngồi nhìn trang trắng 30–40 phút |
| Actor | Sinh viên, người viết chính báo cáo lab/nhóm |
| Thời điểm / bối cảnh | Sau khi có dữ liệu thí nghiệm hoặc kết quả code, trước deadline nộp |
| Quy trình hiện tại | 1. Mở file dữ liệu/code → 2. Nhìn số liệu → 3. Cố nghĩ cách viết narrative → 4. Viết từng đoạn → 5. Sửa đi sửa lại → 6. Kiểm format |
| Bottleneck | Bước 3–4: từ dữ liệu thô thành đoạn văn nhận định (30–40 phút) |
| Impact | 35–50 phút/lần × 1–2 lần/tuần; ảnh hưởng trực tiếp chất lượng và điểm báo cáo |
| Success metric | Thời gian viết phần này từ 35–50 phút → dưới 15 phút (có nháp AI + sửa) |
| Phương án không dùng AI | Template câu mẫu + bảng số liệu sẵn + checklist nội dung bắt buộc |
| Giả thuyết về AI | AI soạn nháp 3–4 đoạn (điểm nổi bật, so sánh, hạn chế, hướng tiếp) từ bảng số liệu đưa vào |
| Cảm nhận nhanh | Workflow |

```text
HIỆN TẠI — 35–50 phút

[1 Mở dữ liệu: 3'] → [2 Nhìn số liệu + nghĩ ý: 10'] → [3 Viết narrative: 25–30'] ← BOTTLENECK
→ [4 Sửa + format: 5–10']
```
### Problem Card #3 — Ôn thi từ nhiều nguồn rời rạc

| Trường | Nội dung |
|---|---|
| Job Story | Khi ôn thi cuối kỳ từ nhiều slide + ghi chú Discord + tài liệu PDF, tôi muốn có bản tóm tắt theo chủ đề, để không phải mở 10 tab cùng lúc và mất 2–3 giờ chỉ để gom tài liệu |
| Actor | Sinh viên đang ôn 6-8 môn |
| Thời điểm / bối cảnh | 2–3 tuần trước kỳ thi |
| Quy trình hiện tại | 1. Mở slide → 2. Mở Discord tìm ghi chú → 3. Mở PDF → 4. Copy từng phần → 5. Tự tổng hợp → 6. Làm flashcard/quiz |
| Bottleneck | Bước 1–5: gom và tổng hợp từ nhiều nguồn (2–3 giờ/môn) |
| Impact | 6-8 môn × 2–3 giờ = 12-18 giờ chỉ để gom tài liệu trước khi ôn thật |
| Success metric | Thời gian gom tài liệu từ 2–3 giờ/môn → dưới 30 phút |
| Phương án không dùng AI | Folder theo môn + template outline thủ công |
| Giả thuyết về AI | Upload slide + PDF + export Discord → AI tạo study guide + quiz theo chủ đề |
| Cảm nhận nhanh | Workflow |

```text
HIỆN TẠI — 2–3 giờ/môn

[1 Mở slide: 10'] → [2 Tìm ghi chú Discord: 20–30'] → [3 Đọc PDF: 30']
→ [4 Copy + tổng hợp: 60–90'] ← BOTTLENECK → [5 Làm flashcard: 20']
```
### Card muốn pitch nhất

- Card số: 1
- Vì sao: Tần suất cao nhất (4–6 lần/tuần), impact lan ra cả nhóm 4–5 người, có số liệu đo được rõ ràng, và research cho thấy đã có nhiều tool sẵn (SummaryBot, Reduck, HARPA AI) nên không cần tự xây từ đầu. Dễ so sánh được 4 mức No AI / Rule / Workflow / Agent.
- Câu hỏi muốn nhóm phản biện: “Nếu nhóm không cho phép thêm bot vào server Discord thì phương án nào vẫn khả thi và ít rủi ro nhất?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Feasibility (Khả thi): Bạn lấy quyền truy cập (API/Bot) vào server của nhóm/lớp bằng cách nào nếu admin không cho phép? |Đồng ý |Thêm giả định "Có thể xuất (export) lịch sử chat thủ công" hoặc "Admin cấp quyền cho bot" vào phần kiểm chứng.|
|Value (Giá trị): Phương án No AI (Pin tin nhắn quyết định, tạo channel #decisions) có thể giải quyết được 80% vấn đề mà không tốn chi phí xây AI không? |Đồng ý một phần |Nhấn mạnh vào bối cảnh "thành viên quên/không có thói quen tóm tắt sau họp", AI sẽ đóng vai trò tự động hóa thói quen này.Usability (Độ tin cậy): Làm sao biết AI tóm tắt đúng quyết định cuối cùng, thay vì tóm tắt một ý tưởng nháp bị cả nhóm bác bỏ ở giữa cuộc hội thoại?Đồng ýThêm tiêu chí đánh giá (Eval) ở các bước sau: "Không bỏ sót quyết định có sự đồng thuận" và "Không tóm tắt sai ý định".|
|Usability (Độ tin cậy): Làm sao biết AI tóm tắt đúng quyết định cuối cùng, thay vì tóm tắt một ý tưởng nháp bị cả nhóm bác bỏ ở giữa cuộc hội thoại?|Đồng ý |Thêm tiêu chí đánh giá (Eval) ở các bước sau: "Không bỏ sót quyết định có sự đồng thuận" và "Không tóm tắt sai ý định".|
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
| --- | --- | --- |
| Pitch Problem Card | Trình bày 3 Problem Cards, nổi bật nhất là Problem Card #10 về nỗi đau mất thời gian mỗi lần để lục lại quyết định, task và deadline trên Discord.| Card #10 của tôi được nhóm đánh giá cao về tính khả thi và đo lường được, gộp cùng Card #7 và #9 thành Candidate cuối cùng của nhóm (Cluster A).|
| Phản biện bài của bạn khác | Đặt câu hỏi phản biện cho các bài toán tự động hóa rà soát tài liệu: "Hệ thống sẽ xác định tài liệu nào là nguồn thông tin chính xác nhất như thế nào nếu có sự mâu thuẫn?" và phản biện sự an toàn của AI.| Giúp nhóm nhận ra rủi ro khi giao toàn quyền cho AI đọc hiểu tài liệu, từ đó hình thành tư duy cần ranh giới Boundary rõ ràng. |
| Nhận phản biện | Nhận câu hỏi phản biện: "Nếu Discord đã có chức năng search, tại sao người dùng vẫn mất 8–12 phút? Vấn đề nằm ở công cụ hay cách tổ chức?" và "Làm sao biết AI tóm tắt đúng quyết định thay vì ý tưởng nháp?".| Tôi nhận ra chức năng search từ khóa không giải quyết được việc "hiểu ngữ cảnh". Tôi đã bổ sung rào cản Boundary: bắt buộc có bước con người duyệt và đo lường tỷ lệ không bỏ sót thông tin.|
| Gom cluster / cây OST | Cùng nhóm gom các card liên quan đến việc thất lạc thông tin trong chat, nhóm họp và báo cáo tiến độ vào Cluster A (Thông tin thất lạc trong Zalo/Discord/Sheets).| Xác định đúng Opportunity cốt lõi của nhóm: Giảm thời gian gom, tìm lại và đối chiếu thông tin phân tán trong các kênh chat.|
| Chọn candidate problem | Cùng nhóm chấm điểm 3 candidate lọt vào vòng trong, bảo vệ lợi thế của bài toán tra cứu Discord/Zalo vì có dữ liệu Actor và số phút thực tế rõ ràng nhất.| Nhóm đạt đồng thuận cao để chọn Candidate A làm bài toán chính thức cho CP4–CP6.|
| Kiểm chứng / research | Cung cấp số liệu hành vi thực tế của bản thân (4–6 lần/tuần, 8–12 phút/lần) và hỗ trợ phân tích kết quả phỏng vấn các học viên khác về thói quen dùng Discord/Zalo.| Bằng chứng chỉ ra 88.9% người dùng biết ghim tin nhắn nhưng 55.6% thất bại vì "hay quên cập nhật", chứng minh giải pháp hiện tại là chưa đủ.|
| Quy trình nhóm | Đóng góp định hình bước nghẽn trong quy trình As-Is: thao tác cuộn và đọc dò hội thoại để phân biệt đâu là ý kiến đang bàn, đâu là quyết định cuối cùng.| Giúp nhóm chốt được sơ đồ quy trình hiện tại gồm 8 bước thủ công và quy trình tương lai rút gọn còn 6 bước.|
| Problem Statement | Hỗ trợ định hình Actor (nhóm 2–6 người trao đổi qua Zalo/Discord) và Metric (giảm từ 8–15 phút xuống dưới 2 phút).| Problem Statement v1 có tính định lượng thực tế, gắn sát với hành vi của thành viên chạy đồ án hoặc làm lab nhóm.|
| Mức can thiệp AI | Phân tích bài toán ở góc độ Feasibility (Khả năng lấy quyền truy cập Bot vào server), bảo vệ quan điểm không nên dùng Agent phức tạp.| Nhóm chốt mức Workflow bán tự động (Rule + AI + HITL), dùng prompt/NotebookLM và có con người duyệt để tránh rủi ro kỹ thuật.|
| Quyết định | Tham gia đánh giá 4 rủi ro, nhấn mạnh mức độ Trung bình của Usability và Feasibility do AI dễ nhầm lẫn ngữ cảnh.| Nhóm chốt quyết định Go (Pilot thử nghiệm nhỏ trên 3 đoạn chat) kèm theo ngưỡng dừng định lượng chặt chẽ.|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| --- | --- | --- | --- | --- |
| **CP1 Scan** | Nhờ AI gợi ý thêm các pain point thường gặp của sinh viên theo 4 lăng kính khi học tập và làm lab/nghiên cứu. | Gợi ý được bài toán ôn thi cuối kỳ từ nhiều nguồn và việc bí ý tưởng khi viết phần "Kết quả & Thảo luận". | AI thường mô tả Job Story có chứa sẵn từ khóa giải pháp (ví dụ: "tôi muốn có tool tạo study guide") và không có số liệu thực tế. | Xóa bỏ mọi từ khóa công cụ/giải pháp trong Job Story, tự điền số liệu bấm giờ thật của mình.|
| **CP2 Problem Card** | Yêu cầu AI đóng vai PM để phản biện 3 Problem Cards cá nhân, đặc biệt là card tìm kiếm thông tin trên Discord. | Chỉ ra rủi ro về Feasibility (làm sao lấy quyền API vào server Discord) và rủi ro Usability (AI tóm tắt nhầm ý tưởng thành quyết định). | Ở card số 2, AI đưa ra metric chung chung như "cải thiện điểm số" thay vì tập trung vào thời gian giải quyết trang giấy trắng.  | Bổ sung giả định "Export chat thủ công" để giải quyết rào cản Feasibility, và thêm yêu cầu đo lường "Không bỏ sót quyết định" để kiểm soát Usability.|
| **CP4 Research** | Dùng AI tìm kiếm các công cụ, tính năng Discord Bot hoặc workflow tự động để tóm tắt hội thoại. | Liệt kê nhanh các công cụ hiện có trên thị trường và tính năng tóm tắt tích hợp sẵn để nhóm có cơ sở so sánh. | AI không làm rõ rào cản thực tế: n8n hay Bot tóm tắt thường yêu cầu quyền Admin server, sinh viên không tự cài đặt được trên server chung. | Đưa hạn chế về quyền Admin vào bảng Research, chốt hướng đi khả thi nhất là kết hợp NotebookLM hoặc dán nội dung vào Prompt chuẩn thay vì xây Bot. |
| **CP5 Quy trình** | Nhờ AI chuyển đổi mô tả các bước thành sơ đồ quy trình dạng text trực quan cho bài nhóm. | Tiết kiệm thời gian gõ định dạng sơ đồ, giúp phân tách rõ quy trình As-Is và To-Be. | Sơ đồ AI vẽ nối thẳng từ bước "AI tạo nháp" sang "Ghim tin nhắn", hoàn toàn bỏ qua việc con người kiểm chứng kết quả. | Vẽ lại sơ đồ: Tách rõ bước AI xử lý và buộc phải có bước con người xác nhận trước khi đăng. |
| **CP5–6 Problem Statement** | Dùng AI soát lỗi logic, định dạng và làm gọn các thành phần trong Problem Statement v0 và v1. | Diễn đạt gọn gàng các phần Actor, Bottleneck và Impact theo chuẩn khuôn mẫu mà không làm mất ý. | Khung Success Metric do AI gợi ý thường chỉ ưu tiên đo tốc độ mà thiếu vắng các chuẩn mực đo lường chất lượng đầu ra. | Trực tiếp bổ sung các tiêu chí chất lượng (Không gán nhầm người phụ trách, trích xuất đúng > 90%) vào phần Metric và bảng rủi ro. |
| **CP6 Mức can thiệp / quyết định** | Nhờ AI phân tích ưu nhược điểm của 4 mức (No AI / Rule / Workflow / Agent) áp dụng riêng cho bối cảnh chat nhóm. | Đưa ra nhắc nhở tốt về rủi ro Viability liên quan đến bảo mật quyền riêng tư khi xuất dữ liệu chat nội bộ đưa lên LLM. | AI đánh giá mức độ rủi ro chung khá thấp và khuyên nên dùng Agent tự hành tự quét Discord để tự động hóa 100%. | Bác bỏ phương án Agent, lập luận vững chắc cho mức Workflow bán tự động vì hội thoại Zalo/Discord có độ mơ hồ cao, buộc phải có người xác nhận cuối cùng.
|
---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các bạn trình bày, tôi nhận ra một pattern chung: nỗi đau lớn nhất của mọi người không nằm ở việc thiếu công cụ giao tiếp hay thiếu tài liệu, mà nằm ở sự phân mảnh thông tin. Dù là sinh viên ôn thi, người làm nghiên cứu hay nhóm trưởng chạy dự án, ai cũng đang phải tự gom nhặt, đối chiếu và tổng hợp từ nhiều nguồn rời rạc. Điều này giúp tôi tự tin hơn với Problem Card về việc tìm lại tin nhắn của mình, vì nó chạm đúng vào nỗi đau phân mảnh thông tin mà ai làm việc nhóm cũng gặp phải.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, ngay ở giai đoạn gom Cluster và vẽ cây OST (CP3). Ban đầu, nhóm đã định đưa thẳng các ý tưởng như làm bot,.. vào làm nhánh cơ hội. Khi đối chiếu nguyên tắc, nhóm nhận ra đó là giải pháp chứ không phải vấn đề. Cả nhóm đã tập trung viết lại nỗi đau ban đầu. Việc này giúp nhóm không bị đóng khung vào việc phải code một con chatBot.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Khi tôi trình bày Problem Card của mình, tôi đã nhận được câu hỏi: Nếu Discord đã có chức năng search, tại sao người dùng vẫn mất thời gian để tìm quyết định cũ? Vấn đề nằm ở công cụ tìm kiếm hay cách tổ chức thông tin?. Ban đầu tôi cứ nghĩ do Discord search kém, nhưng sau câu hỏi đó, tôi nhận ra vấn đề thực sự là do chúng ta thảo luận đan xen quá nhiều ý kiến nháp trước khi chốt hạ. Từ khóa search có thể đưa ta đến đúng dòng tin nhắn, nhưng để hiểu đó có phải "quyết định cuối cùng" hay không thì người dùng vẫn phải đọc dò lại cả chuỗi hội thoại dài. Do đó, tôi đổi hướng bài toán: giải pháp không phải là "tìm kiếm nhanh hơn", mà là "phân tách và tóm tắt ngữ cảnh" chính xác.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả khảo sát ở CP4 làm tôi bất ngờ ở hai điểm. Thứ nhất, tôi từng nghĩ phương án ghim tin nhắn là không quá nhiều người dùng, nhưng khảo sát chỉ ra tới 88.9% người dùng đã dùng Pin; điều bất ngờ là 55.6% trong số đó vẫn thất bại vì lý do rất con người: "hay quên cập nhật" khi chốt việc quá nhanh. Thứ hai là trường hợp của bạn HV09, dù đã dùng Bot/AI tóm tắt tự động trên Discord nhưng vẫn chấm độ phiền 4/5 vì Bot cũng... bị nhóm bỏ quên không đọc. Điều này chứng tỏ công cụ AI nếu không được gắn vào một quy trình  có con người xác nhận thì sẽ vô dụng.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất đối với tôi là định nghĩa phần Boundary và Success Metric cho bài toán. Vì đặc thù của việc dùng AI tóm tắt chat là rất dễ bịa hoặc lấy nhầm ý kiến của người này gán việc cho người khác, nên nếu chỉ đo lường bằng "giảm thời gian xuống dưới 2 phút" thì chưa đủ. Việc phải suy nghĩ để đưa thêm các tiêu chí định lượng khắt khe như "số lần gán nhầm người phụ trách phải bằng 0" và bắt buộc AI phải "có trích dẫn nguồn câu chat gốc" đã tốn của tôi và nhóm rất nhiều thời gian phân tích, nhưng đổi lại Problem Statement trở nên cực kỳ thực tế và chặt chẽ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, ở phần kiểm chứng CP4, thay vì chỉ gửi form khảo sát để người dùng tự ước lượng thời gian (5-10 phút hay >20 phút), tôi sẽ xin phép quan sát trực tiếp (shadowing) 2-3 bạn thao tác tìm lại quyết định cũ trên Discord/Zalo và bấm giờ từng cú click chuột. Về phản biện, tôi sẽ làm gắt hơn ở phần Viability (Tính khả thi về mặt bảo mật): liệu các thành viên nhóm có thoải mái khi toàn bộ lịch sử trò chuyện (có thể chứa thông tin nhạy cảm của dự án) bị copy/paste vào một công cụ LLM bên ngoài như NotebookLM hay không? Chúng ta cần quy định rõ loại tin nhắn nào tuyệt đối không được đưa vào AI.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Bài toán nhóm giải quyết là việc các thành viên học tập/dự án lãng phí trung bình 10 phút mỗi lần để cuộn lịch sử chat Zalo/Discord nhằm tìm lại các quyết định đã chốt, đầu việc và deadline bị trôi. Quy trình hiện tại buộc người dùng phải tự đọc dò các tin nhắn để phân biệt đâu là ý kiến nháp, đâu là quyết định cuối cùng, dễ nhầm lẫn hoặc trùng việc. Nhóm đặt ra mục tiêu giảm thời gian tìm kiếm dưới 2 phút/lần, đạt tối thiểu chính xác 90% và không gán sai người phụ trách. AI chỉ được tạo bản nháp trích dẫn nguồn tin nhắn gốc, không tự ý giao việc hay đăng bản chốt lên nhóm. Do độ độ mơ hồ cao nhưng quy trình khá rõ ràng, nhóm chọn mức can thiệp là Workflow bán tự động (Rule + AI + con người duyệt). Cuối cùng, nhóm ra quyết định Go ở quy mô nhỏ, pilot trên 3 đoạn chat để đo đếm thực tế tỷ lệ lỗi trước khi áp dụng chính thức toàn nhóm.

---

## 7. Tài liệu tham khảo

* Lịch sử chat Discord/Zalo và khảo sát 9 học viên Khóa AI thực chiến (Dữ liệu CP4 nhóm ABC100) — *`report/assets/cp4-survey-and-interviews.md`*.


* Slack Help Center (2024), *Guide to AI features in Slack* — Tham khảo thiết kế đầu ra tóm tắt hội thoại có dẫn nguồn (inline citations).


* Google (2024), *NotebookLM Help* — Tham khảo phương pháp đưa đoạn hội thoại thô vào LLM và yêu cầu trích xuất có đối chiếu dữ liệu gốc (grounding).


* Báo cáo nhóm ABC100 — Day 02 Discovery & Problem Framing (`group_report.md`) — Nguồn tổng hợp kết quả CP3–CP6, Assumption Map, và phân tích ma trận mức can thiệp AI.


* Teresa Torres (2021), *Continuous Discovery Habits* — Khung lý thuyết xây dựng Opportunity Solution Tree để tránh lỗi "solution-first" ở CP3.
* Rob Fitzpatrick (2013), *The Mom Test* — Phương pháp đặt câu hỏi khảo sát hành vi quá khứ thực tế áp dụng tại CP4.
