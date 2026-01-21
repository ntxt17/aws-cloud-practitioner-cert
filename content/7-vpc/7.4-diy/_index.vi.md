---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 7.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Chọn **DIY**

![DIY](/images/7-vpc/7.4-diy/0001-diy.png)

2. Giao diện **DIY** xuất hiện gồm:
- Lab Files
- DIY Activity
- Networking Concepts
- VALIDATION FORM
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/7-vpc/7.4-diy/0002-diy.png)

3. Trong trang **AWS Console**, tìm và chọn **EC2**

![DIY](/images/7-vpc/7.4-diy/0003-diy.png)

4. Chọn **Instances**

- Chọn **Security**
- Trong **Security groups**, chọn **DbServerSecurityGroup**


![DIY](/images/7-vpc/7.4-diy/0004-diy.png)

5. Trong giao diện **Security Groups**

- Chọn **Edit inbound rules**

![DIY](/images/7-vpc/7.4-diy/0005-diy.png)

6. Trong giao diện **Edit inbound rules**
- **Type**: chọn **MYSQL/Aurora**
- **Protocol**: chọn **TCP**
- **Prot range**: nhập ```3306```
- **Source**: chọn **Custom**
- Sau đó chọn **Save rules**

![DIY](/images/7-vpc/7.4-diy/0006-diy.png)

7. Giao diện sau khi tạo **DbServerSecurityGroup**

![DIY](/images/7-vpc/7.4-diy/0007-diy.png)

8. Trong giao diện **Security groups**, sao chép **Security group name**

![DIY](/images/7-vpc/7.4-diy/0008-diy.png)

9. Sau khi sao chép **Security group name**

- Dán **Security group name** vào **VALIDATION FORM** trong trường **Database Security Group name**

- Sau đó, chọn **VALIDATE**
![DIY](/images/7-vpc/7.4-diy/0009-diy.png)

10. Kết quả 

- Trên **VALIDATION MESSAGE**, xuất hiện **Nice!You have properly configured your security!** là đã hoàn thành **DIY**
- Chọn **EXIT** để thoát

![DIY](/images/7-vpc/7.4-diy/00011-diy.png)

11. Chọn **NEXT**

![DIY](/images/7-vpc/7.4-diy/00012-diy.png)

12. Chọn **COLLECT**

![DIY](/images/7-vpc/7.4-diy/00013-diy.png)


13. Chúc mừng người chơi đã hoàn thành lab 7
![DIY](/images/7-vpc/7.4-diy/00014-diy.png)



