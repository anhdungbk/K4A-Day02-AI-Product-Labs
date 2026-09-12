# 03 — Individual Reflection

## Thông tin cá nhân

- Họ và tên: Nguyễn Anh Dũng    
- Mã học viên: 2A202602554
- Nhóm: Random - Zone A
- Candidate problem nhóm chọn: Onboarding thành viên mới vào một nhóm kỹ thuật.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi đưa ra ba candidate: preflight kiểm bài trước khi nộp lab, tìm lại quyết định/tài liệu của nhóm và feedback review chưa được tách thành action item. | Ba bài này bổ sung góc nhìn về chi phí tìm thông tin, kiểm bài và theo dõi công việc; hai bài sau được dùng để hình thành cluster B và C. |
| Pitch Problem Card | Tôi pitch preflight với bottleneck 12/22 phút, bài tìm lại quyết định với time-to-find 11 phút/lượt và bài feedback với khoảng 10 phút/artifact để diễn giải comment. | Nhóm có dữ liệu cụ thể để so sánh, đồng thời nhận ra preflight có vòng đời ngắn theo từng môn nên không được chọn chỉ vì baseline đẹp. |
| Challenge bài của bạn khác | Tôi cùng nhóm challenge câu hỏi: kiến thức đã được ghi lại để search hay chưa; và checklist/process fix có giải được phần lớn pain không. | Nhóm tách cluster “kiến thức ngầm” khỏi cluster “đã ghi nhưng không tìm lại được”, tránh xây search trên một kho kiến thức rỗng. |
| Gom trùng / cluster | Tôi tham gia gộp bài tìm lại quyết định vào cluster B và feedback thành action item vào cluster C. | Việc gom trùng giúp nhóm chấm một pattern thay vì chấm lặp 15 ý tưởng riêng lẻ. |
| Chọn candidate problem | Tôi đồng ý chọn S1 sau khi xem score 34/35 và điều kiện đo ranh giới Rule/Workflow. | Nhóm chọn bài có actor, workflow và boundary rõ thay vì chọn bài nghe “AI” nhất. |
| Validation / research | Tôi phụ trách validation: chuẩn bị hướng đo log chat, time-to-find và bộ câu hỏi phỏng vấn người mới. | Báo cáo nhóm giữ rõ phần phỏng vấn 3 người mới chưa hoàn tất; điều này giúp nhóm không trình bày số ước lượng như dữ liệu đã đo. |
| Workflow nhóm | Tôi góp ý về vòng lặp “tìm thông tin → hỏi người cũ → chờ → tìm lại” và rủi ro của việc tra cứu không có nguồn. | Future workflow bắt buộc mọi câu trả lời của lớp AI phải kèm link nguồn và có fallback về người phụ trách. |
| Problem Statement | Tôi hỗ trợ làm rõ metric phụ: số câu hỏi lặp và số phút người cũ phải trả lời, không chỉ đo số ngày onboarding. | Nhóm tránh tối ưu thời gian của người mới bằng cách đẩy thêm việc sang người cũ. |
| Rule / Workflow / Agent | Tôi challenge việc dùng Agent: bài toán không cần AI tự chạy lệnh, tự cấp quyền hay tự cập nhật tài liệu. | Nhóm chọn Workflow ở một bước hỏi–đáp có nguồn, với lớp Rule phải chạy trước và chạy được độc lập. |
| Decision | Tôi ủng hộ cổng đo sau giai đoạn Rule: nếu số câu hỏi lặp đã dưới 5 câu/người mới thì dừng ở Rule. | Quyết định Go có điều kiện; AI chỉ được làm khi Rule chứng minh còn phần dư chưa giải được. |

