# Giới thiệu
## Đặt vấn đề
Trong các trường đại học hiện nay, các dịch vụ hỗ trợ sinh viên đóng vai trò
quan trọng trong việc giải quyết các thắc mắc và xử lý các yêu cầu của sinh viên
liên quan đến các vấn đề hành chính, học thuật và cá nhân. Những dịch vụ này
hoạt động như một cầu nối giữa sinh viên và nhà trường, giúp giải quyết các vấn
đề như đăng ký môn học, hỗ trợ tài chính, điều chỉnh khóa học và các yêu cầu khác.

Hệ thống hoạt động như một kênh trò chuyện giữa sinh viên và người trả lời.
Đầu tiên, sinh viên có nhu cầu được hỗ trợ, giải đáp thắc mắc sẽ tạo câu hỏi/yêu
cầu và gửi đến hệ thống. Hệ thống sẽ chuyển câu hỏi/yêu cầu của sinh viên đến
người có chuyên môn thích hợp phụ trách trả lời câu hỏi. Người chuyên viên này
sau khi tiếp nhận câu hỏi/yêu cầu sẽ đưa ra phản hồi chính xác nhằm giải đáp vấn
đề sinh viên đang gặp phải và gửi lại cho hệ thống. Cuối cùng hệ thống sẽ chuyển
lại phản hồi đó cho sinh viên. Quy trình được mô tả trực quan ở sơ đồ trong hình
1.

<sơ đồ - Hình 1>


Cụ thể, ở hệ thống BKSI - kênh hỗ trợ sinh viên của Trường Đại học Bách Khoa - Đại học Quốc gia Thành phố Hồ Chí Minh, sinh viên đặt câu hỏi bằng
cách chọn loại câu hỏi/yêu cầu, nhập chủ đề và nội dung câu hỏi, sau đó gửi câu
hỏi/yêu cầu đi (hình 2).

<Giao diện - hình 2>

Các yêu cầu của sinh viên được tiếp nhận và xử lý thông qua những cán bộ
phụ trách trong trường học. Giao diện của cán bộ trả lời cho sinh viên được mô tả
như hình 3 dưới đây. Một câu hỏi của sinh viên bao gồm chủ đề (dòng chữ lớn) và
nội dung. Khi sinh viên gửi một yêu cầu mới, hệ thống sẽ tạo ra một ticket. Đây
là một luồng thông tin giúp sinh viên và người trả lời có thể gửi tin cho nhau như
đoạn hội thoại. Việc trả lời câu hỏi diễn ra trong ticket. Nếu sinh viên tiếp tục có
thắc mắc với vấn đề liên quan hoặc chưa hài lòng với câu trả lời, có thể tiếp tục
gửi yêu cầu trong ticket này.

Các cán bộ phải đọc kỹ và hiểu nội dung câu hỏi được gửi đến từ sinh viên,
đồng thời cũng cần phải có một lượng hiểu biết lớn về các quy chế, quy định và
một số kiến thức nghiệp vụ khác của Nhà trường để trả lời các câu hỏi một cách
chính xác. Hình 4 là hình ảnh giao diện của cán bộ hỗ trợ sinh viên. Người cán bộ
đang trong quá trình trả lời câu hỏi.

<Hình 3, giao dien cac bo tiep nhan cau hoi>
<Hình 4, can bo phu trach nhap noi dung tra loi cau hoi cho tung sinh vien>

Việc nhớ được một khối lượng kiến thức về quy chế, quy định cùng với toàn
bộ nghiệp vụ của nhà trường là rất khó khăn, thậm chí bất khả thi. Những người
phụ trách trả lời câu hỏi có thể sẽ phải đọc lại các tài liệu (trong trường hợp người
cán bộ muốn trả lời chi tiết cho sinh viên, chứ không chỉ đưa đường dẫn quy chế
quy định cho sinh viên tự tìm hiểu), tổng hợp và kiểm tra kỹ càng trước khi đưa
ra câu trả lời của mình. Vì thế, công việc này có thể tiêu tốn nhiều thời gian và
công sức của chuyên viên phụ trách, cũng như có thể xảy ra nhầm lẫn khó tránh
khỏi mà đưa ra những câu trả lời sai, trong khi các kênh hỗ trợ này yêu cầu sự
chính xác và nhanh chóng.

