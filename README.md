# C_basic-Task01-readme.md
1.Markdown Là Gì
Markdown là ngôn ngữ đánh dấu văn bản được tạo ra bởi John Gruber. Markdown sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản và văn bản được viết bằng Markdown sẽ có thể được chuyển đổi sang HTML. Ngược lại các văn bản được viết bằng HTML cũng có thể được chuyển đổi sang Markdown
2.Tác dụng


Các Cú Pháp Cơ Bản

Markdown được thiết kế với ý định rõ ràng để có thể đọc dễ dàng. Bạn có thể thấy rằng hầu hết các cú pháp khác đơn giản và trực quan.

Markdown help
Tạo Tiêu Đề

# Tiêu đề 1 (h1)
## Tiêu đề 2 (h2)
### Tiêu đề 3 (h3)

<h3>Thẻ H3</h3>
Khi viết bằng ngôn ngữ Markdown sẽ như sau:

### Thẻ H3
Để đánh dấu văn bản với thẻ in đậm <strong> và in nghiêng <em> trong HTML, khi chuyển sang Markdown chúng ta sử dụng lần lượt cặp dấu và cặp dấu ****. Ví dụ đoạn mã HTML sau:*nghiêng* hoặc _nghiêng_ là nghiêng
**đậm** hoặc __đậm__ là đậm
[tên link](đường dẫn) là link
![tên ảnh](link đến ảnh) giống link nhưng cho ảnh
# Chương 1, ## Mục 1, ### Mục 1.1
Tạo list:

List gạch đầu dòng:
- Lorem ipsum
- Dolo sit amet
- Consecteur...

List đánh số:
1. Lorem ipsum
2. Dolo sit amet
3. Consecteur..


Chữ <strong>in đậm</strong> và chữ <em>in nghiêng</em>
Sẽ tương đương với:

Chữ **in đậm** và chữ *in nghiêng*
Để dánh dấu 1 danh sách không có thứ tự (unorder list) chúng ta sử dụng dấu - hoặc + hoặc ***** trước mỗi dòng. Ví dụ một danh sách trong HTML như sau:

<ul>
<li>Xe đạp</li>
<li>Xe hơi</li>
<li>Xe gắn máy</li>
</ul>
Tạo Điểm Nhấn (highlight)

==text==
Inline Code

`inline code`
Tạo chú thích cuối trang

Chú thích[^1] chú thích[^2].  

- [^1]: chú thích 1 
- [^2]: chú thích 2
