# Đồ án Triển khai Hệ thống Website Quảng bá Sản phẩm (WordPress)

Website giới thiệu sản phẩm tiếng Việt, phục vụ bằng Nginx trong Docker Compose. Nội dung mẫu có thể chỉnh sửa tại `website/index.html`; hãy thay tên thương hiệu, mô tả, thông tin sản phẩm và địa chỉ email `hello@example.com` trước khi công bố.

## Chạy trên máy tính
1. Cài đặt và khởi động Docker Desktop.
2. Mở PowerShell tại thư mục dự án và chạy:
   ```powershell
   docker compose up -d
   ```
3. Truy cập website tại [http://localhost](http://localhost).

Một số dịch vụ khác:
- phpMyAdmin: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Prometheus: [http://localhost:9090](http://localhost:9090)
- Grafana: [http://localhost:3001](http://localhost:3001)

## Đưa mã nguồn lên GitHub
Tạo repository trống trên GitHub, sau đó cấu hình remote và đẩy nhánh hiện tại:
```powershell
git remote add origin https://github.com/<tai-khoan>/<repository>.git
git push -u origin HEAD
```
Khi được yêu cầu xác thực, hãy dùng Git Credential Manager hoặc GitHub CLI. Không đưa Personal Access Token vào lệnh, tệp cấu hình hay lịch sử Git.
