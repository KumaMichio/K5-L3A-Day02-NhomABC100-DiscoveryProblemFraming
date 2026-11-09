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
| **Pitch Problem Card** | Tôi tham gia lắng nghe và phân tích các Problem Card của những thành viên trong nhóm. Cụ thể, tôi tìm hiểu bốn nhóm vấn đề chính: (1) tổng hợp tiến độ và rủi ro công việc từ GitHub, Google Sheets và Zalo; (2) tìm lại các quyết định, thông tin và nội dung thảo luận cũ trên Discord; (3) hỗ trợ viết phần Kết quả và Thảo luận trong báo cáo lab; (4) tổng hợp tài liệu từ nhiều nguồn để phục vụ ôn thi. Khi nghe từng bài trình bày, tôi chú ý đến đối tượng gặp vấn đề, hoàn cảnh phát sinh, cách giải quyết hiện tại và thời gian mà người dùng phải bỏ ra. | Giúp tôi và nhóm nhận diện được các vấn đề thực tế trong quá trình học tập, nghiên cứu và làm việc nhóm. Đặc biệt, tôi nhận thấy các vấn đề tuy khác nhau về mục đích nhưng đều có điểm chung là người dùng phải xử lý lượng thông tin lớn, phân tán ở nhiều nền tảng và thực hiện nhiều thao tác thủ công. |
| **Phản biện bài của bạn khác** | Tôi tập trung đặt câu hỏi về tính cần thiết của giải pháp AI đối với từng Problem Card. Ví dụ, với vấn đề tổng hợp tiến độ từ GitHub, Google Sheets và Zalo, tôi cho rằng cần phân biệt giữa việc thu thập trạng thái công việc và việc phân tích tiến độ, phát hiện rủi ro. Công đoạn thu thập có thể giải quyết bằng cách thống nhất biểu mẫu cập nhật hoặc kết nối dữ liệu, trong khi việc đánh giá nguy cơ chậm tiến độ mới có thể cần đến khả năng phân tích của AI. Với bài toán tìm kiếm thông tin trên Discord, tôi chú ý đến việc liệu người dùng thực sự không tìm thấy thông tin hay do chưa có cách tổ chức, đánh dấu và lưu trữ các quyết định cũ. | Giúp người đề xuất nhìn nhận lại vấn đề từ nguyên nhân gốc thay vì mặc định rằng cần xây dựng một công cụ AI. Đồng thời, các câu hỏi phản biện giúp xác định rõ phần công việc nào đang gây khó khăn và liệu có phương án đơn giản hơn để giải quyết hay không. |
| **Nhận phản biện** | Tôi tiếp nhận các ý kiến phản biện và xem xét lại cách xác định vấn đề. Chẳng hạn, đối với bài toán tổng hợp tiến độ nhóm, tôi nhận thấy không nên chỉ tính toàn bộ thời gian dành cho việc cập nhật và tổng hợp mà cần tách thành các bước: thu thập thông tin từ từng nền tảng, kiểm tra tính đầy đủ, đối chiếu trạng thái công việc, xác định công việc bị chậm và tổng hợp báo cáo. Tương tự, với bài toán viết báo cáo lab, cần phân biệt thời gian đọc kết quả thí nghiệm, phân tích số liệu, xây dựng lập luận và diễn đạt thành văn bản. | Giúp tôi hiểu rằng một vấn đề có thể bao gồm nhiều công đoạn với những nguyên nhân khác nhau. Việc phân tách quy trình giúp xác định chính xác bottleneck, tránh đưa ra giải pháp chỉ cải thiện một bước nhưng không giải quyết được khó khăn cốt lõi. |
| **Gom cluster / cây OST** | Tôi tham gia xem xét mối liên hệ giữa các Problem Card và phân loại chúng theo nhu cầu thực tế. Tôi nhận thấy có thể chia thành các cụm: (1) tìm kiếm và truy xuất thông tin, đại diện là bài toán tìm lại quyết định cũ trên Discord; (2) tổng hợp thông tin từ nhiều nguồn, đại diện là bài toán tổng hợp tiến độ từ GitHub, Google Sheets và Zalo; (3) xử lý và tạo nội dung học thuật, đại diện là bài toán viết phần Kết quả và Thảo luận của báo cáo lab; (4) tổ chức và khai thác tài liệu học tập, đại diện là bài toán tổng hợp tài liệu ôn thi. | Giúp nhóm nhìn thấy mối liên hệ giữa các vấn đề riêng lẻ và xác định những nhu cầu chung có thể tiếp tục phát triển thành các nhánh trong cây OST. Qua đó, nhóm có thể đánh giá vấn đề ở cấp độ nhu cầu người dùng thay vì chỉ tập trung vào từng công cụ hoặc ý tưởng giải pháp riêng biệt. |
| **Chọn candidate problem** | Tôi tham gia so sánh các vấn đề dựa trên mức độ thường xuyên, thời gian xử lý, số người bị ảnh hưởng, mức độ nghiêm trọng và khả năng đo lường. Tôi đặc biệt chú ý đến những ví dụ có số liệu cụ thể: tìm kiếm thông tin cũ trên Discord mất khoảng 8–10 phút/lần; tổng hợp tiến độ nhóm mất khoảng 70 phút/tuần; viết phần Kết quả và Thảo luận mất khoảng 35–50 phút/lần. Tôi cho rằng cần xem xét thêm tần suất phát sinh để đánh giá tổng thời gian lãng phí trong một tuần hoặc một tháng, thay vì chỉ so sánh thời gian của một lần thực hiện. | Giúp quá trình lựa chọn candidate problem có căn cứ định lượng hơn. Ví dụ, một thao tác mất 8–10 phút có thể chưa phải vấn đề lớn nếu hiếm khi xảy ra, nhưng nếu diễn ra nhiều lần thì tổng thời gian bị lãng phí có thể đáng kể. Nhờ đó, nhóm có cơ sở đánh giá mức độ ưu tiên của từng vấn đề. |
| **Kiểm chứng / Research** | Tôi tham gia xem xét các bằng chứng được sử dụng để chứng minh vấn đề, đặc biệt là thời gian thực hiện và quy trình làm việc thực tế. Tôi chú ý đến việc các con số như 70 phút/tuần để tổng hợp tiến độ, 8–10 phút/lần để tìm thông tin trên Discord và 35–50 phút/lần để viết báo cáo cần được gắn với hoạt động cụ thể. Ngoài ra, tôi xem xét những giải pháp hiện có như chức năng tìm kiếm của Discord, bộ lọc và bảng theo dõi trên Google Sheets, lịch sử hoạt động trên GitHub, các mẫu báo cáo và công cụ quản lý tài liệu. | Giúp nhóm phân biệt giữa khó khăn thực sự và những bất tiện có thể giải quyết bằng tính năng sẵn có. Tôi nhận thấy cần có bằng chứng về thời gian, tần suất, lỗi hoặc thông tin bị bỏ sót để chứng minh giá trị của giải pháp, thay vì chỉ dựa vào nhận xét chủ quan của người dùng. |
| **Quy trình nhóm** | Tôi tham gia phân tích quy trình hiện tại (As-Is) của các vấn đề được đề xuất. Với bài toán tổng hợp tiến độ, tôi xác định các bước gồm: thành viên cập nhật công việc trên từng nền tảng, người phụ trách thu thập dữ liệu, đối chiếu trạng thái, kiểm tra công việc tồn đọng và lập báo cáo. Với bài toán tìm kiếm thông tin Discord, quy trình gồm: xác định nội dung cần tìm, nhớ lại thời điểm hoặc người tham gia thảo luận, tìm kiếm trong lịch sử tin nhắn, đọc các kết quả và xác định đâu là quyết định cuối cùng. | Giúp nhóm hình dung rõ những bước đang được thực hiện thủ công và vị trí phát sinh thời gian chờ, thao tác lặp lại hoặc nguy cơ bỏ sót thông tin. Đây cũng là cơ sở để xây dựng quy trình To-Be và xác định phần nào có thể tự động hóa. |
| **Problem Statement** | Tôi tham gia xem xét cách chuyển các ý tưởng ban đầu thành Problem Statement có đầy đủ Actor, Context, Bottleneck, Impact, Success Metric và Boundary. Ví dụ, với vấn đề tổng hợp tiến độ, Actor là người phụ trách theo dõi công việc nhóm; Context là khi thông tin cập nhật nằm rải rác trên GitHub, Google Sheets và Zalo; Bottleneck là việc phải thu thập, đối chiếu và tổng hợp thủ công; Impact là mất thời gian và có nguy cơ bỏ sót công việc chậm tiến độ. Tôi cho rằng cần xác định thêm chỉ số như thời gian hoàn thành báo cáo, tỷ lệ thông tin được tổng hợp đầy đủ và khả năng phát hiện công việc có nguy cơ trễ hạn. | Giúp Problem Statement phản ánh đúng khó khăn của người dùng, có đối tượng và bối cảnh cụ thể. Đồng thời, việc xác định Success Metric giúp nhóm có thể đánh giá giải pháp sau khi thử nghiệm thay vì chỉ kết luận chung chung rằng công cụ hoạt động tốt. |
| **Mức can thiệp AI** | Tôi tham gia phân tích các mức No AI, Rule, Workflow và Agent dựa trên đặc điểm của từng vấn đề. Chẳng hạn, việc chuẩn hóa biểu mẫu cập nhật tiến độ hoặc nhắc nhở thành viên khi chưa cập nhật có thể sử dụng Rule. Việc thu thập dữ liệu từ nhiều nguồn, phân loại nội dung, tóm tắt tiến độ và tạo báo cáo có thể phát triển thành Workflow kết hợp AI. Với việc tìm kiếm quyết định cũ trên Discord, có thể cân nhắc tìm kiếm ngữ nghĩa và tóm tắt ngữ cảnh, nhưng vẫn cần cung cấp nguồn tin để người dùng kiểm tra. Đối với báo cáo lab, AI có thể hỗ trợ tạo bản nháp và diễn đạt, nhưng không nên tự suy diễn kết quả thí nghiệm. | Giúp nhóm lựa chọn mức độ ứng dụng AI phù hợp với từng công đoạn. Tôi nhận thấy không nhất thiết phải xây dựng một Agent có khả năng tự thực hiện toàn bộ quy trình; trong nhiều trường hợp, Workflow có kiểm soát và có sự xác nhận của con người sẽ phù hợp hơn. |
| **Quyết định** | Tôi tham gia cân nhắc giữa giá trị mang lại, chi phí triển khai, khả năng truy cập dữ liệu và độ tin cậy của kết quả. Ví dụ, đối với bài toán tổng hợp tiến độ, cần xem xét liệu hệ thống có thể lấy được dữ liệu từ GitHub, Google Sheets và Zalo hay không. Đối với bài toán Discord, cần chú ý đến quyền truy cập server, lịch sử tin nhắn và khả năng truy xuất đúng quyết định đã được thống nhất. Đối với báo cáo lab, cần đảm bảo AI không tự tạo ra số liệu hoặc kết luận không có trong kết quả thí nghiệm. | Giúp tôi hiểu rằng quyết định triển khai không chỉ phụ thuộc vào việc AI có thể thực hiện một tác vụ hay không, mà còn phụ thuộc vào dữ liệu, quyền truy cập, độ chính xác và khả năng kiểm soát. Tôi ủng hộ việc thử nghiệm trong phạm vi nhỏ, có tiêu chí đánh giá rõ ràng và có người kiểm tra đầu ra trước khi mở rộng. |

