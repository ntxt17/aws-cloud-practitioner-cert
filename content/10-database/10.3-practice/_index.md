---
title : "Practice"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 10.3 </b> "
---

{{% notice info %}}

After watching **Plan**, the player prepares for **Practice**

{{% /notice %}}


1. In the **Practice** interface

- Read step 1 of **Database in Practice**
- Read **CONCEPT**
- Select **START LAB**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/0001-practice.png)

2. In the **Learn** interface

- Read step 2 of **Database in Practice**
- Read **CONCEPT**
- Select **Open AWS Console**

![Practice](/images/10-database/10.3-practice/0002-practice.png)

3. In the **AWS Console** interface

- Find **RDS**
- Select **RDS**

![Practice](/images/10-database/10.3-practice/0003-practice.png)

4. In the *Practice** interface

- Read step 3 of **Database in Practice**
- Select **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/0004-practice.png)

5. In the **Practice** interface

- Read step 4 of **Database in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps


![Practice](/images/10-database/10.3-practice/0005-practice.png)

6. In the **RDS** interface

- Select **Databases**
- Select **Create database**
- In **Choose a database creation method**, select **Standard create**
- In **Engine options**, select **MariaDB**


![Practice](/images/10-database/10.3-practice/0006-practice.png)

7. In the **Practice** interface

- Read step 5 of **Database in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/0007-practice.png)

8. In the **RDS** interface

- **Version**, select **MariaDB 10.4.13**
- **Templates**, select **Dev/Test**

![Practice](/images/10-database/10.3-practice/0007-practice.png)

8. In the **RDS** interface

- **Version**, select **MariaDB 10.4.13**
- **Templates**, select **Dev/Test**

![Practice](/images/10-database/10.3-practice/0008-practice.png)

9. In the **Practice** interface

- Read step 6 of **Databases in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/0009-practice.png)

10. In the **RDS** interface

- **DB instance identifier**, enter ```my-database```
- **Master username**, enter ```admin```
- **Master password**, enter ```123456789admin```
- **Confirm password**, enter ```123456789admin```

![Practice](/images/10-database/10.3-practice/00010-practice.png)

11. In the **Practice** interface

- Read step 7 of **Databases in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00011-practice.png)

12. In the **RDS** interface

- In **DB instance class**, select **Burstable classes (includes t classes)**
- Select **db.t3.large**
- In **Storage type**, select **General Purpose SSD (gp2)**
- In **Allocated storage**, enter ```20```

![Practice](/images/10-database/10.3-practice/00012-practice.png)

13. In the **Practice** interface

- Read step 8 of **Databases in Practice**
- Select **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00013-practice.png)

14. In the **RDS** interface

- In **Storage autoscaling**, select **Enable storage autoscaling**
- In **Maximum storage threshold**, enter ```1000```
- In **Multi-AZ deployment**, select **Create a standby instance (recommended production usage)**

![Practice](/images/10-database/10.3-practice/00014-practice.png)

15. In the **Practice** interface

- Read step 9 of **Databases in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00015-practice.png)

16. In the **Connectivity** interface

- Choose the default **VPC**
- Select the default **Subnet group**
- In **Public access**, select **No**
- In **VPC security group**, select **Choose existing**
- In **Existing VPC security groups**, select **default**


![Practice](/images/10-database/10.3-practice/00016-practice.png)

17. In the **Practice** interface

- Read step 10 of **Databases in Practice**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00017-practice.png)

18. In the **Additional configuration** interface

- In **Initial database name**, enter ```my_database```
- In **DB parameter group**, select **default:mariadb-10-4**
- In **Option group**, select **default:mariadb-10-4**
- In **Backup**, select **Enable automated backups**
- In **Backup window**, select **No preference**
- Select **Copy tags to snapshots**

![Practice](/images/10-database/10.3-practice/00018-practice.png)

19. In the **Practice** interface

- Read step 11 of **Databases in Practice**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00019-practice.png)

20. In the **RDS** interface

- In **Encrytion**, select **Enable encrytion**
- In **Performance Insights**, uncheck **Enable Performance Insights**
- In **Monitoring**, uncheck **Enable Enhanced monitoring**

![Practice](/images/10-database/10.3-practice/00020-practice.png)

21. In the **Practice** interface

- In step 12 of **Databases in Practice**
- Select the arrow to the right to see the next steps

![Practice](/images/10-database/10.3-practice/00021-practice.png)

22. In the **Create database** interface

- In **Maintenance**, uncheck **Enable auto minor version upgrade**
- In **Maintenance window**, select **No preference**
- View **Estimated monthly costs**
- Select **Create database**

![Practice](/images/10-database/10.3-practice/00022-practice.png)

23. In the **Practice** interface

- Read step 13 of **Databases in Practice**
- Select the right arrow to see the next steps

![Practice](/images/10-database/10.3-practice/00023-practice.png)

24. Congratulations to the player on completing the lab

![Practice](/images/10-database/10.3-practice/00024-practice.png)

25. Review **my-database** just created

![Practice](/images/10-database/10.3-practice/00025-practice.png)