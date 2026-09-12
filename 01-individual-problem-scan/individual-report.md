# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trần Thu Phương
- Mã học viên: 2A202602366
- Vai trò / bối cảnh (VD: sinh viên năm 4, intern AI, ...): Sinh viên thực tập AI/Software, thường xuyên làm bài lab Python, sử dụng Git/GitHub và các API/LLM.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Làm bài lab/lập trình theo yêu cầu, chạy test và sửa lỗi.
    - Đọc tài liệu kỹ thuật, tài liệu API hoặc repository để hiểu cách triển khai.
    - Debug các lỗi về Python, môi trường ảo, package, API key, Git/GitHub.
    -   Commit/push code lên GitHub và xử lý các vấn đề liên quan đến branch, merge hoặc conflict.
    -   Trao đổi với bạn cùng nhóm/mentor khi gặp lỗi hoặc chưa rõ yêu cầu bài tập.
    
 

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Mỗi khi bắt đầu bài lab hoặc project mới phải tự tạo môi trường ảo, cài thư viện và xử lý lỗi dependency. | Sinh viên thực tập, đặc biệt là người mới làm quen với Python. | Khoảng 2-3 lần/tuần, mỗi lần mất 15-30 phút. Tuần gần nhất gặp 2 lỗi liên quan đến package hoặc môi trường Python. Bằng chứng: terminal history. |
| 2 | Tốn thời gian + AI có thể tốt hơn | Khi code hoặc test bị lỗi, phải tự đọc traceback, tìm nguyên nhân, sửa code rồi chạy lại nhiều lần. | Sinh viên thực tập trực tiếp làm bài lab. | Khoảng 4-6 lỗi/tuần, trung bình 20-40 phút/lỗi. Một task có thể phải chạy test lại 5-10 lần. Bằng chứng: pytest output và terminal log. |
| 3 | Lặp lại + Pain từ người khác | Khi sử dụng Git thường nhầm ở các bước tạo branch, commit, push hoặc kiểm tra code đã được push thành công hay chưa. | Sinh viên mới sử dụng Git/GitHub và các bạn cùng nhóm. | Thực hiện Git workflow khoảng 3-5 lần/tuần. Khoảng 1-2 lần/tuần phải hỏi lại hoặc kiểm tra bằng `git status`, `git log`. Mỗi lần xử lý mất khoảng 10-20 phút. |
| 4 | Tốn thời gian + AI có thể tốt hơn | Khi đọc tài liệu API hoặc LLM phải tìm kiếm qua nhiều trang để xác định đúng model, parameter hoặc cách xử lý lỗi. | Sinh viên thực tập AI. | Khoảng 2-3 buổi/tuần, mỗi buổi mất 30-60 phút tìm tài liệu. Có lần phải mở 5-8 tab trước khi tìm được thông tin cần thiết. |
| 5 | Lặp lại + Tốn thời gian | Khi clone một repository mới phải tự đọc README, tìm cấu trúc project, file cần sửa và command cần chạy trước khi bắt đầu làm bài. | Sinh viên mới tham gia project hoặc làm việc với repository mới. | Khoảng 1-2 repository/tuần, mỗi repo mất 20-45 phút để đọc hướng dẫn, xem cấu trúc thư mục và thử command. Bằng chứng: thời gian từ lúc clone repo đến khi chạy chương trình thành công lần đầu. |
| 6 | Pain từ người khác + AI có thể tốt hơn | Khi gặp lỗi và nhờ mentor hoặc bạn học hỗ trợ, thông tin gửi ban đầu thường thiếu traceback, command đã chạy hoặc thông tin môi trường nên phải hỏi qua lại nhiều lần. | Sinh viên gặp lỗi và mentor/người hỗ trợ. | Khoảng 2-3 lần/tuần cần nhờ hỗ trợ. Thường phải trao đổi 2-4 lượt tin nhắn mới đủ thông tin, mất khoảng 15-30 phút/lần. |
| 7 | Lặp lại + Tốn thời gian + AI có thể tốt hơn | Trước khi commit hoặc push code phải tự kiểm tra file thay đổi, test lại code, kiểm tra `.env` hoặc API key và xem commit message đã đúng chưa. | Sinh viên thực tập và các thành viên trong nhóm. | Khoảng 4-8 commit/tuần, mỗi lần kiểm tra mất 5-10 phút. Tổng thời gian khoảng 30-60 phút/tuần. Bằng chứng: `git status`, `git diff` và commit history. |
| 8 | Lặp lại + Tốn thời gian | Sau khi nhận yêu cầu bài lab, phải chia nhỏ yêu cầu, xác định đầu ra, file cần nộp và thứ tự thực hiện trước khi bắt đầu code. | Sinh viên thực tập làm bài lab; mentor phải trả lời khi yêu cầu chưa được hiểu đúng. | Khoảng 2-3 bài lab/tuần, mỗi bài mất 15-25 phút để đọc lại đề và lập danh sách việc cần làm. Có khoảng 1 lần/tuần phải hỏi lại yêu cầu hoặc sửa lại hướng làm do bỏ sót một đầu ra. Bằng chứng: nội dung đề bài và lịch sử trao đổi với mentor. |
| 9 | Tốn thời gian + AI có thể tốt hơn | Khi gặp ví dụ code mới trong tài liệu, phải tự chuyển ví dụ sang đúng cấu trúc project, biến môi trường và dữ liệu đang dùng rồi mới kiểm tra được kết quả. | Sinh viên thực tập AI/Software sử dụng API hoặc thư viện mới. | Khoảng 2-4 lần/tuần, mỗi lần mất 20-35 phút để điều chỉnh ví dụ. Thường cần sửa tên biến, đường dẫn, API key hoặc format input ít nhất 2-3 lần trước khi chạy được. Bằng chứng: notebook/file thử nghiệm và terminal log. |
| 10 | Pain từ người khác + Lặp lại | Khi làm việc nhóm, các thay đổi về cách chạy project hoặc package cần cài không được ghi lại ngay nên bạn khác phải hỏi lại cách setup hoặc command cần dùng. | Thành viên mới trong nhóm và người đã setup project trước đó. | Khoảng 1-2 lần/tuần có câu hỏi lặp lại về command chạy project hoặc package cần cài; mỗi lần trao đổi mất 10-15 phút. Bằng chứng: lịch sử chat nhóm và các câu hỏi lặp lại khi clone repo. |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:Prompt đã hỏi:
Tôi là sinh viên thực tập AI. Hãy giúp tôi phản biện các vấn đề tôi quan sát được trong quá trình học và thực tập như setup môi trường, debug code, sử dụng Git/GitHub, đọc tài liệu API/LLM và nhờ mentor hỗ trợ. Mỗi problem cần có actor cụ thể, workflow lặp lại, bottleneck rõ và có thể đo bằng thời gian hoặc số lần xảy ra.

