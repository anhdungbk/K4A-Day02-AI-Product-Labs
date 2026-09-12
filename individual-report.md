# 01 — Individual Problem Scan

## Thông tin cá nhân

- Họ và tên: Nguyễn Anh Dũng
- Mã học viên: 2A202602554
- Vai trò / bối cảnh: Học viên theo học khóa CNTT, thường làm bài lab và bài tập nhóm 3–4 người. Nhóm trao đổi trên Discord, lưu tài liệu trên Google Drive và dùng GitHub cho các bài có mã nguồn.
- Công việc hằng tuần:
  - đọc tài liệu, yêu cầu bài lab và thông báo của khóa học;
  - họp nhóm, phân công và theo dõi tiến độ;
  - tìm tài liệu, làm phần việc được giao và review chéo;
  - tổng hợp, kiểm tra và nộp bài.

---

## Phase 1 — Scan 10 problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Trước khi nộp lab, một người phải mở README, Discord và Drive để tự kiểm bài còn thiếu gì. | Người tổng hợp/nộp bài và cả nhóm. | Trung bình 22 phút/lần kiểm bài; trong 4 lần nộp gần đây có 2 lần phát hiện thiếu link hoặc thiếu mục ở phút cuối. |
| 2 | Pain từ người khác | Sau họp, action item nằm trong chat nên người vắng mặt không biết mình phải làm gì. | Thành viên vắng họp và nhóm trưởng. | 3/4 cuộc họp gần nhất có ít nhất 2 việc chưa ghi owner hoặc deadline sau 24 giờ. |
| 3 | Lặp lại | Khi cần biết lý do nhóm đã chọn một phương án, thành viên phải tìm lại chat, Drive và commit cũ. | Người làm task phụ thuộc vào quyết định cũ. | Mất khoảng 11 phút/lượt tìm; 5 lượt tìm gần nhất chỉ 3 lượt tìm được nguồn gốc đầy đủ. |
| 4 | Tốn thời gian | Drive có nhiều file tên gần giống nhau như `final`, `final-2`, `final-new`, nên dễ sửa nhầm bản. | Người viết, reviewer và người tổng hợp. | Có 4 lần/tuần phải hỏi lại “file nào là bản mới”; 1 lần đã comment vào bản cũ. |
| 5 | AI có thể tốt hơn | Người mới vào nhóm cần đọc nhiều chat và file mới hiểu bối cảnh trước khi nhận task. | Thành viên mới hoặc thành viên đổi phần việc. | Mất khoảng 35–45 phút để nắm bối cảnh; thường hỏi lại 3–4 câu về deadline, scope và tài liệu. |
| 6 | Pain từ người khác | Feedback từ giảng viên/bạn review dài nhưng không được tách thành việc cần sửa cụ thể. | Người nhận feedback và reviewer. | Trong 3 bài gần nhất, có 5 comment bị hỏi lại vì chưa rõ cần sửa gì; trung bình 2 vòng review/bài. |
| 7 | Lặp lại | Thành viên hỏi lại deadline, format nộp hoặc nơi nộp dù thông tin đã có ở announcement. | Cả nhóm; người thường trả lời. | Khoảng 5–6 câu hỏi lặp lại/tuần trong Discord, chủ yếu trước deadline. |
| 8 | Tốn thời gian | Gộp tiến độ của 4 người trước buổi họp mất thời gian vì mọi người update không cùng format. | Nhóm trưởng/facilitator. | Mất khoảng 18 phút để tổng hợp một lần; 2/4 update thường thiếu blocker hoặc ngày hoàn thành. |
| 9 | AI có thể tốt hơn | Tìm tài liệu kỹ thuật cho một ý trong báo cáo mất thời gian vì phải mở nhiều nguồn để lọc độ liên quan. | Người phụ trách research. | Một câu hỏi research thường mở 8–10 nguồn trong 40 phút nhưng chỉ dùng 2–3 nguồn cuối. |
| 10 | Pain từ người khác | Task giao qua chat không có tiêu chí hoàn thành nên đến review mới biết thiếu phần. | Người làm task, reviewer và cả nhóm. | 4/7 task gần nhất thiếu owner, deadline hoặc definition of done; 2 task phải làm lại một phần. |

### AI đã dùng ở Phase 1

- Prompt: “Trong bối cảnh học viên khóa CNTT làm bài nhóm qua Discord, Google Drive và GitHub, hãy gợi ý các điểm nghẽn lặp lại; nêu actor, workflow và cách đo. Không đề xuất trợ lý AI toàn năng.”
- Ý dùng được: phân biệt vấn đề quy trình, vấn đề tìm thông tin và vấn đề tổng hợp ngôn ngữ để so sánh Rule, Workflow và Agent đúng mức.
- Ý bỏ: chatbot trả lời tất cả câu hỏi của lớp vì phạm vi quá rộng, không có owner vận hành và không thể kiểm chứng trong một lab.

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Preflight kiểm bài trước khi nộp | Actor và thời điểm rõ; có workflow ngắn, baseline đo được và thử được ngay bằng checklist. | Rubric có thay đổi nhiều giữa các bài hay không. |
| 2 | Tìm lại quyết định và nguồn thông tin của nhóm | Pain lặp lại, đi qua nhiều nguồn, gây chậm handoff và có thể đo bằng time-to-find. | Quyết định cũ có được ghi đủ rõ để search chính xác không. |
| 3 | Chuyển feedback review thành action items | Input là ngôn ngữ tự do nhưng đầu ra có cấu trúc; có thể đo bằng số comment bị bỏ sót và số vòng sửa. | Feedback có đủ cụ thể để tách thành action chính xác không. |

