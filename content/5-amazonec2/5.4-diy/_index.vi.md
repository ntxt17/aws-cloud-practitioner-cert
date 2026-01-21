---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Chọn **DIY** để thực hiện 

![DIY](/images/5-amazonec2/5.4-diy/0001-diy.png)

2. Trong giao diện **Plan**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**
- Chọn **Open AWS Console**

![DIY](/images/5-amazonec2/5.4-diy/0002-diy.png)

3. Trong **AWS Console**, tìm và chọn **EC2**

![DIY](/images/5-amazonec2/5.4-diy/0003-diy.png)

4. Chọn **Launch instance**

![DIY](/images/5-amazonec2/5.4-diy/0004-diy.png)

5. Trong **Choose an Amazon Machine Image (AMI)**

-  Chọn **Amazon Linux 2 AMI (HVM) - Kernel 5.10, SSD Volume Type**
-  Chọn **Select**

![DIY](/images/5-amazonec2/5.4-diy/0005-diy.png)

6. Trong **Choose an Instance Type**

- Chọn **t2.micro**
- Sau đó chọn **Next: Configure Instance Details**
  
![DIY](/images/5-amazonec2/5.4-diy/0006-diy.png)

7. Trong **Configure Instance Details**

-  Chọn **VPC**
-  Chọn **Subnet** khác với subnet của bài **Practice**

![DIY](/images/5-amazonec2/5.4-diy/0007-diy.png)

8. Trong **Advanced Details**

- Chọn **As file**
- Chọn **Chọn tệp** và tải file **user-data**
- Chọn **Next: Add Storage**

![DIY](/images/5-amazonec2/5.4-diy/0008-diy.png)


9. Trong **Add Storage**, chọn **Next: Add Tags**

![DIY](/images/5-amazonec2/5.4-diy/0009-diy.png)

10. Trong **Add Tags**, chọn **Next: Configure Security Group**

11. Trong **Configure Security Group**, tạo một security group

- **Security group name**, nhập ``` Security-Group-Lab-2```
- **Description**, nhập ``` HTTP Group Lab 2 ```
- **Rule**, chọn **HTTP**
- Chọn **Review and Launch**

![DIY](/images/5-amazonec2/5.4-diy/00010-diy.png)

12. Trong **Review Instance Launch**, kiểm tra lại và chọn **Launch**

![DIY](/images/5-amazonec2/5.4-diy/00011-diy.png)

13. Trong **Select an existing key pair or create a new key pair**

- Chọn **Proceed without a key pair**
- Chọn **I acknowledge...**
- Chọn **Launch Instances**

![DIY](/images/5-amazonec2/5.4-diy/00012-diy.png)

14. Chọn **View Instances**

![DIY](/images/5-amazonec2/5.4-diy/00013-diy.png)

15. Kết quả tạo 2 **Amazon EC2 Instance**
    
![DIY](/images/5-amazonec2/5.4-diy/00014-diy.png)

16.  Sau khi tạo xong 2 **Amazon EC2 Instance**, copy cả 2 **Instance ID** 

-  Dán vào **Instance ID in AZ1**
-  Dán vào **Instance ID in AZ2**
-  Chọn **VALIDATE**

![DIY](/images/5-amazonec2/5.4-diy/00015-diy.png)

17. Sau khi chọn **VALIDATE**, nếu **VALIDATION MESSAGE** có nội dung **Success! ...** là hoàn thành

![DIY](/images/5-amazonec2/5.4-diy/00016-diy.png)

18. Chọn **EXIT**

![DIY](/images/5-amazonec2/5.4-diy/00017-diy.png)

19. Trong **ASSIGNMENT** chọn **COLLECT**

![DIY](/images/5-amazonec2/5.4-diy/00018-diy.png)

20. Chọn **NEXT**

![DIY](/images/5-amazonec2/5.4-diy/00019-diy.png)

21. Chọn **COLLECT**

![DIY](/images/5-amazonec2/5.4-diy/00020-diy.png)

22. Nhận thưởng

![DIY](/images/5-amazonec2/5.4-diy/00021-diy.png)










