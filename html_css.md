-- HTML viết tắt của HypherText Markup Language. Ngôn ngữ đánh dấu siêu văn bản.

-- Cách tính năng mới của HTML5:

+) Semantic element: là những phần tử mô tả rõ ràng ý nghĩa về cấu trúc của phần tử đó đối
với các trình duyệt và lập trình viên. Nói một cách dễ hiểu hơn có nghĩa là chỉ cần đọc
tên các element này là chúng ta có thể hiểu được nội dung bên trong element này nói về cái gì.

-- <ol>: ordered list --> Mỗi phần tử <li> bên trong sẽ được đánh số 1, 2, 3,... theo thứ tự.
-- <ul>: unordered list --> Mỗi phần tử <li> sẽ được đánh dấu bằng chấm đen (•) theo mặc định.

-- <a>: anchor element --> Có 2 loại link: link với page khác trong cùng project, link tới một trang khác.

-- thuộc tính target trong <a>

+) \_self (mặc định) – Mở liên kết trong cùng tab hoặc cửa sổ hiện tại.

+) \_blank – Mở liên kết sang tab mới.

-- CSS viết tắt của Cascading Style Sheet.

-- Có 3 cách để viết CSS: Inline, Internal và External.

+) Inline --> Viết trực tiếp trong thuộc tính style của thẻ HTML. Chỉ áp dụng cho phần tử đó.
+) Internal: --> Viết trong thẻ <style> bên trong <head>. Dùng khi chỉ cần CSS cho một trang duy nhất.
+) External: --> Viết trong file .css riêng, rồi liên kết bằng <link>. Giúp quản lý code tốt hơn, áp dụng
được cho nhiều trang.

-- Table Element

- Ý nghĩa các thẻ:
  +) <table></table>: Xác định một bảng
  +) <thead></thead>: Phần đầu của bảng
  +) <tbody></tbody>: Phần thân của bảng
  +) <tr></tr> (table row): Xác định một hàng của bảng
  +) <th></th> (table header): Xác định tiêu đề của bảng
  +) <td></td> (table data): Xác định dữ liệu ô của bảng

- Thuộc tính:
  +) colspan: tạo ô mở rộng trên nhiều cột
  +) rowspan: tạo ô kéo dài trên nhiều hàng

-- Block, Inline, Inline-Block

+) Block: Luôn luôn bắt đầu trên một dòng mới, chiếm 100% width của cha. Padding và Margin áp dụng cho 4 phía.
+) Inline: Chiếm đủ width của content, không set width và height được. Padding và Margin
không thể set theo chìu dọc. pseudo element là 1 inline element.
+) Inline-Block: Giống như Inline nhưng set được height và width. img là 1 inline-block element.

-- FLEX BOX

- justify-content: trục chính

- align-items: trục phụ

- flex-grow: giá trị mặc định là 0, dùng để cho phép các phần tử giãn ra để chiếm các
  empty space còn lại. Nếu phần tử A có flex-grow: 1 còn phần tử B có flex-grow: 2 thì sẽ khoảng
  empty space mà B được chiếm sẽ gấp đôi A chứ không phải B sẽ bự gấp 2 lần A.

- flex-basis: giá trị mặc định là auto, đùng để set chiều rộng hoặc chiều cao của phần tử dựa vào
  flex-direction row hay column.

- flex-shrink: giá trị mặc định là 1, đùng để cho phép các phần tử tự động thu hẹp lại
  để phù hợp với flex container.

- flex: cả 3 properties flex-grow, flex-shrink và flex-basis đều dùng cho flex items con. Và flex
  là property shorthand của cả 3.

-- GRID

- Căn chỉnh các tracks bên trong grid containers --> Dùng justify-content, align-content.

- Căn chỉnh các grid items bên trong các grid cells chứa nó --> Dùng justify-items, align-items.

- Căn chỉnh 1 grid item trong grid cell chứa nó --> Dùng align-self, justify-self.

- Muốn element bắt đầu ở dòng hoặc cột cụ thể nào đó trong lưới --> Dùng grid-column, grid-row.

-- CSS SELECTOR

- [elementA] [elementB]: select tất cả elementB bên trong elementA.

- [classA][classB]: select phần tử có cả classA và classB đồng thời.

- [elementA] + [elementB]: select elementB đầu tiên bên trong elementA.

- id và class:

-- ĐỘ ƯU TIÊN SELECTOR

- !important -> ID [#] -> Class [.] hoặc pseudo class [:] -> element -> universal [*].

+) Trong CSS, một id chỉ nên được sử dụng cho một phần tử duy nhất trong một file HTML.

-- COLOR

- Mọi màu đều có thể tạo ra nhờ sự kết hợp giữa 3 màu Red, Green, Blue.

