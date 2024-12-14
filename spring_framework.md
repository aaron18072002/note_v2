- KHÁI QUÁT VỀ J2EE, JEE, Jakarta EE

-- J2EE (Java 2 Platform, Enterprise Edition):

+) J2EE ra đời vào cuối những năm 1990 và đầu những năm 2000 như một phần của nền tảng Java để hỗ trợ phát
triển các ứng dụng web và doanh nghiệp phức tạp.

+) Nền tảng này bao gồm các công nghệ quan trọng như JSP (JavaServer Pages), Servlets, EJB (Enterprise JavaBeans),
JPA (Java Persistence API), và các dịch vụ khác để xây dựng các ứng dụng phân tán, dịch vụ web, và hệ thống quản
lý dữ liệu.

+) Tên gọi "J2EE" xuất phát từ việc phiên bản nền tảng này là "Java 2" (tức J2) và dành cho môi trường doanh nghiệp (Enterprise).

-- JEE (Java Platform, Enterprise Edition):

+) Sau khi J2EE trở nên phổ biến, Oracle (trước là Sun Microsystems) đã quyết định loại bỏ chữ "2"
và gọi nó đơn giản là JEE, trong khi vẫn giữ nguyên các công nghệ cốt lõi.

+) JEE đã được cải tiến để dễ dàng hơn cho các nhà phát triển với các API, container, và framework mạnh mẽ hơn.

+) Các công nghệ của JEE như JPA, JSF (JavaServer Faces), JAX-RS (dùng để xây dựng RESTful Web Services)
được phát triển để thay thế các công nghệ cũ như EJB, đồng thời giảm độ phức tạp trong phát triển ứng dụng.

-- Jakarta EE:

+) Vào năm 2017, Oracle đã chuyển giao quyền sở hữu Java EE cho Eclipse Foundation, và nền tảng này được đổi
tên thành Jakarta EE.

+) Việc đổi tên này xảy ra do vấn đề về bản quyền với Oracle, và Eclipse Foundation đã phát triển Jakarta EE từ JEE.
Điều này có nghĩa là Jakarta EE là sự kế thừa của JEE nhưng với tên gọi mới.

+) Các công nghệ quan trọng của Jakarta EE bao gồm Jakarta Servlet, Jakarta JSP, Jakarta JPA, Jakarta EE RESTful
Services (trước là JAX-RS), và Jakarta Faces (trước là JSF).

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

- SPRING FRAMEWORK

-- Spring là một Framework phát triển các ứng dụng Java được sử dụng bởi hàng triệu lập trình viên.
Nó giúp tạo các ứng dụng có hiệu năng cao, dễ kiểm thử, sử dụng lại code …

-- Spring Framework được xây dựng dựa trên 2 nguyên tắc design chính là: Dependency Injection (DI)
và Aspect Oriented Programming (AOP).

-- Spring Framework chứa các Spring Modules như:

+) Spring Core: IoC Container, DI, Auto wiring, Beans, SpEL - Spring Expression Language.

+) Data Access: JDBC, JPA.

+) Integration: JMS.

+) Web Module: Spring MVC.

+) Testing: Mock Objects, Spring MVC Test.

+) Spring Security: Một module tách biệt cho phép dễ dàng bảo mật ứng dụng, hỗ trợ xác thực và
phân quyền người dùng.

+) Spring Boot: Một module đặc biệt giúp phát triển ứng dụng nhanh chóng, tự động cấu hình các bean
và cung cấp cấu trúc chuẩn cho ứng dụng Spring.

- SPRING BOOT

-- Spring Boot là một module của Spring Framework, và nó tích hợp sẵn IoC (Inversion of Control)
container mà Spring cung cấp. Điều này có nghĩa là Spring Boot tự động cấu hình và khởi tạo các
thành phần trong ứng dụng của bạn mà không cần bạn phải cấu hình.

-- Khi bạn sử dụng Spring Boot, nó đã tích hợp sẵn Spring IoC Container. Điều này giúp bạn không
cần phải cấu hình các lớp XML/Configuration phức tạp hoặc tốn thời gian tự định nghĩa các bean,
như trong Spring Framework trước đây.

-- Spring Boot cung cấp hai cơ chế chính để giúp bạn phát triển ứng dụng nhanh chóng và dễ dàng hơn,
đó là Spring Boot Starter Projects và Auto Configuration:

+) Spring Boot Starter Projects: Spring Boot Starter là một nhóm các dependency được cấu hình
sẵn mà bạn có thể thêm vào dự án của mình để nhanh chóng bắt đầu phát triển ứng dụng mà không
cần phải cấu hình từng phần một. Starter giúp bạn không cần phải tự tìm và cấu hình các thư viện,
thay vào đó chỉ cần thêm một dependency vào pom.xml hoặc build.gradle. Mỗi Starter chứa các
cấu hình cơ bản và các thư viện cần thiết cho một loại ứng dụng cụ thể.

