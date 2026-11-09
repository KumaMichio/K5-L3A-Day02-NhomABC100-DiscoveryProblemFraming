# Báo cáo cá nhân — 2A202603420_PhanSyHung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phan Sỹ Hùng
- MSSV: 2A202603420
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: ABC100
- Link repo nhóm: https://github.com/KumaMichio/K5-L3-Day02-NhomABC100-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Bối cảnh: tôi là học viên chương trình AI20k (K5 · Level 3), mỗi ngày lab làm nhóm 3–4 người trên một repo GitHub chung, nhận thông báo qua LMS và các kênh chat.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu một ngày lab mới, tôi muốn cả nhóm có repo chung với đúng tên, đủ quyền commit và mỗi người có file cá nhân, để bắt đầu CP0 đúng giờ | Nhóm trưởng, cả nhóm (3–4 người) | Mỗi ngày lab 1 lần; README có 5 lưu ý riêng chỉ cho bước fork/đặt tên/mời collaborator. Tôi cần 15-20 phút để setup và thêm 15-20 phút để giải thích vấn đề cần làm cho nhóm |
| 2 | Tốn thời gian | Khi ôn lại một khái niệm từ buổi học 4 tiếng, tôi muốn tìm đúng đoạn giảng về khái niệm đó, để không phải tua lại cả recording | Học viên | 20-30 phút, gần như vid nào cũng phải tua |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi điền một mục trong báo cáo lab, tôi muốn biết mọi yêu cầu cho mục đó (nội dung, định dạng, điểm), để không mất điểm vì thiếu | Học viên, coach chấm bài | Yêu cầu của Day 02 nằm rải rác trong 8 file, tổng ~15.900 từ (README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION, 3 file docs; đếm bằng `wc -w`). ~15-20 phút cho việc scan nội dung các file yêu cầu |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi lab dùng một framework tôi chưa biết (Mom Test, OST, Google PAIR…), tôi muốn nắm được ý chính đủ để áp dụng trong 15–30 phút, để không chậm tiến độ nhóm | Học viên | Day 02 dẫn ~10 framework (docs/03). ~15-20 phút |
| 5 | Tốn thời gian | Khi cuối buổi lab phải điền bảng "Dùng AI", tôi muốn nhớ chính xác mình đã dùng AI ở checkpoint nào, AI sai ở đâu và tôi sửa gì, để ghi đúng sự thật mà không mất điểm | Học viên cả lớp | Mỗi lab 1 lần; RULES §2 yêu cầu ghi lại *mỗi lần* dùng AI; bảng "Dùng AI" có 6 dòng checkpoint × 4 cột, trải trên buổi 240 phút. ~60 phút, không rõ bao nhiêu AI log bị quên |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Đã dùng Claude (Claude Code) để quét repo và gợi ý thêm ý theo 4 lăng kính, đồng thời đếm số commit sửa đề và số từ trong các file hướng dẫn (dòng 2, 4).
- Bỏ ý "chia tiền nhóm / theo dõi chi tiêu nhiều app": có thật nhưng không liên quan bối cảnh học của nhóm, khó tìm người cùng gặp để kiểm chứng trong lab.
- [cần điền: ý nào tôi tự nghĩ trước khi hỏi AI; ý nào AI gợi ý mà tôi chưa thực sự gặp nên bỏ]

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #8 — Nhớ lại việc dùng AI để điền bảng "Dùng AI" cuối buổi | Lặp lại mọi lab và là yêu cầu bắt buộc (RULES §2); bottleneck là 1 bước cụ thể, tự bấm giờ được ngay tối nay; cả lớp cùng điền bảng này nên dễ phỏng vấn ở CP4; có phương án No AI rõ để so sánh | Có thể chỉ mất 5–10 phút nên pain nhỏ? Mất điểm thật là do quên ghi hay do ghi hời hợt? |
| 2 | #4 — Yêu cầu một mục rải rác trong 8 file | Lặp lại mọi lab, ảnh hưởng trực tiếp điểm; quy trình vẽ được rõ | Có thể chỉ là vấn đề đọc lần đầu, từ lab thứ 3 trở đi đã quen? |
| 3 | #6 — Phối hợp repo chung (file, commit, conflict) | Actor rõ (nhóm 3–4 người), có sự cố thật hôm nay | Pain có lớn không hay chỉ vài phút; Git là kỹ năng nên có thể giải bằng hướng dẫn, không cần công cụ |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cuối buổi lab phải điền bảng "Dùng AI", tôi muốn nhớ chính xác mình đã dùng AI ở checkpoint nào, AI sai ở đâu và tôi sửa gì, để ghi đúng sự thật mà không mất điểm |
| Actor | Học viên AI20k K5 · L3, dùng 1–2 trợ lý AI (ChatGPT, Gemini, Claude…) rải rác qua 6 checkpoint của một buổi lab 240 phút |
| Thời điểm / bối cảnh | 15 phút cuối buổi (CP7), lúc đã mệt và cùng lúc phải viết reflection ≥ 200 từ; các cuộc hội thoại AI nằm ở nhiều tab/app khác nhau |
| Quy trình hiện tại (3–7 bước) | 1. Mở bảng "Dùng AI" trong báo cáo → 2. Cố nhớ lại đã dùng AI ở checkpoint nào → 3. Mở lại lịch sử chat của từng app để tìm đúng đoạn hội thoại → 4. Đọc lại để xác định AI giúp gì, sai gì → 5. Nhớ lại mình đã sửa gì và sửa ở đâu trong báo cáo → 6. Viết vào 4 cột của bảng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: tìm lại hội thoại cũ và nhớ "AI sai ở đâu / tôi sửa gì" — chi tiết này không lưu ở đâu cả, chỉ nằm trong trí nhớ — ~20-30 phút |
| Impact (nếu không giải thì sao) | Bảng ghi chung chung ("AI giúp gợi ý ý tưởng") hoặc thiếu dòng → mất điểm phần dùng AI và tiêu chí "có ít nhất 1 chỗ AI sai và bạn đã sửa thế nào" (CP7); lấn thời gian viết reflection |
| Success metric (baseline → target) | Thời gian điền bảng "Dùng AI": 60 phút → ≤ 5 phút. Số lần dùng AI bị quên ghi/buổi: 6-7 → 0. Số ô trong bảng có ví dụ cụ thể (không chung chung): 60-70% → 100% dòng đã dùng AI |
| Phương án không dùng AI | Ghi log ngay sau mỗi lần dùng AI (1 dòng: checkpoint, dùng để làm gì, AI sai gì, tôi sửa gì) vào một file nháp hoặc thẳng vào bảng; đặt nhắc "ghi log" ở cuối mỗi checkpoint |
| Giả thuyết về AI (nếu có) | Tóm tắt lịch sử hội thoại thành nháp 4 cột — nhưng AI không biết tôi đã sửa gì trong báo cáo, nên vẫn phải tự ghi phần đó |
| Cảm nhận nhanh | **No AI / Rule** (thói quen ghi ngay + nhắc cuối mỗi checkpoint) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~60 phút, 1 lần/lab, trong 15' cuối buổi