### Nhận xét cá nhân

Qua các checkpoint từ CP3 đến CP7, tôi nhận thấy bản thân đã thay đổi cách tiếp cận khi đánh giá một bài toán AI. Ban đầu, khi nghe các vấn đề như tổng hợp tiến độ từ GitHub, Google Sheets và Zalo, tìm lại quyết định cũ trên Discord hay hỗ trợ viết báo cáo lab, tôi thường chú ý đến việc có thể xây dựng công cụ nào để giải quyết. Tuy nhiên, qua quá trình phân tích và phản biện các Problem Card của các thành viên, tôi hiểu rằng cần xác định chính xác nguyên nhân khiến người dùng mất thời gian trước khi lựa chọn giải pháp.

Một điều tôi nhận ra là không nên đánh giá mức độ nghiêm trọng của vấn đề chỉ dựa trên thời gian của một lần thực hiện. Ví dụ, việc tìm lại thông tin trên Discord mất 8–10 phút/lần cần được xem xét cùng tần suất xảy ra; việc tổng hợp tiến độ mất 70 phút/tuần cần được phân tích xem thời gian đó chủ yếu dành cho thu thập, đối chiếu hay đánh giá rủi ro. Tương tự, đối với việc viết phần Kết quả và Thảo luận mất 35–50 phút/lần, cần xác định công đoạn nào có thể được hỗ trợ mà không làm ảnh hưởng đến tính chính xác của nội dung học thuật.

