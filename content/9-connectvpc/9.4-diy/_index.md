---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 9.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Interface **DIY**

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**


![DIY](/images/9.-connectvpc/9.4-diy/0000-diy.png)

2. Select **Open AWS Console**

![DIY](/images/9.-connectvpc/9.4-diy/0001-diy.png)


3. In the **AWS Console** interface

- Find **VPC**
- Select **VPC**
- Select **Your VPCs**
- View the VPC

![DIY](/images/9.-connectvpc/9.4-diy/0002-diy.png)

4. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/9.-connectvpc/9.4-diy/0003-diy.png)

5. In the **EC2** interface

- Select **Instances**
- Select **Developer Server**
- Select **Details**
- View **VPC ID**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/0005-diy.png)

6. In the **Connect to instance** interface

- Select **EC2 instance Connect**
- Select **Connect**

![DIY](/images/9.-connectvpc/9.4-diy/0006-diy.png)

7. In CLI . interface

- Enter ```ping 172.31.0.10```
- View results

![DIY](/images/9.-connectvpc/9.4-diy/0007-diy.png)

8. In the **EC2** interface

- Select **Developer Server**
- Select **Subnet ID**


![DIY](/images/9.-connectvpc/9.4-diy/0009-diy.png)

9. In the **Subnet** interface

- Select **DeveloperPublicSubnet1**
- Select **Route table**

![DIY](/images/9.-connectvpc/9.4-diy/00010-diy.png)

10. In the **Route tables** interface

- Select **DeveloperPublicSubnet1**
- Select **Routes**
- View the route rules

![DIY](/images/9.-connectvpc/9.4-diy/00011-diy.png)

11. In the **VPC** interface

- Select **Peering Connections**
- Select **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/00012-diy.png)


12. In the **Peering connection settings** interface

- **Name**, enter ```Developer <> Finance```
- Select **VPC ID**
- **Account**, select **My account**
- **Region**, select **This Region (us-east-1)**

![DIY](/images/9.-connectvpc/9.4-diy/00013-diy.png)

13. In the **Peering connection settings** interface

- Select **Create peering connection**

![DIY](/images/9.-connectvpc/9.4-diy/00014-diy.png)

14. Initialization result

![DIY](/images/9.-connectvpc/9.4-diy/00015-diy.png)

15. In the **VPC** interface

- Select **Peering Connections**
- Select **Developer <> Finance**
- View **Status**
- Select **Actions**
- Select **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/00016-diy.png)

16. In the **Accept VPC peering connection request** interface

- Select **Accept request**

![DIY](/images/9.-connectvpc/9.4-diy/00017-diy.png)

17. Result

![DIY](/images/9.-connectvpc/9.4-diy/00018-diy.png)

18. In the **VPC** interface

- Select **Route Tables**
- Select **DeveloperPublicSubnet1**
- Select **Routes**
- View the route rules
- Select **Edit routes**

![DIY](/images/9.-connectvpc/9.4-diy/00019-diy.png)

19. In the **Edit routes** interface

- Select **Add route**
- In **Destination**, enter ```172.31.0.0/16```
- Select **Target**, select **Developer <> Finance**
- Select **Save changes**

![DIY](/images/9.-connectvpc/9.4-diy/00020-diy.png)

20. Results after initialization

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


