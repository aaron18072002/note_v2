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

- MAVEN

-- Apache Maven là một chương trình quản lý dự án cho phép các developers có thể quản lý về version,
các dependencies( các thư viện sử dụng trong dự án ), các modules của Spring Project, quản lý build,
tự động download javadoc và source …

-- Các tính năng của Maven trong dự án Spring bao gồm:

+) Quản lý dependency/modules: Maven tự động tải về các thư viện cần thiết từ các kho lưu trữ
trực tuyến dựa vào file pom.xml (Project Object Model). Khi bạn khai báo một dependency trong
pom.xml, Maven sẽ tự động tải về các phiên bản tương thích của thư viện đó và các thư viện liên quan.

+) Quản lý phiên bản: Maven cho phép quản lý phiên bản của các thư viện một cách dễ dàng.
Bạn chỉ cần thay đổi phiên bản trong pom.xml, và toàn bộ dự án sẽ tự động cập nhật theo.

+) Xây dựng và đóng gói: Maven hỗ trợ các quy trình xây dựng và đóng gói ứng dụng (build và package)
bằng cách sử dụng các plugin tích hợp sẵn, giúp dễ dàng tạo ra các file jar hoặc war để triển khai.

+) Quản lý lifecycle: Maven cung cấp một mô hình lifecycle, giúp tự động hóa các bước trong quá trình
phát triển phần mềm, từ kiểm thử (test), biên dịch (compile) đến đóng gói (package) và triển khai (deploy).

+) Tích hợp với Spring: Trong các dự án Spring, Maven đóng vai trò rất quan trọng khi tích hợp các
dependency của Spring như Spring Core, Spring MVC, Spring Boot, và nhiều thư viện khác của Spring Framework.

- POM: Project Object Model

-- POM file sẽ chứa:

+) project meta data: Tên dự án, version, packaging.

+) dependencies: Danh sách thư viện cần dùng. Maven sử dụng metadata của dự án khác để tìm và tải các file jars
từ Maven Central Repository.

+) plugins: Các công cụ hỗ trợ build/test/package.

- Có 3 loại built-in lifecycles: default, clean and site

- Common Maven Build Lifecycles: validate, clean, compile, test, package, verify,
  install, deploy.

- Có 2 loại plugins trong Maven: Build plugins và Reporting plugins.

- Maven Commands:

+) validate:

+) clean: xóa file .class (mục đích để compile lại)

+) compile: biên dịch file .java thành file .class

+) test:

+) install:

+) package:

+) deploy:

- Tạo dự án maven:

+) C1: mvn archetype:generate rồi tự config tiếp

+) C2: mvn archetype:generate -DgroupId=[Tên package] -DartifactId=[Tên dự án]
-DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
