# C_basic-Task01-readme.md
Markdown Là Gì?

Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác sử dụng một công cụ cùng tên. Nó thường được dùng để tạo các tập tin readme, viết tin nhắn trên các diễn đàn, và tạo văn bản có định dạng bằng một trình biên tập văn bản thô.
Năm 2004, cùng với sự giúp đỡ của Aaron Swartz, John Gruber đã tạo ra ngôn ngữ Markdown với mục tiêu tạo ra một định dạng văn bản thô dễ viết, dễ đọc, dễ dàng chuyển thành HTML hoặc XHTML.

Tính Năng

Markdown dùng các dấu hiệu từ các quy ước cho văn bản thô trong email, như setext - một ngôn ngữ được thiết kế để có thể đọc bình thường mà không phải lục lọi giữa các thẻ định dạng, khác với văn bản trong ngôn ngữ đánh dấu như RTF hay HTML, vốn chứa nhiều thẻ và cú pháp khó đọc.
Gruber đã viết một công cụ nhỏ bằng Perl, Markdown.pl, cho phép chuyển đổi đoạn văn bản đã đánh dấu theo chuẩn Markdown sang XHTML hoặc HTML. Tiện ích này có thể dùng một mình, hoặc dùng như là plugin cho Bloxom hoặc Movable Type, hoặc là một bộ lọc cho BBEdit.
Markdown sau đó đã được hoàn thiện thành một module Perl và công bố trên CPAN (Text::Markdown) cũng như trên một vài ngôn ngữ khác. Nó được phân phối theo giấy phép BSD và được nhúng sẵn, hoặc là plugin của một hệ thống quản lý nội dung. Một số trang web như GitHub, reddit, Diaspora, Stack Exchange, OpenStreetMap, SourceForge cũng sử dụng các biến thể của Markdown trong hệ thống của mình.

Các Cú Pháp Cơ Bản

Markdown được thiết kế với ý định rõ ràng để có thể đọc dễ dàng. Bạn có thể thấy rằng hầu hết các cú pháp khác đơn giản và trực quan.

Markdown help
Tạo Tiêu Đề

# Tiêu đề 1 (h1)
## Tiêu đề 2 (h2)
### Tiêu đề 3 (h3)
Để tạo tiêu đề trong Markdown bạn chỉ cần chèn ký tự # ngay phía trước. Số lượng ký tự # sẽ xác định độ sâu của tiêu đề (tương đương h1-h6 trong mã HTML).

Định Dạng Chữ

**In đậm** hoặc __In đậm__ (<b>)
*In nghiêng* hoặc _In nghiêng_ (<i>)
~~Chữ gạch ngang~~ (<strike> or <del> or <s>)

Phân đoạn một đoạn văn bản bằng cách chèn một dòng trắng ở giữa các đoạn văn bản.

Xuống dòng bằng cách thêm 2 khoảng trắng ngay phía sau dòng văn bản.


Tạo Danh Sách

Tạo danh sách dạng số:

1. danh sách 1
2. danh sách 2
3. danh sách 3


Tạo danh sách dạng bullet:

- danh sách 1
- danh sách 2
- danh sách 3
Tạo Liên kết

Tạo liên kết tự động

Chỉ cần gõ đường link tuyệt đối (có HTTP hoặc HTTPS) Markdown sẽ tạo liên kết tự động

Tạo Hình Ảnh

Tạo Trích Dẫn (Blockquotes)

Để tạo trích dẫn bạn chèn > ngay phía trước

> câu trích dẫn

Tạo Đường Kẻ Gạch Ngang

Bạn gõ --- hoặc *** hoặc ___

---
***
___
Tạo Điểm Nhấn (highlight)

==text==
Inline Code

`inline code`
Tạo chú thích cuối trang

Chú thích[^1] chú thích[^2].  

- [^1]: chú thích 1 
- [^2]: chú thích 2
