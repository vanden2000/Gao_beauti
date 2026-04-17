# Gao_beauti

Xây dựng website về làm đẹp và dịch vụ đặt lịch.

## Công nghệ sử dụng
- Laravel
- MySQL
- Blade / HTML / CSS / JavaScript

## Cách chạy project
1. Clone repo
2. Chạy `composer install`
3. Copy file môi trường:
   - Windows PowerShell:
     ```powershell
     Copy-Item .env.example .env
     ```
4. Tạo app key:
   ```bash
   php artisan key:generate