+) AutoConfiguration trong Spring Boot dựa vào các dependencies mà bạn thêm vào dự án thông qua
các starter projects để tự động cấu hình ứng dụng. Khi bạn thêm một Spring Boot Starter vào dự án,
AutoConfiguration sẽ kiểm tra các thư viện trong classpath và tự động cấu hình các thành phần
cần thiết cho bạn.

+) AutoConfiguration sử dụng các annotation điều kiện để kích hoạt hoặc bỏ qua việc cấu hình các bean,
tùy thuộc vào sự hiện diện của các thư viện hoặc các thuộc tính cấu hình trong classpath.

- CLASS PATH

-- Classpath là một khái niệm quan trọng trong Java và các ứng dụng Java-based (như Spring Boot),
dùng để chỉ đường dẫn (path) tới các tài nguyên cần thiết để chương trình Java có thể thực thi.
Classpath xác định nơi mà Java Runtime Environment (JRE) hoặc Java Virtual Machine (JVM)
tìm kiếm các lớp (classes), thư viện (libraries), tài nguyên (resources), và các file cấu hình
khi ứng dụng được chạy.

-- Class path là một danh sách các đường dẫn mà JVM sử dụng để tìm kiếm các file .class,
thư viện .jar, hoặc các tài nguyên khác trong quá trình thực thi.

- JAR FILE

-- Trong Spring Boot, một JAR file (Java ARchive) là một file nén chứa tất cả các thành phần cần
thiết để chạy ứng dụng Java, bao gồm các lớp Java đã biên dịch (compiled classes), thư viện bên ngoài
(dependencies), và các tài nguyên (resources). Spring Boot sử dụng JAR file để đóng gói và triển
khai ứng dụng dễ dàng, giúp chạy ứng dụng mà không cần cấu hình thêm hoặc phụ thuộc vào các server bên ngoài.

-- Trong Spring Boot, JAR file có khả năng chứa embedded server (server nhúng), cho phép ứng dụng có thể
tự chạy mà không cần triển khai lên một server bên ngoài. Tomcat là embedded server mặc định được tích hợp
trong Spring Boot khi bạn sử dụng các starter như spring-boot-starter-web.

- EMBEDDED SERVER

-- Embedded server trong Spring Boot là một tính năng cho phép ứng dụng Spring Boot chạy
trên một server được tích hợp sẵn bên trong ứng dụng mà không cần phải triển khai vào một
server bên ngoài như Tomcat, Jetty, hoặc Undertow. Điều này giúp quá trình phát triển, thử nghiệm,
và triển khai ứng dụng nhanh chóng hơn.

- SPRING BOOT ACUTUATOR

-- Spring Boot Actuator là một module tích hợp sẵn trong Spring Boot, giúp cung cấp các endpoints
nhằm theo dõi và quản lý tình trạng của ứng dụng. Các endpoints này giúp bạn nắm bắt các thông tin
quan trọng về hệ thống trong quá trình hoạt động mà
không cần phải thêm mã code phức tạp.

-- Các Tính Năng Chính:

+) Health Checks: Cung cấp endpoint /actuator/health để kiểm tra tình trạng sức khỏe của ứng dụng
(các kết nối với cơ sở dữ liệu, dung lượng bộ nhớ, trạng thái hệ thống, v.v.).

+) Metrics: Thu thập các số liệu như bộ nhớ, số lượng request, sử dụng CPU, và nhiều thông tin chi tiết khác.

+) Environment: Endpoint /actuator/env giúp xem cấu hình môi trường của ứng dụng, bao gồm các biến môi
trường và cấu hình đang hoạt động.

+) Logging: Cho phép kiểm soát mức độ log của ứng dụng một cách linh động tại runtime.

+) Thread Dump và Heap Dump: Hỗ trợ phân tích các vấn đề liên quan đến hiệu suất và bộ nhớ của ứng dụng.

- SPRING BOOT DEVTOOL

-- Spring Boot DevTools tự động khởi động lại ứng dụng khi có thay đổi trong mã nguồn, giúp bạn
tiết kiệm thời gian trong quá trình phát triển. Tuy nhiên, một điểm cần lưu ý là khi bạn thêm
hoặc thay đổi các dependency trong file pom.xml (Maven) hoặc build.gradle (Gradle), bạn vẫn cần
khởi động lại ứng dụng một cách thủ công.

- JUNIT:

-- JUnit là một framework cho phép bạn viết và chạy unit tests trong Java. Nó giúp kiểm tra các thành phần
nhỏ của ứng dụng như các phương thức và lớp, đảm bảo chúng hoạt động đúng như mong đợi.

-- Mockito cho phép bạn tạo các đối tượng giả (mock objects) để thay thế các phụ thuộc trong các unit test.
Điều này rất hữu ích khi bạn muốn kiểm tra một lớp mà không phải phụ thuộc vào các thành phần bên ngoài.

-- Trong một unit test trong Java, có 3 bước cơ bản thường được thực hiện, đó là Arrange, Act, và Assert:

+) Arrange: Thiết lập dữ liệu, đối tượng cần kiểm tra, và các phụ thuộc cần thiết cho bài test.

+) Act: Thực thi phương thức của đối tượng mà bạn muốn kiểm tra.

+) Assert: Sử dụng các phương thức xác nhận của JUnit như assertEquals, assertTrue, assertNull, v.v.,
để kiểm tra xem kết quả trả về có đúng với mong đợi.

- MAVEN

-- Apache Maven là một chương trình quản lý dự án cho phép các developers có thể quản lý về version,
các dependencies( các thư viện sử dụng trong dự án ), các modules của Spring Project, quản lý build,
tự động download javadoc và source …

-- Các tính năng của Maven trong dự án Spring bao gồm:

+) Quản lý dependency/modules: Maven tự động tải về các thư viện cần thiết từ các kho lưu trữ trực tuyến
dựa vào file pom.xml (Project Object Model). Khi bạn khai báo một dependency trong pom.xml, Maven sẽ
tự động tải về các phiên bản tương thích của thư viện đó và các thư viện liên quan.

+) Quản lý phiên bản: Maven cho phép quản lý phiên bản của các thư viện một cách dễ dàng.
Bạn chỉ cần thay đổi phiên bản trong pom.xml, và toàn bộ dự án sẽ tự động cập nhật theo.

+) Xây dựng và đóng gói: Maven hỗ trợ các quy trình xây dựng và đóng gói ứng dụng (build và package)
bằng cách sử dụng các plugin tích hợp sẵn, giúp dễ dàng tạo ra các file jar hoặc war để triển khai.

+) Quản lý lifecycle: Maven cung cấp một mô hình lifecycle, giúp tự động hóa các bước trong quá trình
phát triển phần mềm, từ kiểm thử (test), biên dịch (compile) đến đóng gói (package) và triển khai (deploy).

+) Tích hợp với Spring: Trong các dự án Spring, Maven đóng vai trò rất quan trọng khi tích hợp các
dependency của Spring như Spring Core, Spring MVC, Spring Boot, và nhiều thư viện khác của Spring Framework.

- TIGHTLY COUPLED

-- Trong Java Spring, Tightly Coupled (liên kết chặt chẽ) ám chỉ khi các thành phần (components)
hoặc lớp (classes) có sự phụ thuộc chặt chẽ vào nhau, dẫn đến khó khăn trong việc thay đổi hoặc
mở rộng một thành phần mà không ảnh hưởng đến các thành phần khác.

- SPRING CONTAINER

-- Spring Container (hay còn gọi là Spring IoC Container) là một thành phần quan trọng trong Spring Framework.
Nó chịu trách nhiệm chính trong việc khởi tạo, quản lý vòng đời và xử lý các phụ thuộc (dependencies) cho các
Spring Beans.

-- IoC Container trong Spring có 2 kiểu là: BeanFactory và ApplicationContext:

- SPRING BEAN

-- Trong Spring Framework, các đối tượng được Spring quản lý trong container của nó được gọi là Spring Bean.

-- Bất kì POJO class nào được quản lý bởi IoC Container đều là Spring Bean.

-- Khi một lớp được đánh dấu là một bean, Spring sẽ chịu trách nhiệm khởi tạo nó, quản lý vòng đời của nó,
và xử lý các phụ thuộc cần thiết cho nó.

- BEAN SCOPEs

-- SINGLETON: Trong singleton scope, Spring container sẽ chỉ tạo một instance duy nhất của bean
trong suốt vòng đời của Spring IoC Container (context).

-- PROTOTYPE: Với prototype scope, mỗi lần có yêu cầu về bean, Spring container sẽ tạo ra một
instance mới của bean và trả về instance đó.

-- REQUEST: Với request scope, Spring sẽ tạo ra một instance mới của bean cho mỗi yêu cầu HTTP.
Instance của bean này sẽ chỉ tồn tại trong suốt thời gian xử lý của request đó và sẽ bị hủy khi
request kết thúc.

-- SESSION: Với session scope, Spring sẽ tạo một instance mới cho mỗi session HTTP và tồn tại
trong suốt vòng đời của session đó. Bean sẽ được lưu trữ cho đến khi session kết thúc (hết hạn hoặc bị hủy).

-- APPLICATION: Trong Spring, application scope sẽ tạo một instance của bean và duy trì nó suốt vòng
đời của ServletContext. Điều này rất hữu ích cho các ứng dụng web khi bạn muốn một bean tồn tại và
được chia sẻ giữa tất cả các request và session, nhưng chỉ trong phạm vi của ServletContext.

- VÒNG ĐỜI CỦA BEAN

-- Bean Definition : khởi tạo bean thông qua sử dụng Annotation hoặc XML file.

-- Bean Instantiation : Spring khởi tạo các đối tượng Bean giống như khởi tạo đối tượng Java thông thường
và đưa nó vào ApplicationContext.

