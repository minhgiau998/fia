---
layout: post
current: post
cover: assets/images/thumbnail/linux-fundamental.jpg
navigation: True
title: Linux Fundamental
date: 2021-07-014 23:00:00
tags: [Linux, Fundamental]
class: post-template
subclass: "post"
author: fia
---

<p>Đây là bài nghiên cứu theo hình thức nhóm về làm quen với Linux và các lệnh cơ bản của Linux của <strong>Nhóm 9</strong> gồm các thành viên:</p>
<ul>
	<li>Đặng Phúc An</li>
	<li>Nguyễn Thị Trà My</li>
	<li>Hồ Ngọc Thanh Trúc</li>
</ul>
<p>Bài viết sẽ rất hữu ích với những bạn mới bắt đầu tìm hiểu về hệ điều hành <strong>Linux</strong> cũng như các lệnh điều khiển cơ bản trên <strong>Linux</strong>.</p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Header.png" alt="Header.png"></p>
<h1>I. Shell là gì ?</h1>
<ul>
	<li>
		<p>Shell là một môi trường trong đó chúng ta có thể chạy các lệnh, các chương trình và Shell script. Mỗi phiên bản của Shell có bộ thiết lập các lệnh và hàm được thừa nhận riêng của nó. Shell nhận input từ người dùng để chạy các chương trình trên cơ sở đầu vào đó. Khi một chương trình hoặc lệnh được hoàn thành, nó hiển thị kết quả (output) của chương trình đó.</p>
	</li>
	<li>
		<p>Shell còn được gọi là trình thông dịch. Tương tự như một trình biên dịch, một trình thông dịch dịch mã người dùng thực hiện thành mã máy. Một trong những điểm khác biệt là trình thông dịch thực hiện từng câu một. Trong khi đó, một trình biên dịch sẽ quét toàn bộ chương trình và dịch tất cả thành mã máy.</p>
	</li>
</ul>
<h1>II. Một số kiểu Shell trong Kali Linux</h1>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Shell.png" alt="Shell.png"></p>
<h2>1. Bash</h2>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Bash.png" alt="Bash.png"></p>
<p>Đây là một shell phổ biến nhất trong số những người dùng Linux. Thật khó để nghĩ về shell mà không có <strong>Bourne-Again Shell</strong> (bash). Nhiều bản phân phối Linux có bash là shell mặc định, vì bash shell GNU mặc định. Được phát hành vào năm 1989, nó đã có một vài thập kỷ phát triển mạnh mẽ.</p>
<p>Tiền thân của Bash là <strong>The Bourne Shell</strong> (sh), là một trong những shell gốc của Unix. Một tính năng hấp dẫn đối với các lập trình viên sh là họ có thể chuyển trực tiếp các tập lệnh của mình sang bash mà hoàn toàn được giữ nguyên. Bash cũng cung cấp một số cải tiến cho người dùng:</p>
<ul>
	<li>Hoàn thành lệnh</li>
	<li>Lịch sử lệnh</li>
</ul>
<h2>2. KornShell</h2>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Korn.png" alt="Korn.png"></p>
<p>Thường được gọi là <strong>ksh</strong>, KornShell là một Linux Shell thay thế phổ biến có nguồn gốc từ Bell Labs vào những năm 80. Không có nhiều sự khác biệt giữa bash và ksh, nhưng mỗi cái đều có những lợi thế nhỏ so với cái khác. Ksh, ví dụ, có lệnh cd cũ mới. Nếu bạn đang ở trong thư mục Desktop/bin/a/, nếu cần truy cập /Desktop/bin/b, bạn chỉ cần nhập:</p>
<code>$ cd a b</code>
<p>Các lợi ích của ksh bao gồm:</p>
<ul>
	<li>Cú pháp vòng lặp tốt hơn</li>
	<li>Các cách lặp lại lệnh tự nhiên</li>
	<li>Mảng liên kết</li>
</ul>
<h2>3. Tcsh</h2>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Tcsh.png" alt="Tcsh.png"></p>
<p><strong>Tcsh</strong> có thể bắt nguồn từ những ngày đầu của Unix. Đây là phiên bản cải tiến của C shell (csh) và có các tính năng:</p>
<ul>
	<li>Hoàn thành dòng lệnh có thể lập trình</li>
	<li>Chỉnh sửa dòng lệnh</li>
	<li>Thêm đối số vào bí danh</li>
	<li>Truy cập lịch sử lệnh dễ dàng</li>
</ul>