Ngoài ra, các câu hỏi dài của sinh viên cũng có khả năng gây ra nhiều trở ngại
cho người phụ trách khi trả lời các câu hỏi đó. Các câu hỏi dài này của sinh viên
có thể chứa rất nhiều thông tin lan man hoặc thậm chí không rõ ý định, gây lãng
phí thời gian không cần thiết cho người đọc (hình 5). Vì vậy, việc tìm ra ý định và
những thông tin liên quan đến ý định từ yêu cầu của sinh viên sẽ tiết kiệm được
rất nhiều thời gian của chuyên viên trả lời. Khi nắm được các thông tin này, người
cán bộ hoàn toàn có thể biết được toàn bộ nội dung câu hỏi của sinh viên, và có
thể phản hồi một cách nhanh chóng.

<Hình 5 - cau hoi dai cua sinh vien>

Số lượng yêu cầu và thắc mắc được sinh viên gửi đến là quá lớn, các trường đại
học phải đối mặt với thách thức trong việc quản lý và phản hồi các thắc mắc này
một cách hiệu quả và kịp thời. Vì thế hiện nay các trường đại học đang có mong
muốn chuyển dần các dịch vụ hỗ trợ sinh viên do con người phụ trách sang cho
máy tính thông minh đảm nhiệm, chẳng hạn như trợ lý ảo, chatbot. Nền tảng của
hệ thống thông minh là đồ thị tri thức dùng để quản lý các kiến thức về nghiệp
vụ của trường học cũng như việc phát hiện ý định và thông tin liên quan trong
câu hỏi, yêu cầu của sinh viên.


## Động lực
Trợ lý ảo đang ngày càng phổ biến trong thế giới hiện đại nên việc nâng cao
hiệu quả hoạt động của chúng trở nên thiết yếu. Yếu tố then chốt quyết định sự
thành công của các trợ lý ảo này chính là khả năng nắm bắt và hiểu đúng yêu cầu
của người dùng, từ đó đưa ra hành động hoặc phản hồi thỏa đáng, đáp ứng đúng
nhu cầu mà họ mong đợi. Trong lĩnh vực xử lý ngôn ngữ, nội dung yêu cầu của
người dùng có thể tóm tắt dưới dạng một khung ngữ nghĩa (semantic frame) bao
gồm thông tin về ý định và các thông tin khác có trong câu [49]. Trong hệ thống
hỗ trợ sinh viên, việc nhận diện ý định và các thông tin liên quan cũng vô cùng
quan trọng. Ngoài việc nó có vai trò cốt lõi khi hiện thực một hệ thống tự động,
trước hết nó cũng giúp ích cho các cán bộ tiếp nhận câu hỏi. Thay vì phải đọc
những đoạn nội dung dài trong câu hỏi, người cán bộ chỉ cần tiếp nhận thông tin
ngắn gọn trong khung ngữ nghĩa, từ đó có thể hiểu được toàn bộ nội dung yêu
cầu để cho phản hồi thích hợp. Vì vậy, việc thực hiện nhiệm vụ Phát hiện ý định
và Điền trường thông tin trong đề tài có ý nghĩa thực tiễn.

Một vấn đề khác của hệ thống hỗ trợ sinh viên là một nền tảng để không chỉ
lưu trữ kiến thức và còn phải dễ dàng tìm kiếm và truy xuất. Công nghệ hiện
nay có thể thỏa mãn được điều đó chính là đồ thị tri thức. Đồ thị tri thức vốn
bắt nguồn từ công nghệ Semantic Web (Web ngữ nghĩa) dùng để biểu diễn tất cả
những hiểu biết trong một lĩnh vực hay một vấn đề cụ thể nào đó dưới dạng thực
thể và các mối quan hệ giữa chúng. Trong lĩnh vực giáo dục, đồ thị tri thức có
thể tích hợp thông tin từ các cơ sở dữ liệu khác nhau của trường đại học, chẳng
hạn như hồ sơ sinh viên, các khóa học được cung cấp, quy chế quy định,... vào
một định dạng chung và có cấu trúc. Việc các chatbot, hệ thống hỏi đáp sử dụng
đồ thị tri thức đang rất phổ biến hiện nay, vì nó có thể truy xuất các thông tin
liên quan, cung cấp phản hồi chính xác hơn, giảm thiểu tình trạng "hallucination"
(hiện tượng một mô hình sinh ngôn ngữ có khả năng tạo ra những thông tin không
có cơ sở thực tế) ở các mô hình ngôn ngữ lớn (LLM).

