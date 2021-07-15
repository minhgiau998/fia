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
<h2>4. Fish (Friendly Interactive Shell)</h2>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Fish.png" alt="Fish.png"></p>
<p>Với tất cả sự nghiêm túc của Linux, nhóm phát triển <strong>Fish</strong> đã mang đến một dự án hài hước. Trên trang web của họ, tiêu đề có nội dung “Finally, a command line shell for the 90s” mặc dù Fish đã được phát triển vào năm 2005. Ngoài lời chào mời “Glorious VGA Color”, Fish cũng có một số cải tiến hơn các shell khác:</p>
<ul>
	<li>Các lệnh có cú pháp không hợp lệ sẽ được hiển thị màu đỏ</li>
	<li>Cú pháp đúng sẽ hiển thị bằng màu xanh lam</li>
	<li>Đề xuất tự động hoàn thành</li>
	<li>Hoàn thành lệnh dựa trên trang man trên máy của bạn</li>
</ul>
<p>Tính năng này thêm cú pháp từ trang man của phần mềm mới được cài đặt vào các đề xuất tự động hoàn thành của bạn. Nếu bạn muốn làm quen với dòng lệnh hơn, Fish là một nơi tuyệt vời để bắt đầu.</p>
<h2>5. Zsh (Z Shell)</h2>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Zsh.png" alt="Zsh.png"></p>
<p>Zsh có những điểm tương đồng với bash và ksh, kết hợp nhiều tính năng được tìm thấy trong tcsh. Các tính năng của Zsh bao gồm:</p>
<ul>
	<li>Danh sách tự động hoàn thành có thể điều hướng</li>
	<li>Sửa lỗi chính tả vượt trội</li>
	<li>Hoàn thành dòng lệnh</li>
	<li>Lịch sử được chia sẻ trên các terminal</li>
	<li>Globbing (ký tự đại diện cho tên tệp)</li>
</ul>
<h1>III. Manipulating file</h1>
<ul>
	<li><code><strong>pwd</strong></code>: Print Working Directory</li>
	<li>Được dùng để <strong>tìm đường dẫn</strong> của folder mà ta đang dùng ở hiện tại.</li>
	<li>Command này sẽ trả về đường dẫn hoàn chỉnh, bắt đầu bằng <strong>dấu gạch chéo ( / ).</strong></li>
</ul>
<p>VD: <code>pwd /home/username</code></p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani01.png" alt="Mani01.png"></p>
<ul>
	<li><code><strong>cd</strong></code>: Change Directory</li>
	<li>Để <strong>chuyển hướng</strong> trong hệ thống tệp tin Linux.</li>