-- Populating Bean properties : Spring thực hiện scan các bean thực thi các Aware interfaces và
thực hiện set các giá vào các property như id, scope và giá trị mặc định như khai báo của bean đấy.

-- Pre-Initialization : Các phương thức postProcessBeforeInitialization() bắt đầu thực thi và
@PostConstruct annotation thực thi sau ngay nó.

-- AfterPropertiesSet : Spring thực thi các phương thức afterPropertiesSet() của beans mà có
implement InitializingBean.

-- Custom Initialization : Spring kích hoạt các method khởi tạo với các thuộc tính được define ở
trong initMethod trong @Bean annotations.

-- Post-initialization : BeanPostProcessors của Spring hoạt động lần thứ 2. Lần này nó kích
hoạt các phương thức postProcessAfterInitialization().

-- Ready : các Bean đã được khởi tạo và inject vào trong các dependencies

-- Pre-Destroy : Spring kích hoạt @PreDestroy annotated methods ở bước này.

-- Destroy : Spring thực thi the destroy() methods.

-- Custom Destruction : Có thể tuỳ chỉnh các thời điểm huỷ bằng thuộc tính destroyMethod
ở trong @Bean annotation và Spring sẽ chạy nó trong giai đoạn cuối.

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

- WEB SERVER

-- Web Server là một máy chủ chuyên dụng, chịu trách nhiệm tiếp nhận các request từ trình duyệt web (client)
và gửi lại các response tương ứng.

-- Web Server hoạt động thông qua giao thức HTTP/HTTPS.

- DISPATCHER SERVLET

-- DispatcherServlet trong Spring Framework đóng vai trò là trung gian (hay còn gọi là Front Controller)
giữa Web Server (như Tomcat, Jetty) và các Controller trong ứng dụng web. Nó là thành phần cốt lõi trong
kiến trúc Spring MVC, chịu trách nhiệm xử lý tất cả các yêu cầu HTTP đến từ WebServer và chuyển chúng đến
các Controller phù hợp.

- ORM

-- Object-Relational Mapping là 1 kĩ thuật ánh xạ các table trong hệ quản trị CSDL thành các class tương ứng.

-- ORM biến câu code thành các câu SQL thuần để giao tiếp với hệ quản trị CSDL.

- JPA

-- JPA (Java Persistence API) dùng để persist đối tượng Java (POJO - Plain Old Java Object)
vào trong CSDL hoặc lấy dữ liệu từ CSDL và ánh xạ (mapping) các đối tượng Java một cách đơn giản.

-- JPA (Java Persistence API) cung cấp các annotation để biến một lớp POJO (Plain Old Java Object)
thành một TABLE hay một ENTITY trong cơ sở dữ liệu.

-- FetchType.LAZY: không nạp kèm row ở bảng phụ khi fetch. / FetchType.EAGER: nạp kèm row ở bảng phụ khi fetch.

-- mappedBy không phải là để ánh xạ trực tiếp đến cột trong bảng cơ sở dữ liệu. mappedBy chỉ ra mối quan hệ
giữa các ENTITY và giúp JPA biết rằng phía đối tác của mối quan hệ đã có mối quan hệ 2 chiều với bên còn lại.

- ANNOTATIONs

-- Annotation là cách để chúng ta thêm siêu dữ liệu (metadata) vào các thành phần trong Java
như class, method, field, hay thậm chí là các package.

-- Điều quan trọng là phải biết rằng: Khi mã nguồn Java được biên dịch bằng trình biên dịch javac,
các annotation có thể được lưu vào bytecode (file .class), và từ đó chúng có thể được truy cập bằng
kỹ thuật phản chiếu (reflection) tại runtime. Kỹ thuật này cho phép chương trình có thể
lấy thông tin về các annotation đã được áp dụng (như loại annotation, giá trị của các thuộc tính
trong annotation) và từ đó quyết định hành động cần thực hiện.

-- @Override:

+) @Override giúp trình biên dịch Java kiểm tra xem bạn có thực sự ghi đè (override) một
phương thức từ interface hoặc từ lớp cha hay không.

+) Nếu bạn viết sai tên phương thức hoặc có sai lệch trong danh sách tham số, trình biên dịch sẽ báo lỗi,
giúp bạn phát hiện vấn đề ngay lập tức.

-- @Configuration:

+) Trong Spring Framework, annotation @Configuration được sử dụng để đánh dấu một class
là Java Configuration Class, nơi bạn có thể khai báo các beans và cấu hình cho Spring IoC
(Inversion of Control) container.

-- @Bean:

+) Annotation @Bean thường được sử dụng bên trong một configuration class, được đánh dấu với
@Configuration. Khi một class có annotation @Configuration, Spring hiểu rằng class này chứa
các method định nghĩa bean mà ứng dụng cần, và Spring sẽ xử lý các method có annotation @Bean
để đăng ký các đối tượng trả về từ các method này như các bean trong Spring container.

+) Các bean được tạo ra với @Bean theo mặc định là singleton, tức là chỉ có một instance duy nhất
trong Spring container.

