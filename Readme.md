# Phát triển Front-end cho ứng dụng đặt vé xe khách BlueBus

## Họ và tên :Hoàng Ngọc Tú
## Bản quyền thuộc về htu25578@gmail.com

## Mục Tiêu
Mục tiêu của ứng dụng là cung cấp dịch vụ đặt vé,bên cạnh đó tạo ra một nền tảng kết nối chặt chẽ giữa hành khách và công ty vận tải. Với giao diện thân thiện và các chức năng dễ sử dụng, ứng dụng sẽ phải giúp khách hàng dễ dàng tìm kiếm chuyến xe, đặt vé,và kiểm tra vé. Điều này không chỉ nâng cao chất lượng dịch vụ mà còn gia tăng sự hài lòng của khách hàng, tạo ra một trải nghiệm thuận tiện và hiệu quả trong quá trình di chuyển.

## Các công nghệ được sử dụng:
 - HTML(HyperText Markup Language): HTML là ngôn ngữ đánh dấu tiêu chuẩn được sử dụng để tạo cấu trúc và nội dung của trang web. Nó cho phép xác định các phần tử như tiêu đề, đoạn văn, hình ảnh, và liên kết, tạo khung cơ bản cho giao diện người dùng.
 
 
     ![alt text](image.png)



 - CSS(Cascading Style Sheets): CSS là ngôn ngữ dùng để định kiểu cho các tài liệu HTML. Nó kiểm soát cách nội dung hiển thị, bao gồm màu sắc, phông chữ, khoảng cách và bố cục. CSS giúp tạo ra giao diện đẹp mắt và cho người dùng trải nghiệm tốt về trang web hơn.


     ![alt text](image-2.png)


- JavaScript: JavaScript là ngôn ngữ lập trình kịch bản cho phép thêm tính năng tương tác vào trang web. Nó xử lý sự kiện, thao tác với DOM, và thực hiện các tác vụ bất đồng bộ, từ đó cải thiện trải nghiệm người dùng với các hiệu ứng động và tương tác thời gian thực.


     ![alt text](image-3.png)


- Bootstrap: Bootstrap là một framework front-end mạnh mẽ, được phát triển bởi Twitter, giúp các nhà phát triển xây dựng các giao diện web đẹp mắt và tương thích trên nhiều thiết bị khác nhau. Bootstrap cung cấp sẵn các thành phần giao diện người dùng như forms, buttons, navigation, và nhiều module JavaScript, giúp tiết kiệm thời gian và công sức trong quá trình phát triển.


    ![alt text](image-4.png)



- Git: Git là một công cụ thiết yếu trong phát triển phần mềm hiện đại, giúp lập trình viên quản lý mã nguồn hiệu quả, hỗ trợ làm việc nhóm và cải thiện quy trình phát triển. Với khả năng phân tán và các tính năng mạnh mẽ, Git đã trở thành tiêu chuẩn trong ngành công nghiệp phần mềm.


     ![alt text](image-5.png)

## Các chức năng của trang web
-	Đăng ký/ Đăng nhập:Khách hàng sẽ đăng ký và đăng nhập vào hệ thống để có thể bắt đầu tìm kiếm chuyến xe và đặt vé.
-	Tìm kiếm chuyến xe:Sau khi đăng nhập,khách hàng sẽ tìm kiếm chuyến xe dựa trên nhu cầu của mỗi người và thực hiện việc đặt vé.
-	Đặt vé và thanh toán:Sau khi tìm kiếm chuyến xe,khách hàng thực hiện việc đặt vé xe và thanh toán.
-	Kiểm tra và hủy vé:Sau khi thanh toán thành cồng,mỗi khách hàng sẽ tự kiểm tra vé của mình và có thể hủy vé trước thời gian quy định.

 
## Quy trình đặt vé xe khách
-	Đối với khách hàng chưa có tài khoản.
•	B1:Khi khách hàng bắt đầu vào trang web sẽ nhấn tới thanh điểu hướng đăng nhập/đăng ký.Tại đây khách hàng chưa có tài khoản nên sẽ đăng ký tài khoản,khách hàng sẽ phải nhập các trường thông tin cần thiết như:tên người dùng,gmail,số điện thoại,mật khẩu và xác nhận mật khẩu.Sau khi đã đăng ký tài khoản thành công,khách hàng sẽ thực hiện đăng nhập để có thể sử dụng các dịch vụ của trang web.
•	B2:Sau khi đã đăng nhập thành công,khách hàng sẽ cập nhật và xác thực lại các thông tin cá nhân của mình qua mục thông tin cá nhân.
•	B3:Sau khi cập nhật thành công,sẽ thực hiện việc tìm kiếm các chuyến xe tại mục “Tìm kiếm chuyến xe”.Tại đây khách hàng sẽ thực hiện việc tìm kiếm chuyến xe dựa trên nơi đến,nơi đi,ngày đi,số lượng khách, và khách hàng sẽ tìm kiếm dựa trên nhu cầu của mỗi người.
•	B4:Sau khi tìm kiếm chuyến xe thành công,khách hàng sẽ được đưa đến tới trang thanh toán,tại đây khách hàng sẽ thực hiện việc nhập số tiền cần thanh toán và thanh toán qua việc chuyển khoản.
•	B5:Nếu đã thanh toán thanh công,khách hàng sẽ có thể xem lại vé xe của mình tại mục vé xe,và có thể hủy chuyến trước thời gian quy định của hệ thống.
- Đối với khách hàng đã có tài khoản.
•	B1:Khách hàng khi đã có tài khoản sẽ thực hiện việc đăng nhập để có thể vào sử dụng các dịch vụ của hệ thống.
•	B2:Khách hàng cũng thực hiện các bước như tìm kiếm chuyến xe và thực hiện việc đặt vé.
•	B3: Tại mục đặt vé khách hàng có thể nhập các mã giảm giá mà khách hàng đã tích được khi đã trải nghiệm dịch vụ, và tiếp tục thực hiện việc thanh toán.
•	B3: Sau khi thanh toán thành công, khách hàng có thể xem lại vé xe của mình tại mục vé xe, và có thể hủy chuyến trước thời gian quy định của hệ thống.

