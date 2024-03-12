# Interview questions
## 1. Kiểm thử phần mềm là gì?
```text
Kiểm thử phần mềm là quá trình thực thi và kiểm tra phần mềm nhằm phát hiện lỗi và đảm bảo chất lượng của phần mềm hoạt động
đúng với yêu cầu mong đợi.
```
## 2. 7 nguyên tắc cơ bản của kiểm thử phần mềm là gì?
```text
1. Kiểm thử chứng minh sự hiện diện của lỗi
2. Kiểm thử toàn bộ là không thể
3. Kiểm thử càng sớm càng tốt
4. Lỗi thường phân bố tập trung
5. Nghịch lý thuốc trừ sâu
6. Kiểm thử phụ thuộc vào ngữ cảnh
7. Quan niệm sai về phần mềm không có lỗi
```
## 3. Theo em hiểu nguyên lý thứ nhất "Kiểm thử chứng minh sự hiện diện của lỗi" là như thế nào?
```text
Bằng việc kiểm thử, chúng ta có thể làm giảm lượng bugs khi áp dụng nhiều phương pháp kiểm thử lên phần mềm.
Tuy nhiên khi được đưa lên môi trường thật, người dùng cuối hoàn toàn có thể thấy nhiều lỗi khác không tìm thấy
trong quá trình kiểm thử. Kiểm thử chứng minh được sản phẩm có lỗi nhưng không thể chứng minh rằng sản phẩm
không còn lỗi. Điều này có nghĩa là, sẽ luôn có lỗi không được phát hiện trong phần mềm, ngay cả khi không tìm
thấy lỗi, cũng không đồng nghĩa rằng phần mềm đúng hoàn toàn.
```
## 4. Tại sao "Kiểm thử toàn bộ là không thể"?
```text
Rất khó để kiểm tra toàn bộ các module cũng như các tính năng với việc kết hợp với đầu vào và đầu ra trong suốt quá trình
kiểm tra. Các sản phẩm phần mềm hiện nay cực kỳ đa dạng và phức tạp, được phát triển trên nhiều nền tảng, thêm vào
đó, ngày càng có nhiều công nghệ mới, khả năng kết nối dữ liệu lớn… khiến việc kiểm thử toàn bộ gần như là không thể.
Thay vì cố gắng kiểm thử toàn bộ, hãy xác định mức độ quan trọng và độ ưu tiên của các module để kiểm thử những phần
cần thiết hoặc gặp nhiều nguy cơ hơn.
```
## 5. Tại sao "Kiểm thử càng sớm càng tốt"?
```text
Nguyên tắc kiểm thử sớm có nghĩa là việc kiểm thử cần được thực hiện càng sớm càng tốt trong vòng đời phát triển phần mềm.
Nguyên tắc này cho thấy ta cần phát hiện bug ngay từ các bước đầu tiên như nghiên cứu yêu cầu (requirement) hay design. Phát
hiện lỗi càng muộn, chi phí bỏ ra để xử lý càng cao. Vì vậy, việc thay đổi yêu cầu không đúng từ sớm sẽ khiến tốn ít chi phí
để thay đổi tính năng hơn.
```
## 6. Theo em hiểu nguyên lý thứ năm "Nghịch lý thuốc trừ sâu" là như thế nào?
```text
Trong trồng trọt, nếu người nông dân sử dụng lặp lại một liều trừ sâu, các loại sâu bệnh sẽ dần dần thích nghi và trở nên "nhờn"
với loại thuốc trừ sâu đó. Tương tự với kiểm thử phần mềm, khi lặp đi lặp lại một test case, thì xác suất tìm được lỗi là rất thấp.
Nguyên nhân là hệ thống hoàn thiện hơn, lỗi tìm thấy đã được sửa theo test case cũ. Để xử lý hiệu ứng “thuốc trừ sâu” này, test case
cần được thường xuyên xem lại và chỉnh sửa, thêm nhiều test case mới để tìm lỗi mới (regression test).
Thêm vào đó, Tester cũng không nên phụ thuộc quá nhiều vào các kỹ thuật test sẵn có. Bạn cần liên tục cải tiến các phương pháp có sẵn
để làm việc kiểm thử hiệu quả hơn.
```
## 7. Kiểm thử tại sao lại phụ thuộc vào ngữ cảnh?
```text
Kiểm thử phụ thuộc vào ngữ cảnh, nói một cách đơn giản, là việc kiểm thử một trang thương mại điện tử sẽ phải khác cách test một
ứng dụng đọc tin tức. Tất cả các phần mềm đều được phát triển theo cách khác nhau. Và việc áp dụng chung một “cách giải” là sai lầm.
Bạn cần sử dụng cách tiếp cận khác nhau, phương thức, kỹ thuật test khác nhau, loại test phụ thuộc vào loại phần mềm/ứng dụng/website.
```
## 8. Theo em hiểu nguyên lý thứ bảy "Quan niệm sai về phần mềm không có lỗi" là như thế nào?
```text
Việc phát hiện và sửa chữa lỗi sẽ không giúp được gì nếu hệ thống đó không thể dùng được, hoặc không đáp ứng được nhu cầu và sự mong đợi
của người dùng.
Một số công ty mong đợi tester có thể thực hiện mọi trường hợp kiểm thử (test case) có thể có và tìm ra tất cả lỗi có thể xảy ra, nhưng như
đã đề cập, nguyên tắc 1 và 2 cho chúng ta biết rằng điều này là không thể. Hơn nữa, thật là sai lầm (đây là một niềm tin sai lầm) khi kỳ vọng
rằng chỉ cần tìm và sửa chữa một số lượng lớn lỗi (bug, defect) sẽ đảm bảo sự thành công của một hệ thống phần mềm.
Hoặc nếu hệ thống được xây dựng không thể sử dụng được cũng như không đáp ứng nhu cầu và mong đợi của người dùng thì việc tìm và sửa lỗi không
có ý nghĩa.
```
## 9. Theo em có các mô hình phát triển phần mềm?
```text
Theo em biết có một số mô hình phát triển phần mềm sau:
    - Mô hình thác nước (Waterfall Model)
    - Mô hình chữ V (V - Model)
    - Mô hình phát triển và tăng trưởng - lặp (Iterative-incremental Development Model), điển hình ở đây là Agile
```
## 10. Phân biệt QA (Quanlity Assurance) và QC (Quality Control)?
```text
QA là tập các hoạt động được tạo ra nhằm đảm bảo tiến trình phát triển sản phẩm là phù hợp, hệ thống sẽ đáp ứng các mục tiêu đặt ra
Nhiệm vụ của QA:
    - Chịu trách nhiệm toàn bộ về tiêu chuẩn, quy trình kiểm tra để đảm bảo chất lượng sản phẩm. Đề xuất, đưa ra quy trình phát triển
      cho từng dự án, đưa ra những tài liệu, biểu mẫu và hướng dẫn cho tất cả các bộ phận trong nhóm phát triển sản phẩm nhằm đảm bảo
      tất cả các thành viên nắm rõ các quy trình và tiêu chuẩn đã đề ra
    - Có nhiệm vụ giám sát các tiêu chuẩn và quy trình sản xuất phần mềm được định nghĩa và tuân thủ nghiêm túc. Nhắc nhở đội ngũ phát
      triển sản phẩm việc tuân thủ theo quy trình làm việc đã đưa ra.
    - Điều chỉnh, thay đổi, cái tiến quy trình phù hợp với từng sản phẩm mà các nhóm đang thực hiện
    - QA không trực tiếp kiểm tra chất lượng phần mềm
QC là tập hợp các hoạt động được tạo ra nhằm kiểm soát chất lượng sản phẩm, bảo đảm sản phẩm đúng đặc tả yêu cầu
Nhiệm vụ của QC:
    - Trực tiếp thực hiện kiểm tra chất lượng của sản phẩm trước khi bàn giao cho khách hàng
    - QC tuân thủ các quy trình do QA đề ra
    - Các hoạt động của QC bao gồm: Khảo sát, tìm hiểu hệ thống, phân tích tài liệu mô tả về hệ thống, lên kế hoạch kiểm thử, thiết kế
      các trường hợp kiểm thử, viết kịch bản, viết script, chạy thử, báo cáo lỗi, báo cáo kết quả kiểm thử
```
## 11. Phân biệt Verification và Validation?
```text
Verification là quá trình đánh giá phần mềm để xác định xem các sản phẩm của một giai đoạn phát triển nhất định có đáp ứng được các điều
kiện đặt ra của giai đoạn đó hay không. Sản phẩm ở đây có thể là sản phẩm trung gian trong quá trình phát triển như: Đặc tả yêu cầu, đặc
tả thiết kế, lập trình, hướng dẫn sử dụng và cả sản phẩm cuối cùng.
Verification được thực hiện trong suốt quá trình phát triển dự án. Nếu thực hiện kiểm định các sản phẩm ở giai đoạn khởi đầu cửa sự phát triển
sẽ giúp hiểu rõ sản phẩm một cách tốt hơn, giảm các lỗi sinh ra ở các giai đoạn phát triển về sau, giảm nguy cơ thất bại trong quá trình xây
dựng sản phẩm. Thực hiện verification giúp việc xây dựng sản phẩm đúng theo các thông số kỹ thuật và nhu cầu của khách hàng.
Verification sử dụng phương phát static testing, gồm các kỹ thuật như Walkthrough, Inspection, Review, Desk-checking, ...
Verification không liên quan đến việc thực thi mã nguồn

Validation là quá trình đánh giá một sản phẩm đáp ứng được mục đích sử dụng của nó, tức là hoạt động xác nhận sản phẩm có đúng với mong đợi
của khách hàng hay không? Có đúng yêu cầu nghiệp vụ không?
Validation được thực hiện vào cuối của quá trình phát triển và diễn ra sau khi việc Verification được hoàn thành. Nó đứng từ quan điểm của
khách hàng, sử dụng hệ thống thực, với môi trường thực và tập trung vào sản phẩm cuối cùng. Validation trả lời cho câu hỏi như: Có phải tôi
đang xây dựng đúng sản phẩm không?
```
## 12. Phân biệt Error, bug, defect, fault, failure?
```text
Error/mistake là lỗi xảy ra xuất phát từ hành động của con người dẫn đến kết quả sai.
Error/mistake dẫn đến lỗi xuất hiện trong mã nguồn, tài liệu, đặc tả, hướng dẫn, gọi là fault/defect/bug
Khi lỗi được tìm thấy bởi kiểm thử viên thì được gọi là defect, defect được chấp nhận bởi nhóm phát triển thì nó được gọi là bug
Khi phần mềm được thực thi, hệ thống hoặc phần mềm được tạo ra với kết quả không chính xác, hoặc bản build không phù hợp với quy
định đặc tả hệ thống hoặc không thực hiện đúng hành động điều này được gọi là failure.
```
## 13. Kiểm thử hộp đen là gì?
```text
Kiểm thử hộp đen là thực hiện quá trình kiểm thử mà không cần quan tâm đến mã nguồn của chương trình hay các hoạt động bên trong
hệ thống chạy ra sao, mà chỉ tập trung vào các giá trị đầu vào và các giá trị đầu ra của hệ thống có đúng với kết quả mong đợi của
các trường hợp kiểm thử không để từ đó đánh giá chất lượng hệ thống.
```
## 14. Kiểm thử hộp trắng là gì?
```text
Kiểm thử hộp trắng là thực hiện quá trình kiểm thử dựa trên các dòng lệnh bên trong hệ thống. Kiểm thử hộp trắng đòi hỏi người thực
hiện phải có kiến thức về ngôn ngữ lập trình, nghiên cứu các dòng lệnh, những phần mềm bên trong của hệ thống đẻ xem xét chúng chạy
có đúng không
```
## 15. Kiểm thử hộp xám là gì?
```text
Kiểm thử hộp xám là sự kết hợp giữa kiểm thử hộp đen và kiểm thử hộp trắng. Trong kiểm thử hộp xám, cấu trúc bên trong sản phẩm chỉ
được biết một phần. Người kiểm thử dựa vào yêu cầu và có thể truy cập vào cấu trúc dữ liệu bên trong hay thuật toán của chương trình
với mục đích là để thiết kế test case, nhưng khi kiểm thử thì thực hiện như người dùng cuối hoặc là ở mức hộp đen, thực hiện trên
giao diện của chương trình
```