- RGB/RGBA: rgba(red, green, blue, alpha).
  +) red, green, blue: Giá trị màu (từ 0 đến 255).
  +) alpha: Độ trong suốt (từ 0 đến 1), trong đó

- HEXADECIMAL NOTATION: Trong CSS, màu sắc có thể được biểu diễn bằng hệ thập lục phân (hexadecimal notation)
  với ký hiệu #RRGGBB, trong đó:
  +) RR (Red) là giá trị màu đỏ (từ 00 đến FF).
  +) GG (Green) là giá trị màu xanh lá cây (từ 00 đến FF).
  +) BB (Blue) là giá trị màu xanh dương (từ 00 đến FF).

-- CSS POSITION

- static: mặc định. absolute ko coi static là cha.

- relative: theo vị trí ban đầu của nó.

- absolute: theo vị trí của cha nó. absolute luôn đi tìm relative gần nhất. Một absolute element không
  chiếm diện tích trong dòng chảy bình thường của trang web.

- fixed: đi theo viewport.

- sticky: kết hợp giữa relative và fixed.

+) Có thể dùng left, right, top, bottom với bất kỳ phần tử nào có position khác static.

-- BOX SHADOW

- box-shadow: none|h-offset v-offset blur spread color |inset|initial|inherit;

+) none: Giá trị default: là không có shadow

+) h-offset: Điều chỉnh khoảng cách shadow theo chiều ngang. Giá trị dương cho shadow đổ bóng về bên phải
(bóng hiển thị ở bên phải), giá trị âm đổ bóng về bên trái (bóng đổ về bên trái)

+) v-offset: Điều chỉnh khoảng cách shadow theo chiều dọc. Giá trị dương cho shadow đổ bóng xuống dưới
(bóng xuất hiện ở dưới hình), giá trị âm cho shadow đổ bóng lên phía trên (bóng xuất hiện phía trên hình)

+) blur - không bắt buộc: Độ 'blur' - độ mờ của bóng. Giá trị càng lớn thì bóng càng mờ đi. Giá trị càng
nhỏ càng 'solid'

+) spread - không bắt buộc: Độ phân tán của shadow. Giá trị dương sẽ làm shadow rộng ra, giá trị âm sẽ thu nhỏ
kích cỡ shadow

+) color: màu của shadow. Mặc định là màu font-color hiện tại

+) inset - không bắt buộc: thay đổi shadow ngoài thành shadow nằm trong hình
(giống như mình nhìn đèn trần thạch cao ấy 😃)

- text-shadow: offset-x | offset-y | blur-radius | color

-- BOX MODEL

- Box Model là thứ mà browser dựa vào để tính toán một element rộng/cao bao nhiêu để render cho chính xác
  và đúng ý của developer.

- Kỹ thuật Box Model trong CSS bao gồm 4 phần quan trọng đó là:

+) Margin: Khoảng cách tính từ bên ngoài của phần tử.
+) Border: Đường viền của phần tử.
+) Padding: Khoảng cách tính từ bên trong của phần tử.
+) Content: Nội dung trong phần tử.

-- % trong CSS

- Khi dùng % cho kích thước (width, height, top, left, right, bottom, padding, margin, v.v.), giá trị sẽ
  dựa vào phần tử cha gần nhất có thuộc tính liên quan.

- Khi % áp dụng cho thuộc tính liên quan đến chữ (line-height, font-size), nó sẽ dựa vào chính kích thước
  của phần tử đó.

-- REM trong CSS

- REM trong CSS được viết gọn lại của root em. Nó có nghĩa là "The root element's font-size",
  hiểu đơn giản REM trong CSS sẽ được tính toán dựa trên font-size của html(root).

- Nếu chúng ta không set cho HTML root một giá trị font-size, giá trị mặc định của font-size khi đó sẽ là 16px.
  Do đó, khi phần tử sử dụng đơn vị REM, phần tử này sẽ tìm để phần tử root xem giá trị font-size là bao nhiêu
  để tính toán và set giá trị.

- Nên dùng % thay vì fixed pixel khi set font-size cho html element vì nếu người dùng thay đổi cài đặt mặc định
  trong trình duyệt (ví dụ: font-size mặc định là 18px thay vì 16px), thì layout vẫn co giãn theo đúng tỷ lệ.

-- So sánh normalize và reset CSS

- reset CSS là set các giá trị như margin, padding, font-size về 0, Cũng list-style: none, ...
- normalize cũng như reset CSS nhưng không hoàn toàn loại bỏ các giá trị default mà thay vào đó chuẩn hóa
  lại các giá trị đó sao cho phù hợp với nhu cầu.
