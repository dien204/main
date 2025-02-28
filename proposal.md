Đề Tài: Web Kết Nối Cựu Sinh Viên

1. Giới thiệu
   Dự án Alumni Connect là một nền tảng web giúp kết nối cựu sinh viên của một trường đại học, tạo cơ hội giao lưu, hỗ trợ nghề nghiệp và duy trì quan hệ cộng đồng. Trang web cung cấp các tính năng như đăng ký thành viên, quản lý hồ sơ cá nhân, đăng bài viết, tìm kiếm bạn bè, tạo sự kiện và tham gia các nhóm theo chuyên ngành hoặc sở thích.
   
2. Mục Tiêu
  ●	Kết Nối Cựu Sinh Viên: 
  ●	Chia Sẻ Cơ Hội Nghề Nghiệp: 
  ●	Xây Dựng Cộng Đồng Hỗ Trợ: 
  ●	Tổ Chức Sự Kiện: 
  
3. Chức Năng Chính
  ●	Đăng Nhập/Đăng Ký: 
  ●	Tạo Hồ Sơ Cá Nhân: 
  ●	Chia Sẻ Cơ Hội Nghề Nghiệp: 
  ●	Bảng Tin:.
  ●	Diễn Đàn Thảo Luận
  ●	Actors:
      ○	Cựu Sinh Viên:
          ■	Quản lý hồ sơ cá nhân.
          ■	Kết nối với cựu sinh viên khác.
          ■	Chia sẻ cơ hội nghề nghiệp.
          ■	Tham gia thảo luận và sự kiện.
      ○	Quản Trị Viên (Admin):
          ■	Quản lý người dùng.
          ■	Giám sát nội dung và hoạt động trên nền tảng.
          
5. Use Case Diagram
  ●	Chức Năng của Cựu Sinh Viên 
      ○	Đăng nhập, đăng ký.
      ○	Quản lý hồ sơ cá nhân.
      ○	Đăng bài viết và bình luận.
      ○	Tham gia sự kiện.
  ●	Chức Năng của Quản Trị Viên:
      ○	Quản lý người dùng.
      ○	Giám sát và chỉnh sửa nội dung.
      ○	Tổ chức sự kiện.
      
6. Thiết Kế Lược Đồ CSDL
  ●	USER (user_id, name, email, password, profile_picture, bio)
  ●	JOB_POST (job_id, title, description, company, date_posted, user_id)
  ●	EVENT (event_id, title, description, date, location, user_id)
  ●	COMMENT (comment_id, detail, user_id, post_id)
  
7. Thiết Kế Giao Diện
  ●	Đăng nhập: login.html
  ●	Đăng ký: register.html
  ●	Trang chủ: index.html (Hiển thị danh sách bài post mới nhất từ tất cả user)
  ●	Đặt lại mật khẩu: resetpass.html
  ●	Chi tiết bài viết: post.html (Hiển thị bài viết theo ID và bình luận)
  ●	Danh sách bài viết của user: posts.html
  ●	Danh sách người dùng (chỉ admin): users.html
  
8. Thiết Kế Chi Tiết (Wireframe)
register.html
  ●	Form đăng ký gồm:
      ○	Username
      ○	Password
      ○	Confirm Password
      ○	Nút Register
login.html
  ●	Form đăng nhập gồm:
      ○	Username
      ○	Password
      ○	Nút Login
index.html
  ●	Hiển thị danh sách bài viết mới nhất với tiêu đề, nội dung ngắn gọn, link xem chi tiết.
post.html
  ●	Hiển thị chi tiết bài viết
  ●	Hiển thị bình luận và form nhập bình luận (nếu user đã đăng nhập)
posts.html
  ●	Hiển thị danh sách bài viết của user hiện tại
  ●	Các nút Chỉnh sửa/Xóa bài viết
users.html (Admin Only)
  ●	Hiển thị danh sách user
  ●	Nút reset mật khẩu



