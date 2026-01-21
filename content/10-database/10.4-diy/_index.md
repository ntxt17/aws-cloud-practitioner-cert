---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 10.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/10-database/10.4-diy/0001-diy.png)

2. In the **AWS Console** interface

- Find **RDS**
- Select **RDS**

![DIY](/images/10-database/10.4-diy/0002-diy.png)

3. In the **Amazon RDS** interface

- Select **Databases**

![DIY](/images/10-database/10.4-diy/0003-diy.png)

4. In the **Databases** interface

- Select **my-database**
- Select **Actions**
- Select **Create read replica**

![DIY](/images/10-database/10.4-diy/0004-diy.png)

5. In the **Create read replica DB instance** interface

- In **DB instance class**, select **db.t3.xlarge-4 vCPU**
- In **Multi-AZ deployment**, select **Yes**
- In **Storage type**, select **General Purpose (SSD)**

![DIY](/images/10-database/10.4-diy/0005-diy.png)

6. In the **Network & Security** interface

- In **Destination region**, select **US East (N. Virginia)**
- In **Destination DB subnet group**, select **default-vpc**
- In **Publicly accessible**, select **No**
- In **VPC security groups**, select **default**

![DIY](/images/10-database/10.4-diy/0006-diy.png)

7. In the **RDS** interface

- In **Read replica source**, enter ```my-database```
- In **DB instance identifier**, enter ```my-database-read-replica```
- In **Database options** interface, in **Database port**, enter ```3306```
- Select **Copy tags to snapshots**

![DIY](/images/10-database/10.4-diy/0007-diy.png)

8. In the **RDS** interface

- In **Monitoring**, uncheck **Disable enhanced monitoring**
- In **Performance Insights**, uncheck **Disable Performance Insights**

![DIY](/images/10-database/10.4-diy/0008-diy.png)

9. In the **RDS** interface

- In **Maintenance**, select **No**
- Select **Create read replica**

![DIY](/images/10-database/10.4-diy/0009-diy.png)

10. View initialization results


![DIY](/images/10-database/10.4-diy/00010-diy.png)

11. In the **DIY** interface

- Copy and paste **Your RDS DB identifier**
- Copy and paste **ypur read replica DB identifier**
- Select **VALIDATE**

![DIY](/images/10-database/10.4-diy/00011-diy.png)

12. In the **DIY** interface

- After selecting **VALIDATE**, the **VALIDATION MESSAGE** interface appears **Nice. you have a read replica running properly...**
- Complete the lesson **DIY**
- Select **EXIT** to exit and return to the city interface

![DIY](/images/10-database/10.4-diy/00012-diy.png)

13. After returning to the city interface

- Select **NEXT**

![DIY](/images/10-database/10.4-diy/00013-diy.png)

14. Select **COLLECT**

![DIY](/images/10-database/10.4-diy/00014-diy.png)

15. Congratulations to the player on completing the lab

![DIY](/images/10-database/10.4-diy/00015-diy.png)