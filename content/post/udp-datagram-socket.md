+++
date = '2025-10-20T21:42:47+07:00'
draft = false
title = 'Giao thức UDP và DatagramSocket'
+++
Giao thức UDP và DatagramSocket

UDP (User Datagram Protocol) là giao thức nhanh, không đảm bảo thứ tự dữ liệu. Java sử dụng DatagramSocket và DatagramPacket cho UDP.

Ví dụ: Server UDP

![vidu4.1](/images/vd4_1.png)

Ví dụ: Client UDP

import java.net.*;

![vidu4.2](/images/vd4_2.png)

Lưu ý





UDP không đảm bảo dữ liệu đến đúng thứ tự hoặc đến được.



Thích hợp cho ứng dụng cần tốc độ cao (như streaming).