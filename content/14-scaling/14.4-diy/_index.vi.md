---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 14.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**
- Chọn **Open AWS Console**

![DIY](/images/14-scaling/14.4-diy/0001-diy.png)

2. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/14-scaling/14.4-diy/0002-diy.png)

3. Trong giao diện **EC2**

- Chọn **Instances**

![DIY](/images/14-scaling/14.4-diy/0003-diy.png)

4. Trong giao diện **EC2**

- Chọn **Game Server**
- Chọn **Actions**
- Chọn **Image and templates**
- Chọn **Create image**


![DIY](/images/14-scaling/14.4-diy/0004-diy.png)

5. Trong giao diện **Create image**

- **Image name**, nhập ```GameServer```
- **Image description**, nhập ```Regular customer game server```

![DIY](/images/14-scaling/14.4-diy/0005-diy.png)

6. Trong giao diện **EC2**

- **Tags**, chọn **tag image and snapshots together**
- Chọn **Create image**

![DIY](/images/14-scaling/14.4-diy/0006-diy.png)

7. Trong giao diện **EC2**

- Chọn **AMIs**
- Chọn **GameServer**
- Chọn **Refesh**
- Xem **Status**
- Chọn **Launch Templates**
  

![DIY](/images/14-scaling/14.4-diy/0007-diy.png)

8. Trong giao diện **EC2 launch templates**

- Chọn **Create launch templates**

![DIY](/images/14-scaling/14.4-diy/0008-diy.png)

9. Trong giao diện **Create launch template**

- **Lauch template name**, nhập ```GameServerTemplate```
- **Template version description**, nhập ```Regular customer game server template```


![DIY](/images/14-scaling/14.4-diy/0009-diy.png)

10. Trong giao diện **EC2 launch template**

- Chọn **My AMIs**
- Chọn **Owned by me**
- **Amazon Machine Image (AMI)**, chọn **GameServer**

![DIY](/images/14-scaling/14.4-diy/00010-diy.png)

11. Trong giao diện **EC2 launch template**

- Trong **Instance type**, chọn **t2.nano**
- Chọn **Create new key pair**
- Chọn **Select existing security group**

![DIY](/images/14-scaling/14.4-diy/00011-diy.png)

12. Trong giao diện **Create key pair**

- **Key pair name**, nhập ```GameServerKeyPair```
- **Key pair type***, nhập ```RSA```
- **Private key file format**, chọn **.pem**
- Chọn **Create key pair**

![DIY](/images/14-scaling/14.4-diy/00012-diy.png)

13. Trong giao diện **EC2 launch template**

- Trong **Network settings**, chọn **Select existing security group**
- **Security group**, chọn **WebServerSecurityGroup**

![DIY](/images/14-scaling/14.4-diy/00013-diy.png)

14. Trong giao diện **EC2 Launch Template**

- Xem **Sumary**
- Chọn **Create launch template**

![DIY](/images/14-scaling/14.4-diy/00014-diy.png)

15. Trong giao diện **Create launch template**

- Xem khởi tạo template thành công
- Chọn **View launch templates**

![DIY](/images/14-scaling/14.4-diy/00015-diy.png)

16. Trong giao diện **Launch templates**

- Chọn** Auto Scaling Groups**

![DIY](/images/14-scaling/14.4-diy/00016-diy.png)

17. Trong giao diện **Amazon EC2 Auto Scaling**

- Chọn **Create Auto Scaling group**

![DIY](/images/14-scaling/14.4-diy/00017-diy.png)

18. Trong giao diện **Create Auto Scaling group**

- **Auto Scaling group name**, nhập ``` RegularCustomerGameServer```
- **Launch template**, nhập ```GameServerTemplate```

![DIY](/images/14-scaling/14.4-diy/00018-diy.png)

19. Trong giao diện **Create Auto Scaling group**

- Chọn **Next**

![DIY](/images/14-scaling/14.4-diy/00019-diy.png)

20. Trong giao diện **Create Auto Scaling group**

- Chọn **VPC**
- Chọn **Availability Zone và subnet

![DIY](/images/14-scaling/14.4-diy/00020-diy.png)

21. Trong giao diện **Create Auto Scaling group**

- Chọn **Next**

![DIY](/images/14-scaling/14.4-diy/00021-diy.png)

22.  Trong giao diện **Create Auto Scaling group**

- Trong **Load balancing**, chọn **No load balancer**
- **Health check grace period**, nhập ```240```
- Chọn **Next**

![DIY](/images/14-scaling/14.4-diy/00022-diy.png)

23. Trong giao diện **Create Auto Scaling group**

- **Desired capacity**, nhập ```2```
- **Minimum capacity**, nhập ```2```
- **Maximum capacity**, nhập ```4```
- Chọn **Target tracking scaling policy**

![DIY](/images/14-scaling/14.4-diy/00023-diy.png)

24. Trong giao diện **Create Auto Scaling group**

- **Scaling policy name**, nhập ```CPU Utilization```
- **Tager value**, nhập ```70```
- Chọn **Next**

![DIY](/images/14-scaling/14.4-diy/00024-diy.png)

25. Trong giao diện ***Create Auto Scaling group**

- Chọn **Skip to review** 

![DIY](/images/14-scaling/14.4-diy/00025-diy.png)

26. Trong giao diện **Create Auto Scaling group**

- Chọn **Create Auto Scaling group**

![DIY](/images/14-scaling/14.4-diy/00026-diy.png)

27. Trong giao diện **EC2**

- Xem kết quả khởi tạo **Auto Scaling group**
- Chọn **RegularCustomerGameServer**

![DIY](/images/14-scaling/14.4-diy/00027-diy.png)

28. Trong giao diện **RegularCustomerGameServer**

- Chọn **Activity**
- Xem **Activity history**

![DIY](/images/14-scaling/14.4-diy/00028-diy.png)

29. Trong giao diện **RegularCustomerGameSer**

- Chọn **Automatic scaling**

![DIY](/images/14-scaling/14.4-diy/00029-diy.png)

30. Trong giao diện **RegularCustomerGameServer**

- Chọn **Create scheduled action**

![DIY](/images/14-scaling/14.4-diy/00030-diy.png)

31. Trong giao diện **Create scheduled action**

- **Name**, nhập ```SecondWaveOfRegulars```
- **Desired capacity**, nhập **```0```**
- **Min**, nhập **```0```**
- **Max**, nhập **```0```**
- **Recurrence**, chọn **Every day**
- **Specific start time**, chọn ngày tháng năm và chọn **01:00**
- Chọn **Create**

32. Trong giao diện **DIY**

- **Your Auto Scaling group name**, nhập ```RegularCustomerGameServer```
- **scheduled-action-name**, nhập ```SecondWaveOfRegulars```
- Chọn **VALIDATE**

![DIY](/images/14-scaling/14.4-diy/00031-diy.png)

33. Sau khi chọn **VALIDATE**

- **VALIDATION MESSAGE** xuất hiện **Nice!...**
- Chọn **EXIT** để thoát


![DIY](/images/14-scaling/14.4-diy/00032-diy.png)

34. Trong giao diện thành phố 

- Chọn **ASSIGNMENTS**
- Chọn **COLLECT**

![DIY](/images/14-scaling/14.4-diy/00033-diy.png)

35. Chọn **NEXT**


![DIY](/images/14-scaling/14.4-diy/00034-diy.png)

36. Chọn **COLLECT**


![DIY](/images/14-scaling/14.4-diy/00035-diy.png)

37. Chúc mừng người chơi nhận thưởng


![DIY](/images/14-scaling/14.4-diy/00036-diy.png)