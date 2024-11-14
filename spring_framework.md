- KHÁI QUÁT VỀ J2EE, JEE, Jakarta EE

-- J2EE (Java 2 Platform, Enterprise Edition):

+) J2EE ra đời vào cuối những năm 1990 và đầu những năm 2000 như một phần của nền tảng Java để hỗ trợ phát triển các ứng
dụng web và doanh nghiệp phức tạp.

+) Nền tảng này bao gồm các công nghệ quan trọng như JSP (JavaServer Pages), Servlets, EJB (Enterprise JavaBeans),
JPA (Java Persistence API), và các dịch vụ khác để xây dựng các ứng dụng phân tán, dịch vụ web, và hệ thống quản lý dữ liệu.

+) Tên gọi "J2EE" xuất phát từ việc phiên bản nền tảng này là "Java 2" (tức J2) và dành cho môi trường doanh nghiệp (Enterprise).

-- JEE (Java Platform, Enterprise Edition):

+) Sau khi J2EE trở nên phổ biến, Oracle (trước là Sun Microsystems) đã quyết định loại bỏ chữ "2"
và gọi nó đơn giản là JEE, trong khi vẫn giữ nguyên các công nghệ cốt lõi.

+) JEE đã được cải tiến để dễ dàng hơn cho các nhà phát triển với các API, container, và framework mạnh mẽ hơn.

+) Các công nghệ của JEE như JPA, JSF (JavaServer Faces), JAX-RS (dùng để xây dựng RESTful Web Services)
được phát triển để thay thế các công nghệ cũ như EJB, đồng thời giảm độ phức tạp trong phát triển ứng dụng.

-- Jakarta EE:

+) Vào năm 2017, Oracle đã chuyển giao quyền sở hữu Java EE cho Eclipse Foundation, và nền tảng này được đổi tên thành Jakarta EE.

+) Việc đổi tên này xảy ra do vấn đề về bản quyền với Oracle, và Eclipse Foundation đã phát triển Jakarta EE từ JEE.
Điều này có nghĩa là Jakarta EE là sự kế thừa của JEE nhưng với tên gọi mới.

+) Các công nghệ quan trọng của Jakarta EE bao gồm Jakarta Servlet, Jakarta JSP, Jakarta JPA, Jakarta EE RESTful Services
(trước là JAX-RS), và Jakarta Faces (trước là JSF).

-- J2EE → JEE → Jakarta EE là các tên gọi khác nhau của cùng một nền tảng Java dành cho ứng dụng doanh nghiệp,
với những cải tiến và chuyển giao quyền sở hữu qua các giai đoạn.

-- Các công nghệ phổ biến trong J2EE/JEE/Jakarta EE:

+) JBoss (nay là WildFly): Một ứng dụng container server phổ biến, hỗ trợ các ứng dụng Java EE.

+) Servlets: Là các lớp Java dùng để xử lý các yêu cầu HTTP trong web applications.

+) JSP (JavaServer Pages): Dùng để tạo các trang web động với Java.

+) EJB (Enterprise JavaBeans): Là một framework để phát triển các ứng dụng phân tán trong môi trường doanh nghiệp.

+) JPA (Java Persistence API): Dùng để quản lý dữ liệu trong các ứng dụng doanh nghiệp, thay thế cho các công nghệ
ORM như Hibernate.

+) JAX-RS: Dùng để phát triển các RESTful web service trong Java.

+) JSF(JavaServer Faces): Là một framework giúp xây dựng giao diện web với các thành phần reusable.

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

- BEAN SCOPEs

-- SINGLETON: Trong singleton scope, Spring container sẽ chỉ tạo một instance duy nhất của bean trong suốt vòng đời của
Spring IoC Container (context).

-- PROTOTYPE: Với prototype scope, mỗi lần có yêu cầu về bean, Spring container sẽ tạo ra một instance mới của bean
và trả về instance đó.

-- REQUEST: Với request scope, Spring sẽ tạo ra một instance mới của bean cho mỗi yêu cầu HTTP. Instance của bean này sẽ
chỉ tồn tại trong suốt thời gian xử lý của request đó và sẽ bị hủy khi request kết thúc.

-- SESSION: Với session scope, Spring sẽ tạo một instance mới cho mỗi session HTTP và tồn tại trong suốt vòng đời của session đó.
Bean sẽ được lưu trữ cho đến khi session kết thúc (hết hạn hoặc bị hủy).

-- APPLICATION: Trong Spring, application scope sẽ tạo một instance của bean và duy trì nó suốt vòng đời của ServletContext.
Điều này rất hữu ích cho các ứng dụng web khi bạn muốn một bean tồn tại và được chia sẻ giữa tất cả các request và session,
nhưng chỉ trong phạm vi của ServletContext.

- VÒNG ĐỜI CỦA BEAN

-- Bean Definition : khởi tạo bean thông qua sử dụng Annotation hoặc XML file.

-- Bean Instantiation : Spring khởi tạo các đối tượng Bean giống như khởi tạo đối tượng Java thông thường và đưa nó
vào ApplicationContext.

-- Populating Bean properties : Spring thực hiện scan các bean thực thi các Aware interfaces và thực hiện set
các giá vào các property như id, scope và giá trị mặc định như khai báo của bean đấy.

