- HỌC NHẤT QUÁN, HỌC LIÊN TỤC, LẤY CON A TRÍ TUỆ NHÂN TẠO ĐỂ LÊN 3.1 GPA, LẤY ĐIỂM TOEIC CAO NHẤT CÓ THỂ, CỐ GẮNG HẾT CỠ ĐỂ NĂM 2025 CÓ THỂ PASS FPT ,SAU TẾT 2025 COMBACK!

- VÌ SAO PHẢI THIẾT LẬP PATH environment variable

-- PATH environment variable là một biến môi trường trong hệ điều hành, chứa danh sách các thư mục nơi hệ thống sẽ tìm kiếm các tệp thực thi (executables). Khi bạn nhập một
lệnh vào dòng lệnh (Command Prompt trên Windows hoặc Terminal trên macOS/Linux), hệ thống sẽ tìm kiếm các tệp thực thi trong các thư mục được liệt kê trong PATH.

-- Khi cài đặt JDK, các tệp thực thi của Java như javac và java được đặt trong thư mục bin của JDK (ví dụ: C:\Program Files\Java\jdk-21\bin trên Windows). Nếu không thêm
thư mục này vào PATH, bạn sẽ phải nhập đường dẫn đầy đủ mỗi khi muốn sử dụng các lệnh liên quan đến Java, chẳng hạn: C:\Program Files\Java\jdk-17\bin\javac MyProgram.java

- JAVA PLATFORM

-- JAVA là một ngôn ngữ độc lập với nền tảng ( PLATFORM-INDEPENDENT ) vì mã nguồn của JAVA có thể chạy trên nhiều hệ điều hành. Các chương trình Java có thể chạy trên bất kỳ máy nào hoặc hệ điều hành không cần cài đặt bất kỳ phần mềm đặc biệt nào. Mặc dù JVM cần phải có mặt trong máy để thực thi BYTECODE (.class).

-- JAVA PLATFORM bao gồm Java Virtual Machine (JVM), Java Runtime Environment (JRE), Java Development Kit (JDK), Java Application Programming Interface (API) và Java Language.

-- SOURCE CODE JAVA (.java) sau khi được COMPILE bởi trình biên dịch JAVAC sẽ trở thành BYTECODE (.class), sau đó BYTECODE sẽ được thực thi (EXECUTION) bởi JVM để trở thành ngôn ngữ máy cho từng loại HỆ ĐIỀU HÀNH.

- JDK

-- JDK (Java Development Kit) là bộ công cụ phần mềm cần thiết cho việc phát triển ứng dụng Java. JRM + COMPLILERS + DEBUGGER.

-- Java Runtime Environment (JRE): Môi trường chạy cho ứng dụng Java, chứa JVM (Java Virtual Machine) và các thư viện liên quan tới JAVA.

-- JVM(Java Virtual Machine): thực thi BYTECODE (.class). Tuy nhiên, mỗi hệ điều hành (Windows, macOS, Linux, v.v.) sẽ có JVM riêng để thực thi BYTECODE theo cách phù hợp với hệ điều hành đó.

-- Trình biên dịch - DEBUGGER Java (javac): Công cụ để biên dịch mã nguồn Java (.java) thành mã BYTECODE (.class) mà JVM có thể hiểu và thực thi.

- JSHELL

-- JSHELL được phát hành từ JAVA 9.

-- JSHELL là công cụ REPL đầu tiên được tích hợp trong Java.

-- Nó cho phép các lập trình viên chạy các lệnh và biểu thức Java tương tác trực tiếp trong console mà không cần phải bọc chúng trong các lớp hoặc phương thức.

- JAVA EXPRESSION - BIỂU THỨC

-- EXPRESSION là sự kết hợp giữa các giá trị, biến, toán tử, và các lời gọi phương thức, được tính toán để cho ra một giá trị duy nhất.
Biểu thức có thể là một giá trị đơn lẻ hoặc một tổ hợp các giá trị mà khi được đánh giá sẽ tạo ra kết quả. Biểu thức có thể được sử dụng trong nhiều ngữ cảnh,
chẳng hạn như trong phép gán giá trị, các câu lệnh điều kiện, và các vòng lặp.

- PRINT, PRINTLN và PRINTF

-- Với PRINT: Xuất kết quả ra màn hình nhưng con trỏ chuột không xuống dòng.

-- Với PRINTLN: Xuất kết quả ra màn hình đồng thời con trỏ chuột nhảy xuống dòng tiếp theo.

-- Với PRINTF: Xuất ra màng hình kết quả đồng thời có thể định dạng được kết quả đó nhờ vào các ARGUMENTS và FORMAT SPECIFER (định dạng chuỗi) thích hợp.

- ESCAPE SEQUENCE

-- Trong Java, các chuỗi thoát (ESCAPE SEQUENCE) là các ký tự đặc biệt được sử dụng trong chuỗi để biểu diễn các ký tự điều khiển, ký tự không in ra được,
hoặc khoảng trắng cụ thể. Mỗi chuỗi thoát bắt đầu bằng dấu gạch chéo ngược (\), theo sau là một ký tự đại diện cho hiệu ứng mong muốn.
Dưới đây là các chuỗi thoát phổ biến trong Java: \t, \n, ...

- VARIABLE ( BIẾN )

-- Khái niệm biến (VARIABLE) trong lập trình được sinh ra để chúng ta không cần phải cố định (hard-code) dữ liệu trong mã nguồn.
Biến cho phép bạn lưu trữ giá trị hoặc thông tin để có thể thay đổi trong quá trình chương trình chạy.

-- VARIABLE là 1 thứ mà giá trị của nó có thể thay đổi trong suốt vòng đời của ứng dụng.

-- Trong JAVA, biến được sử dụng để lưu trữ và thao tác với dữ liệu. Nó là một NAMED MEMORY LOCATION, có thể chứa một giá trị thuộc một kiểu dữ liệu cụ thể.
Từ khóa "VARIABLE" được sử dụng để khai báo và định nghĩa các biến, cho phép phân bổ bộ nhớ để lưu trữ dữ liệu trong quá trình thực thi chương trình.

- METHOD OVERLOADING

-- METHOD OVERLOADING trong JAVA có nghĩa là có hai hoặc nhiều phương thức (hoặc hàm) trong một lớp có cùng tên nhưng khác nhau về đối số (hoặc tham số).
Điều này có thể thực hiện bằng cách sử dụng số lượng đối số khác nhau hoặc kiểu dữ liệu của các đối số khác nhau.

-- METHOD OVERLOADING trong JAVA không thể áp dụng chỉ dựa trên kiểu trả về (return type) của phương thức

-- METHOD main() của 1 class cũng có thể bị OVERLOADING;

- DEFINE and INVOKE METHOD

-- DEFINE và INVOKE phương thức là hai bước khác nhau. DEFINE phương thức là quá trình tạo ra một phương thức, tức là một khối mã có thể được thực thi.

-- INVOKE phương thức là quá trình kích hoạt phương thức, nghĩa là thực thi mã bên trong phương thức đó.

- PACKAGE

-- Một PACKAGE (gói) trong JAVA là một nhóm các class, interface và các package con tương tự, liên quan đến nhau.

-- PACKAGE trong JAVA được sử dụng nhằm tránh mâu thuẫn trong cách đặt tên và kiểm soát truy cập của các class, sub-class và interface. Bằng việc sử dụng các package,
lập trình viên sẽ dễ dàng sắp xếp và tìm kiếm các class, đồng thời package cung cấp một cấu trúc tốt cho dự án, đặc biệt với các dự án có lượng class và file lớn

-- Các PACKAGE được chia làm hai loại: Built-in packages và User defined packages.

- JAVA CLASS và OBJECT

-- CLASS như một TEMPLATE, có thể dung TEMPLATE này để tạo ra nhiều INSTANCES của CLASS đó.

