# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Việt Thịnh
- MSSV: 2A202603661
- Email trường (không bắt buộc, repo có thể để public): 26ai.thinhtv@vinuni.edu.vn
- Tên nhóm: Trustmebro
- Link repo nhóm: https://github.com/Tsou0911/K5-L3A-DAY02-Trustmebro-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Pain từ người khác |Khi tôi muốn phát triển tính năng mới và đưa các requirement cho designer, designer muốn rõ ràng vấn đề để không phải hỏi lại |PM, Designer, Developer |Mỗi khi làm thì designer phải hỏi lại 2-3 lần |
| 2 |Pain từ người khác |Mỗi khi tôi code xong 1 task nào đó, đã đẩy lên môi trường dev, nhưng do mới đi làm nên mắc rất nhiều lỗi cơ bản như (convention code, format code) làm tốn thời gian review của tech lead, thay vào đó tech lead có thể dành thời gian review logic hơn |Developer, Tech Lead | |
| 3 |Tốn thời gian |Khi tôi gia nhập 1 công ty startup mới, không có tài liệu để tôi đọc về dự án |Developer |Tôi phải đi đọc code base suốt 1 tuần để có thể hiểu, sau đó lúc vào làm phát triển tính năng mới cũng phải đọc lại lần nữa để có thể follow theo code base |
| 4 |Cần đọc, tổng hợp nhiều thông tin |Khi tôi nhận một bug report từ QA hoặc khách hàng (kèm log, screenshot, mô tả rời rạc), tôi muốn nhanh chóng khoanh vùng được nguyên nhân và đoạn code liên quan, để sửa lỗi mà không phải lần mò qua nhiều file và nhiều nguồn thông tin |Developer, QA |Mỗi bug mất khoảng 1-3 giờ chỉ để tái hiện và xác định đúng chỗ lỗi; xảy ra vài lần mỗi tuần; phải hỏi lại QA để lấy thêm thông tin về bước tái hiện |
| 5 |Lặp lại |Khi tôi viết một tính năng mới, tôi muốn có sẵn khung code, test và cấu trúc theo đúng convention của dự án, để không phải viết lại phần boilerplate (API call, xử lý lỗi, form, unit test) giống nhau mỗi lần |Developer |Mỗi tính năng tốn khoảng 1-2 giờ cho phần boilerplate; lặp lại ở mọi task; code mỗi người viết một kiểu nên khó đồng nhất |
| 6 |Tốn thời gian |Khi tôi cần cập nhật tiến độ cho PM (daily standup, báo cáo sprint, ghi chú release), tôi muốn tổng hợp tự động từ commit, PR và task đã làm, để không mất thời gian ngồi nhớ lại và viết tay |Developer, PM |Mỗi ngày mất 10-15 phút cho standup, cuối sprint mất thêm 1-2 giờ viết báo cáo; thông tin hay thiếu hoặc không khớp với thực tế code |
| 7 |Pain từ người khác |Khi PM hoặc stakeholder đổi yêu cầu giữa sprint hoặc mô tả yêu cầu mơ hồ, tôi muốn có chỗ ghi lại rõ yêu cầu và những thay đổi, để không phải làm lại phần đã xong hoặc tranh cãi về việc “ban đầu yêu cầu là gì” |Developer, PM, Designer |Cứ vài sprint lại có task phải làm lại một phần; mất 0,5-2 ngày công cho mỗi lần đổi yêu cầu; không có tài liệu để đối chiếu |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-Tôi dùng AI đển tạo ra gợi ý từ 4-7. Theo tôi thì nên giữ lại 4 và bỏ đi 5, 6, 7. Gợi ý 5 thì có pain thật nhưng khá chung chung, mơ hồ. Gợi ý 7 thì trùng với gợi ý 1 của tôi viết. Gợi ý 6 thì hiện nay có nhiều công cụ như Jira có thể tracking được những gì đã làm

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

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