-- Pre-Initialization : Các phương thức postProcessBeforeInitialization() bắt đầu thực thi và @PostConstruct annotation thực thi sau ngay nó.

-- AfterPropertiesSet : Spring thực thi các phương thức afterPropertiesSet() của beans mà có implement InitializingBean.

-- Custom Initialization : Spring kích hoạt các method khởi tạo với các thuộc tính được define ở trong initMethod trong @Bean annotations.

-- Post-initialization : BeanPostProcessors của Spring hoạt động lần thứ 2. Lần này nó kích hoạt các phương thức
postProcessAfterInitialization().

-- Ready : các Bean đã được khởi tạo và inject vào trong các dependencies

-- Pre-Destroy : Spring kích hoạt @PreDestroy annotated methods ở bước này.

-- Destroy : Spring thực thi the destroy() methods.

-- Custom Destruction : Có thể tuỳ chỉnh các thời điểm huỷ bằng thuộc tính destroyMethod ở trong @Bean annotation và
Spring sẽ chạy nó trong giai đoạn cuối.

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

-- Điều quan trọng là phải biết rằng: Khi mã nguồn Java được biên dịch bằng trình biên dịch javac,
các annotation có thể được lưu vào bytecode (file .class), và từ đó chúng có thể được truy cập bằng kỹ thuật phản chiếu
(reflection) tại runtime. Kỹ thuật này cho phép chương trình có thể lấy thông tin về các annotation đã được áp dụng
(như loại annotation, giá trị của các thuộc tính trong annotation) và từ đó quyết định hành động cần thực hiện.

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

-- @Autowired:

+) Khi @Autowired được thêm vào một field trong Spring, điều đó có nghĩa là field này cần một instance của một
bean (đối tượng) được Spring quản lý để gán vào.

+) @Autowired sử dụng field injection khi được đặt trực tiếp trên một field (biến) trong lớp.

+) @Autowired sử dụng constructor injection khi được đặt trực tiếp trên một constructor trong lớp.

+) @Autowired sử dụng setter injection khi được đặt trực tiếp trên một hàm setter trong lớp.

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

-- @ComponentScan("tên package"):

+) Sử dụng annotation này để thông báo cho spring container rằng: “Phải biết vào các package nào trong dự án
để quét các Annotation và tạo Bean.”

+) @ComponentScan thường được sử dụng với @Configuration trong Spring để cấu hình phạm vi quét các bean và
tự động đăng ký chúng vào Spring IoC container.

-- @Lazy:

+) @Lazy được sử dụng để trì hoãn việc khởi tạo các bean cho đến khi chúng thực sự được yêu cầu trong ứng dụng.
Điều này giúp cải thiện hiệu suất và tiết kiệm tài nguyên trong những trường hợp khi một số bean không cần thiết
phải khởi tạo ngay từ đầu.

+) Trong Spring, mặc định việc khởi tạo các bean là eager (tức là khởi tạo ngay khi container Spring khởi động),
trừ khi có chỉ định khác. Điều này có nghĩa là tất cả các bean sẽ được tạo và sẵn sàng sử dụng ngay khi ứng dụng
khởi động.

-- @PostConstruct:

+) Được sử dụng để đánh dấu một phương thức sẽ được thực thi ngay lập tức ngay sau khi bean được khởi tạo và
các dependency được tiêm (sau khi hoàn tất quá trình dependency injection).

-- @PreDestroy:

+) Được sử dụng để đánh dấu một phương thức sẽ được gọi trước khi bean bị hủy (destroyed). Điều này thường được
sử dụng để thực hiện các hành động dọn dẹp tài nguyên hoặc các hoạt động cần thiết trước khi bean bị Spring container
thu hồi và đóng lại.

- SO SÁNH @Bean và @Component:

-- Dùng @Component khi:

+) Spring tự động phát hiện và quản lý các class như @Service, @Repository, @Controller:
Khi bạn sử dụng @Component (hoặc các annotation chuyên biệt như @Service, @Repository, @Controller),
Spring sẽ tự động phát hiện các lớp này thông qua component scanning và đăng ký chúng như các bean
trong Spring IoC container.

+) Spring IoC tự động tạo instance của lớp này: Spring sẽ tự động tạo và quản lý vòng đời của các bean này.
Ví dụ, nếu bạn đánh dấu một lớp với @Service, Spring sẽ tự động khởi tạo đối tượng của lớp đó khi cần và
tiêm (inject) vào các lớp khác khi chúng yêu cầu.

-- Dùng @Bean khi:

+) Khai báo bean thủ công: Nếu bạn muốn tự tay tạo ra một instance của bean và cấu hình cách mà nó được khởi tạo,
bạn sử dụng @Bean. Điều này giúp bạn có thể cấu hình và quản lý beans một cách chi tiết hơn,
ví dụ như khi cần tạo một bean với tham số constructor hoặc cần làm gì đó phức tạp trong quá trình khởi tạo.

+) Cấu hình đặc biệt cho bean: Khi bạn cần kiểm soát cách tạo một instance của bean (như việc cấu hình với tham số cụ thể).

+) Lớp cần tạo bean không nằm trong package quét của Spring: Nếu lớp bạn muốn tạo bean không nằm trong package
mà Spring đang quét (thông qua component scanning), bạn có thể sử dụng @Bean để khai báo và tạo bean cho lớp đó
mà không cần phải di chuyển lớp đó vào package đã quét.