-- Có thể xem CLASS như 1 bản thiết kế và OBJECT là các tòa nhà được xây bởi bảng thiết đó.

- OOP

-- Lập trình theo hướng OOP, chúng ta phải nghĩ về OBJECT, nghĩ về OBJECT là nghĩ về OBJECT đó có thể chứa DATA gì và nó có thể làm các chức năng gì.

-- lập trình hướng đối tượng (OOP - Object-Oriented Programming) xoay quanh việc tổ chức chương trình theo các đối tượng (OBJECTS). Mỗi đối tượng là một thực thể có
hai thành phần chính: DỮ LIỆU - hay TRẠNG THÁI của nó ( DATA - STATE ) và Chức năng (Behavior).

- MEMBER VARIABLE

-- Trong Java, MEMBER VARIABLE (biến thành viên) là các biến được khai báo trong lớp (class) nhưng nằm ngoài bất kỳ phương thức, hàm tạo (constructor), hoặc code block nào. Chúng còn được gọi là instance variables (biến thực thể) hoặc fields (trường) và là một phần quan trọng của đối tượng.

-- Mỗi OBJECT của lớp sẽ có một bản sao riêng của các biến này.

-- Các biến này có thể có giá trị khác nhau đối với mỗi OBJECT khác nhau.

-- Các MEMBER VARIABLE không nên được truy cập trực tiếp từ các OBJECTs khác mà nên được GET và SET thông qua METHOD để ngăn chặn việc các OBJECTs khác truyền vào các INVALID VALUE.
Nguyên tắc này được gọi là ENCAPSULATION (tính đóng gói).

- LOCAL VARIABLE

-- Là biến nằm trong khai báo và sử dụng trong phạm vi CODE BLOCK của 1 METHOD, 1 câu lệnh IF, 1 vòng FOR, vv...

-- Những biến này chỉ tồn tại trong phạm vi khối mã đó và sẽ không thể được truy cập từ bên ngoài.

- CONSTRUCTOR (Hàm khởi tạo)

-- CONSTRUCTOR trong java là một dạng đặc biệt của METHOD được sử dụng để khởi tạo các đối tượng.

-- Java CONSTRUCTOR được gọi tại thời điểm tạo đối tượng. Nó khởi tạo các giá trị để cung cấp dữ liệu cho các đối tượng, đó là lý do tại sao nó được gọi là CONSTRUCTOR.

- PRIMITIVE VARIABLE TYPES

-- 1 BYTE = 8 BIT.

-- BYTE: 1 BYTE, SHORT: 2 BYTEs, INT: 4 BYTEs, LONG: 8 BYTEs, FLOAT, DOUBLE: nói về số.

-- CHAR - 2 BYTEs: sử dụng 2 byte (16 bit) để biểu diễn một ký tự, và nó dựa trên tiêu chuẩn Unicode.

-- BOOLEAN: giá trị là 'true' hoặc 'false'.

-- Các toán tử có thể áp dụng cho PRIMITIVE TYPEs gồm: +,-,\*,/,%,++,--.

-- LƯU Ý: Toán tử prefix increment (++) và prefix decrement (--) xảy ra trước toán tử gán (=) trong Java.

-- LƯU Ý: Không nên sử dụng FLOAT và DOUBLE và 2 TYPEs này không thể hiện chính xác các giá trị thập phân.

- CASTING

-- IMPLICIT CASTING: là quá trình Java tự động chuyển đổi từ kiểu dữ liệu thấp hơn sang kiểu dữ liệu cao hơn mà không
cần sự can thiệp của lập trình viên. Điều này thường xảy ra khi không có khả năng mất mát dữ liệu,
ví dụ từ INT sang LONG hoặc từ FLOAT sang DOUBLE.

-- EXPLICIT CASTING: xảy ra khi bạn muốn chuyển đổi từ kiểu dữ liệu cao hơn xuống kiểu thấp hơn.
Điều này yêu cầu lập trình viên phải chỉ định rõ ràng vì có khả năng mất mát dữ liệu.

- BigDecimal CLASS

-- Lớp BigDecimal Đây là một lớp mạnh mẽ được sử dụng để xử lý các số thập phân với độ chính xác cao, đặc biệt hữu ích cho
các phép toán tài chính hoặc các tính toán khoa học mà độ chính xác là rất quan trọng.

-- Lớp BigDecimal có thể xử lý các số dấu phẩy động rất lớn và rất nhỏ với độ chính xác cao nhưng bù lại một chút về độ phức tạp
thời gian.

-- BigDecimal là một IMMUTABLE CLASS trong Java, có nghĩa là giá trị của một đối tượng BigDecimal không thể bị thay đổi
sau khi nó được khởi tạo. Bất kỳ phép toán nào (như cộng, trừ, nhân, chia) trên một đối tượng BigDecimal đều tạo ra
một đối tượng BigDecimal mới với giá trị kết quả, thay vì thay đổi giá trị của đối tượng ban đầu.

-- LƯU Ý: nên dùng new BigDecimal("string"); thay vì new BigDecimal(float/double); thì giá trị sẽ chính xác hơn.

- TOÁN TỬ && và &

-- && là toán tử AND logic ngắn mạch (short-circuit). Điều này có nghĩa là nếu biểu thức bên trái là false,
thì biểu thức bên phải sẽ không được đánh giá vì toàn bộ biểu thức đã biết là false.

-- Toán tử & sẽ tiếp tục tính toán biểu thức bên phải ngay cả khi biểu thức bên trái đã false.

- DEFAULT, BREAK và FALL-THROUGH trong SWITCH CASE

-- DEFAULT là một phần của cấu trúc switch-case, được sử dụng khi không có trường hợp nào (case) khớp với giá trị cần so sánh.
Nó tương tự như else trong một câu lệnh if-else. DEFAULT không bắt buộc phải có trong switch-case, nhưng nếu có, nó thường là câu lệnh cuối cùng.

-- BREAK trong switch-case dùng để kết thúc một case. Nó giúp ngăn chặn việc thực hiện tiếp các case khác sau khi một case đã khớp.
Nếu không có BREAK, sau khi một case khớp, chương trình sẽ tiếp tục thực hiện các câu lệnh trong các case phía dưới (đây gọi là fall-through).

-- Chỉ có SWITCH có các TYPEs như INT, CHAR, STRING (JAVA 7) ,BYTE, SHORT hoặc ENUM (JAVA 5).

- TERNARY OPERATION (TOÁN TỬ 3 NGÔI)

-- Cả 2 vế của TOÁN TỬ 3 NGÔI phải trả về cùng 1 kiểu dữ liệu.

- WHILE, DO WHILE và FOR

-- Dùng FOR khi ta xác định số lần chạy.

-- WHILE sẽ kiểm tra CONDITION trước khi chạy còn DO WHILE sẽ chạy code trong block rồi mới check CONDITION.

-- Dùng DO WHILE khi muốn code trong block được EXCECUTE ít nhất 1 lần.

- BREAK và CONTINUE

-- BREAK sẽ ngay lập tức thoát khỏi tất cả lần lặp còn lại.

-- CONTINUE sẽ ngay lập tức thoát khỏi lần lặp hiện tại.

- REFERENCE TYPEs

-- Khi khai báo một biến kiểu REFERENCE TYPEs (ví dụ như một đối tượng của một class), biến này sẽ nằm trong STACK.
Biến của REFERENCE TYPEs sẽ chỉ chứa địa chỉ của đối tượng dữ liệu tại bộ nhớ STACK.
Đối tượng thực sự được tạo trong vùng nhớ HEAP. Biến tham chiếu trên STACK sẽ chứa địa chỉ trỏ đến vị trí của đối tượng này trên HEAP.

- STACK và HEAP

