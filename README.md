# Name Project
    Fullstack Responsive Movie Website
# Tính Năng nổi bật
- Xác thực người dùng: Đăng ký và đăng nhập an toàn bằng JWT (JSON Web Token).

- Khám phá phim ảnh: Duyệt phim theo danh mục thịnh hành, xếp hạng cao.

- Tìm kiếm thông minh: Tìm kiếm phim nhanh chóng theo tiêu đề.

- Thông tin chi tiết: Xem thông tin đầy đủ về phim, bao gồm tóm tắt, diễn viên, và các bài đánh giá.

- Quản lý danh sách yêu thích: Người dùng có thể thêm/xóa phim khỏi danh sách yêu thích cá nhân.

- Viết đánh giá: Người dùng đã đăng nhập có thể để lại đánh giá và xếp hạng cho phim.

- Giao diện đáp ứng (Responsive): Trải nghiệm mượt mà trên mọi thiết bị từ máy tính để bàn đến điện thoại di động.

# Công nghệ sử dụng
-Back-end: Node.js & Express.js, MongoDB, Mongoose, JWT, Express Validator

# Hướng dẫn cài đặt và chạy dự án
1. Điều kiện tiên quyết:
- Node.js (v14.17.0 hoặc cao hơn)
- MongoDB (v5.0.0 hoặc cao hơn)
2. cài đặt
    * Clone dự án từ GitHub:
    - git clone https://github.com/SherLockLam-ai/Movie-Web
    * cài đặt Back-end:
    - cd server
    - npm install
    - tạo file .env và thêm thông tin kết nối MongoDB: MONGODB_URL=mongodb://localhost:27017/MoonFlix
    JWT_SECRET=your_jwt_secret_key_here
    PORT=5000
3. cài đặt front-end
- cd client
- npm install
- tạo file .env và thêm thông tin kết nối Back-end: REACT_APP_API_URL=

4. chạy dự án:
- chạy máy chủ Back-end từ server:
    npm start
- chạy ứng dụng Front-end từ client:
    npm start

Tác giả: Bùi Văn Lâm
GitHub: https://github.com/SherLockLam-ai/Movie-Web
Giấy phép: MIT
