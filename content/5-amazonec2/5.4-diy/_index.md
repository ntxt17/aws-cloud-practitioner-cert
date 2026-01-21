---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Select **DIY** to make

![DIY](/images/5-amazonec2/5.4-diy/0001-diy.png)

2. In the **Plan** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Select **Open AWS Console**

![DIY](/images/5-amazonec2/5.4-diy/0002-diy.png)

3. In **AWS Console**, find and select **EC2**

![DIY](/images/5-amazonec2/5.4-diy/0003-diy.png)

4. Select **Launch instance**

![DIY](/images/5-amazonec2/5.4-diy/0004-diy.png)

5. In **Choose an Amazon Machine Image (AMI)**

- Select **Amazon Linux 2 AMI (HVM) - Kernel 5.10, SSD Volume Type**
- Select **Select**

![DIY](/images/5-amazonec2/5.4-diy/0005-diy.png)

6. In **Choose an Instance Type**

- Select **t2.micro**
- Then select **Next: Configure Instance Details**
  
![DIY](/images/5-amazonec2/5.4-diy/0006-diy.png)

7. In **Configure Instance Details**

- Select **VPC**
- Choose **Subnet** different from the subnet of **Practice**

![DIY](/images/5-amazonec2/5.4-diy/0007-diy.png)

8. In **Advanced Details**

- Select **As file**
- Select **Select file** and download the file **user-data**
- Select **Next: Add Storage**

![DIY](/images/5-amazonec2/5.4-diy/0008-diy.png)


9. In **Add Storage**, select **Next: Add Tags**

![DIY](/images/5-amazonec2/5.4-diy/0009-diy.png)

10. In **Add Tags**, select **Next: Configure Security Group**

11. In **Configure Security Group**, create a security group

- **Security group name**, enter ``` Security-Group-Lab-2```
- **Description**, enter ``` HTTP Group Lab 2 ```
- **Rule**, select **HTTP**
- Select **Review and Launch**

![DIY](/images/5-amazonec2/5.4-diy/00010-diy.png)

12. In **Review Instance Launch**, double check and select **Launch**

![DIY](/images/5-amazonec2/5.4-diy/00011-diy.png)

13. In **Select an existing key pair or create a new key pair**

- Select **Proceed without a key pair**
- Select **I acknowledge...**
- Select **Launch Instances**

![DIY](/images/5-amazonec2/5.4-diy/00012-diy.png)

14. Select **View Instances**

![DIY](/images/5-amazonec2/5.4-diy/00013-diy.png)

15. Result of creating 2 **Amazon EC2 Instance**
    
![DIY](/images/5-amazonec2/5.4-diy/00014-diy.png)

16. After creating 2 **Amazon EC2 Instance**, copy both **Instance ID**

- Paste in **Instance ID in AZ1**
- Paste in **Instance ID in AZ2**
- Select **VALIDATE**

![DIY](/images/5-amazonec2/5.4-diy/00015-diy.png)

17. After selecting **VALIDATE**, if **VALIDATION MESSAGE** contains **Success! ...** is complete

![DIY](/images/5-amazonec2/5.4-diy/00016-diy.png)

18. Select **EXIT**

![DIY](/images/5-amazonec2/5.4-diy/00017-diy.png)

19. In **ASSIGNMENT** select **COLLECT**

![DIY](/images/5-amazonec2/5.4-diy/00018-diy.png)

20. Select **NEXT**

![DIY](/images/5-amazonec2/5.4-diy/00019-diy.png)

21. Select **COLLECT**

![DIY](/images/5-amazonec2/5.4-diy/00020-diy.png)

22. Get rewarded

![DIY](/images/5-amazonec2/5.4-diy/00021-diy.png)