+++
date = '2025-10-20T21:42:47+07:00'
draft = true
title = 'Gửi và nhận đối tượng qua mạng'
+++
Gửi và nhận đối tượng qua mạng

Java hỗ trợ gửi/nhận đối tượng qua mạng bằng cơ chế serialization (triển khai Serializable).

Ví dụ: Đối tượng Person

![vidu6.1](/images/vd6_1.png)

Code Server

![vidu6.2](/images/vd6_2.png)

Code Client

![vidu6.3](/images/vd6_3.png)

Lưu ý





Class phải implement Serializable.



Cẩn thận với phiên bản class khi deserialize.