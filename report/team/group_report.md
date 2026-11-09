# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Trustmebro
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Dev mới mất nhiều thời gian tìm hiểu hệ thống của công ty vì tài liệu có thể thiếu hoặc không tồn tại. Họ phải tự lần mò đọc mã nguồn hoặc hỏi đồng nghiệp, nhưng câu trả lời không phải lúc nào cũng đầy đủ, khiến quá trình làm việc chậm hơn
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Lê hữu Toàn | Khi nhận câu hỏi thường gặp từ khách hàng tôi muốn tôi muốn trả lời nhanh và đúng thông tin, để khách hàng sớm đc giải quyết vấn đề | Nhân viên hỗ trợ, khách hàng | lặp lại | |
| 2 | Lê hữu Toàn | Khi cần thông tin trong nhiều tài liệu nội bộ, tôi muốn tìm được câu trả lời nhanh chóng để không bị mất nhiều thời gian | Nhân viên mới, nhân viên vận hành | Cần đọc, tổng hợp nhiều thông tin | |
| 3 | Lê hữu Toàn | khi chuẩn bị cải thiện sản phẩm, tôi muốn hiểu khách hàng đang gặp khó khăn gì để đề xuất giải quyết đúng yêu cầu | Nhóm hỗ trợ, nhóm sản phẩm | Cần đọc, tổng hợp nhiều thông tin | |
| 4 | Vũ Lê Đức | Trong khoảng 2 tuần đầu tại nơi thuê, tôi muốn tìm quán ăn hợp ngân sách và gần chỗ ở, để không chi vượt kỳ vọng hay phải đi xa | Sinh viên | Thiếu thông tin giá và khoảng cách thật khi chọn | (Lê Hữu Toàn) Tại sao không sử dụng Google Map để tìm kiếm? |
| 5 | Vũ Lê Đức | Khi tới 9h sáng Thứ Ba, Non-tech Manager muốn tổng hợp tiến độ của Dev Team từ tất cả file report, để báo cáo lên Technical Manager đầy đủ và đúng giờ | Non-tech Manager, Technical Manager | Chờ dev bổ sung, khoảng 15p và trong lúc report phải check nhiều file | (Trần Viết Thịnh) Mốc thời gian chưa rõ là khi nào thì Non-tech Manager biết để tôngt hợp tiến độ của Dev Team? |
| 6 | Vũ Lê Đức | Khi cập nhật tiến độ, tôi muốn chỉ nhập một lần, để không phải viết lại ở Jira, file report và chat, và báo cáo không bị thiếu hoặc lệch | Dev, Non-Tech Manager | Cùng một lúc phải nhập 3 nơi để file report | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian dev mới cần để hiểu công ty và dự án trước khi bắt đầu xử lý công việc
├── Opportunity A: Dev mới mất thời gian tìm thông tin vì tài liệu nằm rải rác ở nhiều nơi
├── Opportunity B: Dev mới khó biết tài liệu nào đầy đủ, mới nhất và đáng tin cậy
└── Opportunity C: Khi thiếu thông tin, dev mới khó biết cần hỏi ai và phải tự lần theo code
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | dev mới thường mất nhiều thời gian để tìm hiểu cấu trúc và các vận hành hệ thống | value | 5 | 2 | có |
| 2 | thông tin thường được rải trong nhiều tài liệu | value | 4 | 3 | có |
| 3 | thời gian kéo dài do khó tìm thông tin | value | 4 | 2 | có |
| 4 | sử dụng ai để tra cứu dữ liệu nội bộ |Viability| 5 | 1 |- |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:dev mới mất nhiều thời gian tìm hiểu hệ thống vì thông tin nằm rải rác; khó khăn chính là tìm đúng thông tin, và một nơi tra cứu tập trung có thể giúp họ tìm câu trả lời nhanh hơn

### 3.2. Kiểm chứng

Cách đã dùng: Khảo sát trực tiếp bằng cách đặt câu hỏi cho các nhóm

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi | Các bạn dev đã bắt đầu đi làm |
| Câu nói đáng nhớ nhất | "Nhiều nhất 1 tháng 3 lần phải đọc các tài liệu liên quan đến features" |
| Lần gần nhất gặp vấn đề này | 5 tháng trước, đọc lại source mất khoảng 1 buổi (4 tiếng) |
| Hiện đang xử lý bằng cách nào | Hỏi lại người trước về flow và đọc thêm tài liệu liên quan đến features đang làm |
| Mất bao lâu, bao lần | Tìm hiểu ít nhất 1 buổi (4 tiếng), tuỳ theo tháng, nhiều nhất là 3 lần 1 tháng |
| Insight | Pain target đúng được features đang làm và các phần liên đới, không phải toàn bộ codebase của project |

Tổng hợp:

