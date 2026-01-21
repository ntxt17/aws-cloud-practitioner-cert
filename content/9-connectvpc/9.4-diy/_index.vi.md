---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 9.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**


![DIY](/images/9.-connectvpc/9.4-diy/0000-diy.png)

2. Chọn **Open AWS Console**

![DIY](/images/9.-connectvpc/9.4-diy/0001-diy.png)


3. Trong giao diện **AWS Console**

- Tìm **VPC**
- Chọn **VPC**
- Chọn **Your VPCs**
- Xem các VPC

![DIY](/images/9.-connectvpc/9.4-diy/0002-diy.png)

4. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/9.-connectvpc/9.4-diy/0003-diy.png)

5. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Developer Server**
- Chọn **Details**
- Xem **VPC ID**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/0005-diy.png)

6. Trong giao diện **Connect to instance**

- Chọn **EC2 instance Connect**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/0006-diy.png)

7. Trong giao diện CLI

- Nhập ```ping 172.31.0.10```
- Xem kết quả

![DIY](/images/9.-connectvpc/9.4-diy/0007-diy.png)

8.  Trong giao diện **EC2**

- Chọn **Developer Server**
- Chọn **Subnet ID**


![DIY](/images/9.-connectvpc/9.4-diy/0009-diy.png)

9. Trong giao diẹn **Subnet**

- Chọn **DeveloperPublicSubnet1**
- Chọn **Route table**

![DIY](/images/9.-connectvpc/9.4-diy/00010-diy.png)

10. Trong giao diện **Route tables**

- Chọn **DeveloperPublicSubnet1**
- Chọn **Routes**
- Xem các route rule

![DIY](/images/9.-connectvpc/9.4-diy/00011-diy.png)

11. Trong giao diện **VPC**

- Chọn **Peering Connections**
- Chọn **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/00012-diy.png)


12. Trong giao diện **Peering connection settings**

- **Name**, nhập ```Developer <> Finance```
- Chọn **VPC ID**
- **Account**, chọn **My account**
- **Region**, chọn **This Region (us-east-1)**

![DIY](/images/9.-connectvpc/9.4-diy/00013-diy.png)

13. Trong giao diện **Peering connection settings**

- Chọn **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/00014-diy.png)

14. Kết quả khởi tạo

![DIY](/images/9.-connectvpc/9.4-diy/00015-diy.png)

15. Trong giao diện **VPC**

- Chọn **Peering Connections**
- Chọn **Developer <> Finance**
- Xem **Status**
- Chọn **Actions**
- Chọn **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/00016-diy.png)

16. Trong giao diện **Accept VPC peering connection request**

- Chọn **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/00017-diy.png)

17. Kết quả 

![DIY](/images/9.-connectvpc/9.4-diy/00018-diy.png)

18. Trong giao diện **VPC**

- Chọn **Route Tables**
- Chọn **DeveloperPublicSubnet1**
- Chọn **Routes**
- Xem các route rule 
- Chọn **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/00019-diy.png)

19. Trong giao diện **Edit routes**

- Chọn **Add route**
- Trong **Destination**, nhập ```172.31.0.0/16```
- Chọn **Target**, chọn **Developer <> Finance**
- Chọn **Save changes**

![DIY](/images/9.-connectvpc/9.4-diy/00020-diy.png)

20. Kết quả sau khởi tạo

![DIY](/images/9.-connectvpc/9.4-diy/00021-diy.png)

21. Trong giao diện **VPC**

- Chọn **Route Tables**
- Chọn **FinancePrivatesSubnet1**
- Chọn **Routes**
- Xem các route rule
- Chọn **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/00022-diy.png)

22.  Trong giao diện **Edit routes**

- Chọn **Add route**
- Trong **Destination**, nhập ```192.168.0.10/32```
- Trong **Target**, chọn **Developer <> Finance**
- Chọn **Save changes**

![DIY](/images/9.-connectvpc/9.4-diy/00023-diy.png)

23. Kết quả khởi tạo 

![DIY](/images/9.-connectvpc/9.4-diy/00024-diy.png)

24. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Developer Server**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/00025-diy.png)

25. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/00026-diy.png)

26. Trong giao diện **Developer  Server**

- Nhập ```ping 172.31.0.10```
- Xem kết quả

![DIY](/images/9.-connectvpc/9.4-diy/00027-diy.png)

27. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Finacial Services Server**
- Chọn **Security**
- Chọn **Security groups**

![DIY](/images/9.-connectvpc/9.4-diy/00028-diy.png)

28. Trong **FinanceServerSecurityGroup**

- Chọn **Inbound rules**
- Xem các inbound rule
- Chọn **Edit inbound rules**
  
![DIY](/images/9.-connectvpc/9.4-diy/00029-diy.png)

29. Trong giao diện **Edit inbound rules**

- Chọn **Add rule**
- Chọn **All ICMP-IPv4**
- Chọn **Custom**
- Chọn **192.168.10.32**
- Chọn **Save rules**
  

![DIY](/images/9.-connectvpc/9.4-diy/00030-diy.png)

30. Kết quả sau khởi tạo

![DIY](/images/9.-connectvpc/9.4-diy/00031-diy.png)

31. Trong giao diện CLI

- Nhập ```ping 172.31.0.10```
- Xem kết quả 

![DIY](/images/9.-connectvpc/9.4-diy/00032-diy.png)

32. Trong giao diện **DIY**

- Nhập **Developer instance id**
- Nhập **Finance instance id**
- Sau đó, chọn **VALIDATE**

![DIY](/images/9.-connectvpc/9.4-diy/00033-diy.png)

33. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Developer Server**
- Chọn **Details**
- Sao chép **Instance ID**

![DIY](/images/9.-connectvpc/9.4-diy/00034-diy.png)

34. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Financial Services Server**
- Chọn **Details**
- Sao chép **Instance ID**

![DIY](/images/9.-connectvpc/9.4-diy/00035-diy.png)

35. Trong giao diện **DIY**

- Dán 2 Instance ID vào **VALIDATION FORM**
- Chọn **VALIDATE**

![DIY](/images/9.-connectvpc/9.4-diy/00036-diy.png)

36. Trong giao diện **VALIDATION MESSAGE**

- Xuất hiện **You dit it!...**
- Chọn **EXIT** để thoát

![DIY](/images/9.-connectvpc/9.4-diy/00037-diy.png)

37. Trong giao diện thành phố

- Chọn **ASSIGNMENTs**
- Chọn **COLLECT**


![DIY](/images/9.-connectvpc/9.4-diy/00038-diy.png)

38. Chọn **NEXT**

![DIY](/images/9.-connectvpc/9.4-diy/00039-diy.png)

39. Chọn **COLLECT**

![DIY](/images/9.-connectvpc/9.4-diy/00040-diy.png)

40. Chúc mừng người chơi đã hoàn thành bài lab

![DIY](/images/9.-connectvpc/9.4-diy/00041-diy.png)


