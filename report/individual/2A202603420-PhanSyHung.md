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
| 1 | Lặp lại | Khi bắt đầu một ngày lab mới, tôi muốn cả nhóm có repo chung với đúng tên, đủ quyền commit và mỗi người có file cá nhân, để bắt đầu CP0 đúng giờ | Nhóm trưởng, cả nhóm (3–4 người) | Mỗi ngày lab 1 lần; README có 5 lưu ý riêng chỉ cho bước fork/đặt tên/mời collaborator. [cần điền: số phút setup hôm nay, số tin nhắn hỏi qua lại trong nhóm] |
| 2 | Lặp lại | Khi đề bài hoặc hướng dẫn được sửa sau khi đã phát, tôi muốn biết chính xác chỗ nào đổi, để không làm theo bản cũ | Học viên cả lớp L3A/L3B | Repo đề Day 02 có 12 commit sửa đề từ 07/11 21:05 đến 09/11 00:30; 9 commit trong số đó sau 22:00 đêm trước lab (xem `git log`). [cần điền: số kênh tôi phải theo dõi (LMS, Discord, Zalo…), số lần đã làm theo bản cũ] |
| 3 | Tốn thời gian | Khi ôn lại một khái niệm từ buổi học 4 tiếng, tôi muốn tìm đúng đoạn giảng về khái niệm đó, để không phải tua lại cả recording | Học viên | [cần điền: số phút tua tìm lần gần nhất, số lần/tuần] |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi điền một mục trong báo cáo lab, tôi muốn biết mọi yêu cầu cho mục đó (nội dung, định dạng, điểm), để không mất điểm vì thiếu | Học viên, coach chấm bài | Yêu cầu của Day 02 nằm rải rác trong 8 file, tổng ~15.900 từ (README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION, 3 file docs; đếm bằng `wc -w`). [cần điền: số phút đối chiếu mỗi lab, số điểm từng mất vì thiếu mục] |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi lab dùng một framework tôi chưa biết (Mom Test, OST, Google PAIR…), tôi muốn nắm được ý chính đủ để áp dụng trong 15–30 phút, để không chậm tiến độ nhóm | Học viên | Day 02 dẫn ~10 framework (docs/03). [cần điền: số phút đọc, số nguồn mở cho 1 framework] |
| 6 | Pain từ người khác | Khi làm chung một repo, bạn cùng nhóm muốn biết file nào của mình và commit thế nào cho đúng, để không ghi đè hoặc conflict với người khác | Thành viên nhóm | Hôm nay template `MSSV_HoTen.md` đã bị xóa trên máy tôi trong khi README yêu cầu giữ lại đến khi mọi người có file. [cần điền: số câu hỏi kiểu này trong chat nhóm, số lần conflict] |
| 7 | Pain từ người khác | Khi nhóm chia việc qua chat, mỗi thành viên muốn biết ai làm phần nào và đến đâu, để không làm trùng hay bỏ sót | Cả nhóm | [cần điền: số lần làm trùng/bỏ sót ở các lab trước, dẫn chứng tin nhắn] |
| 8 | Tốn thời gian | Khi cuối buổi lab phải điền bảng "Dùng AI", tôi muốn nhớ chính xác mình đã dùng AI ở checkpoint nào, AI sai ở đâu và tôi sửa gì, để ghi đúng sự thật mà không mất điểm | Học viên cả lớp | Mỗi lab 1 lần; RULES §2 yêu cầu ghi lại *mỗi lần* dùng AI; bảng "Dùng AI" có 6 dòng checkpoint × 4 cột, trải trên buổi 240 phút. [cần điền: số phút điền bảng ở lab trước, số lần dùng AI mà tôi quên ghi] |

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
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: tìm lại hội thoại cũ và nhớ "AI sai ở đâu / tôi sửa gì" — chi tiết này không lưu ở đâu cả, chỉ nằm trong trí nhớ — [cần điền] phút |
| Impact (nếu không giải thì sao) | Bảng ghi chung chung ("AI giúp gợi ý ý tưởng") hoặc thiếu dòng → mất điểm phần dùng AI và tiêu chí "có ít nhất 1 chỗ AI sai và bạn đã sửa thế nào" (CP7); lấn thời gian viết reflection |
| Success metric (baseline → target) | Thời gian điền bảng "Dùng AI": [cần điền baseline] phút → ≤ 5 phút. Số lần dùng AI bị quên ghi/buổi: [cần điền] → 0. Số ô trong bảng có ví dụ cụ thể (không chung chung): [cần điền] → 100% dòng đã dùng AI |
| Phương án không dùng AI | Ghi log ngay sau mỗi lần dùng AI (1 dòng: checkpoint, dùng để làm gì, AI sai gì, tôi sửa gì) vào một file nháp hoặc thẳng vào bảng; đặt nhắc "ghi log" ở cuối mỗi checkpoint |
| Giả thuyết về AI (nếu có) | Tóm tắt lịch sử hội thoại thành nháp 4 cột — nhưng AI không biết tôi đã sửa gì trong báo cáo, nên vẫn phải tự ghi phần đó |
| Cảm nhận nhanh | **No AI / Rule** (thói quen ghi ngay + nhắc cuối mỗi checkpoint) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — [cần điền] phút, 1 lần/lab, trong 15' cuối buổi