[1. Mở bảng "Dùng AI": 4'] → [2. Nhớ checkpoint nào đã dùng AI: 15']
→ [3. Lục lịch sử chat từng app: 15'] ← BOTTLENECK
→ [4. Đọc lại, xác định AI giúp/sai gì: 10'] ← BOTTLENECK
→ [5. Nhớ mình đã sửa gì: 8'] ← BOTTLENECK
→ [6. Viết 4 cột: 2-4']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi điền một mục trong báo cáo lab, tôi muốn biết mọi yêu cầu cho mục đó (nội dung, định dạng, cách chấm), để không mất điểm vì thiếu |
| Actor | Học viên AI20k làm báo cáo lab cá nhân và nhóm |
| Thời điểm / bối cảnh | Trong lúc làm từng checkpoint và 30 phút trước khi nộp |
| Quy trình hiện tại (3–7 bước) | 1. Mở template báo cáo → 2. Đọc CHECKPOINTS cho mục đó → 3. Mở worksheet xem hướng dẫn chi tiết → 4. Mở RUBRIC xem tiêu chí chấm → 5. Mở bài mẫu xem cách viết → 6. Viết → 7. Tự kiểm checklist |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4: nhảy giữa 3–4 file để gom yêu cầu của **một** mục — [cần điền] phút/mục |
| Impact (nếu không giải thì sao) | Thiếu trường bắt buộc (ví dụ quên "phương án không dùng AI" trong card) → mất điểm; tốn thời gian buổi lab vốn chỉ 35' cho CP2 |
| Success metric (baseline → target) | Số mục bị chấm thiếu yêu cầu/lab: 1-2 → 0. Thời gian gom yêu cầu/mục: 10 phút → ≤ 2 phút |
| Phương án không dùng AI | Một checklist gộp mỗi checkpoint (đã có một phần ở "Tự kiểm tra"); tự làm bảng tra mục → file → dòng |
| Giả thuyết về AI (nếu có) | Tra cứu tài liệu lab theo câu hỏi, có dẫn nguồn file/dòng — chỉ đáng nếu checklist gộp vẫn thiếu |
| Cảm nhận nhanh | **No AI / Rule** (checklist) — Workflow nếu tài liệu đổi liên tục |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 2-10 phút cho mỗi mục báo cáo

[1. Mở template: 2'] → [2. Đọc CHECKPOINTS: 4'] → [3. Đọc worksheet: 4']
→ [4. Đối chiếu RUBRIC: 4'] ← BOTTLENECK (gom yêu cầu từ nhiều file)
→ [5. Xem bài mẫu: 2'] → [6. Viết: 4'] → [7. Tự kiểm: 4']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm chung một repo, mỗi thành viên muốn biết file nào là của mình và commit thế nào cho đúng, để không ghi đè hoặc conflict với người khác |
| Actor | Thành viên nhóm 3–4 người, khác nhau về mức quen Git |
| Thời điểm / bối cảnh | Đầu buổi (tạo file cá nhân) và lúc nhiều người cùng sửa `group_report.md`, `TEAM.md` (CP3–CP7) |
| Quy trình hiện tại (3–7 bước) | 1. Nhóm trưởng fork + mời collaborator → 2. Thành viên chấp nhận lời mời, clone → 3. Tạo file cá nhân từ template → 4. Cùng sửa file nhóm → 5. Pull/push, gặp conflict → 6. Hỏi trên chat, sửa conflict |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5–6: xử lý conflict khi nhiều người sửa cùng `group_report.md` — 15-20 phút/lần |
| Impact (nếu không giải thì sao) | Mất nội dung của người khác; commit sai tài khoản → không được tính đóng góp (RULES §3) |
| Success metric (baseline → target) | Số conflict/buổi: ~10-11 → ≤ 1. Số phút xử lý: 30-40 → ≤ 5 |
| Phương án không dùng AI | Chia section `group_report.md` theo người phụ trách trong `TEAM.md`; quy ước "pull trước khi sửa"; 1 người merge file nhóm |
| Giả thuyết về AI (nếu có) | Không thấy cần — bài toán là phối hợp, không phải đọc/tổng hợp |
| Cảm nhận nhanh | **No AI** |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 50-60 phút/buổi

[1. Fork + mời: 10'] → [2. Accept + clone: 5'] → [3. Tạo file cá nhân: 5']
→ [4. Cùng sửa file nhóm: 15'] → [5. Pull/push gặp conflict: 10'] ← BOTTLENECK
→ [6. Hỏi chat + sửa: 10']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Lặp lại ở mọi lab của chương trình, là yêu cầu bắt buộc nên ảnh hưởng điểm trực tiếp, cả lớp cùng điền bảng này nên dễ phỏng vấn người thật ở CP4, và bottleneck đo được ngay trong buổi hôm nay (tự bấm giờ lúc điền mục 5).
- Câu hỏi muốn nhóm phản biện: "Lab trước bạn điền bảng 'Dùng AI' mất bao lâu, và có lần dùng AI nào bạn quên ghi không?" — nếu mọi người đều điền nhanh và đủ thì pain này nhỏ, nên bỏ.

### AI đã phản biện card thế nào

Card #1 ban đầu là problem #2 (đề bài/hướng dẫn thay đổi sau khi phát). Tôi tự phản biện và đổi card trước khi đưa cho AI:

| Điểm yếu (ai chỉ ra) | Đồng ý? | Đã sửa gì |
|---|---|---|
| (Tôi tự phản biện) Đề không thay đổi nhiều *trong* buổi lab — phần lớn 12 commit sửa đề nằm trước buổi học, nên pain khi đang làm lab là nhỏ | Đồng ý | Bỏ card "đề thay đổi" khỏi top 3 (vẫn giữ ở bảng scan CP1, dòng 2); thay bằng problem #8 "điền bảng Dùng AI cuối buổi" |
| 

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card (#1 bảng "Dùng AI" cuối buổi, #2 yêu cầu rải rác 8 file, #3 phối hợp repo chung) — dòng #1–#3 bảng pitch `group_report.md` mục 2.1 | Card #1, #2 vào cluster B, card #3 được gộp vào cluster A — cluster nhóm chọn |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: [cần điền: câu hỏi tôi đã hỏi, cho card số mấy của ai] | [cần điền] |
| Nhận phản biện | Câu hỏi tôi nhận được: [cần điền] | Tôi đã sửa gì: [cần điền] |
| Gom cluster / cây OST | Người chính CP3: tổng hợp 12 candidate của 4 thành viên vào bảng pitch, gom 4 cluster (A–D), dựng cây OST 1 outcome – 4 opportunity, gạch bỏ 6 ý là solution đội lốt opportunity | `group_report.md` mục 2.1–2.3 |
| Chọn candidate problem | Chấm điểm shortlist 3 candidate (A, B, #7); chỉ ra #7 có điểm cao nhất (33) nhưng trùng hướng với bài mẫu "báo cáo tuần", đề xuất A; ghi lý do chọn/loại | Nhóm thống nhất chọn **A — quyết định & trạng thái việc nhóm thất lạc trong chat**; ghi vào `group_report.md` mục 1, 2.4 và `TEAM.md` |
| Kiểm chứng / research | Soạn bộ 11 câu hỏi khảo sát theo The Mom Test (`report/assets/cp4-survey-form.md`), script tạo Google Form có skip logic, và template interview snapshot (`report/assets/cp4-interview-snapshot-template.md`) | Bộ câu hỏi Q1–Q11 được nhóm dùng để thu 9 phản hồi thật (mục 3.2); Hoàng là người chính chạy kiểm chứng và research |
| Quy trình nhóm | [cần điền nếu có tham gia] | |
| Problem Statement | [cần điền nếu có tham gia] | |
| Mức can thiệp AI | [cần điền nếu có tham gia] | |
| Quyết định | [cần điền nếu có tham gia] | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Claude quét repo, gợi ý thêm problem theo 4 lăng kính, đếm commit sửa đề và số từ tài liệu | Lấy được bằng chứng đo được từ `git log` và `wc -w` thay vì cảm giác | AI không biết số phút/tần suất thật của tôi — phần dấu hiệu cá nhân AI để trống, không bịa được | [cần điền: tự bổ sung số liệu thật, bỏ ý nào] |
| CP2 Problem Card | Claude nháp 3 card + quy trình; đề xuất problem thay thế khi tôi bác card "đề thay đổi" | Gợi ý card "điền bảng Dùng AI" có bottleneck đo được và phương án No AI rõ | Ban đầu AI chọn card "đề thay đổi" vì có nhiều commit, nhưng không phân biệt commit trước buổi lab với thay đổi trong buổi lab — tôi phải tự chỉ ra; một số bước quy trình là AI suy luận | Đổi Card #1 sang problem #8; [cần điền: bước quy trình nào tôi sửa lại theo cách mình thực sự làm] |
| CP3 Hội tụ (tổng hợp, không dùng cho pitch/phản biện) | Claude đọc 4 báo cáo cá nhân, nháp bảng pitch, cluster, cây OST và bảng chấm điểm để nhóm thảo luận | Gom nhanh 12 card, phát hiện ý "solution đội lốt opportunity" trong card; chỉ ra candidate #7 trùng hướng bài mẫu | AI chấm điểm dựa trên văn bản báo cáo, không biết nội dung thảo luận thật; ban đầu AI nháp cả lý do chọn/loại thay nhóm | Câu hỏi phản biện và quyết định chọn A do nhóm tự đưa ra trong buổi; [cần điền: điểm/lý do nào nhóm đã sửa so với nháp] |
| CP4 Kiểm chứng (soạn công cụ) | Claude soạn bộ 11 câu hỏi khảo sát, template interview snapshot và script Google Apps Script tạo form | Câu hỏi bám hành vi đã xảy ra (7 ngày qua), có skip logic, có câu bắt tín hiệu phản bác (Q9) | Câu Q10 (mức phiền 1–5) vẫn là ý kiến, không phải hành vi; script chưa được AI chạy thử | [cần điền: tôi đã sửa câu hỏi nào trước khi gửi, ví dụ đổi "7 ngày qua" thành "những ngày đầu khóa"] |
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

- Lịch sử commit repo đề Day 02 (`git log`, 07/11/2026 – 09/11/2026), ví dụ commit 5fef14b, 5a6fba0.
- [docs/01-worksheet.md](../../docs/01-worksheet.md) — template Problem Card và prompt phản biện.