Đồ thị tri thức dùng cho hệ thống hỗ trợ sinh viên không chỉ chứa những thông
tin kiến thức nghiệp vụ hay quy chế quy định khác của nhà trường mà còn nên
chứa thông tin về ý định của sinh viên, nhằm giúp hệ thống dễ dàng suy luận
phản hồi thông qua các thông tin liên quan đến ý định. Lấy ví dụ, một bạn sinh
viên muốn đăng ký luận văn tốt nghiệp vào học kì 231. Ta có thông tin của bạn
sinh viên và cả thời điểm bạn đăng ký luận văn. Với thông tin của sinh viên này
lưu trên đồ thị tri thức, ta biết được điểm anh văn của bạn, cùng với thông tin
quy chế quy định của nhà trường trên đồ thị, hệ thống có thể kết luận bạn đạt
chuẩn anh văn để được đăng ký luận văn hay không và đưa ra phản hồi tương
ứng. Với ví dụ trên, ta thấy thông tin khung ngữ nghĩa (semantic frame) gồm ý
định và các thông tin liên qua (còn gọi là các trường - slot) nên được tích hợp vào
trong đồ thị tri thức giúp hệ thông hoạt động hiệu quả. Cùng ý tưởng này, bài
báo "Cross-Data Knowledge Graph Construction for LLM-enabled Educational
Question-Answering System: A Case Study at HCMUT" [4] cũng đã xây dựng đồ
thị tri thức gồm ý định được xem như là thực thể, và mối quan hệ giữa ý định và
các quy chế quy định. Tiếp nối ý tưởng này, nhóm thực hiện đề tài cũng thực hiện
xây dựng đồ thị tri thức chứa thông tin ý định, nhưng xem chúng như mối quan
hệ giữa các thực thể. Do cùng lĩnh vực và phạm vi nghiên cứu, nhóm có sử dụng
lại một số kết quả của bài báo. Hình 6 dưới đây mô tả lược đồ đồ thị tri thức của
nghiên cứu trên. Trong đó, các khối hình chữ nhật cạnh tròn chỉ các thực thể ý
định; các khối hình bình hành chỉ các thực thể là quy chế quy định; và các khối
oval là các thực thể còn lại trong trong trường.

<Hình 6: Đồ thị tri thức bao gồm ý định trong lĩnh vực giáo dục [4]>
Rất nhiều nghiên cứu cho đến nay tiếp cận nhiệm vụ xây dựng đồ thị tri thức
theo hướng top-down (rút trích tri thức theo một lược đồ cho trước). Hướng tiệp
cận này cần nhiều nỗ lực từ những chuyên gia hiểu biết sâu về lĩnh vực mà ta xây
dựng đồ thị để thiết kế ra một lược đồ chính xác, vững chắc, đầy đủ làm khung
cho đồ thị. Nhưng trong những tình huống thực tế, việc có sẵn những chuyên gia
này là điều không chắc chắn. Dựa trên vấn đề này, nhiều nghiên cứu hiện nay đang
theo hướng tiếp cận bottom-up (rút trích thông tin trước rồi tổng hợp lại thành
lược đồ). Tuy đánh đổi một phần chất lượng, nhưng quá trình sinh đồ thị theo
hướng này có thể thực hiện tự động và không cần hoặc chỉ cần ít sự tham gia của
con người, khiến nó trở thành một hướng đi hứa hẹn trong tương lai. Các nghiên
cứu xây dựng đồ thị tri thức theo hướng bottom-up cho tới hiện nay vẫn chỉ giới
hạn trong việc khám phá ra các kiểu quan hệ, các kiểu thực thể vẫn phải được
cho từ trước từ một người chuyên gia nào đó. Trong đề tài, nhóm sẽ thử nghiệm
hướng tiếp cận bottom-up và khám phá kiểu thực thể để xây dựng đồ thị tri thức.

# Cơ sở lý thuyết
# Các công trình liên quan
# Phương pháp thực hiện