+) Bạn có thể thay đổi scope của bean bằng cách sử dụng thuộc tính @Scope.

-- @Autowired:

+) Khi @Autowired được thêm vào một field trong Spring, điều đó có nghĩa là field này cần
một instance của một bean (đối tượng) được Spring quản lý để gán vào.

+) @Autowired sử dụng field injection khi được đặt trực tiếp trên một field (biến) trong lớp.

+) @Autowired sử dụng constructor injection khi được đặt trực tiếp trên một constructor trong lớp.

+) @Autowired sử dụng setter injection khi được đặt trực tiếp trên một hàm setter trong lớp.

-- @Qualifier("tên");

+) @Qualifier cho phép chỉ định bean name khi có nhiều bean cùng loại.

+) Nếu bạn không sử dụng @Qualifier và có nhiều bean cùng kiểu, Spring sẽ không biết phải
tiêm bean nào và sẽ ném ra lỗi.

-- @Component: Khi một class sử dụng annotation @Component trong Spring Framework, đây là một phần của cơ chế
dependency injection (DI). Cụ thể, khi bạn đánh dấu một class với @Component, Spring sẽ:

+) Tạo Bean: Spring sẽ tự động phát hiện class này và đăng ký các instances nó như một Bean trong
Spring Application Context. Điều này có nghĩa là Spring sẽ quản lý vòng đời của đối tượng này và
bạn có thể sử dụng nó trong các phần khác của ứng dụng.

+) Tiêm vào các lớp khác: Các lớp khác có thể sử dụng đối tượng này thông qua dependency injection.
Spring sẽ tự động tiêm (inject) Bean vào các lớp cần sử dụng nó, thông qua constructor, setter,
hoặc trường (field) của lớp đó.

+) Trong Spring Framework, Stereotype Annotations là các annotation đặc biệt để đánh dấu vai trò của một
class trong ứng dụng và giúp Spring tự động phát hiện và quản lý các thành phần này. Các Stereotype Annotations
là biến thể @Component annotation, bao gồm: @Service, @Repository, @Controller, @RestController.

-- @ResponseBody:

+) @ResponseBody là một annotation trong Spring dùng để chỉ định rằng dữ liệu trả về từ một
phương thức controller sẽ được chuyển thành định dạng JSON hoặc XML (tùy vào yêu cầu từ client)
và gửi thẳng về cho client, thay vì điều hướng tới một view.

-- @RestController:

+) Là sự kết hợp giữa @Controller và @ResponseBody.

-- @ComponentScan("tên package"):

+) Sử dụng annotation này để thông báo cho spring container rằng: “Phải biết vào các package nào trong dự án
để quét các Annotation và tạo Bean.”

+) @ComponentScan thường được sử dụng với @Configuration trong Spring để cấu hình phạm vi quét các bean và
tự động đăng ký chúng vào Spring IoC container.

-- @RequestMapping:

+) Ánh xạ URL: @RequestMapping giúp ánh xạ một URL cụ thể tới một phương thức xử lý trong controller.

+) Hỗ trợ nhiều HTTP Method: Mặc định, @RequestMapping ánh xạ với tất cả các HTTP method
(GET, POST, PUT, DELETE, PATCH, etc.). Tuy nhiên, có thể chỉ định phương thức cụ thể bằng
cách sử dụng thuộc tính method.

+) @RequestMapping thường được áp dụng ở cấp độ class để xác định một URL gốc (base URL) cho tất cả
các phương thức trong controller đó.

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

-- @SpringBootApplication:

+) @SpringBootApplication annotation là sự kết hợp của: @SpringBootConfiguration + @EnableAutoConfiguration

- @ComponentScan.

-- @SpringBootConfiguration:

+) Annotation này là một biến thể của @Configuration và được sử dụng để chỉ định rằng lớp này là lớp cấu hình
chính của Spring Boot.

+) Nó cho phép Spring Boot tạo ra một ApplicationContext với các cấu hình mà bạn định nghĩa.

-- @EnableAutoConfiguration:

+) Đây là annotation rất quan trọng của Spring Boot, cho phép Spring Boot tự động cấu hình ứng dụng dựa trên các
dependency mà bạn đã thêm vào.

+) Khi @EnableAutoConfiguration được kích hoạt, Spring Boot sẽ tự động quét classpath để tìm các thư viện
cần thiết (như spring-boot-starter-web, spring-boot-starter-data-jpa, v.v.) và tự động cấu hình các bean
tương ứng mà không cần cấu hình thủ công.

+) Bạn có thể tắt hoặc cấu hình các chức năng tự động này bằng cách thêm tùy chọn trong file application.properties.

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

- Các annotation để GET request data từ Client:

+) Nhận dữ liệu từ Request Body (@RequestBody) -- nhận dữ liệu JSON hoặc XML từ body của request..

+) Nhận dữ liệu từ Form Data (@ModelAttribute).

+) Nhận dữ liệu từ Query String (@RequestParam).