[1. Mở bảng "Dùng AI": __'] → [2. Nhớ checkpoint nào đã dùng AI: __']
→ [3. Lục lịch sử chat từng app: __'] ← BOTTLENECK
→ [4. Đọc lại, xác định AI giúp/sai gì: __'] ← BOTTLENECK
→ [5. Nhớ mình đã sửa gì: __'] ← BOTTLENECK
→ [6. Viết 4 cột: __']
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
| Success metric (baseline → target) | Số mục bị chấm thiếu yêu cầu/lab: [cần điền] → 0. Thời gian gom yêu cầu/mục: [cần điền] → ≤ 2 phút |
| Phương án không dùng AI | Một checklist gộp mỗi checkpoint (đã có một phần ở "Tự kiểm tra"); tự làm bảng tra mục → file → dòng |
| Giả thuyết về AI (nếu có) | Tra cứu tài liệu lab theo câu hỏi, có dẫn nguồn file/dòng — chỉ đáng nếu checklist gộp vẫn thiếu |
| Cảm nhận nhanh | **No AI / Rule** (checklist) — Workflow nếu tài liệu đổi liên tục |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — [cần điền] phút cho mỗi mục báo cáo

[1. Mở template: __'] → [2. Đọc CHECKPOINTS: __'] → [3. Đọc worksheet: __']
→ [4. Đối chiếu RUBRIC: __'] ← BOTTLENECK (gom yêu cầu từ nhiều file)
→ [5. Xem bài mẫu: __'] → [6. Viết: __'] → [7. Tự kiểm: __']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm chung một repo, mỗi thành viên muốn biết file nào là của mình và commit thế nào cho đúng, để không ghi đè hoặc conflict với người khác |
| Actor | Thành viên nhóm 3–4 người, khác nhau về mức quen Git |
| Thời điểm / bối cảnh | Đầu buổi (tạo file cá nhân) và lúc nhiều người cùng sửa `group_report.md`, `TEAM.md` (CP3–CP7) |
| Quy trình hiện tại (3–7 bước) | 1. Nhóm trưởng fork + mời collaborator → 2. Thành viên chấp nhận lời mời, clone → 3. Tạo file cá nhân từ template → 4. Cùng sửa file nhóm → 5. Pull/push, gặp conflict → 6. Hỏi trên chat, sửa conflict |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5–6: xử lý conflict khi nhiều người sửa cùng `group_report.md` — [cần điền] phút/lần |
| Impact (nếu không giải thì sao) | Mất nội dung của người khác; commit sai tài khoản → không được tính đóng góp (RULES §3) |
| Success metric (baseline → target) | Số conflict/buổi: [cần điền] → ≤ 1. Số phút xử lý: [cần điền] → ≤ 5 |
| Phương án không dùng AI | Chia section `group_report.md` theo người phụ trách trong `TEAM.md`; quy ước "pull trước khi sửa"; 1 người merge file nhóm |
| Giả thuyết về AI (nếu có) | Không thấy cần — bài toán là phối hợp, không phải đọc/tổng hợp |
| Cảm nhận nhanh | **No AI** |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — [cần điền] phút/buổi

[1. Fork + mời: __'] → [2. Accept + clone: __'] → [3. Tạo file cá nhân: __']
→ [4. Cùng sửa file nhóm: __'] → [5. Pull/push gặp conflict: __'] ← BOTTLENECK
→ [6. Hỏi chat + sửa: __']
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
| [cần điền: chạy prompt "PM hoài nghi" (docs/01-worksheet.md) cho Card #1 mới và ghi điểm yếu AI chỉ ra] | | |

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
| CP1 Scan | Claude quét repo, gợi ý thêm problem theo 4 lăng kính, đếm commit sửa đề và số từ tài liệu | Lấy được bằng chứng đo được từ `git log` và `wc -w` thay vì cảm giác | AI không biết số phút/tần suất thật của tôi — phần dấu hiệu cá nhân AI để trống, không bịa được | [cần điền: tự bổ sung số liệu thật, bỏ ý nào] |
| CP2 Problem Card | Claude nháp 3 card + quy trình; đề xuất problem thay thế khi tôi bác card "đề thay đổi" | Gợi ý card "điền bảng Dùng AI" có bottleneck đo được và phương án No AI rõ | Ban đầu AI chọn card "đề thay đổi" vì có nhiều commit, nhưng không phân biệt commit trước buổi lab với thay đổi trong buổi lab — tôi phải tự chỉ ra; một số bước quy trình là AI suy luận | Đổi Card #1 sang problem #8; [cần điền: bước quy trình nào tôi sửa lại theo cách mình thực sự làm] |
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