---

#### Problem Card #1 — Preflight kiểm bài trước khi nộp

**Problem 1 câu:** Trước deadline, người phụ trách nộp bài phải dò yêu cầu ở nhiều nơi để biết bài còn thiếu gì; việc này mất thời gian và dễ bỏ sót.

**Actor:** Thành viên được giao tổng hợp và nộp deliverable của nhóm.

**Thời điểm / bối cảnh:** 30–60 phút trước deadline; yêu cầu nằm trong README/rubric, announcement và các file nhóm.

**Current workflow 3–7 bước:**

1. Mở README hoặc rubric để đọc tiêu chí.
2. Mở Discord để kiểm announcement và thay đổi gần đây.
3. Mở từng file trong Drive/repo để đối chiếu.
4. Nhắn thành viên hỏi những phần chưa tìm thấy.
5. Tự lập checklist tạm và nộp bài.

**Bottleneck:** Đối chiếu yêu cầu với file thực tế mất khoảng 12 trong tổng 22 phút, vì requirement không được chuyển thành checklist kiểm được và file phân tán.

**Impact:** 2/4 lần nộp gần nhất phát hiện thiếu link hoặc thiếu mục vào phút cuối; việc này làm chậm nộp và tạo áp lực cho cả nhóm.

**Success metric:** Giảm thời gian preflight từ 22 phút xuống dưới 10 phút; 100% tiêu chí bắt buộc có trạng thái “đã có bằng chứng/thiếu/không áp dụng”; không còn lỗi thiếu file hoặc link trong 3 lần nộp pilot.

**Non-AI alternative:** Checklist Markdown theo rubric, quy ước tên file và một người review cuối. Đây là lựa chọn rẻ và đủ nếu rubric ổn định.

**AI hypothesis:** AI nhận rubric dạng văn bản, tách thành checklist và gợi ý mục cần kiểm trong các file đã cung cấp. Người nộp vẫn mở file, xác nhận từng mục và tự submit.

**Quick gut:** ☑ Rule / Workflow nhẹ  ☐ Agent

**Draft workflow Card #1:**

```text
CURRENT STATE — 22 phút

[Đọc README/rubric: 4']
→ [Tìm announcement: 3']
→ [Mở/đối chiếu từng file: 12']  <-- bottleneck
→ [Nhắn hỏi thành viên: 2']
→ [Nộp: 1']

FUTURE STATE — mục tiêu 9 phút

[Rubric → checklist chuẩn: 1']
→ [Đối chiếu file/link bằng rule: 3']
→ [AI gợi ý mục mơ hồ: 1']
→ [Người nộp kiểm và tick: 3']  <-- human boundary
→ [Nộp: 1']

Fallback: nếu checklist hoặc AI không chắc, đọc rubric gốc và không nộp khi còn mục “chưa xác minh”.
```

---

#### Problem Card #2 — Tìm lại quyết định và nguồn thông tin của nhóm

**Problem 1 câu:** Khi tiếp tục một task phụ thuộc vào quyết định cũ, học viên mất thời gian tìm lại bối cảnh trong Discord, Drive và GitHub; kết quả thường là hỏi lại hoặc làm theo suy đoán.

**Actor:** Thành viên làm task sau hoặc thành viên vắng buổi thảo luận trước.

**Thời điểm / bối cảnh:** Khi cần biết nhóm đã chốt gì, ai chốt và dựa vào tài liệu nào trước khi code hoặc viết báo cáo.

**Current workflow 3–7 bước:**

1. Nhớ từ khóa gần đúng.
2. Search Discord.
3. Mở từng thread và link trong kết quả.
4. Search Drive và thư mục dự án.
5. Mở issue/commit liên quan trên GitHub.
6. Tự ghép context hoặc hỏi lại nhóm.

**Bottleneck:** Search và tự ghép context từ nhiều nguồn mất trung bình 11 phút/lượt; 2/5 lượt gần nhất không tìm được nguồn đầy đủ.

**Impact:** Task bị chậm, câu hỏi bị lặp lại và có nguy cơ tạo quyết định mâu thuẫn với nhóm.

**Success metric:** Median time-to-find dưới 5 phút; ít nhất 80% quyết định pilot có link nguồn; giảm số lần hỏi lại một quyết định xuống còn tối đa một lần/tuần.

**Non-AI alternative:** Sau mỗi họp, ghi decision log có ngày, quyết định, lý do, owner và link nguồn; dùng Discord filter và GitHub Issues để tìm theo tag.