+) Nhận dữ liệu từ URL Parameters (@PathVariable).

- FILTER và INTERCEPTOR

-- Filter là một thành phần của Servlet API, được triển khai từ interface javax.servlet.Filter.
Nó hoạt động ở mức Servlet Container, tức là trước khi Spring xử lý request.
Filter được áp dụng cho tất cả các request đến ứng dụng web, không phụ thuộc vào Spring.

-- Filter chặn và xử lý request trước khi nó đến DispatcherServlet và sau khi phản hồi được trả về
từ DispatcherServlet. Thường được sử dụng để xử lý các tác vụ như:

+) Thay đổi hoặc thêm HTTP Header.

+) Authentication (Xác thực) và Authorization (Phân quyền).

+) Logging hoặc kiểm tra hiệu suất.

+) CORS (Cross-Origin Resource Sharing).

-- Interceptor là một thành phần của Spring MVC, được triển khai từ interface HandlerInterceptor.
Nó hoạt động trong phạm vi Spring MVC, tức là sau khi request đã được DispatcherServlet xử lý nhưng
trước khi nó đến Controller.

- WEB APPLICATION

-- Web Application chạy trên Web Server hoặc Application Server (ví dụ: Tomcat, Nginx).

-- Web Application là một phần mềm chạy trên Web Server, cung cấp các dịch vụ, tính năng mà người
dùng có thể truy cập thông qua trình duyệt hoặc các giao thức web. Có vai trò:

+) Thực hiện xử lý logic nghiệp vụ và truy xuất dữ liệu từ cơ sở dữ liệu.

+) Tương tác với người dùng thông qua giao diện động (HTML, JSON, XML, v.v.).

-- Web Application là một phần mềm hoàn chỉnh, bao gồm:

+) Frontend: Giao diện người dùng (HTML, CSS, JavaScript).

+) Backend: Logic xử lý (Servlet, JSP, hoặc các framework như Spring MVC).

+) Cơ sở dữ liệu: Lưu trữ và quản lý dữ liệu.

- QUY TRÌNH HOẠT ĐỘNG giữa WEB SERVER và WEB APPLICATION

-- Client gửi request đến Web Server:

+) Khi người dùng truy cập vào một URL, trình duyệt sẽ gửi một request HTTP đến Web Server.

-- Web Server nhận request:

+) Web Server phân tích request và xác định:

+) Nếu request yêu cầu nội dung tĩnh (HTML, CSS, hình ảnh), Web Server sẽ trả trực tiếp.

+) Nếu request yêu cầu xử lý logic động, Web Server chuyển request đến Web Application.

-- Web Application xử lý request:

+) Web Server chuyển request đến Web Application (ví dụ: Servlet trong Java hoặc controller trong Spring).

+) Web Application thực hiện các công việc như:

+) Lấy thông tin từ request (dữ liệu form, tham số URL, v.v.).

+) Tương tác với cơ sở dữ liệu (nếu cần).

+) Xử lý logic nghiệp vụ.

+) Tạo phản hồi (response).

-- Web Application gửi response về Web Server:

+) Sau khi xử lý xong, Web Application trả về kết quả cho Web Server (thường là HTML, JSON, XML hoặc file).

-- Web Server gửi response về cho client:

+) Web Server nhận response từ Web Application và chuyển lại cho client (trình duyệt).

+) Client sẽ hiển thị kết quả hoặc thực hiện các hành động dựa trên response đó.

- SERVLET

-- Servlet là một lớp Java được thiết kế để xử lý các request cụ thể, phổ biến nhất là HTTP request.

-- Servlet đóng vai trò như một Controller trong mô hình MVC (Model-View-Controller), quản lý logic điều hướng
giữa Model (dữ liệu) và View (giao diện người dùng). Servlet nhận các HTTP request từ Web Server, xử lý chúng
(bao gồm tương tác với cơ sở dữ liệu hoặc các logic nghiệp vụ), và trả về HTTP response.

-- Mục đích của servlet là tạo ra các phản hồi động (như HTML hoặc JSON) dựa trên request.

-- Servlet Container là môi trường runtime nơi các servlet hoạt động. Nó chịu trách nhiệm đảm bảo vòng
đời của servlet và tương tác với client.

-- Apache Tomcat là một trong những Servlet Container mã nguồn mở phổ biến và có thể hoạt động như một
web server nhẹ và servlet container.

- SERVLET CONTEXT

-- ServletContext là một interface trong Java Servlet API, và các Servlet Container (hay Web Container)
như Apache Tomcat, Jetty, hoặc WildFly sẽ triển khai (implement) interface này.

-- Web Container (hay Servlet Container) sẽ tạo ra một đối tượng ServletContext duy nhất/singletion
khi ứng dụng web được khởi chạy.

-- Đối tượng ServletContext được chia sẻ giữa tất cả các servlet, JSP, và các thành phần khác
trong cùng một ứng dụng.

