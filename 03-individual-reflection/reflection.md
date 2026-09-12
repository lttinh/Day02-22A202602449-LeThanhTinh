# 03 — Individual Reflection

Khi nghe các bạn pitch bài toán, tôi ấn tượng với góc nhìn đa dạng từ quản lý Agile của chị Tiên đến khâu trace dependency code của anh Khải. Đóng góp lớn nhất của tôi vào artifact cuối là đưa điểm nghẽn đếm khuẩn lạc đĩa Petri từ thực tế làm lab vi sinh ra làm đề tài chung cho nhóm. Lúc thảo luận, khi anh Khải và anh Khoa lo ngại khuẩn lạc dính chùm dễ đếm sai, nhóm từng định làm AI Agent thật phức tạp cho "ngầu". Tuy nhiên, tôi đã giải thích rằng nghiên cứu viên không cần hệ thống tự động hóa đắt đỏ, mà chỉ cần công cụ giảm mỏi mắt khi chấm đếm. Điều khó nhất khi viết Problem Statement chính là vạch ra Boundary để AI không làm thay việc của con người. Tôi đề xuất tính năng click ±1 trên giao diện Overlay mask, giúp nghiên cứu viên sửa lỗi đếm sót trong vài giây trước khi xuất Excel. Nhờ đó, nhóm thống nhất đưa giải pháp về đúng bản chất là một AI-assisted Workflow tinh gọn và an toàn cho dữ liệu khoa học. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ đầu ở khâu chuẩn hóa ánh sáng chụp ảnh để bộ metric đạt độ chính xác tối ưu.

## Thông tin cá nhân

- Họ và tên: Lê Thanh Tình
- Mã học viên: 2A202602449
- Nhóm: Nhóm 1
- Candidate problem nhóm chọn: AI Workflow đếm khuẩn lạc tự động trên đĩa Petri trong phòng thí nghiệm vi sinh bằng Watershed kết hợp AI Vision, hỗ trợ giao diện Overlay chấm màu để NCV kiểm tra nhanh (click ±1) và tự động xuất kết quả Excel.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đề xuất 3 bài toán thuộc lĩnh vực Sinh học - Nông nghiệp: Đếm khuẩn lạc đĩa Petri, Đo diện tích lá cây, Nhận diện sâu keo thực địa. | Đưa góc nhìn chuyên môn domain vi sinh/nông nghiệp vào ngân hàng ý tưởng của nhóm. |
| Pitch Problem Card | Pitch chi tiết điểm nghẽn đếm khuẩn lạc thủ công tốn 10-15 phút/đĩa, mỏi mắt, dễ đếm sót khi mật độ > 100 CFU và gõ Excel tay. | Giúp nhóm hình dung rõ nét nỗi đau thực tế tại các phòng lab (như UET Microbiology Innovation). |
| Challenge bài của bạn khác | Đặt câu hỏi cho bài đọc công thức toán của Khoa (rủi ro hallucinate) và bài rã task sprint của Tiên (thiếu ground-truth). | Giúp nhóm nhận diện rủi ro kỹ thuật và chuyển hướng chọn bài toán có tính kiểm chứng định lượng rõ ràng. |
| Gom trùng / cluster | Nhóm các bài toán thị giác máy tính (#16, #17, #18) vào Cụm A (Bio-Vision Lab). | Định hình rõ cụm bài toán có tiềm năng ứng dụng AI Vision cao nhất. |
| Chọn candidate problem | Trực tiếp phản biện nghi ngờ của Khải và Khoa về khả năng xử lý cụm khuẩn dính chùm bằng giải pháp kết hợp Watershed. | Thuyết phục 100% thành viên nhóm chốt chọn bài toán Đếm khuẩn lạc làm Problem Statement chính thức. |
| Validation / research | Tiến hành phỏng vấn 3 nhân sự lab vi sinh (1 Trưởng lab, 1 NCV, 1 KTV) và khảo sát 10 sinh viên/học viên. | Thu thập evidence thực tế: sai số 10-15% khi mật độ cao, gõ Excel tốn 2-3 phút, hình thành insight về Overlay chấm màu. |
| Workflow nhóm | Thiết kế các bước cho Future Workflow: Ảnh chụp chuẩn hóa → Watershed + AI Vision → Overlay mask → Click ±1 → Export Excel. | Xác định chính xác AI Intervention Point (bước 2-3) và Human Review Boundary (bước 4). |
| Problem Statement | Cùng Tiên và Dũng viết PS v0 và v1; thiết lập Success Metric (< 2 phút/đĩa, độ chính xác ≥ 93%) và Boundary. | Giúp PS đạt độ chặt chẽ cao, ranh giới can thiệp AI rõ ràng, không làm thay việc của con người. |
| Rule / Workflow / Agent | Phân tích lý do chọn AI-assisted Workflow thay vì Rule cổ điển hay Agent đắt đỏ; làm rõ 5 câu hỏi chốt. | Định vị đúng bài toán ở ô Medium Ambiguity — High Complexity, đưa ra phương án triển khai thực tế. |
| Decision | Cung cấp luận cứ chốt GO dựa trên tính khả thi kỹ thuật, chi phí thấp và giá trị giải phóng sức lao động cho NCV. | Giúp nhóm đạt sự đồng thuận tuyệt đối (GO) với độ tin cậy cao. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc đề xuất và bảo vệ thành công bài toán đếm khuẩn lạc đĩa Petri từ thực tế nghiên cứu vi sinh, đồng thời thiết kế chi tiết cơ chế phân đoạn Watershed kết hợp giao diện Overlay mask chấm màu (click ±1) làm chốt chặn Human Boundary vững chắc cho AI Workflow.
Khi nghe phần trình bày top 3 problems từ các bạn trong nhóm, tôi học được cách quan sát điểm nghẽn dưới nhiều góc nhìn đa dạng, từ quản lý Agile của Tiên đến việc trace dependency code của Khải. Đóng góp lớn nhất của tôi vào artifact cuối chính là đưa bài toán đếm khuẩn lạc đĩa Petri từ trải nghiệm thực tế trong phòng lab vi sinh ra làm Problem Statement chung của nhóm, đồng thời trực tiếp xây dựng luồng xử lý AI Vision kết hợp thuật toán Watershed. Ban đầu, khi Khải và Khoa đặt nghi vấn về rủi ro đếm sai khi khuẩn lạc dính chùm hoặc bóng phản xạ trên đĩa thạch, nhóm từng có lúc rơi vào bẫy solution-first khi đề xuất dùng AI Agent tự động cân chỉnh tham số nâng cao cho "ngầu". Tuy nhiên, tôi đã dùng kiến thức chuyên ngành để giải thích rằng việc cố gắng tự động hóa 100% bằng Agent trong nghiên cứu khoa học là cực kỳ rủi ro và tốn kém không cần thiết. Thay vào đó, điều khó nhất khi viết Problem Statement chính là xác định Boundary: làm sao để AI thực hiện phần việc nặng nhất (tách cụm và chấm điểm), nhưng con người vẫn giữ quyền chốt chặn cuối cùng. Tôi đã đề xuất giải pháp giao diện Overlay mask chấm màu cho phép nghiên cứu viên click ±1 sửa lỗi trong vài giây, giúp đưa bài toán về đúng mô hình AI-assisted Workflow vừa tinh gọn vừa đảm bảo độ chính xác tuyệt đối. Nếu được làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ đầu ở khâu chuẩn hóa điều kiện chụp ảnh thực địa để bộ metric đạt độ tiệm cận hoàn hảo hơn nữa.