**AI hypothesis:** Workflow retrieval tìm trong các nguồn nhóm đã cấp quyền, trả về tối đa 3 quyết định phù hợp, tóm tắt ngắn và kèm link gốc. Người dùng mở nguồn để xác nhận trước khi dùng.

**Quick gut:** ☑ Workflow  ☐ Agent

**Draft workflow Card #2:**

```text
CURRENT STATE — 11 phút

[Nhớ từ khóa: 1']
→ [Search Discord: 3']
→ [Search Drive/GitHub: 3']
→ [Mở link, tự ghép context: 3']  <-- bottleneck
→ [Hỏi lại: 1']

FUTURE STATE — mục tiêu dưới 5 phút

[Ghi decision log theo template: Rule]
→ [Search theo tag và nguồn: 1']
→ [AI tóm tắt tối đa 3 kết quả có link: 1']
→ [Người dùng mở nguồn, xác nhận: 2']  <-- human boundary
→ [Tiếp tục task: 1']

Fallback: không có link nguồn hoặc kết quả không chắc → hỏi owner; không dùng câu trả lời AI như quyết định chính thức.
```

---

#### Problem Card #3 — Chuyển feedback review thành action items

**Problem 1 câu:** Feedback từ review thường dài và không cùng cấu trúc, khiến học viên không rõ cần sửa gì, ai sửa và thế nào là hoàn tất.

**Actor:** Người nhận feedback và reviewer/nhóm trưởng theo dõi vòng sửa.

**Thời điểm / bối cảnh:** Sau khi nhận comment trên Google Docs, GitHub Pull Request, Discord hoặc góp ý của giảng viên.

**Current workflow 3–7 bước:**

1. Nhận feedback ở nhiều kênh.
2. Đọc từng comment.
3. Tự diễn giải thành việc cần làm.
4. Hỏi lại nếu feedback mơ hồ.
5. Sửa tài liệu/mã và gửi review lại.

**Bottleneck:** Tự diễn giải và hỏi lại mất khoảng 10 phút cho một artifact; trong 3 bài gần nhất có 5 comment bị hỏi lại và trung bình 2 vòng review/bài.

**Impact:** Bỏ sót comment, tăng vòng review và làm reviewer phải nhắc lại cùng một điểm.

**Success metric:** 100% feedback có trạng thái Action/Question/Observation; giảm comment bị nhắc lại ít nhất 30%; mỗi action có owner và definition of done trước khi bắt đầu sửa.

**Non-AI alternative:** Dùng form feedback gồm vấn đề, vị trí/bằng chứng, mức ưu tiên và hành động mong muốn; sau đó tạo task có owner và deadline.

**AI hypothesis:** AI phân loại feedback thành Action, Question hoặc Observation và tạo draft task. Người nhận và reviewer xác nhận priority, owner và definition of done trước khi thực hiện.

**Quick gut:** ☑ Workflow  ☐ Agent

**Draft workflow Card #3:**

```text
CURRENT STATE — 10 phút/artifact để diễn giải feedback

[Nhận comment/chat]
→ [Đọc từng feedback: 3']
→ [Tự diễn giải: 4']  <-- bottleneck
→ [Hỏi lại: 3']
→ [Sửa và gửi review lại]

FUTURE STATE — mục tiêu 5 phút/artifact

[Feedback template: Rule]
→ [AI phân loại/draft task: 1']
→ [Người nhận + reviewer xác nhận owner & DoD: 3']  <-- human boundary
→ [Sửa theo checklist: 1']
→ [Review/đóng task]

Fallback: feedback mơ hồ giữ ở trạng thái Question; hỏi reviewer trước khi tạo task hoặc sửa.
```

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:** Preflight kiểm bài trước khi nộp.

**Vì sao:** Đây là workflow ngắn, xuất hiện đúng thời điểm rủi ro cao và có thể thử trong lần nộp tiếp theo. Baseline 22 phút, mục tiêu dưới 10 phút và lỗi thiếu file/link là những metric dễ theo dõi. Quan trọng hơn, nhóm có thể thử checklist Rule trước rồi mới cân nhắc AI cho phần yêu cầu dạng văn bản mơ hồ.

**Câu hỏi tôi muốn nhóm challenge:**

1. Checklist/rule đã giải quyết 80% vấn đề chưa, hay có bằng chứng cho thấy cần AI?
2. Nếu rubric thay đổi giữa các bài, AI nên hỗ trợ bước nào và ai chịu trách nhiệm kiểm checklist cuối?

**AI phản biện Card:**

- Điểm yếu AI chỉ ra: dễ nhảy ngay sang AI trong khi lỗi có thể đến từ thiếu owner và thiếu checklist chuẩn.
- Tôi sửa: chọn Rule/Workflow nhẹ thay vì Agent; yêu cầu người nộp xác nhận từng tiêu chí và không cho AI tự submit.

### Self-check nộp phần 01

- [x] Có 10 problems, dùng 4 lăng kính.
- [x] Có 3 Problem Cards đủ actor, workflow, bottleneck, impact, metric, phương án non-AI và AI hypothesis.
- [x] Mỗi card có workflow trước/sau, human boundary và fallback.
- [x] Đã chọn 1 card để pitch và có câu hỏi challenge.
