Trong ghi chú này, chúng ta sẽ xây dựng một chiếc máy tính thật sự. Dưới đây là kiến trúc Von Neumann, là kiến trúc máy tính (có lẽ là) phổ biến nhất. Phần học này sẽ được viết dưới góc nhìn của một người lập trình viên chứ không phải là một chuyên viết thiết kế phần cứng. Chắc chắn sẽ còn sai sót, mọi người có thể góp ý để mình cải thiện về vấn đề này.
![[img/Pasted image 20250527090242.png]]
Các bộ phận của một chiếc máy tính dựa trên kiến trúc Von Neumann bao gồm: [[CPU]] (Central Processing Unit hay bộ xử lý trung tâm, bao gồm [[Arithmetic Logic Unit]], [[Register]] với [[Control Unit]]), [[Memory]] (Bao gồm data memory với instruction memory) và [[Input & Output]] (Đưa input vào để máy tính xử lý và trả output ra sau khi xử lý).

Chúng ta sẽ bắt đầu bằng cách tìm hiểu về nền tảng của toàn bộ hệ thống này: các [[Cổng Logic]] và [[Boolean Algebra]]. Các cổng Logic cơ bản sau đó sẽ được sử dụng để xây dựng lên các hành phần khác trong máy tính.

Hai loại chip cơ bản là [[Combinational chips]] (Thực hiện phần tính toán và xử lý dữ liệu), và [[Sequential chips]] (Lưu trữ dữ liệu theo thời gian).

Hai phần nâng cao hơn chút là: [[Machine Language]] và [[Assembly]]

