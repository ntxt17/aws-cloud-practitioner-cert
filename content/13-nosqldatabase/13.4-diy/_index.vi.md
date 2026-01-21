---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 13.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **AWS Console**

- Tìm **Amazon DynamoDB**
- Chọn **Amazon DynamoDB**
- Chọn **Create table**

![DIY](/images/13-nosqldatabase/13.4-diy/0001-diy.png)

2. Trong giao diện **DynamoDB**

- Chọn **Update settings**
- Chọn **UserVideoHistory**
- Chọn **Actions**
- Chọn **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/0002-diy.png)

3. Trong giao diện **Create item**

- Trong **userId**, nhập ```12345-abcd-6785```
- Trong **lastDateWatched**, nhập ```1619156407```

![DIY](/images/13-nosqldatabase/13.4-diy/0003-diy.png)

4. Trong giao diện **Create item**

- Chọn **Add new attribute**
- Chọn **Number**

![DIY](/images/13-nosqldatabase/13.4-diy/0004-diy.png)

5. Trong giao diện **Create item**

- **Attribute name**, nhập ```Rating``` **(lưu ý phải viết thường)**
- **Value**, nhập ```5```
- Chọn **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/0005-diy.png)

6. Trong giao diện **DynamoDB**

- Xem **Items returned**

![DIY](/images/13-nosqldatabase/13.4-diy/0006-diy.png)

7. Trong giao diện **Item editor**

- Trong **Attribute name**, nhập ```rating```
- Chọn **Save changes**

![DIY](/images/13-nosqldatabase/13.4-diy/0007-diy.png)

8. Trong giao diện **DIY**

- Nhập **```UserVideoHistory```** vào **DynamoDB table name**
- Nhập ***```12345-abcd-6785```** vào **Item User Id**
- Chọn **VALIDATE**
- Sau khi chọn **VALIDATE**, **VALIDATION MESSAGE** xuất hiện **The DynamoDB record has been correctly configured! Good job!...**

![DIY](/images/13-nosqldatabase/13.4-diy/0008-diy.png)

9. Trong giao diện **DIY**

- Chọn **EXIT** để thoát 

![DIY](/images/13-nosqldatabase/13.4-diy/0009-diy.png)

10. Trong giao diện thành phố 

- Chọn **ASSIGNMENTS**
- Chọn **COLLECT**

![DIY](/images/13-nosqldatabase/13.4-diy/00010-diy.png)

11. Chọn **NEXT**

![DIY](/images/13-nosqldatabase/13.4-diy/00011-diy.png)

12. Chọn **COLLECT**

![DIY](/images/13-nosqldatabase/13.4-diy/00012-diy.png)

13. Chúc mừng người chơi hoàn thành bài **DIY**

![DIY](/images/13-nosqldatabase/13.4-diy/00013-diy.png)
