## Bài Test 1: baitest1.cpp
### Mô Tả
- Client gửi đến server một bản tin 5 byte, trong đó có cmd là DET_STATE_WORK.
- Client nhận lại 5 byte và nhận bản tin 21Mb từ server.
- Client gửi liên tiếp 4 lần bản tin 5 byte, trong đó cmd không liên quan đến State của server, và đồng thời nhận lại 4 lần bản tin 5 byte từ server.
- Cuối cùng, client gửi bản tin 5 byte với cmd là DET_STATE_WORK, nhận lại bản tin 5 byte và bản tin 21Mb từ server.
## Bài Test 2: baitest2.cpp
### Mô Tả
- Client gửi liên tiếp 5 lần bản tin 5 byte, trong đó cmd là DET_STATE_WORK.
- Đồng thời client nhận lại 5 lần bản tin 5 byte và bản tin 21Mb từ server.
## Bài Test 2: baitest2.cpp
# Trong file baitest3.cpp
### Mô Tả
- Client gửi đến server một bản tin 5 byte, trong đó có cmd là DET_STATE_WORK.
- Client nhận lại 5 byte và nhận bản tin 21Mb từ server.
- Trong lúc nhận bản tin 21Mb, client chỉ nhận 15Mb và thoát khỏi chương trình.      