## Sơ đồ phân rã chức năng
![alt text](image-6.png)

## Phát triển giao diện tuần 3
### Trang chủ đã được phát triển với các yếu tố cần thiết như banner nổi bật, bài viết mới nhất và đánh giá của người dùng, từ đó nâng cao trải nghiệm ứng dụng.

 <video controls src="img-readme/Quay màn hình 2024-10-30 214416.mp4" title="Title"></video>


 ## Phát triển giao diện tuần 4
### Trong tuần 4, đã hoàn thiện chức năng tìm kiếm chuyến xe cho ứng dụng đặt vé xe khách BlueBus của Công ty TNHH Vận Tải Hoàng Long. Chức năng này cho phép người dùng nhập thông tin về nơi đi, nơi đến, ngày đi và số lượng khách để tìm kiếm các chuyến xe phù hợp. Việc này không chỉ giúp nâng cao trải nghiệm người dùng mà còn làm cho quá trình đặt vé trở nên dễ dàng và nhanh chóng hơn.

<video controls src="img-readme/nguoidungnhantimkiem.mp4" title="Title"></video>


## Phát triển giao diện tuần 5
### Trong tuần năm, quá trình phát triển chức năng đăng nhập và đăng ký cho ứng dụng đặt vé xe khách BlueBus của Công ty TNHH Vận Tải Hoàng Long đã được hoàn thiện. Chức năng này cho phép người dùng dễ dàng tạo tài khoản và truy cập vào hệ thống, từ đó quản lý thông tin cá nhân và đặt vé một cách thuận tiện.


<video controls src="img-readme/nguoidungkhinhandangkydangnhap.mp4" title="Title"></video>

## Phát triển giao diện tuần 6
### Trong tuần qua, việc phát triển trang chủ sau khi đăng nhập và trang thông tin cá nhân cho ứng dụng đặt vé xe khách BlueBus thuộc Công ty TNHH Vận Tải Hoàng Long đã được hoàn thiện. Trang chủ được thiết kế nhằm tạo điều kiện thuận lợi cho người dùng trong việc đăng ký và đăng nhập vào hệ thống. Sau khi đăng nhập, người dùng sẽ được đưa đến trang chủ tại đây người dùng cũng có thể di chuyển đến trang thông tin cá nhân, nơi họ có thể xem và cập nhật thông tin của mình. 

<video controls src="img-readme/thongtincanhan.mp4" title="Title"></video>


## Phát triển giao diện tuần 7
### Trong tuần này, việc phát triển chức năng tìm kiếm chuyến xe và áp dụng mã giảm giá sau khi đăng nhập cho ứng dụng đặt vé xe khách BlueBus thuộc Công ty TNHH Vận Tải Hoàng Long đang được triển khai. Chức năng tìm kiếm chuyến xe giúp người dùng dễ dàng tìm thấy các lựa chọn phù hợp với nhu cầu di chuyển của mình. Bên cạnh đó, việc áp dụng mã giảm giá sẽ mang lại ưu đãi hấp dẫn, khuyến khích người dùng đặt vé thường xuyên hơn.


<video controls src="img-readme/Tìm kiếm chuyến xe và mã giảm giá.mp4" title="Title"></video>