-- Nếu khai báo trong phương thức, hàm, hoặc khối mã, biến PRIMITIVE sẽ được lưu trong STACK vì nó có phạm vi giới hạn
và được quản lý bởi ngăn xếp trong quá trình thực thi.

-- Nếu là MEMBER VARIABLE của một đối tượng, dù có là PRIMITIVE hay không, nó sẽ được lưu trong HEAP, cùng với đối tượng mà nó thuộc về.

- STRING trong JAVA

-- STRING là 1 CLASS đặc biệt trong JAVA, khác với các class khác, ta không cần gọi CONSTRUCTOR khi khai báo 1 INSTANCE của class STRING.

-- Mọi chuỗi-string đều là INSTANCE của lớp có kiểu là STRING.

-- STRING là 1 IMMUTABLE, có nghĩa là khi một đối tượng của lớp String được tạo ra, giá trị của nó không thể thay đổi được.
Bất kỳ thao tác nào thay đổi giá trị của String sẽ tạo ra một đối tượng String mới thay vì thay đổi nội dung của đối tượng ban đầu.

-- Trong Java, chuỗi (String) thực chất là một mảng các ký tự (char) được sắp xếp liền kề trong bộ nhớ.

- String, StringBuffer và StringBuilder trong JAVA

-- Khu vực lưu trữ: Với String, String Pool đóng vai trò là khu vực lưu trữ. Đối với StringBuilder và StringBuffer, bộ nhớ HEAP là vùng lưu trữ.

-- Tính thay đổi: Một String là IMMUTABLE, trong khi cả StringBuilder và StringBuffer đều có thể thay đổi.

-- Thread-safe: Trong trường hợp môi trường luồng, StringBuilder và StringBuffer được sử dụng trong khi một String không được sử dụng.
Tuy nhiên, StringBuilder phù hợp với môi trường có một luồng duy nhất và StringBuffer phù hợp với đa luồng.

- EQUALS METHOD và TOÁN TỬ ==

-- Toán tử == dùng để so sánh địa chỉ (hoặc tham chiếu), tức là kiểm tra xem cả hai đối tượng có trỏ đến cùng một vị trí bộ nhớ hay không.

-- Phương thức Equals() so sánh dựa trên code bên trong instance chứa nó.

-- Trong trường hợp phương thức equals không được ghi đè trong một lớp, thì lớp đó sử dụng cách triển khai mặc định của phương thức equals
gần với lớp cha nhất.

-- Lớp Object được coi là lớp cha của tất cả các lớp Java. Và cách triển khai equals() của 1 Object là so sánh cả hai đối tượng có trỏ đến cùng
một vị trí bộ nhớ hay không.

- HASHCODE METHOD

-- Phương thức hashCode() trả về một số int đại diện cho 1 instance của class. Khi 2 object là bằng nhau thì hashCode() method của chúng
cũng phải trả về giá trị bằng nhau. Đó là lý do nếu đã override equals() method thì cũng phải override hashCode() method.

-- Phương thức hashCode() là cơ chế giúp các hash collection như HashMap, HashSet, và Hashtable phân chia và lưu trữ các đối tượng một
cách hiệu quả bằng cách sử dụng mã băm (hash code) của các đối tượng để đặt chúng vào các bucket.

- WRAPPER CLASS

-- Trong Java, các Wrapper Class được thiết kế để "bọc" (wrap) các kiểu dữ liệu nguyên thủy (như int, double, boolean, v.v.) thành các đối tượng, từ đó
cho phép xử lý các giá trị nguyên thủy như thể chúng là các đối tượng. Điều này rất hữu ích vì:

++ Chuyển đổi giữa kiểu nguyên thủy và đối tượng: Các wrapper class cung cấp các phương thức để chuyển đổi qua lại giữa kiểu nguyên thủy và đối tượng.
Ví dụ: Integer có phương thức parseInt() để chuyển đổi String thành int.

- AUTO BOXING

-- Autoboxing hay Boxing trong JAVA là quá trình chuyển dữ liệu từ kiểu tham trị sang kiểu tham chiếu.
Khi bạn gán một giá trị nguyên thủy vào một biến tham chiếu của lớp bao, Java sẽ tự động tạo một đối tượng
(instance) của lớp bao này trên vùng nhớ HEAP và gán giá trị của kiểu nguyên thủy vào đó.

++ Hỗ trợ Collection Framework:

-- Trong Java, có hai cách phổ biến để tạo một đối tượng của Wrapper Class: phương thức valueOf() và từ khóa NEW.

-- Khi sử dụng phương thức valueOf() trong các wrapper class như Integer, Double, Boolean, v.v., Java sẽ cố gắng tái sử dụng (reuse) các đối tượng
có giá trị đã được tạo trước đó, thay vì tạo đối tượng mới mỗi lần. Cơ chế này được gọi là caching và giúp tiết kiệm bộ nhớ, đặc biệt là với các giá trị thường xuyên được sử dụng.

- DATETIME API trong JAVA

-- JAVA 8 đã giới thiệu ba lớp quan trọng trong gói java.time để làm việc với ngày và giờ là LocalDate, LocalDateTime và LocalTime.

-- Cả ba lớp LocalDate, LocalTime, và LocalDateTime trong Java 8 đều là immutable. Điều này có nghĩa là một khi đã khởi tạo,
các đối tượng từ những lớp này không thể thay đổi được. Mọi thao tác trên những đối tượng này, chẳng hạn như cộng thêm hoặc
trừ bớt ngày, giờ, sẽ tạo ra một đối tượng mới thay vì thay đổi đối tượng ban đầu.

- ARRAY

-- Array không phải là 1 COLLECTION.

-- ARRAY là cấu trúc cơ bản trong Java cho phép chúng ta lưu trữ nhiều giá trị có cùng kiểu giá trị trong một biến duy nhất.

-- Trong JAVA, các phần tử trong một mảng (ARRAY) đều được lưu trữ ở các vị trí bộ nhớ liên tiếp nhau.

-- Kích thước cố định: Khi đã tạo, Array có kích thước cố định và không thể thay đổi. Bạn phải biết số phần tử cần lưu trữ ngay từ đầu.
Nghĩa là không thể thêm và xóa phần tử của 1 ARRAY đã được khởi tạo.

- ARRAYLIST

-- Trong Java, ArrayList là 1 COLLECTION. Do đó, nó chỉ có thể chứa các kiểu tham chiếu (reference types),
không thể chứa trực tiếp các kiểu nguyên thủy (primitive types) như int, double, boolean, v.v.

- VARIABLE ARGUMENT - Varargs

-- https://viblo.asia/p/java-core-tat-tan-tat-ve-varargs-trong-java-WAyK8reelxX#_1-dat-van-de-0

- FINAL

-- Sử dụng với biến: Khi một biến được khai báo với từ khóa final, giá trị của nó không thể thay đổi sau khi được khởi tạo.
Điều này tương tự như một hằng số. Khác với CONST Biến FINAL có thể được khởi tạo ở giai đoạn runtime bằng CONSTRUCTOR.

-- Sử dụng với phương thức: Khi một phương thức được khai báo là final, phương thức này không thể bị ghi đè (override) bởi các lớp con.

-- Sử dụng với lớp: Khi một lớp được khai báo là final, lớp đó không thể được kế thừa.

-- Sử dụng với tham số: Trong Java, từ khóa final có thể được sử dụng với các tham số của phương thức để chỉ ra rằng giá trị của tham
số không thể thay đổi trong suốt quá trình thực thi của phương thức.

- DEFAULT

-- Kể từ Java 8, có thể định nghĩa các phương thức có thân (body) trong một Interface bằng cách sử dụng từ khóa default.
Điều này cho phép các Interface cung cấp các phương thức mặc định mà các lớp triển khai có thể sử dụng hoặc ghi đè.

- INHERITANCE

