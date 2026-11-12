# BÀI 5: ÁP DỤNG AI POLICY VÀ NGUYÊN TẮC HUMAN-IN-THE-LOOP TRONG ĐÁNH GIÁ NHÂN SỰ

**Họ và tên:** Võ Xuân Thịnh  
**Mã sinh viên:** N26DTCN032  
**Lớp:** HCMKS26CNTT2  
**Môn học:** IT\_206



## 1\. Phân tích vấn đề trong tình huống

Trong tình huống tại công ty MartX, Trưởng phòng Nhân sự đã đưa dữ liệu
KPI và lịch sử chấm công của 50 nhân viên vào AI, sau đó yêu cầu AI chọn
ra 3 nhân viên kém nhất để sa thải ngay lập tức. Sau khi nhận kết quả,
Trưởng phòng ký quyết định sa thải mà không kiểm tra lại.

Cách làm này là không phù hợp vì AI chỉ là công cụ hỗ trợ phân tích và
đưa ra gợi ý, không phải người có thẩm quyền quyết định việc sa thải.
Trưởng phòng Nhân sự đã phụ thuộc hoàn toàn vào kết quả AI và không thực
hiện trách nhiệm kiểm tra, đánh giá của con người.

Ngoài ra, việc có KPI thấp hoặc đi làm không đầy đủ trong một khoảng
thời gian chưa đủ để kết luận một nhân viên làm việc kém hoặc phải bị sa
thải. Cần xem xét nguyên nhân, tính chính xác của dữ liệu, hoàn cảnh
thực tế và các quy định của công ty cũng như pháp luật lao động.

## 2\. Nguyên tắc Human-in-the-loop là gì?

Human-in-the-loop (con người tham gia vào quy trình) là nguyên tắc yêu
cầu con người giám sát, kiểm tra và có quyền can thiệp vào quá trình AI
xử lý thông tin, đặc biệt là những quyết định có ảnh hưởng lớn đến con
người.

Trong đánh giá nhân sự, AI có thể hỗ trợ: - Tổng hợp dữ liệu KPI và chấm
công. - Phát hiện những điểm bất thường trong dữ liệu. - Đưa ra báo cáo
hoặc gợi ý để người quản lý xem xét.

Tuy nhiên, con người phải kiểm tra nguồn dữ liệu, đánh giá bối cảnh, xác
minh kết quả và tự chịu trách nhiệm về quyết định cuối cùng. AI không
được tự động thay thế người có thẩm quyền trong quyết định sa thải.

## 3\. Những rủi ro khi sử dụng AI để quyết định sa thải

**a. Rủi ro về định kiến (Bias)**

Dữ liệu đầu vào có thể chứa định kiến hoặc không phản ánh đầy đủ năng
lực của nhân viên. Ví dụ, nhân viên nghỉ làm do có lý do chính đáng hoặc
được công ty cho phép có thể bị AI đánh giá thấp nếu hệ thống chỉ nhìn
vào số ngày vắng mặt. AI cũng có thể đánh giá sai nếu KPI được giao
không đồng đều giữa các vị trí.

**b. Rủi ro dữ liệu không chính xác hoặc thiếu bối cảnh**

Dữ liệu KPI và chấm công có thể bị nhập sai, thiếu hoặc chưa được cập
nhật. AI có thể không biết một nhân viên đang được đào tạo, đang xử lý
công việc khó hoặc gặp vấn đề khách quan. Vì vậy, kết quả phân tích có
thể không phản ánh đúng hiệu quả làm việc.

**c. Rủi ro về quyền riêng tư**

KPI và lịch sử chấm công là thông tin liên quan đến người lao động. Công
ty cần kiểm soát việc thu thập, sử dụng và chia sẻ dữ liệu đúng mục
đích, đúng thẩm quyền và bảo vệ dữ liệu cá nhân. Không nên đưa dữ liệu
nhận dạng hoặc thông tin nhạy cảm của nhân viên lên công cụ AI không
được công ty cho phép.

