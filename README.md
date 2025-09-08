# chatj

lưu ý chỉ sử dụng js, ejs, chức năng đăng nhập và đăng ký của website không được sử dụng chức năng đăng nhập của replit

Tôi muốn tạo Website chat "Chat J" với pure JavaScript, EJS templates, SQLite database và tất cả advanced features
- giao diện giống 100% như: 
+ hình 1 giao diện trên máy tính.
+ hình 2 giao diện trên điện thoại khi đăng nhập thành công.
+ hình 3 giao diện chat khi truy câp vào cuộc trò chuyện). 
- và tôi muốn giao diện được tối ưu hóa cho mọi thiết bị desktops, tablets, and mobile phones
- chat realtime với websocket, hiện thị trạng thái online ,thời gian online, thời gian nhắn tin theo thời gian thực,...
- database: sqlite + chỉ sử dụng js, ejs,...
* lưu ý: website phát triển để phát triển API cho mobile app sau này
- hiện thị tin nhắn mới nhất khi chọn cuộc trò chuyện,...
có chức năng đồng nhất trong 1 trang:
- đăng nhập (email,số điện thoại,tên đăng nhập không phân biệt hoa thường)
- đăng ký (họ và tên, ngày tháng năm sinh, số điện thoại, email, mật khẩu, địa chỉ,...)
- hồ sơ tài khoản ( có thể thay đổi ảnh đại diện, ảnh bìa, Tên Tài khoản, tên đăng nhập [chỉ thay đổi được 1 lần], email , số điện thoại, mật khẩu) - xác nhận kích hoạt email khi đăng ký
- quên mật khẩu 
- xác minh 2 bước 2fa (nếu bật khi đăng nhập thì phải lại mã trên ứng dụng authenticator)
- đăng xuất
- hình ảnh mặc định khi không cài ảnh đại diện và ảnh bìa
- thêm chức năng gửi video
- thêm dấu tích xanh giống facebook khi được bật (đã xác minh) nếu được cấp bởi admin hoặc mod
- thêm chức năng hiện thị quyền (admin, Moderator, user (thành viên))
- tạo và phát triển trang admin (admin hoặc mod mới có thẻ truy cập) để quản lý dung lượng file, video, tin nhắn, ghi âm, người dùng, quyền và chức năng của quyền được cấp hoặc tạo thêm quyền
- đồng bộ chức năng tìm kiếm username, số điện thoại, email để thêm bạn bè và chức năng tìm kiếm tin nhắn với nhau
- thêm chức năng bạn bè (có thể xóa bản bè)
- thêm tính năng dòng thời gian giống facebook để thành viên có thể đăng hình ảnh, video, bài viết (3 chế độ: công khai, bạn bè, riêng tư
- thêm chức năng cài đặt hoàn chỉnh
- tạo sẵn 1 tài khoản admin (tên đăng nhập admin - email:will.crying@gmail.com - mật khẩu là admin123)
yêu cầu các chức năng phải hoạt động ổn định và hoàn chỉnh
hãy sử dụng tiếng việt
tài khoản gmail info.vedjsc@gmail.com/fxpbyjlgfkaashir (bảo mật .env)
hãy kiểm tra toàn bộ code và bổ sung các chức năng còn thiếu hoăc sửa lỗi đang có. có rất nhiều tính năng chưa hoạt động và chưa hoàn thiện. 

chuyển đổi toàn bộ mã nguồn ts và tsx sang js và ejs và sqlite và xóa các file liên quan tới TypeScript  (ts ,tsx,...)

toàn bộ mã nguồn chỉ được sử dụng đuôi file js và ejs và sqlite (tôi sẽ tự upload) không được sử dụng công nghệ TypeScript  (ts ,tsx,...), python ,...