- Ý dùng được: Bổ sung số lần/tuần và thời gian mất cho từng problem; mô tả problem cụ thể hơn thay vì ghi chung chung; xác định rõ người chịu ảnh hưởng; ưu tiên các problem có workflow lặp lại và có khả năng cải thiện bằng AI hoặc automation.

- Ý bỏ vì không phải pain thật: Tự động viết Weekly Report, tự động trả lời email, tự động đặt lịch họp và các ý tưởng chatbot quá chung chung vì đây không phải những công việc gây mất nhiều thời gian hoặc lặp lại thường xuyên trong bối cảnh thực tập hiện tại.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"



## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

### Top 3 Problem

| Rank | Problem | Actor | Workflow hiện tại | Bottleneck | Impact đo được | No AI / Rule / Workflow / Agent | Độ phù hợp lab |
|---|---|---|---|---|---|---|---|
| 🥇 1 | Debug code/test mất nhiều thời gian do phải thử sửa và chạy lại nhiều lần | Sinh viên thực tập AI/Software | Chạy test → đọc traceback → tìm file lỗi → tìm nguyên nhân → sửa code → chạy test lại | Phải tự phân tích traceback và thử nhiều cách sửa; context lỗi nằm rải rác trong code, terminal và tài liệu | 4-6 lỗi/tuần; trung bình 20-40 phút/lỗi; một task phải chạy test lại 5-10 lần | Agent | ⭐⭐⭐⭐⭐ |
| 🥈 2 | Setup môi trường Python và xử lý dependency lặp lại khi bắt đầu lab/project mới | Sinh viên thực tập, đặc biệt sinh viên mới dùng Python | Clone/mở project → tạo virtual environment → cài package → chạy chương trình → gặp lỗi → tìm và sửa dependency | Cài đặt thủ công, khác version package/Python và khó xác định nguyên nhân khi môi trường lỗi | 2-3 lần/tuần; mỗi lần mất 15-30 phút; tuần gần nhất gặp khoảng 2 lỗi về package/môi trường | Workflow | ⭐⭐⭐⭐ |
| 🥉 3 | Khi nhờ mentor hỗ trợ debug thường thiếu thông tin nên phải hỏi qua lại nhiều lần | Sinh viên gặp lỗi và mentor/người hỗ trợ | Gặp lỗi → gửi tin nhắn hỏi → mentor hỏi thêm context → lấy traceback/command/môi trường → gửi lại → phân tích lỗi | Context debug không được thu thập theo format thống nhất, thiếu traceback, command hoặc thông tin môi trường | 2-3 lần/tuần; 2-4 lượt trao đổi/issue; mất khoảng 15-30 phút trước khi đủ thông tin để xử lý | Agent | ⭐⭐⭐⭐⭐ |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---
### Problem Card #1 — Debug code/test mất nhiều thời gian

