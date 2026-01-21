---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 10.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**

- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/10-database/10.4-diy/0001-diy.png)

2. Trong giao diện **AWS Console**

- Tìm **RDS**
- Chọn **RDS**

![DIY](/images/10-database/10.4-diy/0002-diy.png)

3. Trong giao diện **Amazon RDS**

- Chọn **Databases**

![DIY](/images/10-database/10.4-diy/0003-diy.png)

4. Trong giao diện **Databases**

- Chọn **my-database**
- Chọn **Actions**
- Chọn **Create read replica**

![DIY](/images/10-database/10.4-diy/0004-diy.png)

5. Trong giao diện **Create read replica DB instance**

- Trong **DB instance class**, chọn **db.t3.xlarge-4 vCPU**
- Trong **Multi-AZ deployment**, chọn **Yes**
- Trong **Storage type**, chọn **General Purpose (SSD)**

![DIY](/images/10-database/10.4-diy/0005-diy.png)

6. Trong giao diện **Network & Security**

- Trong **Destination region**, chọn **US East (N. Virginia)**
- Trong **Destination DB subnet group**, chọn **default-vpc**
- Trong **Publicly accessible**, chọn **No**
- Trong **VPC security groups**, chọn **default**

![DIY](/images/10-database/10.4-diy/0006-diy.png)

7. Trong giao diện **RDS**

- Trong **Read replica source**, nhập ```my-database```
- Trong **DB instance identifier**, nhập ```my-database-read-replica```
- Trong giao diện **Database options**, trong **Database port**, nhập ```3306```
- Chọn **Copy tags to snapshots**

![DIY](/images/10-database/10.4-diy/0007-diy.png)

8. Trong giao diện **RDS**

- Trong **Monitoring**, bỏ chọn **Disable enhanced monitoring**
- Trong **Performance Insights**, bỏ chọn **Disable Performance Insights**

![DIY](/images/10-database/10.4-diy/0008-diy.png)

9. Trong giao diện **RDS**

- Trong **Maintenance**, chọn **No**
- Chọn **Create read replica**

![DIY](/images/10-database/10.4-diy/0009-diy.png)

10. Xem kết quả khởi tạo 


![DIY](/images/10-database/10.4-diy/00010-diy.png)

11. Trong giao diện **DIY**

- Sao chép và dán **Your RDS DB identifier**
- Sao chép và dán **ypur read replica DB identifier**
- Chọn **VALIDATE**

![DIY](/images/10-database/10.4-diy/00011-diy.png)

12. Trong giao diện **DIY**

- Sau khi chọn **VALIDATE**, giao diện **VALIDATION MESSAGE** xuất hiện **Nice. you have a read replica running properly...**
- Hoàn thành bài **DIY**
- Chọn **EXIT** để thoát và quay về giao diện thành phố

![DIY](/images/10-database/10.4-diy/00012-diy.png)

13. Sau khi quay lại giao diện thành phố

- Chọn **NEXT**

![DIY](/images/10-database/10.4-diy/00013-diy.png)

14. Chọn **COLLECT**

![DIY](/images/10-database/10.4-diy/00014-diy.png)

15. Chúc mừng người chơi đã hoàn thành bài lab

![DIY](/images/10-database/10.4-diy/00015-diy.png)