-- ServletContext được sử dụng để đọc các tham số cấu hình (params) được định nghĩa trong file web.xml và
chia sẻ các tham số đó giữa các servlets và JSP trong cùng một ứng dụng web.

-- ServletContext dùng để tạo 1 RequestDispatcher object.

- VÒNG ĐỜI CỦA 1 SERVLET INSTANCE

-- Vòng đời của một Servlet được quản lý bởi Servlet Container, một thành phần bên trong Web Server
(ví dụ: Apache Tomcat, Jetty). Servlet Container đảm bảo rằng Servlet được tải, khởi tạo, xử lý request,
và hủy đúng cách. Có 5 bước:

+) Tải lớp Servlet vào bộ nhớ.

+) Tạo đối tượng Servlet.

+) Gọi phương thức init() của Servlet.

+) Gọi phương thức service() của Servlet.

+) Gọi phương thức destroy() của Servlet.

-- Bước 1, 2 và 3 được thực thi một lần duy nhất, khi mà Servlet được nạp lần đầu. Mặc định các Servlet
không được tải (load) lên cho tới khi nó nhận một đòi hỏi đầu tiên từ người dùng. Bạn có thể bắt buộc
Servlet Container (Bộ chứa các Servlet) tải các Servlet khi nó khởi động.

-- Bước 4 được thực thi nhiều lần, mỗi khi có đòi hỏi từ phía người dùng tới Servlet.

-- Bước 5 được thực thi khi bộ chứa Servlet (Servlet Container) gỡ bỏ tải (unloaded) một Servlet.

- JSP

-- JSP (JavaServer Pages) là một công nghệ Java cho phép tạo các trang web động. Nó cho phép
nhúng mã Java trong các tệp HTML để tạo nội dung web đa dạng và tương tác với dữ liệu từ máy chủ.

-- Quá trình biên dịch trang JSP bao gồm ba bước:

+) Phân tích cú pháp của JSP

+) Biến JSP thành servlet

+) Biên dịch servlet

-- vòng đời của JSP:

+) Bản dịch trang JSP

+) Biên dịch trang JSP(Biên dịch trang JSP thành \_jsp.java)

+) Tải lớp (\_jsp.java được chuyển đổi thành tệp lớp \_jsp.class)

+) Khởi tạo(Đối tượng của servlet được tạo được tạo)

+) Khởi tạo(\_jspinit() phương thức được gọi bởi container)

+) Yêu cầu xử lý(\_jspservice() phương thức được gọi bởi container)

+) Hủy hoại (\_jspDestroy() phương thức được gọi bởi container)

-- JSP là một Servlet, nó được biên dịch thành một lớp Servlet bởi Servlet Container:

+) config -> ServletConfig

+) request -> HttpServletRequest

+) respone -> HttpServletResponse

+) session -> HttpSession

+) application -> ServletContext

+) out -> PrintWriter

+) jspInit() -> init() / jspDestroy -> destroy()

- JDBC

-- JDBC (Java Database Connectivity) là một API (Application Programming Interface) trong Java.

-- JDBC API cung cấp các Class và Interface để kết nối với cơ sở dữ liệu, gửi câu lệnh SQL, và xử lý kết quả.

-- JDBC Driver là 1 class mà implement Interface của JDBC API để connect và tương tác với db.

-- JDBC Driver thường được thiết kế dưới dạng singleton (mẫu thiết kế đơn thể) trong nhiều trường hợp
Điều này có nghĩa là mỗi JDBC Driver chỉ cần một thể hiện duy nhất trong suốt quá trình chạy của ứng dụng.

-- JDBC Client là class hoặc code Java do bạn viết. Sử dụng JDBC API (các interface và lớp như Connection,
Statement, ResultSet, v.v.) để kết nối và thực hiện thao tác trên cơ sở dữ liệu.
Mã ứng dụng không tự trực tiếp kết nối với cơ sở dữ liệu mà thông qua JDBC Driver.

-- DriverManager là một class quản lý tập hợp các JDBC Driver đã được đăng ký. JDBC Client (ứng dụng của bạn)
sử dụng DriverManager để tìm JDBC Driver phù hợp. Sau đó, JDBC Driver thực hiện công việc cụ thể để kết nối
và giao tiếp với cơ sở dữ liệu.

-- Các thành phần chính trong JDBC:

+) DriverManager: Là một class dùng để quản lý danh sách các Driver

+) Driver: Là một interface, chịu trách nhiệm xử lý các hoạt động giao tiếp giữa ứng dụng và database

+) Connection: Là một interface, cung cấp các phương thức cho việc thao tác với database

+) Statement: Là một interface, để thực thi các câu lệnh SQL xuống database

+) ResultSet: Là một đối tượng trong Java được sử dụng để lưu trữ và thao tác với dữ liệu kết quả từ câu lệnh
SELECT trong SQL. Nó đại diện cho một bảng dữ liệu (các dòng và cột) mà bạn nhận được từ cơ sở dữ liệu sau khi
thực thi một câu truy vấn SELECT.