-- Kế thừa là sự liên quan giữa hai class với nhau, trong đó có class cha (superclass) và class con (subclass).
Khi kế thừa class con được hưởng tất cả các phương thức và thuộc tính của class cha. Tuy nhiên, nó chỉ được truy cập các thành viên public và protected của class cha.
Nó không được phép truy cập đến thành viên private của class cha.

-- Trong Java, khi một đối tượng con được tạo, một đối tượng cha cũng được khởi tạo ngầm. Điều này xảy ra vì lớp con luôn phải gọi constructor của lớp cha,
trực tiếp hoặc gián tiếp. Nếu bạn không gọi constructor của lớp cha rõ ràng bằng từ khóa super(), Java sẽ tự động gọi constructor
không tham số (nếu có) của lớp cha trước khi thực hiện constructor của lớp con. Quy trình này giúp đảm bảo rằng tất cả các phần thuộc lớp cha đều
được khởi tạo trước khi lớp con có thể sử dụng.

-- Trong Java, nếu một lớp không mở rộng (extend) bất kỳ lớp nào, thì nó mặc định sẽ kế thừa lớp Object. Object là lớp gốc của tất cả các lớp
trong Java và cung cấp một số phương thức cơ bản như toString(), equals(), hashCode(), và clone(). Do đó, ngay cả khi bạn không viết
extends Object, mọi lớp trong Java vẫn kế thừa lớp Object và có thể sử dụng các phương thức này.

-- JAVA không hỗ trợ đa kế thừa (multiple inheritance) để tránh vấn đề "diamond problem". Vấn đề này xảy ra khi một lớp kế thừa từ hai lớp cha,
mà cả hai lớp cha này đều có phương thức cùng tên và cùng tham số (signature). Khi đó, trình biên dịch sẽ gặp khó khăn trong việc xác định nên gọi phương thức nào.

-- Tại sao sử dụng tính kế thừa trong Java?

+) Để ghi đè phương thức (Method Overriding), do đó có thể thu được tính đa hình tại runtime.

+) Để làm tăng tính tái sử dụng của code.

- ABSTRACTION

-- Trong JAVA, abstract class (lớp trừu tượng) được sử dụng để làm lớp cha, chứa các đặc điểm và hành vi chung mà các lớp con kế thừa,
abstract class được sử dụng để định nghĩa các hành vi và thuộc tính chung.

-- Lớp con bắt buộc phải implement tất cả các phương thức trừu tượng của lớp cha.

-- Không thể khởi tạo đối tượng từ lớp trừu tượng.

-- Trong JAVA, một abstract method (phương thức trừu tượng) bắt buộc phải được override (ghi đè) trong các lớp con kế thừa.
Phương thức trừu tượng chỉ được khai báo trong lớp cha, nhưng không có phần thân thực thi (implementation),
vì vậy các lớp con cần phải cung cấp chi tiết cụ thể cho phương thức này.

-- Trong 1 lớp trừu tượng, từ khóa this vẫn có thể được sử dụng mặc dù lớp này không thể được khởi tạo trực tiếp.
Điều này là do this là một tham chiếu đến đối tượng hiện tại và sẽ trỏ tới các đối tượng của bất kỳ lớp con nào kế thừa từ
lớp trừu tượng đó.

-- Abstract thể hiện mối quan hệ IS-A còn Interface thể hiện mối quan hệ HAS-A.

-- Phiên bản Java < 8, Interface chỉ có thể có phương thức abstract. Phiên bản Java 8, có thể thêm default và static methods.
Phiên bản Java 9, có thể thêm private methods.

-- Interface chỉ có các biến static final.

-- Tất cả các methods trong Interface đều được ngầm định là public và abstract (trừ default và static method).

- POLYMORPHISM

-- Tính đa hình là khả năng một đối tượng có thể thực hiện một tác vụ theo nhiều cách khác nhau.

-- Trong Java, chúng ta sử dụng nạp chồng phương thức (method overloading) và ghi đè phương thức
(method overriding) để có tính đa hình.

- COLLECTIONS

-- Interface Iterable -> Interface Collection -> Interface List.

-- Iterable: Đây là Interface gốc, cung cấp phương thức iterator() để lặp qua các phần tử. Tất cả các lớp triển khai Iterable
có thể được duyệt bằng vòng lặp for-each.

-- Collection: Kế thừa Iterable và định nghĩa một tập hợp các phương thức cơ bản cho các cấu trúc dữ liệu dạng tập hợp
(collection) như thêm, xóa, kiểm tra kích thước, kiểm tra trống, và duyệt các phần tử.

-- List: Kế thừa Collection và mở rộng thêm các phương thức cụ thể cho kiểu danh sách (list), bao gồm truy cập phần tử
theo chỉ mục, tìm kiếm phần tử, thêm/xóa theo vị trí, và hỗ trợ các danh sách có thứ tự và trùng lặp.

-- List trong JAVA là 1 Interface nằm trong gói java.util. List định nghĩa một tập hợp các phương thức mà các Class
như ArrayList, LinkedList, và Vector phải implement.

-- Bất kỳ collection nào được tạo từ phương thức tĩnh of() trong các interface như List, Set, hoặc Map đều là immutable (bất biến).
Điều này có nghĩa là sau khi được khởi tạo bằng of(), collection sẽ không thể thay đổi—không thể thêm, xóa, hoặc cập nhật các phần tử

- VERTOR và ARRAYLIST

-- Cả 2 class đều implement Interface List.

-- Cả 2 class đều sử dụng cấu trúc dữ liệu Array.

-- Tất cả các phương thức (methods) của lớp Vector trong Java đều được đồng bộ hóa (synchronized).
Điều này có nghĩa là các phương thức của Vector được bảo vệ để chỉ một luồng (thread) có thể truy cập vào chúng tại một thời điểm.
Điều này giúp đảm bảo tính an toàn khi truy cập dữ liệu trong môi trường đa luồng.

- SET

-- Iterable -> Collection -> Set

-- Set (tập hợp) trong Java là một Interface, được kế thừa từ Interface Collection. Set ĐẶC BIỆT không chứa các phần tử trùng nhau.

-- Khác với Interface List, Interface Set ĐẶC BIỆT không có các phương thức thao tác với phần tử theo vị trí/chỉ mục.

-- Set định nghĩa một tập hợp các phương thức mà các Class như HashSet, LinkedHashSet và TreeSet phải implement.

-- HashSet: Không đảm bảo thứ tự của phần tử, vì nó sử dụng bảng băm (hash table) để lưu trữ.

-- LinkedHashSet: Sắp xếp thứ tự của phần tử theo thứ tự chèn.

-- TreeSet: Sắp xếp phần tử theo thứ tự tự nhiên hoặc theo Comparator tùy chỉnh.

- QUEUE

-- Iterable -> Collection -> Queue

-- QUEUE (tập hợp) trong Java là một Interface, được kế thừa từ Interface Collection và hoạt động theo cơ chế FIFO (First-In-First-Out).

-- QUEUE được sử dụng khi muốn sắp xếp mọi thứ theo thứ tự mà bạn muốn xử lý chúng.

- Map

-- Map trong Java không có super Interface trực tiếp. Tuy nhiên, Map vẫn gián tiếp kế thừa một số đặc điểm từ các interface khác thông qua
các phương thức mặc định hoặc các tính năng chung của Collection Framework.

-- Trong java, Map là 1 Interface được sử dụng để lưu trữ và truy xuất dữ liệu theo cặp khóa (key) và giá trị (value). Mỗi cặp key và value được gọi là entry.

-- Map chỉ chứa các giá trị key duy nhất, không chứa các key trùng lặp.

Các lớp triển khai (implements) Map Interface là HashMap, HashTable, LinkedHashMap and TreeMap:

+) HashMap không đảm bảo thứ tự các entry được thêm vào. HashMap cho phép một key duy nhất có giá trị null nhưng bất kỳ value nào cũng có thể null

