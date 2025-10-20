+++
date = '2025-10-20T21:42:47+07:00'
draft = true
title = 'Giao thức TCP và lập trình Socket cơ bản'
+++
Giao thức TCP và lập trình Socket cơ bản

Giao thức TCP (Transmission Control Protocol) đảm bảo truyền dữ liệu đáng tin cậy giữa client và server. Java cung cấp các lớp ServerSocket và Socket để làm việc với TCP.

Ví dụ: Server TCP cơ bản

Tạo một server lắng nghe kết nối trên cổng 12345:

![vidu2](/images/vd2.png)

Giải thích





ServerSocket: Lắng nghe kết nối từ client.



accept(): Chấp nhận kết nối và trả về một Socket.



Sau khi kết nối, server và client có thể trao đổi dữ liệu qua InputStream và OutputStream.

Hãy thử viết một client kết nối đến server này trong bài tiếp theo!
