+++
date = '2025-10-20T21:42:47+07:00'
draft = true
title = 'Xử lý nhiều client với Multithreading'
+++
Xử lý nhiều client với Multithreading

Để server xử lý nhiều client đồng thời, ta sử dụng đa luồng (multithreading) trong Java.

Code Server

![vidu5](/images/vd5.png)


Giải thích





Mỗi client kết nối sẽ được xử lý trong một thread riêng.



ClientHandler là một class xử lý từng client, chạy trong thread riêng.