**Dấu tay rõ nhất của tôi trong artifact cuối:** Tôi giúp nhóm giữ kỷ luật đo lường và không nhầm bài toán “tìm kiếm” với bài toán “chưa có tri thức được ghi lại”. Điều tôi đóng góp mạnh nhất là metric chống đẩy gánh nặng sang người cũ và cổng đo buộc nhóm dừng ở Rule nếu Rule đã đủ.

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI sau khi đã có ba candidate để tìm các lăng kính problem và cách đo. | AI giúp phân tách actor, workflow, bottleneck và metric. | AI gợi ý chatbot trả lời tất cả câu hỏi của lớp, quá rộng và không có owner vận hành. | Tôi bỏ ý tưởng đó, giữ các problem có workflow cụ thể và số đo được. |
| Problem Card | Nhờ AI đóng vai skeptical product manager để phản biện ba card. | AI chỉ ra cần so sánh phương án không-AI trước. | AI có xu hướng đẩy bài tìm lại quyết định lên thành knowledge agent quá sớm. | Tôi đặt lại câu hỏi: kiến thức có được ghi ra trước chưa; nếu chưa thì phải làm Rule/documentation trước. |
| Workflow | Dùng AI để gợi ý cách biểu diễn before/after workflow. | Giúp nhìn rõ bước nào là Rule, bước nào là human boundary và fallback. | AI có thể gộp “tìm kiếm” và “tạo tri thức” làm một bước. | Tôi cùng nhóm tách cluster A và B, rồi giữ lớp Rule tạo `LAB_FACTS.md` trước lớp AI. |
| Research | Không dùng AI để thay nguồn hoặc khẳng định số liệu. | AI chỉ hỗ trợ gợi ý từ khóa để nhóm tìm các tool/pattern phù hợp. | Một số claim và số liệu AI nêu không có nguồn kiểm được. | Nhóm chỉ giữ link đã mở kiểm trực tiếp và không đưa số không kiểm được vào báo cáo nhóm. |
| Problem Statement | Dùng AI để hỏi field nào còn mơ hồ trong PS v0. | AI làm lộ weakness của baseline 5–6 ngày và metric có thể bị gaming. | AI không tự nhận ra rằng người cũ có thể làm sẵn mọi thứ để số ngày onboarding đẹp hơn. | Nhóm thêm metric phụ về câu hỏi lặp, giờ công người cũ và bước giải thích lại 5 phút. |
| Rule / Workflow / Agent | Dùng AI để phản biện nhu cầu dùng Agent. | AI giúp liệt kê rủi ro khi tự chạy lệnh, sửa cấu hình hay cấp quyền. | AI vẫn có thể đề xuất Agent để “tự động hoá toàn bộ onboarding”. | Tôi cùng nhóm chọn Workflow một bước, cấm AI thay đổi trạng thái hệ thống và yêu cầu có nguồn cho mọi câu trả lời. |
| Decision | Không dùng AI để chốt quyết định. | AI chỉ được dùng để kiểm checklist Yes/Not Yet/No. | AI không thể quyết định thay nhóm liệu Rule đã giải được đủ pain hay chưa. | Nhóm đặt cổng đo với ngưỡng dưới 5 câu hỏi lặp/người mới để quyết định có làm lớp AI hay không. |

---

## 3. Reflection

Khi nghe top 3 problems của các bạn, tôi nhận ra một problem nghe rất giống AI chưa chắc đã là problem đáng làm nhất. Ban đầu tôi bị thuyết phục bởi bài tìm lại quyết định vì nó có workflow nhiều nguồn và có thể đo time-to-find, nhưng khi nhóm hỏi “thông tin đó đã được ghi đủ để search chưa?” thì tôi thấy đây có thể là một search solution đặt lên kho tri thức rỗng. Tôi cũng thay đổi cách nhìn về preflight kiểm bài: baseline 12 trong 22 phút rất rõ, nhưng vòng đời bài toán ngắn và checklist có thể đã giải gần hết. Thảo luận với nhóm giúp tôi hiểu rằng Rule không phải phương án kém hơn AI; nó là lớp phải được kiểm tra trước khi thêm AI vào workflow.

Đóng góp rõ nhất của tôi là giữ metric không chỉ đo lợi ích cho người mới mà còn đo chi phí còn lại của người cũ. Nếu chỉ giảm số ngày onboarding bằng cách để một người cũ chuẩn bị mọi thứ sẵn, nhóm có thể có kết quả đẹp nhưng không giải đúng pain. Tôi thấy phần khó nhất khi viết Problem Statement không phải chọn một metric, mà là đặt boundary và thiết kế metric chống gaming. Tôi cũng học được rằng AI hữu ích nhất ở bước ngôn ngữ có nguồn rõ ràng, còn các bước thay đổi trạng thái như cấp quyền, sửa cấu hình hoặc chốt quyết định khoa học phải do người có trách nhiệm thực hiện. Nếu làm lại, tôi sẽ hoàn tất ba cuộc phỏng vấn người mới sớm hơn để biến baseline 5–6 ngày từ ước lượng thành số đo thật trước khi nhóm bước sang giai đoạn AI.

---

## 4. Tự kiểm cuối bài

- [x] Có mô tả rõ đóng góp vào scan, pitch, challenge và hội tụ nhóm.
- [x] Có nêu vai trò validation, workflow, metric và quyết định cuối.
- [x] Có bảng dùng AI: AI hữu ích ở đâu, sai/hời hợt ở đâu và tôi đã sửa gì.
- [x] Có reflection về bài học, thay đổi quan điểm, boundary và điều sẽ làm khác.
- [x] Có thể giải thích mạch problem → workflow → metric → boundary → Rule/Workflow/Agent → Decision.