```text
Problem 1 
Sinh viên thực tập mất nhiều thời gian khi debug vì phải đọc traceback, tự tìm nguyên nhân, sửa code và chạy test lại nhiều lần trước khi lỗi được xử lý.

Actor:
Sinh viên thực tập AI/Software trực tiếp làm bài lab hoặc project.

Thời điểm / bối cảnh:
Xảy ra khi chạy code hoặc test trong quá trình làm bài lab/project và chương trình trả về lỗi, test fail hoặc kết quả không đúng mong đợi.

Current workflow 3-7 bước:

1. Chạy code hoặc chạy test bằng pytest.
2. Đọc traceback và error message trong terminal.
3. Tìm file, hàm hoặc đoạn code có khả năng gây lỗi.
4. Tìm nguyên nhân bằng cách đọc code, tài liệu hoặc search lỗi.
5. Sửa code dựa trên nguyên nhân dự đoán.
6. Chạy test lại để kiểm tra.
7. Nếu vẫn lỗi, quay lại bước 2 và lặp lại cho đến khi test pass.

Bottleneck:
Việc xác định nguyên nhân gốc của lỗi phụ thuộc nhiều vào khả năng đọc traceback và kinh nghiệm của sinh viên. Context cần để debug nằm rải rác trong source code, terminal output và tài liệu nên thường phải thử nhiều cách sửa trước khi tìm đúng nguyên nhân.

Impact:
Khoảng 4-6 lỗi/tuần, trung bình mất 20-40 phút cho mỗi lỗi. Một task có thể phải chạy test lại 5-10 lần, tương đương khoảng 2-4 giờ/tuần dành cho việc debug.

Success metric:
- Giảm thời gian debug trung bình từ 20-40 phút/lỗi xuống còn dưới 15 phút/lỗi.
- Giảm số vòng test → sửa → test lại từ 5-10 lần xuống còn 2-4 lần.
- Xác định đúng nguyên nhân lỗi ngay trong 1-2 lần phân tích đầu tiên ở ít nhất 70% trường hợp.
- Giảm số lần phải nhờ mentor hỗ trợ các lỗi phổ biến.

Non-AI alternative:
Tạo checklist debug cố định gồm: đọc error message → xác định file/dòng lỗi → kiểm tra dependency → kiểm tra input/output → chạy test nhỏ hơn → tra tài liệu. Đồng thời xây dựng tài liệu tổng hợp các lỗi thường gặp và cách xử lý.

AI hypothesis:
Một AI Agent có thể tự thu thập traceback, source code liên quan và kết quả test; sau đó phân tích nguyên nhân, đề xuất cách sửa và tiếp tục kiểm tra kết quả sau mỗi lần chạy test. Agent có thể giúp giảm số vòng thử-sai và thời gian sinh viên phải tự tìm kiếm nguyên nhân lỗi.

Quick gut:

[ ] No AI / process fix

[ ] Rule

[ ] Workflow

[x] Agent

[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

CURRENT STATE — ~35 phút/lỗi

[1. Chạy code/test: 3'] 
        ↓
[2. Đọc traceback + xác định vị trí lỗi: 7']
        ↓
[3. Tìm nguyên nhân trong code/docs: 15']  <-- bottleneck
        ↓
[4. Sửa code + chạy test lại: 10']
        ↳ Nếu vẫn lỗi → quay lại bước 2

Bottleneck:
Sinh viên phải tự kết nối thông tin từ traceback, source code và tài liệu để đoán nguyên nhân lỗi.
Nếu đoán sai, vòng "đọc lỗi → tìm nguyên nhân → sửa → test lại" phải lặp lại nhiều lần.


FUTURE STATE — ~12 phút/lỗi

[1. Chạy test + thu thập traceback/context: 2']
        ↓
[2. AI Agent phân tích lỗi + đề xuất nguyên nhân và cách sửa: 5']
        ↓
[3. Sinh viên review đề xuất + quyết định sửa code: 3']  <-- human boundary
        ↓
[4. Chạy test xác nhận kết quả: 2']
        ↳ Nếu vẫn lỗi → Agent nhận kết quả mới và phân tích lại

Human boundary:
AI chỉ phân tích và đề xuất cách sửa. Sinh viên vẫn review nguyên nhân, kiểm tra thay đổi
và quyết định có áp dụng sửa đổi trước khi chạy lại code.

Fallback: nếu AI sai thì sinh viên giữ nguyên code ban đầu, kiểm tra lại traceback,
quay về checklist debug thủ công (error message → file/dòng lỗi → input/output →
dependency → tài liệu) hoặc nhờ mentor hỗ trợ khi lỗi vẫn chưa được giải quyết.

File đính kèm (nếu vẽ riêng): `![alt text](image.png)`

---

#### Problem Card #2 — Setup môi trường Python và xử lý dependency lặp lại

```text
Problem 1 câu:
Sinh viên thực tập mất thời gian setup môi trường Python cho lab/project mới vì phải cài đặt thủ công và xử lý lỗi version package hoặc dependency.

