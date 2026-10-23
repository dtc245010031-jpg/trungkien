# Website quảng bá sản phẩm

Trang giới thiệu sản phẩm tiếng Việt, chạy bằng Nginx trong Docker Compose. Nội dung mẫu nằm trong `website/index.html`; trước khi công bố, hãy thay tên thương hiệu, mô tả sản phẩm và địa chỉ email `hello@example.com`.

## Chạy trên máy tính
1. Cài đặt và khởi động Docker Desktop.
2. Mở PowerShell tại thư mục dự án và chạy:
   ```powershell
   docker compose up -d
   ```
3. Mở [http://localhost](http://localhost).

Các dịch vụ khác:
- phpMyAdmin: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Prometheus: [http://localhost:9090](http://localhost:9090)
- Grafana: [http://localhost:3000](http://localhost:3000)

## Đưa mã nguồn lên GitHub
Tạo repository trống rồi cấu hình remote và đẩy nhánh:
```powershell
git remote add origin https://github.com/<tai-khoan>/<repository>.git
git push -u origin HEAD
```
Khi được yêu cầu xác thực, hãy dùng Git Credential Manager hoặc GitHub CLI. Không đưa Personal Access Token vào lệnh, tệp cấu hình hay lịch sử Git.
