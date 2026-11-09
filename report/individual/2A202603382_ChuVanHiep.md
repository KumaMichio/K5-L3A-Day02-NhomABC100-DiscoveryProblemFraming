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
