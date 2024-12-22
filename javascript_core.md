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

-- biến CONST không thể gán lại giá trị sau khi đã khai báo.

-- biến LET thì có thể thể gán lại giá trị sau khi đã khai báo.

-- biến VAR giống biến LET nhưng hỗ trợ cơ chế HOISTING.

- UNDEFINED và NULL

-- UNDEFINED là khi khai báo biến mà chưa gán giá trị.

-- UNDEFINED là kiểu giá trị nguyên thủy.

-- NULL là giá trị đã gán -> đại diện cho 1 ô nhớ chưa khởi tạo trong HEAP.

- FALSY và TRUTHY

-- FALSY VALUES bao gồm : "", 0, false, undefined, null, NaN.

-- FALSY VALUES trong điều kiện sẽ luôn trả về FALSE.

- TYPE COERCION

-- Type coercion là quá trình JavaScript tự động chuyển đổi kiểu dữ liệu của
một giá trị thành kiểu khác để thực hiện một phép toán hoặc so sánh.

-- Toán tử + luôn tự ép kiểu thành String với String(value).

- TOÁN TỬ == và ===

-- TOÁN TỬ == so sánh theo giá trị, nó sẽ tự động convert 2 vế thành cùng 1
kiểu data type.

-- TOÁN TỬ === so sánh theo giá trị và kiểu dữ liệu
(typeof(value1) == typeof(value2)).

- FUNCTION

-- FUNCTION có cơ chế HOISTING.

-- Nếu không return thì FUNCTION sẽ trả về undefined.

-- Nếu FUNCTION có khai báo tham số mà ta không truyền đối số vào thì giá trị tham số
đó sẽ là undefined. Có thể truyền FUNCTION vào 1 FUNCTION với tư cách là tham số.

-- FUNCTION có thể lưu vào 1 biến.

-- ANONYMOUS FUNCTION không có cơ chế HOISTING.
