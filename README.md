# Deploy Frontend

- Sao chép source code từ project student-management sang thư mục frontend (Bỏ qua thư mục node_modules), vì sau này trỏ terminal vào gõ `npm i` để tải thư viện.
- các file và folder cần copy như là: package.json, public, src, .gitignore.
- Sau đó gõ `npm i` để cài thư viện thì nó tự tạo thư mục node_modules.

- Sửa lại `api.js` chỗ BASE_URL là link backend đã deploy ở trên render:

## Deploy trên render.com

- Chọn Add new
- Chọn Static sites
- Chọn project frontend ở Github
- Các cấu hình giữ nguyên
- Chọn Deploy ....
