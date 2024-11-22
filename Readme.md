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
 - Tìm kiếm chuyến xe theo điểm khởi hành, điểm đến, ngày giờ và số lượng hành khách.
 - Chọn chuyến xe phù hợp và thực hiện đăng ký/đăng nhập.
 - Quản lý và cập nhật thông tin như số điện thoại,tên,địa chỉ,…
 - Đặt vé và quản lý vé đã đặt, bao gồm kiểm tra, hủy vé và nhận thông báo về tình trạng chuyến đi.
 
## Quy trình đặt vé xe khách
- B1: Khi người dùng bắt đầu vào trang web,người dùng có thể chọn phần điều hướng là tìm kiếm chuyến xe hoặc đăng nhập/đăng ký ở trên thanh header.
  - TH1:Người dùng ấn vào thanh tìm kiếm và chọn chuyến xe khi đó ấn nút “đặt vé ” thì hệ thống sẽ tự động điều hướng đến phần đăng ký/đăng nhập.
  - TH2:Người dùng nhấn vào phần đăng ký/đăng nhập,ở đây nếu chưa có tài khoản người dùng sẽ phải đăng ký và tạo tài khoản để đăng nhập vào hệ thống.
- B2: Sau khi đã đăng nhập được và hệ thống,người dùng sẽ tìm đến chức năng tìm kiếm chuyến xe nằm trong biểu tượng icon trên thanh header,tại đây sẽ nhập thông tin cần thiết (nơi đi, nơi đến, ngày đi, số lượng khách) để tìm chuyến xe.
- B3: Sau khi chọn chuyến xe, người dùng ấn nút “Đặt vé” và sẽ được đưa đến trang vé xe để xác nhận và đặt vé và thanh toán.
- B4: Người dùng sau khi đặt vé thành công hệ thống sẽ hiện lên thông báo đã đặt vé thành công.Và trong cùng trang vé xe đó người dùng có thể xem lại các chuyến xe đã đặt,đã đi và có thể hủy vé.
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