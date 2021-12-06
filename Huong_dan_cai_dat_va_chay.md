# Demo_Web
Demo môn Công nghệ Web

//****Clone dự án php laravel trên github và cài đặt nó chạy trên môi trường local*****//

Chú ý: Máy các bạn phải cài sẵn apche hoặc nginx, php, mysql,
npm(node),git và xampp.

---Bước 1: Mở Terminal hoặc git base và thực hiện clone dự án 
vào thư mục xampp/htdocs bằng câu lệnh

git clone https://github.com/Corn070201/Demo_Web.git

---Bước 2:Chạy composer và npm để cài đặt các gói cần thiết trong
dự án.

composer install

npm install

---Bước 3:Extract to file"vender"bên trong thư mục C:\xampp\htdocs\shoplaravel
---Bước 4:Tạo database và config database
Ví dụ tạo database có tên là: shopbanhang và import file shopbanhang.sql mà mình đã push.

Sau đó thực hiện lệnh sau để copy từ file .env.example ra file .env:

cp .env.example .env

Cập nhật file .env của bạn như sau:
	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=shopbanhang //tên database mà bạn đã tạo trước đó
	DB_USERNAME=root
	DB_PASSWORD=
--Bước 5: chạy dự án.
//**Trang bán hàng**//:

localhost/shoplaravel/

//**Trang quản lý bán hàng**//:

localhost/shoplaravel/admin
