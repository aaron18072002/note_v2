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
