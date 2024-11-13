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

- SPRING CONTAINER

-- Spring Container (hay còn gọi là Spring IoC Container) là một thành phần quan trọng trong Spring Framework.
Nó chịu trách nhiệm chính trong việc khởi tạo, quản lý vòng đời và xử lý các phụ thuộc (dependencies) cho các
Spring Beans.

-- IoC Container trong Spring có 2 kiểu là: BeanFactory và ApplicationContext:

- SPRING BEAN

-- Trong Spring Framework, các đối tượng được Spring quản lý trong container của nó được gọi là Spring Bean.

-- Spring Bean là một đối tượng được khởi tạo, cấu hình và quản lý bởi Spring IoC (Inversion of Control) container.
Khi một lớp được đánh dấu là một bean, Spring sẽ chịu trách nhiệm khởi tạo nó, quản lý vòng đời của nó, và xử lý các
phụ thuộc cần thiết cho nó.

- POJO

-- POJO viết tắt của Plain old Java object.

-- POJO dùng để chỉ một đối tượng đơn giản, không bị ràng buộc vào bất kỳ framework hoặc cấu trúc
phức tạp nào. tức là:

+) Không extends bất kỳ 1 class nào.

+) Không implement bất kỳ 1 interface nào.

+) Không chứa anntation nào.

+) Chỉ chứa fields và getter setter cơ bản.

- JAVA BEAN

-- Là 1 java class với các quy ước sau:

+) Tất cả properties đều private.

+) Một public constructor với không argument.

+) Triển khai Serializable Interface.

+) Các Java Bean yêu cầu các phương thức getter và setter để truy cập các thuộc tính private.

- AUTO WIRING

-- Autowiring trong Spring là cơ chế tự động tiêm các phụ thuộc (dependencies) vào các bean trong
Spring container mà không cần phải cấu hình thủ công. Spring sẽ tự động xác định các phụ thuộc
cần thiết và tiêm chúng vào các đối tượng của bạn, giúp giảm bớt sự phức tạp và mã lặp lại trong
việc cấu hình các bean.

-- Autowiring trong Spring có thể tìm các beans trong container dựa trên tên của Bean hoặc
type của tham số và tự động tiêm (inject) chúng vào đối tượng của bạn.

-- Spring hỗ trợ ba kiểu autowiring chính:

+) Autowiring theo tên (by name).

+) Autowiring theo kiểu (by type).

+) Autowiring theo constructor (by constructor).

- ANNOTATIONs

-- Annotation là cách để chúng ta thêm siêu dữ liệu (metadata) vào các thành phần trong Java như class,
method, field, hay thậm chí là các package.

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

+) Annotation @Bean thường được sử dụng bên trong một configuration class, được đánh dấu với @Configuration.
Khi một class có annotation @Configuration, Spring hiểu rằng class này chứa các method định nghĩa bean
mà ứng dụng cần, và Spring sẽ xử lý các method có annotation @Bean để đăng ký các đối tượng trả về từ
các method này như các bean trong Spring container.

+) Các bean được tạo ra với @Bean theo mặc định là singleton, tức là chỉ có một instance duy nhất
trong Spring container.

+) Bạn có thể thay đổi scope của bean bằng cách sử dụng thuộc tính @Scope.

-- @Qualifier("tên");

+) @Qualifier cho phép chỉ định bean name khi có nhiều bean cùng loại.

+) Nếu bạn không sử dụng @Qualifier và có nhiều bean cùng kiểu, Spring sẽ không biết phải
tiêm bean nào và sẽ ném ra lỗi.

-- @Component: Khi một class sử dụng annotation @Component trong Spring Framework, đây là một phần của cơ chế
dependency injection (DI). Cụ thể, khi bạn đánh dấu một class với @Component, Spring sẽ:

+) Tạo Bean: Spring sẽ tự động phát hiện class này và đăng ký nó như một Bean trong Spring Application Context.
Điều này có nghĩa là Spring sẽ quản lý vòng đời của đối tượng này và bạn có thể sử dụng nó trong các
phần khác của ứng dụng.

+) Tiêm vào các lớp khác: Các lớp khác có thể sử dụng đối tượng này thông qua dependency injection.
Spring sẽ tự động tiêm (inject) Bean vào các lớp cần sử dụng nó, thông qua constructor, setter,
hoặc trường (field) của lớp đó.
