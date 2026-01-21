---
title : "Practice"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 10.3 </b> "
---

{{% notice info %}}

Sau khi xem **Plan**, người chơi chuẩn bị cho **Practice**

{{% /notice %}}


1. Trong giao diện **Practice**

- Đọc bước 1 của **Database in Practice**
- Đọc **CONCEPT**
- Chọn **START LAB**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/0001-practice.png)

2. Trong giao diện **Learn**

- Đọc bước 2 của **Database in Practice**
- Đọc **CONCEPT**
- Chọn **Open AWS Console**

![Practice](/images/10-database/10.3-practice/0002-practice.png)

3. Trong giao diện **AWS Console**

- Tìm **RDS**
- Chọn **RDS**

![Practice](/images/10-database/10.3-practice/0003-practice.png)

4. Trong giao diện *Practice**

- Đọc bước 3 của **Database in Practice**
- Chọn **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/0004-practice.png)

5. Trong giao diện **Practice**

- Đọc bước 4 của **Database in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/10-database/10.3-practice/0005-practice.png)

6. Trong giao diện **RDS**

- Chọn **Databases**
- Chọn **Create database**
- Trong **Choose a database creation method**, chọn **Standard create**
- Trong **Engine options**, chọn **MariaDB**


![Practice](/images/10-database/10.3-practice/0006-practice.png)

7. Trong giao diện **Practice**

- Đọc bước 5 của **Database in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/0007-practice.png)

8. Trong giao diện **RDS**

- **Version**, chọn **MariaDB 10.4.13**
- **Templates**, chọn **Dev/Test**

![Practice](/images/10-database/10.3-practice/0008-practice.png)

9. Trong giao diện **Practice**

- Đọc bước 6 của **Databases in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/0009-practice.png)

10. Trong giao diện **RDS**

- **DB instance identifier**, nhập ```my-database```
- **Master username**, nhập ```admin```
- **Master password**, nhập ```123456789admin```
- **Confirm password**, nhập ```123456789admin```

![Practice](/images/10-database/10.3-practice/00010-practice.png)

11. Trong giao diện **Practice**

- Đọc bước 7 của **Databases in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00011-practice.png)

12. Trong giao diện **RDS**

- Trong **DB instance class**, chọn **Burstable classes (includes t classes)**
- Chọn **db.t3.large**
- Trong **Storage type**, chọn **General Purpose SSD (gp2)**
- Trong **Allocated storage**, nhập ```20```

![Practice](/images/10-database/10.3-practice/00012-practice.png)

13. Trong giao diện **Practice**

- Đọc bước 8 của **Databases in Practice**
- Chọn **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00013-practice.png)

14. Trong giao diện **RDS**

- Trong **Storage autoscaling**, chọn **Enable storage autoscaling**
- Trong **Maximum storage threshold**, nhập ```1000```
- Trong **Multi-AZ deployment**, chọn **Create a standby instance (recommended production usage)**

![Practice](/images/10-database/10.3-practice/00014-practice.png)

15. Trong giao diện **Practice**

- Đọc bước 9 của **Databases in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00015-practice.png)

16. Trong giao diện **Connectivity**

- Chọn **VPC** mặc định
- Chọn **Subnet group** mặc định 
- Trong **Public access**, chọn **No**
- Trong **VPC security group**, chọn **Choose existing**
- Trong **Existing VPC security groups**, chọn **default**


![Practice](/images/10-database/10.3-practice/00016-practice.png)

17. Trong giao diện **Practice**

- Đọc bước 10 của **Databases in Practice**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00017-practice.png)

18. Trong giao diện **Additional configuration**

- Trong **Initial database name**, nhập ```my_database```
- Trong **DB parameter group**, chọn **default:mariadb-10-4**
- Trong **Option group**, chọn **default:mariadb-10-4**
- Trong **Backup**, chọn **Enable automated backups**
- Trong **Backup window**, chọn **No preference**
- Chọn **Copy tags to snapshots**

![Practice](/images/10-database/10.3-practice/00018-practice.png)

19. Trong giao diện **Practice**

- Đọc bước 11 của **Databases in Practice**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00019-practice.png)

20. Trong giao diện **RDS**

- Trong **Encrytion**, chọn **Enable encrytion**
- Trong **Performance Insights**, bỏ chọn **Enable Performance Insights**
- Trong **Monitoring**, bỏ chọn **Enable Enhanced monitoring**

![Practice](/images/10-database/10.3-practice/00020-practice.png)

21. Trong giao diện **Practice**

- Trong bước 12 của **Databases in Practice**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00021-practice.png)

22. Trong giao diện **Create database**

- Trong **Maintenance**, bỏ chọn **Enable auto minor version upgrade**
- Trong **Maintenance window**, chọn **No preference**
- Xem **Estimated monthly costs**
- Chọn **Create database**

![Practice](/images/10-database/10.3-practice/00022-practice.png)

23. Trong giao diện **Practice**

- Đọc bước 13 của **Databases in Practice**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/10-database/10.3-practice/00023-practice.png)

24. Chúc mừng người chơi đã hoàn thành bài lab

![Practice](/images/10-database/10.3-practice/00024-practice.png)

25. Xem lại **my-database** vừa tạo

![Practice](/images/10-database/10.3-practice/00025-practice.png)