| Nguồn | Số người - Số nhóm | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Khảo sát | 24 - 4 | 7/24 người đã từng đi làm đều gặp phải việc mất thời gian đọc và tìm hiểu cho features đang làm | - |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — khoảng 4 tiếng/lần tìm hiểu feature

[1 Nhận task, xác định phần cần tìm hiểu: 15']
→ [2 Đọc kiến trúc và quy ước dự án: 45']
→ [3 Tìm tài liệu về feature: 60']
→ [4 Đọc code và lần theo feature liên quan: 90'] ← BOTTLENECK
→ [5 Hỏi đồng nghiệp, xác nhận cách hiểu: 30']


```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 |Dev mới |Task được giao|Xác định feature cần tìm hiểu |Ước tính 15 phút |Xác định phạm vi cần đọc |
| 2 | Dev mới|Tài liệu dự án |Hiểu kiến trúc và quy ước cơ bản |Ước tính 45 phút |Tài liệu có thể thiếu |
| 3 |Dev mới |Tên feature, tài liệu liên quan |Thông tin ban đầu về feature | Ước tính 60 phút|Khó biết tài liệu nào liên quan |
| 4 |Dev mới |Mã nguồn, feature liên quan |Hiểu flow và các phần liên đới |Ước tính 90 phút |Phải tự lần theo code |
| 5 |Dev mới |Câu hỏi chưa rõ |Xác nhận cách hiểu |Ước tính 30 phút |Có thể phải chờ lead |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — mục tiêu dưới 2 tiếng/lần tìm hiểu

[1 Dev nhập tên feature và câu hỏi: 5']               ← CON NGƯỜI
→ [2 Tìm tài liệu và code liên quan: 10']             ← RULE
→ [3 Tóm tắt flow, kiến trúc và liên kết nguồn: 10']  ← AI
→ [4 Dev kiểm tra nguồn, hỏi người hướng dẫn nếu thiếu: 30'] ← CON NGƯỜI
→ [5 Dev đọc sâu phần liên quan và bắt đầu task: 60'] ← CON NGƯỜI
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước |5 |5 |Một số bước tìm và tổng hợp được hỗ trợ |
| Tổng thời gian |Khoảng 4 tiếng	 |Dưới 2 tiếng	 | |
| Số bước thủ công | 5/5|3/5 |Dev vẫn kiểm chứng và đọc phần code cần thiết |
| Bottleneck chính |Tự tìm và lần theo code feature liên quan |Dev kiểm tra độ phù hợp của nguồn và tóm tắt |Cần xác nhận nguồn trước khi áp dụng |
| Rủi ro mới phát sinh | |AI bỏ sót hoặc diễn giải sai flow |dev kiểm tra và hỏi người hướng dẫn khi chưa chắc chắn|

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Dev mới dưới 1 năm kinh nghiệm vào dự án, cần tìm hiểu một feature trước khi bắt đầu làm task đầu tiên |
| **Quy trình** | Nhận task → đọc kiến trúc & quy ước → tìm tài liệu feature → đọc code và lần theo feature liên quan → hỏi đồng nghiệp để xác nhận cách hiểu (5 bước, hiện khoảng 240 phút/feature |
| **Bottleneck** | Bước 4 (90p) là nút thắt chính: dev phải tự lần theo code để hiểu flow và các phần liên đới, nên khó viết đúng quy ước và sợ ảnh hưởng feature khác. Bước 2-3 (105p) là nút thắt phụ: tài liệu thiếu, khó biết tài liệu nào liên quan |
| **Impact** | Mỗi feature mất khoảng 4h chỉ để tìm hiểu, trước khi viết dòng code đầu tiên. Khi phải tìm hiểu nhiều feature trong tuần, dev mất 4-8h và phải lùi deadline các việc khác. Bước 5 còn bị chặn chờ lead phản hồi |
| **Success Metric** | Tra cứu tài liệu (bước 2+3): giảm 105p xuống 50p. Đọc code và lần theo feature (bước 4): giảm 90p xuống 60p. Tổng thời gian tìm hiểu: giảm 240p xuống 155p. Đo bằng bấm giờ từng bước khi dev mới tìm hiểu một feature thật |
| **Boundary** | AI không được bịa ra cấu trúc khi codebase chưa đủ hoặc thiếu code. Dev mới cần hỏi người hướng dẫn để xác nhận thông tin sau khi đã đọc hiểu |

Phản biện nhận được từ AI và nhóm có đồng ý không:
- Bottleneck đang gom chung các bước lại và mỗi bước khác nhau cần có giải pháp khác nhau.
- Boundary chưa rõ nghĩa khi xác nhận như thế nào là "không bịa".
</br>=> Nhóm đồng ý và bổ sung vào v1

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
| **Actor** | Dev mới dưới 1 năm kinh nghiệm vào dự án , cần tìm hiểu một feature trước khi làm task đầu tiên |
| **Quy trình** | 5 bước: (1) nhận task, xác định phạm vi → (2) đọc kiến trúc & quy ước → (3) tìm tài liệu feature → (4) đọc code, lần theo feature liên quan → (5) hỏi đồng nghiệp xác nhận. Hiện khoảng 240 phút/feature (ước tính) |
| **Bottleneck** | Chính: bước 4 (90p), dev phải tự lần theo code để hiểu flow và các phần liên đới, nên khó viết đúng quy ước và dễ ảnh hưởng feature khác </br>Phụ: bước 2-3 (105p), tài liệu có thể thiếu và khó biết tài liệu nào liên quan |
| **Impact** | Mỗi feature mất khoảng 4h chỉ để tìm hiểu, trước khi viết dòng code đầu tiên. Khi phải tìm hiểu nhiều feature trong tuần, dev mất 4-8h và phải lùi deadline các việc khác. Bước 5 còn bị chặn chờ lead phản hồi |
| **Success Metric** | Tra cứu tài liệu (bước 2+3): giảm 105p xuống 50p. Đọc code và lần theo feature (bước 4): giảm 90p xuống 60p. Tổng thời gian tìm hiểu: giảm 240p xuống 155p. Đo bằng bấm giờ từng bước khi dev mới tìm hiểu một feature thật |
| **Boundary** | AI chỉ hỗ trợ đọc hiểu, tóm tắt, chỉ ra file/feature liên quan, đối chiếu coding convention. AI không tự sửa hay merge code. Khi thiếu tài liệu hoặc code, AI phải nói “không đủ thông tin” và chỉ ra phần thiếu, không được bịa cấu trúc. Dev vẫn phải xác nhận với người hướng dẫn. Cần quy định codebase có được đưa lên AI bên ngoài hay không |
| **AI intervention point** | Bước 2-4: AI tóm tắt kiến trúc và quy ước, tìm tài liệu liên quan, lần theo code để liệt kê flow và các file/feature liên đới. Bước 5: AI gom các điểm chưa chắc thành danh sách câu hỏi cho lead, để dev hỏi một lần thay vì nhiều lần |
| **Mức chọn** | Workflow (không cần Agent). Các bước cố định: truy xuất tài liệu + code → tóm tắt có dẫn nguồn → liệt kê phần liên đới → đối chiếu convention → ghi chú chỗ thiếu. Boundary không cho AI tự sửa code nên chưa cần AI tự quyết định hành động |
| **Rủi ro & người kiểm tra** | (1) AI bịa file/flow không tồn tại → dev đối chiếu nguồn được dẫn, mentor/lead xác nhận ở bước 5 </br>(2) AI bỏ sót feature liên đới → reviewer và test regression </br>(3) Dev phụ thuộc, bỏ qua việc đọc code → mentor kiểm tra mức hiểu bằng vài câu hỏi </br>(4) Lộ code công ty → tech lead/bảo mật quyết định phạm vi dữ liệu được dùng |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Bottleneck | Gộp 4 vấn đề vào 1 câu (đọc code, format, convention, ảnh hưởng feature khác) | Chốt bước 4 là chính, bước 2-3 là phụ | Nên ưu tiên thứ tự để tìm giải pháp phù hợp cho mỗi bước |
| Boundary | Chỉ nói AI không bịa | Thêm: AI không sửa/merge code, phải nói “không đủ thông tin”, vấn đề bảo mật | Làm rõ ràng, cụ thể như thế nào là không bịa |

**Tiêu chí đánh giá đầu ra của AI:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Trung thực khi thiếu thông tin | Khi tài liệu/code không đủ, AI nói rõ “không đủ thông tin” và chỉ ra phần thiếu | AI tự suy đoán hoặc “lấp chỗ trống” bằng cấu trúc nghe hợp lý |
| 2 | Đúng coding convention | Chỉ ra đúng quy ước áp dụng cho feature và khớp tài liệu quy ước của dự án | Nêu quy ước không có trong dự án, hoặc mâu thuẫn với code mẫu hiện có |
| 3 | Rút ngắn thời gian thật | Dev đạt target: bước 2-3 ít hơn 50p, bước 4 ít hơn 60p, và vẫn hiểu đúng khi mentor hỏi lại | Thời gian giảm nhưng dev không giải thích được flow, hoặc phải hỏi lại nhiều lần ở bước 5 |

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

-Khảo sát mới có 24 người, trong đó 7 người đã đi làm xác nhận gặp vấn đề này
-Chưa kiểm chứng mục tiêu dùng AI có giúp giảm thời gian tìm hiểu xuống dưới 2 tiếng mà vẫn đảm bảo dev hiểu đúng feature hay không
-phỏng vấn thêm dev mới, bấm giờ quy trình hiện tại và thử nghiệm trên một feature nhỏ

## 10. Tài liệu tham khảo

-
