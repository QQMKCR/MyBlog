+++
date = '2025-10-20T21:42:47+07:00'
draft = false
title = 'Sử dụng Java NIO cho lập trình mạng'
+++
Sử dụng Java NIO cho lập trình mạng

Java NIO (Non-blocking I/O) cho phép xử lý nhiều kết nối hiệu quả hơn so với socket truyền thống.

Ví dụ: Server NIO

![vidu7](/images/vd7.png)

Giải thích





Selector: Quản lý nhiều kênh (channels).



ServerSocketChannel: Thay thế ServerSocket cho non-blocking I/O.



Hiệu quả hơn khi xử lý hàng nghìn kết nối.