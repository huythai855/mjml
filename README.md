# MJML Project

## Introduction
- Nhân một ngày đẹp trời, huythai855 được giao nhiệm vụ làm và gửi mail cho các diễn giả của TSK Big Game 2022
- huythai855 đã dùng Unlayer để build một template thư bằng HTML, trông khá nice. Sử dụng hệ thống backend tự code (có sử dụng API của google) để làm phần confirm xác nhận tham gia cho diễn giả.
- NHƯNG, well, *"Life is like math if it goes too easy, something is wrong"*. Xảy ra một vấn đề khi gửi mail là phần responsive của HTML Mail rất là ngu, và huythai855 không có cách nào khắc phục được.
- Cuối cùng, sau 7749 lần thử, huythai855 đã quyết định dùng **MJML**.

## MJML là gì?
- Mailjet Markdown Language: đại loại là html nhưng là loại chuyên dùng để build mail responsive do một ông chú nào đó chế tạo ra.
- // nghĩ ra thế thôi, có gì update sau

## How to use?
- Trang chủ [mjml.io](https://mjml.io/): tất tần tật về dự án (nhưng mà đừng đọc, dài vl).
- [Templates](https://mjml.io/templates/): không nhiều lắm nhưng dùng tạm chắp vá cũng được.
- [Try it live](https://mjml.io/try-it-live): kiểu vừa viết vừa dịch được luôn giống IDE Bracket (nhưng hơi đần hơn xíu, dùng cũng được).
- Lên youtube hay google mà kiếm thêm templates và cách dùng. Cảm giác cái này khá phổ biến nhưng mà giờ mình mới biết, hơi wê :>

Ok, đi đá bóng đã ️⚽️⚽️⚽

# Update cho Hà Nguỹn 1:48 AM 29/10

## Intro
- **Bỏ qua phần bên trên đi, đọc từ chỗ này**.
- MJML là một cái ngôn ngữ (?) đại loại thế để đơn giản hóa việc viết mail bằng HTML, để viết siêu ngắn, siêu dễ và tránh các lỗi sai kiểu không fit vào khung blabla, đại loại là 1 ngôn ngữ sinh ra để viết mail động như thế này.
- Nhìn chung nên hiểu 1 chút, biết 1 chút kiến thức về HTML, một số thẻ, thì nó sẽ dễ hơn (Hình như Hà Nguyễn cũng học HTML với CSS rồi thì phải)

## Rồi, giờ phải làm gì?
- Mở mấy folder trong này ra, lấy ra 1 file **.mjml** bất kỳ (có thể lấy cái <a href="https://github.com/huythai855/mjml/blob/master/mail/oct27-2022/mail.mjml">này</a>).
- Copy code của cái file đấy ra, ném vào <a href="https://mjml.io/try-it-live">đây</a>.
- Nhìn cách nó compile ra HTML, cố hiểu hiểu 1 chút rồi mò tiếp thui, easy.
- Sau khi MJML render ra ảnh thì bôi đen phần đó rồi ném vào mail để gửi đi thôi.

<br>

*MJML sau khi render. Bôi đen tất cả phần bên phải rồi ném vào phần mail gửi đi thôi.*
<img src="https://i.imgur.com/4p91Mbj.png"> 

*Demo thêm MJML to HTML*
<img src="https://i.imgur.com/IKrNxAu.png"> 



*Chúc Hà Nguỹn may mắn và đỡ đau cổ 🙆*