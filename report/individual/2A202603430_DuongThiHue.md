# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Dương Thị Huệ
- MSSV:2A202603430
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NhomABC100
- Link repo nhóm: https://github.com/KumaMichio/K5-L3-Day02-NhomABC100-DiscoveryProblemFraming

---

# 2. Scan problem (CP1)

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu giải quyết một bài toán nghiên cứu mới, tôi muốn tìm được tài liệu chứa thuật toán phù hợp mà không phải lặp đi lặp lại quá trình tìm kiếm và đọc nhiều tài liệu, để tiết kiệm thời gian nghiên cứu. | Sinh viên nghiên cứu, học viên cao học, nhà nghiên cứu. | Trong quá trình nghiên cứu, thường phải tìm kiếm và đọc nhiều bài báo, sách chuyên ngành. Cần ghi lại số tài liệu đã đọc và thời gian tìm được thuật toán phù hợp. |
| 2 | Tốn thời gian | Khi triển khai một thuật toán từ bài báo khoa học bằng MATLAB hoặc Python, tôi muốn chuyển đổi các công thức toán học thành chương trình nhanh chóng và chính xác, để giảm thời gian lập trình và sửa lỗi. | Sinh viên kỹ thuật, người làm nghiên cứu. | Cần ghi lại thời gian triển khai một thuật toán, số lần sửa code và số lỗi phát sinh. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm hiểu một chủ đề nghiên cứu mới, tôi muốn tổng hợp và so sánh thông tin từ nhiều bài báo khoa học, để hiểu các phương pháp hiện có và lựa chọn hướng nghiên cứu phù hợp. | Sinh viên làm khóa luận, học viên cao học, nhà nghiên cứu. | Phải đọc nhiều bài báo; thông tin về phương pháp, công thức và kết quả nằm ở nhiều phần khác nhau. Cần ghi lại số bài báo và thời gian tổng hợp. |
| 4 | Pain từ người khác | Khi làm việc nhóm trong một đề tài nghiên cứu, tôi muốn các thành viên chia sẻ và cập nhật tài liệu, tiến độ và kết quả một cách thống nhất, để tránh thất lạc thông tin và trùng lặp công việc. | Thành viên nhóm nghiên cứu, người hướng dẫn. | Có thể ghi nhận số lần thành viên phải hỏi lại thông tin, gửi lại tài liệu hoặc thực hiện trùng công việc. |
| 5 | Dễ sai sót | Khi thực hiện nhiều lần mô phỏng với các bộ tham số khác nhau, tôi muốn lưu trữ và theo dõi cấu hình cùng kết quả của từng lần chạy, để dễ dàng so sánh và tránh nhầm lẫn. | Sinh viên kỹ thuật, người làm nghiên cứu, kỹ sư mô phỏng. | Cần ghi lại số lần chạy mô phỏng, số bộ tham số và số lần phải chạy lại do nhầm lẫn hoặc thiếu dữ liệu. |

**Nếu có dùng AI để gợi ý thêm:**

- Ý tưởng giữ lại: Vấn đề triển khai thuật toán, tổng hợp tài liệu và quản lý kết quả mô phỏng vì có liên quan trực tiếp đến quá trình học tập và nghiên cứu kỹ thuật.
- Ý tưởng bỏ hoặc chưa lựa chọn: Những vấn đề chưa có trải nghiệm thực tế hoặc chưa xác định được mức độ ảnh hưởng. Không lựa chọn một vấn đề chỉ vì AI đề xuất rằng vấn đề đó có thể ứng dụng AI.

---

# 3. Top 3 Problem Cards + quy trình nháp (CP2)

## Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | **Tìm kiếm tài liệu chứa thuật toán phù hợp với bài toán nghiên cứu.** | Đây là vấn đề tôi trực tiếp gặp phải trong quá trình nghiên cứu. Tôi phải tìm kiếm, đọc nhiều bài báo và sách chuyên ngành mới có thể lựa chọn được thuật toán phù hợp. | Chưa xác định khó khăn lớn nhất nằm ở khâu tìm kiếm tài liệu, xác định thuật toán bên trong tài liệu hay đánh giá mức độ phù hợp. |
| 2 | **Triển khai thuật toán từ bài báo khoa học thành chương trình mô phỏng.** | Đây là công việc thường gặp khi nghiên cứu kỹ thuật, đặc biệt khi sử dụng MATLAB hoặc Python để kiểm chứng thuật toán. | Chưa xác định thời gian chủ yếu mất ở khâu hiểu công thức, viết code hay sửa lỗi. |
| 3 | **Tổng hợp và so sánh thông tin từ nhiều bài báo khoa học.** | Đây là công việc cần thiết khi tìm hiểu một chủ đề mới và xác định hướng nghiên cứu. | Chưa xác định bộ tiêu chí so sánh phù hợp và số lượng tài liệu cần tổng hợp. |

## Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu giải quyết một bài toán nghiên cứu mới, tôi muốn tìm được tài liệu chứa thuật toán phù hợp mà không phải lặp đi lặp lại quá trình tìm kiếm và đọc nhiều tài liệu, để tiết kiệm thời gian nghiên cứu. |
| Actor | Sinh viên nghiên cứu, học viên cao học, nhà nghiên cứu hoặc kỹ sư. |
| Thời điểm / bối cảnh | Khi bắt đầu một đề tài mới hoặc gặp một bài toán chưa biết phương pháp giải quyết; cần tham khảo sách và bài báo khoa học. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định bài toán cần giải quyết. 2. Xác định từ khóa chuyên ngành. 3. Tìm kiếm tài liệu trên Google Scholar, IEEE Xplore. 4. Đọc tiêu đề, abstract và introduction để lọc tài liệu. 5. Đọc phần methodology và các công thức liên quan. 6. So sánh thuật toán với yêu cầu bài toán. 7. Lựa chọn phương pháp phù hợp. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–6: Phải đọc nhiều tài liệu để tìm đúng phần trình bày thuật toán và đánh giá mức độ phù hợp. Thời gian cụ thể cần được đo qua trải nghiệm thực tế. |
| Impact (nếu không giải thì sao) | Tốn thời gian nghiên cứu, khó lựa chọn phương pháp, có thể bỏ sót thuật toán phù hợp hoặc chọn phương pháp không đáp ứng yêu cầu. |
| Success metric (baseline → target) | Thời gian trung bình để tìm được thuật toán phù hợp và số lượng tài liệu phải đọc. Mục tiêu dự kiến giảm 30% thời gian so với quy trình hiện tại sau khi đo baseline. |
| Phương án không dùng AI | Xây dựng bộ từ khóa tìm kiếm; sử dụng bộ lọc học thuật; đọc abstract và mục lục; lập bảng so sánh các thuật toán theo đầu vào, đầu ra, độ phức tạp và ưu nhược điểm. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ tìm kiếm tài liệu theo mô tả bài toán, xác định phần chứa thuật toán, trích xuất các bước thực hiện và so sánh mức độ phù hợp giữa các phương pháp. |
| Cảm nhận nhanh | Workflow / Chưa biết. Cần đánh giá xem AI hỗ trợ ở khâu nào và người nghiên cứu cần kiểm chứng kết quả ra sao. |

**Quy trình nháp hiện tại:**

```text
Xác định bài toán cần giải quyết
          ↓
Xác định từ khóa chuyên ngành
          ↓
Tìm kiếm sách và bài báo khoa học
          ↓
Đọc tiêu đề, abstract, introduction
          ↓
Đọc methodology và thuật toán
          ↓
So sánh các phương pháp
          ↓
Lựa chọn thuật toán phù hợp
          ↓
Thử triển khai và đánh giá
```

## Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi triển khai một thuật toán từ bài báo khoa học bằng MATLAB hoặc Python, tôi muốn chuyển đổi các công thức toán học thành chương trình nhanh chóng và chính xác, để giảm thời gian lập trình và sửa lỗi. |
| Actor | Sinh viên kỹ thuật, người làm nghiên cứu, kỹ sư phát triển thuật toán. |
| Thời điểm / bối cảnh | Sau khi đã lựa chọn được thuật toán và cần triển khai bằng MATLAB hoặc Python để mô phỏng, đánh giá. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc và hiểu thuật toán trong bài báo. 2. Xác định các biến và tham số. 3. Phân tích các công thức toán học. 4. Viết pseudocode. 5. Chuyển pseudocode thành chương trình. 6. Chạy thử và kiểm tra kết quả. 7. Sửa lỗi và hoàn thiện. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–5: Khó xác định ý nghĩa biến, điều kiện khởi tạo và chuyển đổi công thức thành code. Thời gian cụ thể cần được đo thực tế. |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian lập trình, phát sinh lỗi và có thể thu được kết quả mô phỏng không chính xác. |
| Success metric (baseline → target) | Thời gian triển khai một thuật toán, số lỗi cần sửa và số lần chạy lại. Mục tiêu dự kiến giảm 30% thời gian triển khai. |
| Phương án không dùng AI | Viết pseudocode trước khi lập trình; chia thuật toán thành các module nhỏ; kiểm tra từng công thức và đối chiếu với tài liệu gốc. |
| Giả thuyết về AI (nếu có) | AI có thể giải thích công thức, hỗ trợ viết code mẫu và tìm lỗi lập trình. Người nghiên cứu vẫn cần kiểm tra tính đúng đắn của code và kết quả. |
| Cảm nhận nhanh | Workflow. |

**Quy trình nháp hiện tại:**