+) SQLException: Xử lý ngoại lệ xảy ra trong database

-- Các bước kết nối database với Java:

+) Tạo kết nối (Connection) với DriverManager / Load JDBC Driver

+) Tạo câu lệnh truy vấn SQL (Statement) với Connection

+) Dùng Statement Thực thi câu lệnh truy vấn SQL (Excute query)

+) Đóng kết nối (Close Connection)

-- Class.forName("com.mysql.cj.jdbc.Driver"): Dòng lệnh này được sử dụng để tải lớp driver MySQL JDBC vào bộ
nhớ tại runtime, để DriverManager có thể dùng Service Provider Mechanisum để tìm JDBC Driver cho MySql.

- PREPARED STATEMENT

-- Khi nào nên dùng PreparedStatement?

+) Khi cần thực thi cùng một câu lệnh nhiều lần với các tham số khác nhau. Vì câu lệnh SQL được biên dịch trước
(precompiled), có thể tái sử dụng nhiều lần với các tham số khác nhau.

+) Khi cần tăng cường bảo mật và ngăn chặn SQL Injection. vì các tham số được truyền riêng biệt, không bị nhúng
trực tiếp vào chuỗi SQL.

-- Khi nào nên dùng Statement?

+) Khi chỉ cần thực thi câu lệnh SQL một lần và không có tham số.

+) Khi làm việc với các câu lệnh SQL đơn giản, không phức tạp.

- INTER SERVLET COMMUNICATION là gì?

-- InterServletCommunication (ISC) là cơ chế trong Servlet API cho phép các servlet trong cùng một ứng dụng web
trao đổi dữ liệu hoặc yêu cầu nhau thực thi một số nhiệm vụ. Các cơ chế phổ biến trong ISC gồm:

-- Forward (chuyển tiếp):

+) Sử dụng RequestDispatcher.forward(request,response) để chuyển tiếp request và response từ servlet hiện tại
sang servlet khác.

-- Include (bao gồm):

+) Phương thức RequestDispatcher.include() được sử dụng để lấy nội dung từ một trang (Servlet, JSP, HTML, v.v.)
và chèn nó vào phản hồi của servlet hiện tại. Điều này giúp bạn tái sử dụng nội dung từ các tài nguyên khác mà
không phải sao chép mã.

-- Chia sẻ dữ liệu:

+) Servlet có thể chia sẻ dữ liệu thông qua các đối tượng như HttpServletRequest, HttpSession, hoặc ServletContext.

- SERVICE PROVIDER MECHANISM

-- Service Provider Mechanism (SPM) là cơ chế mà Java sử dụng để tự động phát hiện và đăng ký các dịch vụ
(như các JDBC Driver).

-- Khi bạn sử dụng Class.forName("com.mysql.cj.jdbc.Driver"), dòng lệnh này giúp JVM biết rằng cần phải
nạp lớp driver tại runtime.

- HTTPSESSION trong SERVLET

-- HttpSession là một giao diện (interface) trong Java Servlets được sử dụng để duy trì thông tin phiên
làm việc (session) của người dùng trong ứng dụng web. Phiên làm việc là một khoảng thời gian mà một người
dùng tương tác với ứng dụng. HttpSession cho phép bạn lưu trữ và truy xuất thông tin phiên để duy trì
trạng thái giữa các yêu cầu của người dùng.

-- HttpSession object được tạo ra bởi Servlet Container (như Apache Tomcat, Jetty, hoặc WildFly)
để duy trì trạng thái phiên làm việc (session) giữa client và server.

- HTTPCOOKIE trong SERVLET

-- Cookie là những đoạn dữ liệu nhỏ được lưu trữ trên máy tính của người dùng bởi trình duyệt web.

-- Cookie sẽ được trình duyệt tự động gửi kèm trong header của HTTP request.

-- Trong SERVLET, có thể get cookies thông qua HttpRequest.getCookies()

- URL REWRITING

-- URL rewriting được sử dụng chủ yếu trong trường hợp cookies bị vô hiệu hóa trên client hoặc
không thể sử dụng cookies để duy trì trạng thái (session) giữa client và server. Đây là một kỹ
thuật giúp duy trì trạng thái phiên làm việc bằng cách gắn ID phiên (session ID) trực tiếp vào
URL của các yêu cầu HTTP.

- DAO

-- DAO (Data Access Object) là 1 quy ước đặt tên cho các class. Ám chỉ class đó được thiết kế để quản lý
việc kết nối và tương tác với cơ sở dữ liệu (database).

-- Trong một ứng dụng Java sử dụng DAO, lớp này thường chứa:

+) Kết nối tới cơ sở dữ liệu: Sử dụng JDBC hoặc các framework ORM (như Hibernate).

+) Thực thi các câu lệnh SQL: Bao gồm các lệnh SELECT, INSERT, UPDATE, DELETE.

+) Chuyển đổi kết quả từ cơ sở dữ liệu thành đối tượng Java.