</ul>
<p>Cách cơ bản khi dùng lệnh cd để chuyển hướng:</p>
<p>VD: Nếu bạn đang ở trong  <code>/home/username/Documents</code> và muốn đến <strong>Album</strong> (thư mục con ở Documents), bạn chỉ cần gõ <code>cd Album</code></p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani02.png" alt="Mani02.png"></p>
<p>Có nhiều cách di chuyển nhanh bằng <code>cd</code>:</p>
<p>VD: <code>cd</code> để tới thẳng thư mục home.</p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani03.png" alt="Mani03.png"></p>
<p><em>(Hiện tại bạn đang ở thư mục <strong>Album</strong> và chuyển đến thư mục <strong>home</strong>)</em></p>
<p>VD: <code>cd ..</code> (hai dấu chấm) để chuyển lên 1 cấp thư mục trên.</p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani04.png" alt="Mani04.png"></p>
<p><em>(Hiện tại bạn đang ở thư mục <strong>tramy</strong> và chuyển lên 1 cấp là thư mục <strong>Users</strong>)</em></p>
<p>VD: <code>cd -</code> (dấu gạch ngang) để chuyển tới thư mục bạn đã ở trước đó.</p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani05.png" alt="Mani05.png"></p>
<p><em>(Hiện tại bạn đang ở thư mục <strong>tramy</strong> và chuyển đến thư mục <strong>Users</strong> trước đó.)</em></p>
<p>Và còn rất nhiều cách khác nhau các bạn có thể tự tìm hiểu theo mong muốn của mình</p>
<ul>
	<li><p><code>mkdir</code> là lệnh để tạo ra 1 thư mục ( ví dụ như để tạo ra 1 thư mục mới đặt tên là <strong>thumuc1</strong> ta sẽ gõ: <code>mkdir thumuc1</code> ( nó sẽ tạo ra thư mục mang tên thumuc1 ) – sau công đoạn này thì nếu muốn vào thư mục mới đặt (thumuc1) thì gõ <code>cd thumuc1</code> thì sẽ được chuyển tới thumuc1.</p></li>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani06.png" alt="Mani06.png"></p>
	<li><p>Còn đối với lệnh <code>ls</code> là khi ta tạo 1 file trong <strong>thumuc1</strong> bằng cách gõ <code>touch</code> + (tên file) => <code>touch file1</code>. Sau khi có file1 đó thì ta gõ lệnh <code>ls</code> để coi trong <strong>thumuc1</strong> đó có gì thì nó sẽ in ra file1.</p></li>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani07.png" alt="Mani07.png"></p>
	<li>Muốn có thêm thông tin rõ ràng hơn thì ta chỉ cần gõ thêm là <code>ls -l</code> hoặc <code>ls -la</code></li>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani08.png" alt="Mani08.png"></p>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani09.png" alt="Mani09.png"></p>
	<li>Còn đối với lệnh <code>rmdir</code> là chỉ để xóa đi các thư mục rỗng , còn đối với những thư mục nào chứa file thì không thể xóa được và báo lỗi</li>
	<li>Ví dụ trong <strong>thumuc1</strong> ta tạo ra 1 thư mục mới là <strong>thumuc2</strong> và trong đó không có bất kỳ file nào được tạo</li>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani10.png" alt="Mani10.png"></p>
	<li>Ta đã tạo ra thumuc2 trong thumuc1 và kiểm tra trong thumuc1 chứa thumuc2 và file1 mới tạo lúc nãy bằng cách dùng <code>ls</code> để kiểm tra thành phần trong thumuc1</li>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Mani11.png" alt="Mani11.png"></p>
	<li>Sau khi tiến hành xóa đi thumuc2 bằng lệnh <code>rmdir thumuc2</code> thì thumuc2 đã biến mất và chỉ còn lại file1 mới tạo lúc nãy</li>
</ul>
<h2>Lệnh CP</h2>
<h3>Định nghĩa</h3>
<p>Lệnh <code>cp</code> trên Linux được sử dụng để copy một file hoặc một thư mục từ một vị trí đến vị trí khác. Đây gần như là chương trình lệnh cơ bản của các dòng Linux phân phối khác.</p>
<h3>Cú pháp</h3>
<p><code>cp [Options] Source Destination</code></p>
<p>Trong đó:</p>
<ul>
	<li><strong>Options</strong> là các tùy chọn.</li>
	<li><strong>Source</strong> là file nguồn hoặc thư mục nguồn.</li>
	<li><strong>Destination</strong> là tên file đích hoặc thư mục đích.</li>
</ul>
<p><em>Ví dụ: Copy vidu1.txt từ thumuc1 sang thumuc2</em></p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp01.png" alt="Cp01.png"></p>
<p><em>Ví dụ: Copy nhiều thư mục vào một thư mục</em></p>
<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp02.png" alt="Cp02.png"></p>
<p>Như vậy lệnh <code>cp</code> được mở rộng ra thành cấu trúc:
<code>cp [Options] Source1 Source2 Source3...Source-n Destination</code></p>
<h3>Các Option của lệnh <code>cp</code></h3>
<ul>
	<li><code>-r</code>, <code>-R</code>, <code>--recursive</code>: copy folder và file đệ quy, tức là copy toàn bộ thư mục hoặc các file con của thư mục được copy.</li>
	<em>Ví dụ: Copy toàn bộ file con của thư mục docm trong thumuc1 sang thư mục backup trong thumuc2</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp03.png" alt="Cp03.png"></p>
	<li><code>-a</code>, <code>--archive</code>: sử dụng <code>-a</code>, sẽ lưu trữ các tệp và thư mục trong khi sao chép. Nghĩa là với tùy chọn <code>-a</code> sẽ sinh ra một thư mục trong thư mục đến cùng tên với thư mục gốc và chuyển file vào đó.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp04.png" alt="Cp04.png"></p>
	<li><code>-i</code>, <code>--interactive</code>: Ghi đè file ở thư mục đích. Luôn có nhắc nhở trước khi ghi đè. <strong>Y</strong> là chấp nhận thao tác ghi đè và <strong>N</strong> là từ chối.</li>
	<em>Ví dụ: Ghi đè file1 trong thumuc1 lên file2 trong thumuc2 với thao tác chấp thuận ghi đè</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp05.png" alt="Cp05.png"></p>
	<em>Ví dụ: Ghi đè file1 trong thumuc1 lên file2 trong thumuc2 với thao tác không chấp thuận ghi đè.</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp06.png" alt="Cp06.png"></p>
	<li><code>-v</code>, <code>--verbose</code>: Quá trình hoạt động của lệnh <code>cp</code> sẽ được hiển thị.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp07.png" alt="Cp07.png"></p>
	<li><code>-p</code>: Để giữ lại các thuộc tính thông tin của file được copy.</li>
	<p>Các thuộc tính được giữ lại gồm : Access time, Modification date, User ID, Group ID, File flags, File mode, Access Control Lists.</p>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp08.png" alt="Cp08.png"></p>
	<li><code>-n</code>, <code>--no clobber</code>: Giả sử thư mục đích của bạn đã có file cùng tên file bạn đang muốn copy. Thì bạn có thể sử dụng <code>-n</code> để ép buộc lệnh <code>cp</code> không được ghi đè nếu file nguồn và file đích cùng tên. Khi sử dụng option <code>-n</code>, thì sẽ không có hiện prompt xác nhận copy mà là ép lệnh luôn.</li>
	<em>Ví dụ:</em>
	<p>Bình thường copy như sau:</p>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp09.png" alt="Cp09.png"></p>
	<p>Khi dùng tham số <code>-n</code>:</p>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp10.png" alt="Cp10.png"></p>
	<li><code>-f</code>, <code>--force</code>:  Để ép buộc lệnh cp copy file ghi đè lên file đang tồn tại ở thư mục đích nếu nó cùng tên file nguồn copy.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp11.png" alt="Cp11.png"></p>
	<li><code>-l</code>, <code>--link</code>: Tạo hard-link thay vì copy.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp12.png" alt="Cp12.png"></p>
	<em>Kết quả:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp13.png" alt="Cp13.png"></p>
	<li><code>-s</code>, <code>--symbolic-link</code>: Tạo <strong>symbolic links</strong> thay vì copy.</li>
	<p><strong>Symbolic Link</strong> (liên kết tượng trưng) trong ngành máy tính là thuật ngữ chỉ một file tham chiếu đến file khác hoặc thư mục khác dưới dạng đường dẫn tương đối hoặc tuyệt đối. Ngoài ra, <strong>symbolic link</strong> cũng hay được gọi tắt là <strong>Symlink</strong> hay <strong>Softlink</strong>.</p>
	<li><code>--attributes-only</code>: Sao chép các thuộc tính từ nguồn đến đích. Có thể thấy file mới được tạo ra nhưng chỉ có thuộc tính còn nội dung file là không có.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp14.png" alt="Cp14.png"></p>
	<li><code>-u</code>, <code>--update</code>: Copy chỉ khi file nguồn mới hơn file đích hoặc file đích bị mất.</li>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp15.png" alt="Cp15.png"></p>
	<li><code>--backup</code>: Tạo một bản backup ở thư mục đích. Khi dùng tham số này thì một file backup sẽ được tạo ra ở thư mục đích cùng với việc copy file.</li>
	<p>Phần backup có các tùy chọn:</p>
	<ul>
		<li><strong>none, off</strong>: không tạo file backup.</li>
		<li><strong>numbered, t</strong>: số lượng file backup là bao nhiêu.</li>
		<li><strong>existing, nil</strong>: nếu file backup có rồi thì ghi đè hoặc bỏ qua.</li>
		<li><strong>simple, never</strong>: luôn tạo bản backup simple.</li>
	</ul>
	<em>Ví dụ:</em>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp16.png" alt="Cp16.png"></p>
	<li><code>--sparse</code>: Copy tên file và tạo ở thư mục đích 1 file cùng tên và dung lượng bằng 0.</li>
	<p>Một số tham số khi dùng sparse:</p>
	<ul>
		<li><strong>sparse=auto</strong></li>
		<li><strong>sparse-always</strong></li>
		<li><strong>sparse=never</strong></li>
	</ul>
	<li><code>--help</code>: hỗ trợ.</li>
	<p>Trích một phần trong phần <code>--help</code>.</p>
	<p><img src="https://github.com/FIA-FPT/fia/blob/develop/assets/images/linux-fundamental/Cp17.png" alt="Cp17.png"></p>
</ul>
