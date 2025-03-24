# checkscam
v1.9
DATABASE
tạo SCHEMAS tên là `checkscam` bên MYSQL
vào `setting` trong folder [checkscam] kéo xuống phần DATABSE để sửa mật khẩu của MYSQL

Cài thư viện
- Django: `pip install django` → Framework chính để xây dựng web  
- Django REST Framework: `pip install djangorestframework` → Hỗ trợ API REST trong Django  
- Google Generative AI: `pip install google-generativeai` → Tích hợp AI của Google  
- Pillow: `pip install pillow` → Hỗ trợ xử lý hình ảnh trong Django  
- Requests: `pip install requests` → Gửi HTTP requests trong Python  
- MySQL Client: `pip install mysqlclient` → Hỗ trợ kết nối Django với MySQL

Đồng bộ dữ liệu
- python manage.py migrate
- python manage.py makemigrations

Tạo tài khoản admin
- Chạy lệnh `python manage.py createsuperuser` 


Chạy dự án: `cd checkscam` 