```text
Đọc thuật toán trong bài báo
          ↓
Xác định biến và tham số
          ↓
Phân tích công thức toán học
          ↓
Viết pseudocode
          ↓
Chuyển thành MATLAB/Python
          ↓
Chạy thử và kiểm tra
          ↓
Sửa lỗi và hoàn thiện
```

## Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tìm hiểu một chủ đề nghiên cứu mới, tôi muốn tổng hợp và so sánh thông tin từ nhiều bài báo khoa học, để hiểu các phương pháp hiện có và lựa chọn hướng nghiên cứu phù hợp. |
| Actor | Sinh viên làm khóa luận, học viên cao học, nhà nghiên cứu. |
| Thời điểm / bối cảnh | Khi tìm hiểu tổng quan về một chủ đề hoặc chuẩn bị viết phần Literature Review. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định chủ đề cần tìm hiểu. 2. Tìm kiếm các bài báo liên quan. 3. Đọc từng bài báo và ghi chú phương pháp. 4. Trích xuất thông tin quan trọng. 5. Phân loại các phương pháp. 6. So sánh ưu điểm, hạn chế và kết quả. 7. Tổng hợp nhận xét. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–6: Thông tin nằm rải rác trong nhiều tài liệu, cách trình bày không đồng nhất nên khó tổng hợp và đối chiếu. Cần đo thời gian thực tế. |
| Impact (nếu không giải thì sao) | Khó có cái nhìn tổng quan về lĩnh vực, có thể bỏ sót phương pháp quan trọng và mất thời gian viết báo cáo nghiên cứu. |
| Success metric (baseline → target) | Thời gian tổng hợp một nhóm 5–10 bài báo; tỷ lệ thông tin được phân loại đầy đủ và có nguồn đối chiếu. Mục tiêu dự kiến giảm 30% thời gian tổng hợp. |
| Phương án không dùng AI | Sử dụng bảng tổng hợp tài liệu với các cột: tên bài báo, năm công bố, bài toán, phương pháp, ưu điểm, hạn chế và kết quả. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ trích xuất thông tin, phân loại và lập bảng so sánh từ nhiều tài liệu. |
| Cảm nhận nhanh | Workflow. |

**Quy trình nháp hiện tại:**

```text
Xác định chủ đề nghiên cứu
          ↓
Tìm kiếm bài báo liên quan
          ↓
Đọc và ghi chú từng bài
          ↓
Trích xuất thông tin quan trọng
          ↓
Phân loại phương pháp
          ↓
So sánh ưu nhược điểm
          ↓
Tổng hợp nhận xét
```

## Card muốn pitch nhất

- **Card số:** 1
- **Vì sao:** Đây là vấn đề tôi trực tiếp gặp phải khi thực hiện nghiên cứu kỹ thuật. Khi giải quyết một bài toán, tôi thường phải tìm kiếm và đọc nhiều bài báo, sách chuyên ngành để xác định tài liệu nào có thuật toán phù hợp. Ngay cả khi tìm được tài liệu có chủ đề liên quan, tôi vẫn cần đọc sâu hơn để tìm phần trình bày thuật toán và đánh giá khả năng áp dụng. Quá trình này mất nhiều thời gian và ảnh hưởng đến tiến độ nghiên cứu.
- **Câu hỏi muốn nhóm phản biện:** Liệu khó khăn chính nằm ở việc tìm kiếm đúng tài liệu, xác định thuật toán bên trong tài liệu hay đánh giá mức độ phù hợp của thuật toán với bài toán cụ thể? Có nên xem đây là một vấn đề thống nhất hay tách thành các vấn đề nhỏ?

## AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Problem đang mô tả khá rộng, chưa phân biệt rõ khó khăn trong tìm kiếm tài liệu và khó khăn trong việc xác định thuật toán bên trong tài liệu. | Đồng ý | Làm rõ quy trình từ tìm kiếm tài liệu đến đọc, xác định và đánh giá thuật toán. |
| Chưa có bằng chứng định lượng về thời gian thực tế dành cho việc tìm kiếm và đọc tài liệu. | Đồng ý | Bổ sung kế hoạch ghi lại thời gian và số lượng tài liệu đã đọc trong các lần nghiên cứu tiếp theo. |
| Chưa xác định rõ thế nào là một thuật toán phù hợp với bài toán. | Đồng ý | Bổ sung các tiêu chí cần xem xét như đầu vào, đầu ra, giả thiết, độ phức tạp tính toán và khả năng đáp ứng yêu cầu bài toán. |
| Có thể giải quyết một phần vấn đề bằng công cụ tìm kiếm học thuật và bảng tổng hợp tài liệu mà không cần AI. | Đồng ý | Bổ sung phương án không dùng AI để đánh giá xem AI có thực sự tạo ra giá trị bổ sung hay không. |

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