Actor:
Sinh viên thực tập AI/Software, đặc biệt là sinh viên mới làm quen với Python và virtual environment.

Thời điểm / bối cảnh:
Xảy ra khi clone hoặc mở một repository mới, bắt đầu bài lab mới, thay đổi máy/môi trường làm việc hoặc khi package trong project không tương thích.

Current workflow 3-7 bước:
1. Clone hoặc mở repository/bài lab.
2. Đọc README để tìm phiên bản Python và command cài đặt.
3. Tạo virtual environment và kích hoạt môi trường.
4. Cài package từ requirements hoặc cài thủ công.
5. Chạy chương trình/test lần đầu.
6. Đọc lỗi thiếu package, sai version hoặc sai môi trường.
7. Tìm cách sửa rồi cài lại/chạy lại cho đến khi chương trình hoạt động.

Bottleneck:
Thông tin setup thường nằm rải rác giữa README, file requirements và terminal output. Việc cài đặt thủ công khiến sinh viên khó biết chính xác package, version Python hoặc command nào còn thiếu khi lần chạy đầu bị lỗi.

Impact:
Khoảng 2-3 lần/tuần, mỗi lần mất 15-30 phút; tuần gần nhất gặp khoảng 2 lỗi liên quan đến package hoặc môi trường Python. Khi setup không thành công, thời gian bắt đầu làm phần code chính bị chậm và có thể phải hỏi mentor/bạn học.