+) HashTable giống với HashMap nhưng tất cả các methods của HashTable đều có thêm synchronized. HashTable không cho phép null trong cả key lẫn value.

+) LinkedHashMap đảm bảo thứ tự các entry được thêm vào.

+) TreeMap duy trình thứ tự các phần tử dựa vào bộ so sánh Comparator.

-- Sức chứa (compacity) mặc định khi khởi tạo map là 24 = 16. Kích thước này sẽ tự động tăng gấp đôi mỗi khi thêm phần tử vượt quá kích thước của nó.

- PHƯƠNG THỨC of() và copyOf()

-- Trong Java, cả copyOf và of là 2 static method của các lớp như List, Set, và Map trong java.util.
Tuy nhiên, chúng có mục đích và cách sử dụng khác nhau:

+) of: Dùng để tạo một collection bất biến từ các phần tử cụ thể, không phải từ một collection đã có sẵn.

+) copyOf: Dùng để tạo một bản sao bất biến của một collection đã tồn tại.

- GENERICS

-- Generics trong Java là một tính năng cho phép chúng ta tạo ra các Class, Interface và Method có thể hoạt động với nhiều kiểu dữ liệu khác nhau
mà không cần phải xác định rõ kiểu dữ liệu đó từ trước. Điều này giúp mã có thể xử lý nhiều loại dữ liệu khác nhau mà không cần phải tạo ra các lớp riêng biệt
cho từng loại dữ liệu.

- WILDCARD

-- Wildcard-Ký tự đại diện trong Java là ký hiệu dùng trong Generics để đại diện cho một kiểu không xác định. Nó thường được sử dụng khi bạn muốn tạo tính linh hoạt
trong các phương thức, lớp hoặc interface mà không cần chỉ rõ kiểu cụ thể, giúp các lớp generic có thể làm việc với nhiều loại dữ liệu khác nhau
mà không bị hạn chế vào một kiểu cố định.

-- Unbounded Wildcard (?): Chấp nhận bất kỳ kiểu nào.

-- Upper Bounded Wildcard (? extends T) - Giới hạn trên.: Chấp nhận các kiểu là con của T, hữu ích khi đọc dữ liệu từ cấu trúc generic.

-- Lower Bounded Wildcard (? super T) - Giới hạn dưới.: Chấp nhận các kiểu là cha của T, hữu ích khi thêm dữ liệu vào cấu trúc generic.

- STREAM trong JAVA

-- Trong Java, Stream là 1 Interface đại diện cho một chuỗi dữ liệu mà bạn có thể xử lý theo kiểu khai báo (declarative) và phong cách hàm (functional).
Stream cho phép thực hiện các thao tác như lọc (filtering), ánh xạ (mapping), và tổng hợp (reducing) trên một tập hợp dữ liệu.
Stream có thể được sử dụng với nhiều nguồn dữ liệu khác nhau, bao gồm mảng (arrays), bộ sưu tập (collections),
và thậm chí cả kênh I/O (I/O channels).

-- Không lưu trữ các phần tử của collection hoặc array: Stream không phải là một cấu trúc dữ liệu lưu trữ như List hoặc Set.
Thay vào đó, nó xử lý từng phần tử khi chúng được yêu cầu (demand-driven) thông qua pipeline các thao tác.
Khi sử dụng Stream, các phần tử sẽ được đọc từ nguồn (collection, array, hoặc các nguồn khác), truyền qua các thao tác
và cuối cùng kết thúc ở thao tác terminal.

-- Không phải là cấu trúc dữ liệu: Do không chứa dữ liệu thực tế, Stream chỉ là một abstraction để xử lý và thao tác trên dữ liệu nguồn.
Nó giúp loại bỏ sự cần thiết phải lưu trữ hoặc thao tác trực tiếp trên cấu trúc dữ liệu nguồn, mà thay vào đó xử lý các phần tử thông qua pipeline
các thao tác trung gian và kết thúc.

-- Immutable Object: Các thao tác trên Stream (như filter(), map()) không thay đổi dữ liệu gốc mà trả về một Stream mới.
Điều này đảm bảo rằng nguồn dữ liệu ban đầu không bị ảnh hưởng, tránh side-effects. Tính bất biến này cũng góp phần vào
tính an toàn khi xử lý song song vì các thao tác trên luồng sẽ không làm thay đổi trạng thái của dữ liệu.

-- Lazy Evaluation (đánh giá lười biếng): Tính lười biếng có nghĩa là các thao tác trung gian (như filter() và map())
không được thực thi ngay lập tức. Thay vào đó, chúng được xâu chuỗi lại thành một pipeline và chỉ thực thi khi có
thao tác kết thúc (terminal operation) như collect(), forEach(). Điều này giúp Java tối ưu hóa các thao tác trên Stream,
chỉ xử lý các phần tử cần thiết và tránh xử lý dư thừa. Để làm được điều này, hầu hết các thao tác với Stream đều return
lại một Stream mới, giúp tạo một mắc xích bao gồm một loạt các thao tác nhằm thực thi các thao tác đó một cách tối ưu nhất.
Mắc xích này còn được gọi là pipeline.

-- Pipeline: Khi sử dụng các thao tác trung gian và terminal, Stream tạo thành một pipeline các thao tác.
Pipeline cho phép xây dựng các chuỗi thao tác rõ ràng, linh hoạt và tối ưu. Các thao tác này có thể được sắp xếp thành
chuỗi từ các thao tác trung gian đến thao tác cuối cùng để đảm bảo chúng được thực hiện theo thứ tự tối ưu nhất.

-- Truy cập một lần duy nhất: Stream có tính chất "chỉ đọc một lần", tương tự như Iterator. Các phần tử chỉ có thể được xử lý
một lần trong suốt vòng đời của Stream. Sau khi thao tác kết thúc được thực thi, Stream trở nên vô hiệu và không thể tái sử dụng.
Để duyệt lại, cần tạo một Stream mới từ nguồn dữ liệu ban đầu.

-- Không thể tái sử dụng: Sau khi một thao tác kết thúc được thực thi trên Stream, nó không còn sử dụng được nữa,
và mọi nỗ lực truy xuất hoặc thao tác lại trên nó sẽ dẫn đến lỗi. Điều này đảm bảo các luồng không bị xử lý nhiều lần không cần thiết.

-- Không hỗ trợ index: Stream không cung cấp quyền truy cập trực tiếp vào các phần tử dựa trên chỉ số (index).
Đây là khác biệt lớn so với danh sách (List) hoặc mảng (Array). Stream hoạt động trên từng phần tử mà không cần biết
vị trí của chúng, phù hợp cho việc xử lý tuần tự và song song.

-- Hỗ trợ xử lý song song: Với parallelStream(), Stream hỗ trợ chia công việc thành nhiều luồng xử lý song song,
giúp tăng hiệu năng khi xử lý dữ liệu lớn. Việc này cho phép Stream tận dụng đa lõi CPU mà không cần quản lý trực tiếp luồng (thread).

-- Trong Java Stream, một chuỗi thao tác (pipeline) có thể bao gồm nhiều intermediate operators (các toán tử trung gian)
nhưng chỉ có một terminal operator (toán tử kết thúc) để kích hoạt pipeline.

- FUNCTIONAL INTERFACE

-- Functional Interface là một interface chỉ có một phương thức trừu tượng. Điều này cho phép Java biết rằng interface đó có thể được thay thế bởi một biểu thức lambda,
giúp đơn giản hóa cú pháp khi làm việc với các hàm callback, xử lý sự kiện, hoặc các phương thức ngắn gọn.

-- Lợi ích chính của functional interface là chúng ta có thể sử dụng Lambda Expression để tạo ra thể hiện (instance) cho interface đó.

-- Các đặc điểm của 1 Functional Interface:

+) Một Functional Interface hợp lệ chỉ có duy nhất một phương thức trừu tượng
Đây là đặc điểm cốt lõi của functional interface. Một functional interface chỉ có một phương thức trừu tượng (abstract method),
nghĩa là chỉ có một phương thức chưa được triển khai. Điều này giúp Java biết rằng interface đó có thể được thay thế bằng một biểu thức lambda.
Đặc điểm này còn được gọi là Single Abstract Method (SAM).

+) Một Functional Interface có thể có các phương thức của lớp java.lang.Object
Functional interface có thể kế thừa các phương thức từ java.lang.Object (chẳng hạn như equals(), hashCode(), và toString()).
Những phương thức này không ảnh hưởng đến tính chất của functional interface vì chúng không được xem là các phương thức trừu tượng.

+) Phương thức default và static không phá vỡ quy tắc của functional interface
Functional interface có thể chứa các phương thức default và static mà không làm mất đi tính chất của nó. Các phương thức default và static đều
có phần triển khai (implementation), nên chúng không được xem là các phương thức trừu tượng và không ảnh hưởng đến đặc tính "một phương thức trừu tượng duy nhất".

+) Một Functional Interface có thể mở rộng một interface khác chỉ khi nó không có bất kỳ phương thức trừu tượng nào Functional interface
có thể mở rộng một interface khác, nhưng chỉ khi interface kia không có phương thức trừu tượng hoặc có chính xác một phương thức
trừu tượng (bao gồm cả trường hợp nó là một functional interface). Điều này đảm bảo rằng functional interface mở rộng vẫn tuân theo
quy tắc "một phương thức trừu tượng duy nhất".

- THREAD

-- Luồng (thread) trong Java là một đơn vị xử lý độc lập trong chương trình, cho phép thực hiện đa luồng (multithreading)
để cải thiện hiệu suất và tận dụng tối đa tài nguyên máy tính. Mỗi luồng là một dòng thực thi độc lập trong chương trình,
có thể chạy song song với các luồng khác.

-- Trong Java, mọi chương trình đều có ít nhất một luồng, gọi là luồng chính (main thread), được cung cấp bởi
Java Virtual Machine (JVM) khi chương trình bắt đầu thực thi.

-- Các cách sử dụng luồng:

+) Kế thừa từ lớp Thread

+) Triển khai interface Runnable

-- Việc triển khai một luồng bằng phương thức của interface Runnable được ưu tiên và thuận lợi hơn vì Java không hỗ trợ kế thừa
nhiều lớp.

-- Phương thức start() tạo một call stack riêng biệt cho luồng mới và kích hoạt JVM gọi run() trong call stack đó.

-- Việc gọi trực tiếp run() sẽ không tạo call stack mới, mà chỉ thực thi mã bên trong run() trên call stack hiện tại.

-- State của Thread:

+) New: Khi instance của luồng được tạo và phương thức start() chưa được gọi, luồng được coi là còn sống và do đó ở trạng thái NEW.

+) Terminate/Dead: Khi quá trình thực thi phương thức run() hoàn tất, luồng được cho là đi vào bước TERMINATED và được coi là
không còn tồn tại.

+) Runnable: Khi phương thức start() được gọi, trước khi phương thức run() được gọi bởi JVM, luồng được cho là ở trạng thái RUNNABLE
(sẵn sàng chạy). Trạng thái này cũng có thể được nhập từ trạng thái Waiting hoặc Sleeping của luồng.

+) Running: Khi phương thức run() được gọi và luồng bắt đầu thực thi, luồng được cho là đang ở trạng thái RUNNING.

+) Blocked: Một luồng sẽ ở trạng thái Blocked khi nó cố gắng truy cập một đoạn mã được đồng bộ hóa (synchronized block)
nhưng không thể vì có một luồng khác đang thực thi đoạn mã đó trên cùng một đối tượng.
Trong tình huống này, luồng bị chặn sẽ phải đợi cho đến khi luồng đang thực thi thoát khỏi khối được đồng bộ hóa,
sau đó nó mới có thể tiếp tục.

+) Waiting: Trạng thái Waiting xảy ra khi một luồng đang đợi tín hiệu từ một luồng khác để tiếp tục thực thi.
Trong trường hợp này, luồng không bị chặn bởi mã đồng bộ hóa nhưng đang "tạm dừng" để chờ tín hiệu báo hiệu từ một luồng khác
để tiếp tục công việc của nó.

-- Độ ưu tiên của 1 Thread có phạm vi từ 1 đến 10.

- SYNCHRONIZED

-- Java sử dụng từ khóa synchronized để khóa một khối mã hoặc phương thức.

-- Khi một luồng truy cập vào một phương thức hoặc khối mã được đánh dấu synchronized, nó sẽ giữ khóa của đối tượng đó
và ngăn các luồng khác truy cập vào cùng một khối hoặc phương thức cho đến khi khóa được giải phóng.

-- Vấn đề của synchronized là chỉ 1 Thread được quyền truy cập vào tất cả các synchronized methods khác của 1 object tại 1 thời điểm.
Khi một thread đang thực thi một phương thức synchronized, tất cả các phương thức synchronized khác của cùng đối tượng đều bị khóa.
Điều này xảy ra ngay cả khi các phương thức synchronized khác có thể không xung đột với nhau hoặc không tác động lên cùng tài nguyên.
Các thread khác phải chờ thread hiện tại giải phóng khóa trước khi truy cập bất kỳ phương thức synchronized nào.

- LOCK

-- Lock trong JAVA là 1 Interface.

-- Lock được dùng để giải quyết vấn đề của synchronized.

-- Lock cung cấp một cơ chế khóa linh hoạt hơn, cho phép kiểm soát chính xác khi nào khóa được cấp, được nhả,
và hỗ trợ một số tính năng mà synchronized không có:

+) Với synchronized, khóa được cấp và giải phóng tự động khi thread vào và thoát khỏi khối mã.

+) Ngược lại, Lock yêu cầu bạn phải khóa thủ công bằng cách gọi lock() và giải phóng khóa bằng cách gọi unlock().
Điều này cho phép kiểm soát chính xác thời điểm chiếm và nhả khóa.

- ATOMIC

-- Atomic classes trong Java là các lớp cung cấp các thao tác nguyên tử (atomic operations) trên các giá trị đơn lẻ như số nguyên (int),
số thực (long), boolean, hoặc các tham chiếu đối tượng. Những thao tác này là nguyên tử vì chúng đảm bảo rằng các hành động sẽ diễn ra một cách toàn vẹn,
không bị can thiệp bởi các luồng khác, mà không cần sử dụng khóa (lock) để điều phối luồng.

- COPY ON WRITE

-- CopyOnWriteArrayList là một lớp trong Java Collection Framework được thiết kế đặc biệt để hỗ trợ các hoạt động đọc (truy xuất dữ liệu)
với hiệu suất cao trong môi trường đa luồng. Nó thực hiện điều này bằng cách đảm bảo rằng các thao tác đọc không cần khóa và chỉ sử dụng
khóa khi có các thao tác ghi (thêm, sửa, xóa).

-- Hoạt động ghi (thêm, sửa, xóa): Khi thực hiện một thao tác ghi, CopyOnWriteArrayList sẽ:

+) Sử dụng ReentrantLock để khóa danh sách nhằm đảm bảo tính an toàn trong môi trường đa luồng.

+) Tạo một bản sao mới của mảng cơ bản (mảng lưu trữ dữ liệu danh sách).

+) Thực hiện thao tác ghi trên bản sao mới đó.

+) Cập nhật tham chiếu của mảng sang bản sao mới thông qua phương thức setArray().

+) Điều này có nghĩa là các thao tác ghi sẽ không thay đổi ngay mảng cơ bản mà tạo ra một bản sao mới.
Sau khi ghi xong, tham chiếu mảng sẽ trỏ tới mảng mới này. Các thao tác đọc thực hiện trước khi gọi setArray()
sẽ thấy dữ liệu cũ.

