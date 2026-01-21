---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 14.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Select **Open AWS Console**

![DIY](/images/14-scaling/14.4-diy/0001-diy.png)

2. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/14-scaling/14.4-diy/0002-diy.png)

3. In **EC2** interface

- Select **Instances**

![DIY](/images/14-scaling/14.4-diy/0003-diy.png)

4. In the **EC2** interface

- Select **Game Server**
- Select **Actions**
- Select **Image and templates**
- Select **Create image**


![DIY](/images/14-scaling/14.4-diy/0004-diy.png)

5. In the **Create image** interface

- **Image name**, enter ```GameServer````
- **Image description**, enter ```Regular customer game server```

![DIY](/images/14-scaling/14.4-diy/0005-diy.png)

6. In the **EC2** interface

- **Tags**, select **tag image and snapshots together**
- Select **Create image**

![DIY](/images/14-scaling/14.4-diy/0006-diy.png)

7. In the **EC2** interface

- Select **AMIs**
- Select **GameServer**
- Select **Refresh**
- View **Status**
- Select **Launch Templates**
  

![DIY](/images/14-scaling/14.4-diy/0007-diy.png)

8. In the **EC2 launch templates** interface

- Select **Create launch templates**

![DIY](/images/14-scaling/14.4-diy/0008-diy.png)

9. In the **Create launch template** interface

- **Lauch template name**, enter ```GameServerTemplate```
- **Template version description**, enter ```Regular customer game server template```


![DIY](/images/14-scaling/14.4-diy/0009-diy.png)

10. In the **EC2 launch template** interface

- Select **My AMIs**
- Select **Owned by me**
- **Amazon Machine Image (AMI)**, select **GameServer**

![DIY](/images/14-scaling/14.4-diy/00010-diy.png)

11. In the **EC2 launch template** interface

- In **Instance type**, select **t2.nano**
- Select **Create new key pair**
- Select **Select existing security group**

![DIY](/images/14-scaling/14.4-diy/00011-diy.png)

12. In the **Create key pair** interface

- **Key pair name**, enter ```GameServerKeyPair```
- **Key pair type***, enter ```RSA```
- **Private key file format**, select **.pem**
- Select **Create key pair**

![DIY](/images/14-scaling/14.4-diy/00012-diy.png)

13. In the **EC2 launch template** interface

- In **Network settings**, select **Select existing security group**
- **Security group**, select **WebServerSecurityGroup**

![DIY](/images/14-scaling/14.4-diy/00013-diy.png)

14. In the **EC2 Launch Template** interface

- Watch **Sumary**
- Select **Create launch template**

![DIY](/images/14-scaling/14.4-diy/00014-diy.png)

15. In the **Create launch template** interface

- See the successful template initialization
- Select **View launch templates**

![DIY](/images/14-scaling/14.4-diy/00015-diy.png)

16. In the **Launch templates** interface

- Select** Auto Scaling Groups**

![DIY](/images/14-scaling/14.4-diy/00016-diy.png)

17. In the **Amazon EC2 Auto Scaling** interface

- Select **Create Auto Scaling group**

![DIY](/images/14-scaling/14.4-diy/00017-diy.png)

18. In the **Create Auto Scaling group** interface

- **Auto Scaling group name**, enter ``` RegularCustomerGameServer```
- **Launch template**, enter ```GameServerTemplate```

![DIY](/images/14-scaling/14.4-diy/00018-diy.png)

19. In the **Create Auto Scaling group** interface

- Select **Next**

![DIY](/images/14-scaling/14.4-diy/00019-diy.png)

20. In the **Create Auto Scaling group** interface

- Select **VPC**
- Select **Availability Zone and subnet

![DIY](/images/14-scaling/14.4-diy/00020-diy.png)

21. In the **Create Auto Scaling group** interface

- Select **Next**

![DIY](/images/14-scaling/14.4-diy/00021-diy.png)

22. In the **Create Auto Scaling group** interface

- In **Load balancing**, select **No load balancer**
- **Health check grace period**, enter ```240````
- Select **Next**

![DIY](/images/14-scaling/14.4-diy/00022-diy.png)

23. In the **Create Auto Scaling group** interface

- **Desired capacity**, enter ```2```
- **Minimum capacity**, enter ```2```
- **Maximum capacity**, enter ```4```
- Select **Target tracking scaling policy**

![DIY](/images/14-scaling/14.4-diy/00023-diy.png)

24. In the **Create Auto Scaling group** interface

- **Scaling policy name**, enter ```CPU Utilization```
- **Tager value**, enter ```70````
- Select **Next**

![DIY](/images/14-scaling/14.4-diy/00024-diy.png)

25. In the interface ***Create Auto Scaling group**

- Select **Skip to review**

![DIY](/images/14-scaling/14.4-diy/00025-diy.png)

26. In the **Create Auto Scaling group** interface

- Select **Create Auto Scaling group**

![DIY](/images/14-scaling/14.4-diy/00026-diy.png)

27. In the **EC2** interface

- View initialization results **Auto Scaling group**
- Select **RegularCustomerGameServer**

![DIY](/images/14-scaling/14.4-diy/00027-diy.png)

28. In the **RegularCustomerGameServer** interface

- Select **Activity**
- View **Activity history**

![DIY](/images/14-scaling/14.4-diy/00028-diy.png)

29. In the **RegularCustomerGameSer** interface

- Select **Automatic scaling**

![DIY](/images/14-scaling/14.4-diy/00029-diy.png)

30. In the **RegularCustomerGameServer** interface

- Select **Create scheduled action**

![DIY](/images/14-scaling/14.4-diy/00030-diy.png)

31. In the **Create scheduled action** interface

- **Name**, enter ```SecondWaveOfRegulars```
- **Desired capacity**, enter **```0```**
- **Min**, enter **```0```**
- **Max**, enter **```0```**
- **Recurrence**, select **Every day**
- **Specific start time**, select date and year and select **01:00**
- Select **Create**

32. In the **DIY** interface

- **Your Auto Scaling group name**, enter ```RegularCustomerGameServer````
- **scheduled-action-name**, enter ```SecondWaveOfRegulars```
- Select **VALIDATE**

![DIY](/images/14-scaling/14.4-diy/00031-diy.png)

33. After selecting **VALIDATE**

- **VALIDATION MESSAGE** Appears **Nice!...**
- Select **EXIT** to exit


![DIY](/images/14-scaling/14.4-diy/00032-diy.png)

34. In the city view

- Select **ASSIGNMENTS**
- Select **COLLECT**

![DIY](/images/14-scaling/14.4-diy/00033-diy.png)

35. Select **NEXT**


![DIY](/images/14-scaling/14.4-diy/00034-diy.png)

36. Select **COLLECT**


![DIY](/images/14-scaling/14.4-diy/00035-diy.png)

37. Congratulations to the award-winning player


![DIY](/images/14-scaling/14.4-diy/00036-diy.png)