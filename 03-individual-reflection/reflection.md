# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Thu Phương
- Mã học viên: 2A202602366
- Nhóm:      (đang lập nhóm)
- Candidate problem nhóm chọn: ( chưa_ chọn)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi liệt kê các pain lặp lại khi setup Python, debug code, dùng Git, đọc tài liệu và nhờ mentor; đồng thời bổ sung số lần và thời gian. | Nhóm có thêm các candidate có actor, workflow và metric rõ để so sánh. |
| Pitch Problem Card | Tôi pitch card debug code/test, giải thích bottleneck ở bước tìm nguyên nhân và metric 20-40 phút/lỗi. | Nhóm hiểu đây là pain cụ thể, có thể thử nghiệm trong lab. |
| Challenge bài của bạn khác | Tôi hỏi actor, cách đo baseline và cách xử lý khi AI đề xuất sai. | Các candidate được cụ thể hóa hơn, tránh solution-first. |
| Gom trùng / cluster | Tôi gom các ý tưởng về debug, setup/dependency và giao tiếp khi nhờ hỗ trợ thành các nhóm pain. | Nhóm nhìn thấy các workflow lặp lại và bottleneck chính. |
| Chọn candidate problem | Tôi đề xuất ưu tiên debug code/test vì gặp 4-6 lỗi/tuần và có pytest/terminal log để đo. | Nhóm có cơ sở chọn candidate có pain thật, actor rõ và phạm vi vừa sức. |
| Validation / research | Tôi đối chiếu metric với terminal history, pytest output và tìm hiểu các pattern hỗ trợ phân tích traceback. | Nhóm phân biệt được phần nên làm bằng checklist/workflow với phần cần Agent. |
| Workflow nhóm | Tôi vẽ current/future workflow, ước lượng thời gian và đặt human boundary trước khi sửa code. | Nhóm có before/after workflow thay vì chỉ mô tả giải pháp. |
| Problem Statement | Tôi góp ý Actor, Bottleneck, Impact và Success Metric theo phạm vi lỗi Python/pytest phổ biến. | Problem Statement rõ hơn về đối tượng, điểm can thiệp và cách đo. |
| Rule / Workflow / Agent | Tôi so sánh checklist debug, workflow thu thập context và Agent phân tích traceback. | Nhóm không chọn Agent theo phản xạ mà dựa trên độ phức tạp của workflow. |
| Decision | Tôi đồng ý pilot nhỏ, bắt buộc review của sinh viên và có fallback checklist thủ công. | Quyết định có boundary, metric và rollback rõ ràng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần có dấu tay rõ nhất của tôi là Problem Card debug code/test và workflow current/future. Tôi đưa vào các con số 4-6 lỗi/tuần, 20-40 phút/lỗi và 5-10 vòng test để card không bị chung chung.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi nhờ AI gợi ý các pain có workflow lặp lại và cách đo. | Gợi ý thêm góc nhìn, nhắc bổ sung actor và số đo. | AI đưa ra nhiều ý tưởng chung chung như chatbot, email, lịch. | Tôi bỏ các ý không gắn với công việc thực tế và tự điền số liệu quan sát được. |
| Problem Card | Tôi dùng AI để phản biện field còn thiếu và phạm vi debug. | Nhắc cần success metric, non-AI alternative và human boundary. | AI có xu hướng đề xuất Agent quá rộng, không biết context project. | Tôi giới hạn ở Python/pytest và bắt Agent nêu evidence, sinh viên review trước khi sửa. |
| Workflow | Tôi nhờ AI góp ý cách tách current state, future state và fallback. | Giúp kiểm tra thời gian và boundary. | AI không biết thời gian debug thực tế của tôi. | Tôi giữ số liệu từ terminal history và để người dùng quyết định thay đổi. |
| Research | Tôi dùng AI gợi ý các tool/pattern cho debug và thu thập context. | Giúp định hướng so sánh checklist, workflow và Agent. | AI không thay được việc kiểm tra tài liệu chính thức. | Tôi chỉ giữ nhận định có thể đối chiếu với log, docs hoặc trải nghiệm. |
| Problem Statement | Tôi nhờ AI kiểm tra Actor, Workflow, Bottleneck và Metric. | Phát hiện field còn mơ hồ. | AI dễ viết hay nhưng thiếu baseline. | Tôi thay bằng số đo cụ thể và boundary không tự động sửa code. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh ba mức và hỏi khi nào hạ từ Agent xuống Workflow/Rule. | Làm rõ trade-off giữa tự động hóa và rủi ro. | AI thiên về Agent dù checklist có thể đủ. | Tôi chỉ dùng Agent cho phân tích, vẫn giữ người thu thập context và review. |
| Decision | Tôi nhờ AI liệt kê rủi ro, pilot metric và fallback. | Nhắc đến rollback và cách đo sau pilot. | AI không thể tự quyết định Go khi chưa có log pilot. | Tôi chỉ đề xuất pilot nhỏ có review và checklist thủ công khi Agent sai. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems, tôi nhận ra cùng một việc “mất nhiều thời gian” nhưng nếu không có actor và số đo thì rất khó làm thành bài lab. Ban đầu tôi muốn làm Agent debug có thể tự sửa code, nhưng sau khi bị challenge tôi thấy solution đó quá rộng và có rủi ro. Tôi đóng góp việc tách workflow thành các bước nhỏ, đặt bottleneck ở khâu tìm nguyên nhân và ghi baseline 20-40 phút cho mỗi lỗi. Metric là phần khó vì tôi không muốn chỉ nói AI nhanh hơn mà cần đo cả số vòng test và tỉ lệ tìm đúng nguyên nhân. Tôi học được cách đặt boundary rõ: Agent chỉ đề xuất, sinh viên review và quyết định có sửa code hay không. AI hữu ích khi gợi ý câu hỏi và cấu trúc, nhưng không biết log thực tế nên tôi không dùng các con số AI tự đưa ra. Nếu làm lại, tôi sẽ hỏi nhóm sớm hơn về nguồn context và cách rollback nếu gợi ý sai. Qua bài này, tôi hiểu rõ hơn mạch problem → workflow → metric → boundary → độ phù hợp AI.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