Success metric:
- Giảm thời gian setup một lab/project mới từ 15-30 phút xuống dưới 10 phút.
- Ít nhất 80% repository có thể chạy thành công ngay sau một checklist setup chuẩn.
- Giảm số lần cài lại package hoặc tạo lại môi trường xuống còn tối đa 1 lần/repository.
- Giảm số câu hỏi lặp lại về command setup và dependency.

Non-AI alternative:
Chuẩn hóa README theo một template gồm phiên bản Python, command tạo môi trường, command cài package, file `.env.example` và command chạy test. Có thể dùng `requirements.txt` hoặc lock file để cố định dependency.

AI hypothesis:
Một workflow hỗ trợ setup có thể đọc README, kiểm tra phiên bản Python, file dependency và lỗi terminal để tạo checklist theo từng repository. Khi chạy lỗi, AI đề xuất nguyên nhân có khả năng cao và command cần kiểm tra; sinh viên vẫn tự chạy command và xác nhận thay đổi trong môi trường của mình.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~25 phút/repository

[1. Clone/mở repo: 2']
        ↓
[2. Đọc README + tìm command setup: 5']
        ↓
[3. Tạo venv + cài package: 8']
        ↓
[4. Chạy lần đầu, đọc lỗi dependency: 7']  <-- bottleneck
        ↓
[5. Tìm cách sửa + chạy lại: 3']

FUTURE STATE — ~10 phút/repository

[1. Đọc README, requirements và kiểm tra máy: 2']
        ↓
[2. Workflow tạo checklist + command setup phù hợp: 3']
        ↓
[3. Sinh viên review command, tạo venv và chạy: 3']  <-- human boundary
        ↓
[4. Kiểm tra kết quả/lỗi còn lại: 2']

Fallback: nếu checklist hoặc gợi ý không đúng, sinh viên dừng trước khi thay đổi môi trường, đối chiếu README/requirements, dùng checklist setup thủ công và hỏi mentor khi cần.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Nhờ mentor hỗ trợ debug thiếu context

```text
Problem 1 câu:
Sinh viên mất thêm thời gian khi nhờ mentor hỗ trợ debug vì thông tin gửi ban đầu thiếu traceback, command đã chạy hoặc thông tin môi trường.

Actor:
Sinh viên thực tập gặp lỗi và mentor/người hỗ trợ cần đủ context để phân tích lỗi.

Thời điểm / bối cảnh:
Xảy ra sau khi sinh viên đã tự thử debug nhưng chưa xử lý được và gửi tin nhắn hoặc tạo issue để nhờ hỗ trợ.

Current workflow 3-7 bước:
1. Sinh viên gặp lỗi khi chạy code hoặc test.
2. Sinh viên gửi mô tả ngắn hoặc ảnh lỗi cho mentor.
3. Mentor hỏi thêm traceback, file liên quan, command đã chạy hoặc thông tin môi trường.
4. Sinh viên quay lại terminal/source code để thu thập thông tin.
5. Sinh viên gửi bổ sung context qua nhiều lượt tin nhắn.
6. Mentor mới phân tích nguyên nhân và hướng dẫn cách xử lý.

Bottleneck:
Context debug không được thu thập theo một format thống nhất ngay từ đầu. Mentor không thể tái hiện hoặc phân tích lỗi khi thiếu traceback đầy đủ, bước tái hiện lỗi, phiên bản môi trường và phần code liên quan.

Impact:
Khoảng 2-3 lần/tuần cần nhờ hỗ trợ; mỗi issue thường mất 2-4 lượt trao đổi và 15-30 phút trước khi đủ thông tin để bắt đầu xử lý. Thời gian chờ này làm chậm cả sinh viên và mentor.

Success metric:
- Giảm số lượt hỏi-đáp để đủ context từ 2-4 lượt xuống còn 1 lượt gửi ban đầu.
- Ít nhất 80% yêu cầu hỗ trợ có đủ traceback, bước tái hiện, command và thông tin môi trường.
- Giảm thời gian từ lúc gửi yêu cầu đến khi mentor có thể phân tích từ 15-30 phút xuống dưới 10 phút.
- Giảm số issue phải hỏi lại thông tin cơ bản.

Non-AI alternative:
Tạo mẫu tin nhắn/issue cố định gồm: mô tả lỗi, expected/actual result, command chạy, traceback đầy đủ, phiên bản Python/package, file hoặc đoạn code liên quan và các cách đã thử.

AI hypothesis:
Một AI Agent có thể hỏi sinh viên các trường còn thiếu, trích xuất traceback và thông tin môi trường từ terminal, sau đó tạo bản tóm tắt issue theo format chuẩn trước khi gửi mentor. Agent chỉ chuẩn bị context, không tự gửi thông tin nhạy cảm như API key và không thay mentor đưa ra quyết định kỹ thuật cuối cùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~20 phút/issue

[1. Gặp lỗi + tự thử xử lý: 5']
        ↓
[2. Gửi mô tả ngắn cho mentor: 2']
        ↓
[3. Mentor hỏi thêm traceback/context: 5']  <-- bottleneck
        ↓
[4. Thu thập thông tin + gửi lại: 8']
        ↓
[5. Mentor bắt đầu phân tích]

FUTURE STATE — ~7 phút/issue để đủ context

[1. Gặp lỗi + mở form hỗ trợ: 1']
        ↓
[2. Agent kiểm tra các trường bắt buộc và tạo draft issue: 3']
        ↓
[3. Sinh viên review, xóa thông tin nhạy cảm và gửi mentor: 2']  <-- human boundary
        ↓
[4. Mentor nhận đủ context để phân tích: 1']

Fallback: nếu Agent không thu thập được thông tin hoặc tóm tắt sai, sinh viên dùng mẫu issue thủ công, đính kèm terminal log/traceback và trao đổi trực tiếp với mentor.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Debug code/test mất nhiều thời gian.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow debug lặp lại 4-6 lỗi mỗi tuần, với 20-40 phút cho mỗi lỗi và 5-10 vòng test → sửa → test lại. Đây là pain có số đo rõ ràng, bottleneck tập trung ở bước tìm nguyên nhân từ traceback, code và tài liệu. Một Agent có thể gom context và đề xuất hướng sửa, còn sinh viên vẫn review thay đổi trước khi áp dụng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Agent sẽ dựa vào nguồn context nào để tránh đề xuất sửa sai hoặc quá chung chung? Metric nào ngoài thời gian debug sẽ chứng minh giải pháp thực sự tốt hơn, ví dụ tỉ lệ test pass hoặc số lỗi phát sinh sau khi sửa?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Phạm vi “debug mọi lỗi” quá rộng; Agent có thể thiếu context project, đề xuất sai hoặc làm sinh viên phụ thuộc vào gợi ý mà không hiểu nguyên nhân.
- Tôi sửa gì: Giới hạn MVP ở lỗi Python/pytest phổ biến, bắt buộc Agent nêu evidence từ traceback và file liên quan, đồng thời giữ bước review của sinh viên trước khi sửa code/chạy lại test.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