**d. Rủi ro pháp lý và trách nhiệm**

Nếu quyết định sa thải được thực hiện sai căn cứ hoặc sai trình tự, công
ty có thể phát sinh tranh chấp lao động và phải chịu trách nhiệm theo
quy định pháp luật. Không thể lấy lý do "AI đưa ra kết quả" để miễn
trách nhiệm cho người quản lý hoặc doanh nghiệp.

## 4\. Vì sao câu nói của Trưởng phòng Nhân sự là sai?

Câu nói "Do AI phân tích khách quan từ số liệu, tôi không can thiệp nên
hoàn toàn công bằng" là sai ở các điểm:

* AI không mặc nhiên khách quan. Kết quả phụ thuộc vào dữ liệu đầu
vào, cách thiết kế hệ thống và câu lệnh được sử dụng.
* Không kiểm tra kết quả không có nghĩa là công bằng. Ngược lại, điều
đó làm tăng nguy cơ sai sót và định kiến.
* AI không có tư cách pháp lý hay thẩm quyền của người sử dụng lao
động để tự quyết định sa thải.
* Trưởng phòng Nhân sự và công ty không thể đẩy trách nhiệm sang AI.
Người có thẩm quyền vẫn phải xem xét căn cứ, quy trình và chịu trách
nhiệm đối với quyết định của mình.

## 5\. Đề xuất quy trình sử dụng AI đúng cách tại MartX

1. **Xác định mục đích:** Chỉ sử dụng AI để hỗ trợ tổng hợp và phân
tích hiệu quả công việc, không yêu cầu AI tự chọn người để sa thải.
2. **Kiểm tra dữ liệu:** Đối chiếu KPI, chấm công, thời gian cập nhật
và các trường hợp nghỉ phép hoặc vắng mặt có lý do.
3. **Bảo vệ dữ liệu:** Chỉ sử dụng dữ liệu cần thiết, hạn chế thông tin
nhận dạng và dùng công cụ AI được công ty cho phép.
4. **AI đưa ra báo cáo:** Yêu cầu AI nêu rõ tiêu chí, dữ liệu được sử
dụng, điểm chưa chắc chắn và các yếu tố có thể ảnh hưởng đến kết
quả.
5. **Con người xác minh:** Bộ phận Nhân sự và quản lý trực tiếp kiểm
tra từng trường hợp, trao đổi với nhân viên khi cần và cho nhân viên
cơ hội giải trình.
6. **Đưa ra quyết định:** Người có thẩm quyền xem xét toàn bộ thông
tin, căn cứ nội quy và pháp luật lao động trước khi quyết định.
Không sử dụng kết quả AI làm căn cứ duy nhất để sa thải.
7. **Lưu lại quá trình:** Ghi nhận dữ liệu, tiêu chí, kết quả AI, nội
dung kiểm tra của con người và lý do của quyết định để có thể giải
trình khi cần.

## 6\. AI Policy đề xuất cho công ty MartX

Công ty MartX nên áp dụng các nguyên tắc sau khi sử dụng AI trong quản
lý nhân sự:

* AI chỉ có vai trò hỗ trợ, không tự động đưa ra quyết định tuyển
dụng, kỷ luật hoặc sa thải.
* Không sử dụng kết quả AI làm căn cứ duy nhất cho quyết định ảnh
hưởng lớn đến quyền lợi của nhân viên.
* Dữ liệu đưa vào AI phải hợp pháp, chính xác, cần thiết và được bảo
vệ.
* Phải có người phụ trách kiểm tra kết quả AI, phát hiện định kiến và
sửa sai khi cần.
* Nhân viên cần được thông tin phù hợp và có cơ hội phản hồi khi kết
quả phân tích AI được sử dụng để đánh giá họ.
* Mọi quyết định cuối cùng phải do người có thẩm quyền xem xét và chịu
trách nhiệm.