Tôi cũng học được cách phân biệt giữa vấn đề và giải pháp. Chẳng hạn, việc người dùng mất thời gian tìm thông tin không đồng nghĩa với việc phải xây dựng một hệ thống AI mới; đôi khi chỉ cần tổ chức lại dữ liệu, thống nhất cách đặt tên, sử dụng chức năng tìm kiếm hoặc chuẩn hóa quy trình là đã có thể cải thiện đáng kể. AI chỉ thực sự có giá trị khi nó giải quyết được phần công việc mà các phương pháp hiện tại còn hạn chế.

**Sau quá trình này, tôi rút ra ba kinh nghiệm chính:**
1. **Xác định đúng vấn đề:** Phải làm rõ Actor, Context, Bottleneck và Impact trước khi đề xuất giải pháp.
2. **Đánh giá bằng bằng chứng:** Cần có số liệu về thời gian, tần suất, số người bị ảnh hưởng và mức độ sai sót để chứng minh vấn đề.
3. **Lựa chọn mức AI phù hợp:** Không phải vấn đề nào cũng cần Agent; cần ưu tiên giải pháp đơn giản, khả thi và có thể kiểm chứng hiệu quả.

Tôi cho rằng những kiến thức này không chỉ hữu ích đối với bài tập nhóm hiện tại mà còn giúp tôi có tư duy thực tế hơn khi tham gia các dự án kỹ thuật sau này: bắt đầu từ nhu cầu của người dùng, phân tích quy trình, xác định điểm nghẽn và chỉ lựa chọn công nghệ khi thực sự cần thiết.

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
Khi nghe top 3, tôi nhận ra cùng 1 vấn đề còn tồn tại thêm rất nhiều vấn đề nhỏ khác cần giải quyết. Mỗi ý tưởng, có thể nghe rất hữu ích và quan trọng, nhưng cần check lại và quyết định xem thứ tự giải quyết các vấn đề nhỏ trong đó để chọn ra vấn đề quan trọng nhất rồi giải quyết dần. Nếu vấn đề không đủ lớn thì có thể bỏ qua để tiết kiệm tài nguyên và thời gian.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, đôi lúc bị lao vào giải quyết vấn đề ngay mà chưa xem xét xem vấn đề có thật sự cần giải quyết hay không. Lúc đó nhóm có nhận ra, và check lại các list vấn đề và chọn vấn đề cần ưu tiên giải trước.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
 Khi nhóm thảo luận về việc ứng dụng AI để tóm tắt thông tin trong Zalo/Discord. Ban đầu, tôi nghiêng về hướng sử dụng AI vì nghĩ rằng nó sẽ giúp tiết kiệm nhiều thời gian. Nhưng sau khi xem xét việc ghim những quyết định quan trọng hoặc ghi trực tiếp vào bảng phân công có giải quyết được vấn đề hay không, tôi nhận ra không phải trường hợp nào cũng cần AI. Nếu nhóm ít thành viên, trao đổi trực tiếp và có cách ghi chép rõ ràng thì giải pháp thủ công thì đã đủ hiệu quả mà không cần dùng AI.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Quá trình kiểm chứng có làm tôi bất ngờ vì kết quả khảo sát rất khác so với suy nghĩ ban đầu. Khảo sát thực tế khác rất nhiều so với lý thuyết.
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là xác định đúng vấn đề cốt lõi và giới hạn phạm vi sao cho đủ cụ thể
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ dành nhiều thời gian hơn để phân tích và kiểm chứng từng vấn đề trước khi lựa chọn. Tôi cũng muốn nhóm xác định rõ bước nghẽn và thử các cách giải quyết đơn giản trước khi dùng AI. Khi phản biện, tôi sẽ đặt nhiều câu hỏi hơn về mức độ cần thiết của vấn đề, chẳng hạn như vấn đề này xảy ra bao nhiêu lần, ảnh hưởng đến bao nhiêu người và nếu không giải quyết thì hậu quả có thực sự lớn không. Tôi cũng sẽ chú ý hơn đến việc AI có thể tạo ra lỗi gì, ai chịu trách nhiệm kiểm tra và liệu lợi ích mang lại có xứng đáng với thời gian triển khai hay không.
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.



## 7. Tài liệu tham khảo

-
