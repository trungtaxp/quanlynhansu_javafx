# quanlynhansu_javafx
Code java sử dụng javafx

# Mở file và tải thư viện javafx
Dùng phần mềm IntelliJ IDEA mở thư mục lên.
– Vào File, chọn Open File
– Trỏ đến thư mục tải về quanlynhansu_javafx rồi mở lên
Sau đó lên trang https://gluonhq.com/products/javafx/ tải bản 16 tương thích với hệ điều hành  
Nhớ là là dạng SDK nha rồi giải nén file ra.

# ép thư viện vào Intellij
Sau khi mở xong dự án Java FX trong Intellij
– Vào File, chọn Project Structure
– Chọn Libraries
– Bấm vào dấu +, rồi chọn Java
– Trỏ đến thư mục lib của thư mục được giải nén ở trên trước.

# ép lib vào run để chạy javafx
Tiếp theo vào Run, chọn Edit Configurations
Trong mục VM options của lớp chính nhập thông tin sau vào
--module-path (đường dẫn đến thư mục lib) --add-modules javafx.controls,javafx.fxml

Note: nhớ bỏ dấu ngoặc đi nha.
Ví dụ thư mực lib tải về mk để ở trong User thì sẽ là:
--module-path User/lib --add-modules javafx.controls,javafx.fxml

Rồi chúng ta mở main ở trong src/quanlynhansu/main ấn run chạy là ok.