- EXECUTOR SERVICE

-- Bên trong ThreadPool, các task sẽ được chèn vào trong một Blocking Queue. Blocking Queue có thể hiểu là nơi chứa các task
mà các Thread sẽ lấy chúng ra và thực thi lần lượt. Mỗi khi có một task mới được thêm vào Queue và sau đó sẽ chỉ có một Thread đang
không phải thực hiện một task nào vào Queue lấy task đó ra, còn các Thread còn lại phải chờ đợi cho đến khi Thread đó lấy task ra thành công.

-- Kể từ Java 5 trở đi, ThreadPool đã được xây dựng sẵn trong gói java.util.concurrent, vì vậy chúng ta không cần phải tạo một ThreadPool
mà thay vào đó chúng ta sẽ sử dụng các lớp có sẵn của gói này. Java cung cấp cho chúng ta lớp Executor, interface của lớp Executor là
ExecutorService. Interface ExecutorService đại diện cho cơ chế thực thi bất đồng bộ có khả năng thực thi các nhiệm vụ trong background.
ExecutorService là một đối tượng chịu trách nhiệm quản lý các luồng và thực hiện các tác vụ Runnable được yêu cầu xử lý. Nó tách riêng các
chi tiết của việc tạo Thread, lập kế hoạch (scheduling), … để chúng ta có thể tập trung phát triển logic của tác vụ mà không quan tâm
đến các chi tiết quản lý Thread.

-- Khi sử dụng ExecutorService, bạn tạo một ThreadPool - tập hợp các thread có sẵn để xử lý nhiệm vụ. Khi một thread hoàn thành nhiệm vụ của nó,
thread đó có thể được tái sử dụng cho nhiệm vụ mới, thay vì tạo mới một thread. Điều này giúp tiết kiệm tài nguyên,
đặc biệt là khi cần xử lý nhiều tác vụ nhỏ hoặc ngắn.

-- Cách tạo ExecutorService instance:

+) Single Thread Executor : Trong ThreadPool chỉ có 1 Thread và các task sẽ được sử lý một cách tuần tự. Tên method “newSingleThreadExecutor()”.

+) Fixed Thread Pool : Trong ThreadPool sẽ được cố định (fixed) số lượng các Thread. Nếu một task mới được đưa vào mà các thread đều đang
“bận rộn” thì task đó sẽ được gửi vào Blocking Queue và ngay sau khi một Thread đã thực thi xong nhiệm vụ của nó thì nhiệm vụ đang ở
trong Queue đó sẽ được push ra khỏi Queue và được Thread đó xử lý tiếp. Method “newFixedThreadPool()”

-- Phương thức ExecutorService.submit(Callable) tương tự như ExecutorService.submit(Runnable) ngoại trừ việc hàm call() của nó cần 1 giá trị trả về để
xác định kết quả thu được sau khi hòan thành nhiệm vụ còn phương thức Runnable.run() không thể trả lại kết quả.
Kết quả của Callable có thể thu được thông qua đối tượng Future được trả về bởi phương thức submit(Callable).

-- Sử dụng phương thức get() của đối tượng Future được trả về từ ExecutorService.submit() để thu được kết quả. Chú ý phương thức này được thực
thi đồng bộ (Asynchronous - tức là sau khi call() của Callable hoàn thành nhiệm vụ kết quả được trả về thì nó mới được thực thi).

-- Phương thức get() là blocking nên nó sẽ block luôn cả main thread.

-- Phương thức ExecutorService.invokeAll(Collection<?> extends Callable<T> tasks) Phương thức invokeAll() gọi tất cả đối tượng Callable
bạn add vào trong Collection. Phương thức này trả về 1 List các đối tượng Future (list of Future) mà được trả về từ việc thực thi các Callables.

-- Phương thức invokeAll() là một phương thức blocking, nghĩa là nó sẽ chặn luồng hiện tại (bao gồm cả main thread nếu được gọi từ đó)
cho đến khi tất cả các tác vụ trong Collection hoàn thành. Điều này có nghĩa là invokeAll() sẽ không trả về cho đến khi tất cả các
Callable trong Collection được thực thi xong.

-- Phương thức invokeAny(Collection<?> extends Callable<T> tasks) Phương thức invokeAny() nhận một tập hợp (collection)
của các đối tượng Callable hoặc các lớp được kế thừa từ Callable chúng. Gọi phương thức này không trả về một Future,
nhưng trả về kết quả của một trong những đối tượng Callables. Bạn không đảm bảo về kết quả nào bạn sẽ nhận được từ callable.
Chỉ cần một trong số chúng hoàn thành (Tức là ko cần tất cả các thread hoàn thành, chỉ cần 1 task hoàn thành phương thức get()
sẽ nhận được kết quả.

- FUTURE

-- Future là 1 class trong Java:

-- Future đại diện cho kết quả của một tác vụ sẽ hoàn thành trong tương lai.

-- Được sử dụng cùng với ExecutorService khi submit() một tác vụ không đồng bộ.

-- Phương thức chính là get(), cho phép lấy kết quả khi tác vụ hoàn tất (hoặc chờ đợi đến khi hoàn tất).

-- Hạn chế: Future không có phương thức tích hợp để xử lý chaining (chuỗi tác vụ) hoặc callback (hàm gọi lại) khi tác vụ hoàn thành.

- STATIC

-- Biến static (static variables):

+) Biến static thuộc về lớp chứ không phải thuộc về từng đối tượng cụ thể.

+) Chỉ có một bản sao duy nhất của biến static được tạo ra trong bộ nhớ, bất kể có bao nhiêu đối tượng của lớp đó được tạo ra.

+) Biến static có thể được sử dụng làm thuộc tính chung, để làm dữ liệu chung cho tất cả objects (hoặc instances)
của lớp đó và điều đó giúp cho chương trình tiết kiệm bộ nhớ hơn.

-- Phương thức static (static methods):

+) Một phương thức static thuộc lớp chứ không phải đối tượng của lớp.

+) Một phương thức static có thể được gọi mà không cần tạo khởi tạo (instance) của một lớp.

+) Phương thức static có thể truy cập biến static và có thể thay đổi giá trị của nó.

+) Một phương thức static chỉ có thể gọi một phương thức static khác, không thể gọi được một phương thức non-static.

+) Một phương thức static không thể được sử dụng từ khóa this và super.

+) Người dùng không thể override (đè) phương thức static trong Java.

-- Lớp static (static class):

+) Trong Java, một lớp static phải là lớp lồng nhau (nested class) bên trong một lớp không phải static khác,
tức là nó không thể tồn tại độc lập như một lớp riêng biệt.

+) Một nested class được khai báo với từ khóa static gọi là nested static class.

+) Khác với các lớp thông thường, một nested static class có thể được truy cập mà không cần tạo một đối tượng của outer class
(lớp bên ngoài).

+) Lớp này hoạt động độc lập với thể hiện của lớp bên ngoài, nghĩa là nó không thể truy cập trực tiếp vào các thành viên non-static
của lớp bên ngoài (như biến hoặc phương thức non-static)....

-- Import static:

+) Java cho phép import các thành viên tĩnh (static member) và static method của một class hoặc package vào một class khác
với từ khóa import static.

- EXCEPTION

-- Trong JAVA, Exception là 1 class mà extends class Throwable.

-- Exception là những lỗi xảy ra trong quá trình chạy chương trình (runtime). Exception thường được sử dụng để chỉ các
tình huống bất thường mà chương trình gặp phải và cần xử lý.

-- Khi một Exception xảy ra trong Java và nó không được handle (xử lý) bởi bất kỳ khối try-catch nào, luồng thực thi sẽ bị gián đoạn,
và tất cả các dòng mã sau điểm xảy ra Exception sẽ không được thực hiện.

-- Stack trace là một biểu diễn của call stack tại thời điểm mà Exception xảy ra, cho thấy trình tự các phương thức đã được gọi
trước khi đến vị trí gây ra lỗi. Mỗi phần tử trong stack trace đại diện cho một lời gọi phương thức, bắt đầu từ phương thức gốc
(ở cuối stack trace) cho đến phương thức nơi Exception được ném ra (ở đầu stack trace).

-- Trong Java, khối finally được thiết kế để luôn thực thi sau khối try hoặc catch, bất kể có Exception xảy ra hay không,
hoặc thậm chí khi có câu lệnh return trong khối try hoặc catch. Trường hợp duy nhất mà khối finally không được thực thi là
khi nó gặp phương thức System.exit() ở bất kỳ đâu trong khối try/catch.

-- Các loại Exception trong JAVA:

+) Checked Exception: Các lớp kế thừa trực tiếp Throwable class ngoại trừ RuntimeException và Error được gọi là checked exception,
ví dụ: IOException, SQLException,... Các checked exception được kiểm tra tại thời điểm biên dịch.
Throwable -> Exception -> InterruptedException.

+) Unchecked Exception: Các lớp kế thừa RuntimeException được gọi là unchecked exception, ví dụ: ArithmeticException,
NullPointerException, ArrayIndexOutOfBoundsException, ... Các unchecked exception không được kiểm tra tại thời điểm biên dịch,
nhưng chúng được kiểm tra trong thời gian chạy (runtime).
Throwable -> Exception -> RuntimeException.

+) Error: Là các lỗi nghiêm trọng xảy ra trong hệ thống, và chúng thường là các vấn đề nằm ngoài tầm kiểm soát của ứng dụng,
ví dụ: OutOfMemoryError, VirtualMachineError, AssertionError, v.v.
Throwable -> Error.

- ACCESS MODIFIER

-- Có hai loại modifier trong java: access modifiers và non-access modifiers.

-- Các access modifiers trong java xác định độ truy cập (Phạm vi) vào dữ liệu của của các trường (field),
phương thức (method), cấu tử (constructor) hoặc lớp (class).

-- Và có một vài non-access modifiers chẳng hạn static, abstract, synchronized, native, volatile, transient, v.v..

-- PUBLIC:

+) Phạm vi truy cập: Bất kỳ đâu trong chương trình, kể cả từ các package khác.

+) Sử dụng cho: Lớp, phương thức, biến.

-- PROTECTED:

+) Phạm vi truy cập: Trong cùng một package hoặc các lớp con (subclass) kể cả khi chúng ở package khác.

+) Sử dụng cho: Phương thức và biến (không dùng cho lớp ngoài cùng).

-- DEFAULT (hay còn gọi là package-private):

+) Phạm vi truy cập: Trong cùng một package.

+) Sử dụng cho: Lớp, phương thức, biến.

+) Ý nghĩa: Khi không có modifier nào được khai báo, Java sẽ coi đó là phạm vi default.

-- PRIVATE:

+) Phạm vi truy cập: Chỉ trong lớp khai báo.

+) Sử dụng cho: Phương thức và biến (không dùng cho lớp ngoài cùng).

- UNMANAGED và MANAGED RESOURCES

-- Interface AutoCloseable -> Interface Closeable -> Unmanaged Resources.

-- Managed Resources và Unmanaged Resources trong Java:

+) Managed Resources trong Java thường được coi là các đối tượng mà Java Virtual Machine (JVM) và Garbage Collector (GC) quản lý,
như các đối tượng tiêu chuẩn của Java (chuỗi, danh sách, v.v.). Garbage Collector sẽ tự động thu hồi các đối tượng này khỏi bộ nhớ
khi chúng không còn được tham chiếu.

+) Unmanaged Resources trong Java bao gồm các tài nguyên hệ thống như luồng I/O, kết nối cơ sở dữ liệu, kết nối mạng, file handles,
và các tài nguyên khác không tự động được giải phóng bởi GC. Vì Garbage Collector không biết cách xử lý các tài nguyên này,
lập trình viên phải giải phóng chúng một cách thủ công, thường là bằng cách gọi phương thức close() hoặc sử dụng cú pháp try-with-resources để đảm bảo chúng được giải phóng ngay cả khi có lỗi xảy ra.

- ANONYMOUS CLASS

-- Trong Java, lớp ẩn danh là một loại lớp nội mà không có tên, được khai báo và khởi tạo trong một dòng mã.
Lớp này thường được sử dụng để mở rộng một lớp hoặc triển khai một interface với hành vi cụ thể mà không cần
tạo ra một lớp riêng biệt. Lớp ẩn danh thường rất hữu ích khi bạn chỉ cần một lần triển khai đơn giản.

- ENUM

-- Trong Java, enum thực chất là một tập hợp các đối tượng (object) đại diện cho các hằng số của kiểu enum.
Mỗi hằng số trong enum là một thể hiện (instance) duy nhất của lớp enum, vì thế chúng đều là các đối tượng với các
thuộc tính và phương thức riêng.

-- Các đặc điểm quan trọng của enum trong Java:

+) Mỗi hằng số là một đối tượng: Khi khai báo một enum với các hằng số, Java tự động tạo ra các đối tượng duy nhất
cho mỗi hằng số đó. Các đối tượng này là singleton (chỉ có một thể hiện duy nhất trong toàn bộ ứng dụng).

+) Có thể có phương thức và thuộc tính: enum không chỉ là tập hợp các giá trị tĩnh. Bạn có thể khai báo các thuộc tính
và phương thức trong enum để cung cấp thêm thông tin hoặc hành vi cho từng hằng số.

+) Có thể sử dụng các constructor: Mặc dù các constructor trong enum phải là private hoặc package-private, bạn vẫn có thể tạo constructor
để khởi tạo các thuộc tính của từng đối tượng enum.

- MODULARIZATION

-- Được giới thiệu từ Java 9 trở đi với hệ thống module (Java Platform Module System - JPMS).

-- Một module là một nhóm các package và tài nguyên, được tổ chức và đóng gói để cung cấp một API cụ thể
cho các module khác và có thể kiểm soát quyền truy cập vào các thành phần bên trong.

-- Module thường có một tệp module-info.java ở gốc của nó, dùng để định nghĩa tên module và những gì
mà module xuất ra (exports) hoặc yêu cầu từ các module khác (requires).

-- requires:

+) Khi bạn sử dụng requires, module hiện tại sẽ phụ thuộc vào module được chỉ định, nhưng sự phụ thuộc này không
được chuyển tiếp cho các module khác.

+) Chỉ module hiện tại mới có thể trực tiếp truy cập các API của module được yêu cầu.

-- requires transitive:

+) requires transitive không chỉ cho phép module hiện tại truy cập vào module phụ thuộc mà còn cho phép tất cả các module
khác phụ thuộc vào module hiện tại truy cập module phụ thuộc đó.

+) B phụ thuộc C, A phụ thuộc B, suy ra A có thể truy cập vào C.

- YIELD

-- RETURN trong Java được dùng để thoát ra khỏi phương thức hiện tại và trả về một giá trị cho người gọi phương thức.

-- YIELD trong Switch Expression có chức năng trả về giá trị cho chính biểu thức switch, không phải thoát ra khỏi
phương thức. yield cho phép biểu thức switch tiếp tục hoạt động như một khối lệnh trả về giá trị mà không ảnh hưởng
đến luồng điều khiển của phương thức.

- JAVA VERSIONS

-- JAVA 5.0: Enhanced for loop, Generics, Enum, Autoboxing.

-- JAVA 8: Functional Programming, Lambda và Streams, Static Method trong Interface.

-- JAVA 9: Modularization.

-- JAVA 14: Switch Expression.
