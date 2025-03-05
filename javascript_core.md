- JS là 1 ngôn ngữ thông dịch

- BABEL

-- Babel.js là một công cụ JavaScript phổ biến được sử dụng chủ yếu cho việc
biên dịch (transpile) mã nguồn JavaScript hiện đại thành mã nguồn tương thích
với các trình duyệt hoặc môi trường không hỗ trợ các tính năng mới của JavaScript.

-- Biên dịch mã ES6+ thành ES5.

-- Hỗ trợ JSX. Babel chuyển đổi code JSX thành JavaScript thuần để trình
duyệt hiểu được. Sau đó, JavaScript Engine (như V8/NodeJs): Biên dịch và
thực thi mã JavaScript thành ngôn ngữ máy tại runtime.

- HOISTING

-- HOISTING là một khái niệm trong JavaScript, mô tả cách mà trình biên dịch
JavaScript "đưa" phần khai báo của các biến, hàm, hoặc lớp lên đầu phạm vi
của chúng (scope) trước khi thực thi mã.

-- Tuy nhiên, HOISTING không thực sự "di chuyển" mã nguồn lên đầu. Nó chỉ là cách
JavaScript xử lý các khai báo trong quá trình biên dịch trước khi chạy chương trình.

- CONST, LET, VAR

-- biến CONST không thể gán lại giá trị sau khi đã khai báo (bắt buộc phải gán giá trị
lúc khai báo). Tính bất biến của biến CONST giống như FINAL trong java.

-- biến LET thì có thể thể gán lại giá trị sau khi đã khai báo.

-- biến VAR giống biến LET nhưng hỗ trợ cơ chế HOISTING.

- TRONG JS CÓ 7 LOẠI GIÁ TRỊ NGUYÊN THỦY

-- Number, String, Boolean, Undefined, Null, Symbol(ES2015), BigInt

- UNDEFINED và NULL

-- UNDEFINED là khi khai báo biến mà chưa gán giá trị.

-- UNDEFINED là kiểu giá trị nguyên thủy.

-- NULL là giá trị đã gán -> đại diện cho 1 ô nhớ chưa khởi tạo trong HEAP.

- FALSY và TRUTHY

-- FALSY VALUES bao gồm : "", 0, undefined, null, NaN.

-- FALSY VALUES trong điều kiện sẽ luôn tự ép kiểu trả về FALSE.

- TYPE COERCION

-- Type coercion là quá trình JavaScript tự động chuyển đổi kiểu dữ liệu của
một giá trị thành kiểu khác để thực hiện một phép toán hoặc so sánh.

-- Type Coercion (Ép kiểu tự động) trong JavaScript không thay đổi giá trị gốc,
mà chỉ chuyển đổi kiểu dữ liệu tạm thời trong quá trình tính toán.

-- Type Coercion (Ép kiểu tự động) trong JavaScript chỉ chuyển đổi giá trị
sang Boolean, String, hoặc Number, tùy vào ngữ cảnh sử dụng.

-- Toán tử + luôn tự ép kiểu thành String với String(value).

- TOÁN TỬ == và ===

-- TOÁN TỬ == so sánh theo giá trị, nó sẽ tự động convert 2 vế thành cùng 1
kiểu data type.

-- TOÁN TỬ === so sánh theo giá trị và kiểu dữ liệu
(typeof(value1) == typeof(value2)).

- STATEMENT VÀ EXPRESSION

- Bất cứ đoạn code nào trả về một giá trị đều là một Expression.

- Statement (Câu lệnh) là một đoạn code thực thi nhưng không nhất thiết
  phải trả về 1 giá trị.

- FUNCTION

-- FUNCTION có cơ chế HOISTING.

-- Nếu không return thì FUNCTION sẽ trả về undefined.

-- Nếu FUNCTION có khai báo tham số mà ta không truyền đối số vào thì giá trị tham số
đó sẽ là undefined. Có thể truyền FUNCTION vào 1 FUNCTION với tư cách là tham số.

-- ANONYMOUS FUNCTION không có cơ chế HOISTING.

-- ARROW FUNCTION chỉ là 1 cách viết ngắn gọn của ANONYMOUS FUNCTION.

-- ARROW FUNCTION là một Expression Function vì nó tạo ra một giá trị và
có thể gán vào biến.

-- Không giống FUNCTION DECLARATION, ARROW FUNCTION không thể đứng một mình
như một câu lệnh (Statement).

-- ARROW FUNCTION không thể sử dụng từ khóa this.

- ARRAY BUILT-IN FUNCTIONS

-- push: thêm phần tử vào cuối mảng, trả về độ dài mảng mới

-- unshift: thêm phần tử vào đầu mảng, trả về độ dài mảng mới

-- pop: xóa phần tử ở cuối mảng, trả về phần tử đã xóa.

-- shift: xóa phần tử ở đầu mảng, trả về phần tử đã xóa.

-- indexOf: tìm index của 1 phần tử trong mảng, trả về -1 nếu
trong mảng ko có phần tử đó.

-- includes: xác định xem phần tử có ở trong mảng ko, trả về true
hoặc false (includes so sánh cả giá trị lẫn kiểu dữ liệu).

- DOM LÀ GÌ

-- DOM viết tắt của Document Object Model.

-- DOM là 1 model dưới dạng cây, nó thị đầy đủ mối quan hệ, thuộc tính và nội dung
của trang HTML mà trình duyệt nhận được. Document trỏ tới trang html hoặc xml
được thể hiện như một đối tượng.

-- HTML DOM sẽ cho phép Javascipt chỉnh sửa nội dung của các elements trong trang HTML
bằng Javascript thông qua DOM interface - document.

- SCOPE

-- SCOPE là phạm vi truy cập của 1 biến.

-- Biến VAR luôn luôn là 1 GLOBAL SCOPE vì cơ chế HOISTING.

- CLOSURE

-- CLOSURE cho phép một FUNCTION bên trong có thể truy cập các biến
của FUNCTION bên ngoài ngay cả khi FUNCTION bên ngoài đã hoàn tất thực thi.
