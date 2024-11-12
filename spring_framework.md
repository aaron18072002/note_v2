- SPRING là gì

-- Spring là một Framework phát triển các ứng dụng Java được sử dụng bởi hàng triệu lập trình viên. Nó giúp tạo các ứng dụng
có hiệu năng cao, dễ kiểm thử, sử dụng lại code …

-- Spring Framework được xây dựng dựa trên 2 nguyên tắc design chính là: Dependency Injection (DI)
và Aspect Oriented Programming (AOP).

- MAVEN

-- Trong các dự án Spring, Maven được sử dụng như một công cụ quản lý dependency rất phổ biến.
Maven giúp tự động hóa việc tải và quản lý các thư viện (dependency) cần thiết cho dự án,
từ đó tiết kiệm thời gian và giảm rủi ro gặp lỗi khi cấu hình môi trường.

-- Các tính năng của Maven trong dự án Spring bao gồm:

+) Quản lý dependency: Maven tự động tải về các thư viện cần thiết từ các kho lưu trữ trực tuyến
dựa vào file pom.xml (Project Object Model). Khi bạn khai báo một dependency trong pom.xml, Maven sẽ
tự động tải về các phiên bản tương thích của thư viện đó và các thư viện liên quan.

+) Quản lý phiên bản: Maven cho phép quản lý phiên bản của các thư viện một cách dễ dàng. Bạn chỉ cần thay
đổi phiên bản trong pom.xml, và toàn bộ dự án sẽ tự động cập nhật theo.

+) Xây dựng và đóng gói: Maven hỗ trợ các quy trình xây dựng và đóng gói ứng dụng (build và package)
bằng cách sử dụng các plugin tích hợp sẵn, giúp dễ dàng tạo ra các file jar hoặc war để triển khai.

+) Quản lý lifecycle: Maven cung cấp một mô hình lifecycle, giúp tự động hóa các bước trong quá trình
phát triển phần mềm, từ kiểm thử (test), biên dịch (compile) đến đóng gói (package) và triển khai (deploy).

+) Tích hợp với Spring: Trong các dự án Spring, Maven đóng vai trò rất quan trọng khi tích hợp các dependency
của Spring như Spring Core, Spring MVC, Spring Boot, và nhiều thư viện khác của Spring Framework.

- TIGHTLY COUPLED

-- Trong Java Spring, Tightly Coupled (liên kết chặt chẽ) ám chỉ khi các thành phần (components) hoặc lớp (classes)
có sự phụ thuộc chặt chẽ vào nhau, dẫn đến khó khăn trong việc thay đổi hoặc mở rộng một thành phần mà không ảnh hưởng
đến các thành phần khác.

- SPRING BEAN

-- Trong Spring Framework, các đối tượng được Spring quản lý trong container của nó được gọi là Spring Bean.

-- Spring Bean là một đối tượng được khởi tạo, cấu hình và quản lý bởi Spring IoC (Inversion of Control) container.
Khi một lớp được đánh dấu là một bean, Spring sẽ chịu trách nhiệm khởi tạo nó, quản lý vòng đời của nó, và xử lý các
phụ thuộc cần thiết cho nó.

- ANNOTATIONs

-- Annotation (chú thích) là một loại siêu dữ liệu (metadata information) trong java có thể được áp dụng
ở các phần tử mã nguồn java để sau đó một số công cụ (tool), trình gỡ lỗi (debugger) hoặc chương trình
ứng dụng có thể tận dụng các Annotation này.

-- Điều quan trọng là phải biết rằng: các Annotation được áp dụng trên mã nguồn java được biên dịch
thành bytecode bởi javac và sử dụng kỹ thuật lập trình phản chiếu (Reflection) để có thể truy vấn
thông tin siêu dữ liệu (metadata information) và quyết định hành động thích hợp để thực hiện trong
ngữ cảnh cụ thể.

-- @Override:

+) @Override giúp trình biên dịch Java kiểm tra xem bạn có thực sự ghi đè (override) một phương thức từ interface
hoặc từ lớp cha hay không.

+) Nếu bạn viết sai tên phương thức hoặc có sai lệch trong danh sách tham số, trình biên dịch sẽ báo lỗi,
giúp bạn phát hiện vấn đề ngay lập tức.

-- @Configuration:

+) Trong Spring Framework, annotation @Configuration được sử dụng để đánh dấu một class
là Java Configuration Class, nơi bạn có thể khai báo các beans và cấu hình cho Spring IoC
(Inversion of Control) container.

-- @Bean:
