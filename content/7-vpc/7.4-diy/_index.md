---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b>7.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. Select **DIY**

![DIY](/images/7-vpc/7.4-diy/0001-diy.png)

2. The **DIY** interface appears including:
- Lab Files
- DIY Activity
- Networking Concepts
- VALIDATION FORM
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/7-vpc/7.4-diy/0002-diy.png)

3. In the **AWS Console** page, find and select **EC2**

![DIY](/images/7-vpc/7.4-diy/0003-diy.png)

4. Select **Instances**

- Select **Security**
- In **Security groups**, select **DbServerSecurityGroup**


![DIY](/images/7-vpc/7.4-diy/0004-diy.png)

5. In the **Security Groups** interface

- Select **Edit inbound rules**

![DIY](/images/7-vpc/7.4-diy/0005-diy.png)

6. In the **Edit inbound rules** interface
- **Type**: select **MYSQL/Aurora**
- **Protocol**: select **TCP**
- **Prot range**: enter ```3306```
- **Source**: choose **Custom**
- Then select **Save rules**

![DIY](/images/7-vpc/7.4-diy/0006-diy.png)

7. Interface after creating **DbServerSecurityGroup**

![DIY](/images/7-vpc/7.4-diy/0007-diy.png)

8. In the **Security groups** view, copy **Security group name**

![DIY](/images/7-vpc/7.4-diy/0008-diy.png)

9. After copying **Security group name**

- Paste **Security group name** into **VALIDATION FORM** in **Database Security Group name** field

- Then select **VALIDATE**
![DIY](/images/7-vpc/7.4-diy/0009-diy.png)

10. Results

- On **VALIDATION MESSAGE**, appears **Nice!You have properly configured your security!** and done **DIY**
- Select **EXIT** to exit

![DIY](/images/7-vpc/7.4-diy/00011-diy.png)

11. Select **NEXT**

![DIY](/images/7-vpc/7.4-diy/00012-diy.png)

12. Select **COLLECT**

![DIY](/images/7-vpc/7.4-diy/00013-diy.png)


13. Congratulations on completing lab 7
![DIY](/images/7-vpc/7.4-diy/00014-diy.png)