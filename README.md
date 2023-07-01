## Khởi động AI server được lập trình bằng python - flask
- Bước 1 : Chuẩn bị môi trường:\
Cài đặt Python trên máy tính của bạn. Flask yêu cầu Python 3.6 trở lên.\
- Bước 2 : Tạo môi trường ảo python và install các thư viện trong file requirements.text bằng lệnh sau :\
    `python -m venv env`\
    `env\Scripts\activate`\
    `pip install -r requirements.txt`
- Bước 3 : chạy chương trình trên cổng 5555 :\
`python main.py`\
Lúc này chương trình AI sẽ được khởi động
## Khởi động Back-end Server được lập trình bằng java - spring boot

- Bước 1 : Import dự án vào IDE (IntelliJ IDEA hoặc Eclipse là những ide hàng đầu\
Mở IDE của bạn và import dự án Spring Boot đã có vào.
Trong IntelliJ IDEA, bạn có thể chọn "Import Project" và chọn thư mục chứa mã nguồn dự án.
- Bước 2 : Cấu hình dự án\
Kiểm tra các tệp cấu hình như application.properties hoặc application.yml để cấu hình các thông số và tùy chọn cho dự án của bạn. Điều này bao gồm cấu hình cơ sở dữ liệu, bảo mật, tài nguyên tĩnh và nhiều hơn nữa.
- Bước 4 :Xây dựng dự án:\
Sử dụng Maven hoặc Gradle để xây dựng dự án Spring Boot. Trong dự án Maven, sử dụng lệnh `mvn clean install`
Lệnh xây dựng sẽ tạo ra file JAR hoặc WAR chứa ứng dụng của bạn và các phụ thuộc của nó.
- Bước 5 :Chạy ứng dụng:\
Sử dụng command line hoặc IDE để chạy ứng dụng Spring Boot.
Trong command line, bạn có thể sử dụng lệnh `java -jar` để chạy file JAR đã xây dựng. Ví dụ: `java -jar myapp.jar`.\
Trong IDE, bạn có thể chọn lệnh "Run" hoặc "Debug" để chạy ứng dụng Spring Boot.
## Khởi chạy giao diện người dùng được lập trình bằng Java Script - ReactJS
- Bước 1 : Chuẩn bị môi trường:\
Cài đặt Node.js trên máy tính của bạn. Bạn có thể tải Node.js từ trang web chính thức của Node.js (https://nodejs.org) và cài đặt phiên bản LTS (Long-Term Support).
- Bước 2 :Cài đặt các phụ thuộc:\
Di chuyển đến thư mục gốc của dự án React trong command line hoặc terminal.
Chạy lệnh `npm install` để cài đặt các phụ thuộc của dự án từ file package.json. Quá trình này sẽ tải xuống và cài đặt các gói cần thiết cho dự án.
- Bước 2 :Chạy ứng dụng trong môi trường phát triển:\
Sau khi quá trình cài đặt các phụ thuộc hoàn tất, bạn có thể chạy ứng dụng React trong môi trường phát triển bằng lệnh `npm start` 
