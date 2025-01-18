- Thông thường

1. Tìm và download Lhu viện về máy
2. Import thư viện đó vào dự án cần dùng

- Maven

1. Khai báo trong pom.xml (dependency) nào mà dự án cần dùng
2. Save pom.xml kiểm tra trong đường dẫn C:/User/machine_name/.m2/repository/group_id/artifact_id/... jars.
   ++ Nếu dependency chưa có trong m2 --> download từ maven central (server) về bỏ vào m2
   ++ Nếu đã có rồi thì không download

3. Import thư viện đó vào dự án cần dùng

- Làm thế nào để maven giúp download/import quản lý thư viện cho dự án Java
  +) Có 2 cách:
  1. Thông qua editor có hỗ trợ maven --> Eclipse
     VD: pom.xml --> save --> cập nhật thư viện
     --> dự án lớn, muốn tự quán lý cách tháo Lác với maven
  2. Cài đặt maven cho hệ thống
     --> Cung cấp cmd để thực hiện với maven
     --> clean, validate, build, install
     --> -UskipTests
