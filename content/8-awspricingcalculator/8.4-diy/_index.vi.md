---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 8.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**
- Đọc **DIY ACTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/8-awspricingcalculator/8.4-diy/0000-diy.png)

2. Truy cập vào trang [AWS Pricing Calculator](https://calculator.aws/#/)

- Chọn **Create estimate**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/0001-diy.png)

3. Trong **My Estimate**

- Chọn **Add group**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/0003-diy.png)

4. Trong **Add group**
- **Group name**, nhập ```Web Servers```
- Chọn **Add group**

![DIY](/images/8-awspricingcalculator/8.4-diy/0004-diy.png)

5. Trong giao diện **Web Servers**
- Chọn **Add service**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/0005-diy.png)

6. Trong **Add service**

- Tìm kiếm **EC2**
- Chọn **Configure**

![DIY](/images/8-awspricingcalculator/8.4-diy/0006-diy.png)

7. Trong **Configure Amazon EC2**
- **Description**, nhập ```Web Server Estimate```
- **Region**, chọn **US East (N. Virginia)**
- Trong **EC2 instance specifications**, chọn **Linux**
![DIY](/images/8-awspricingcalculator/8.4-diy/0007-diy.png)

8. Trong giao diện **Workload**
- Chọn **Daily spike traffic**
- **Daily spike pattern**, phần **Workload days**, chọn các ngày trong tuần
- **Baseline**, nhập ```2```
- **Peak**, nhập ```4```
- **Duration of peak**, nhập ```8``` và ```0```

![DIY](/images/8-awspricingcalculator/8.4-diy/0008-diy.png)

9. Trong **EC2 Instances**
- Chọn **t2.micro**

![DIY](/images/8-awspricingcalculator/8.4-diy/0009-diy.png)

10. Trong **Pricing strategy**

- **Pricing model**, chọn **On-demand**
- Chọn **Show calculations**
- Chọn **estimate workload hours**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/00010-diy.png)

11. Trong **Amazon Elastic Block Storage (EBS)**

- **Storage for each EC2 instance**, chọn **General Purpose SSD (gp2)**
- **Storage amount**, nhập ```30```
- **Snapshot Frequency**, nhập ```Weekly```
- **Amount changed per snapshot**, nhập ```1```
  
![DIY](/images/8-awspricingcalculator/8.4-diy/00011-diy.png)

12. Xem kết quả **Estimated workload hours**

![DIY](/images/8-awspricingcalculator/8.4-diy/00012-diy.png)

13. Trong **Data Transfer**
- **Inbound Data Transfer**, chọn **Internet (free)**
- Chọn ```1```
- Chọn **TB per month**
- **Outbound Data Transfer**, chọn **Internet (0.05 USD - 0.09 USD per GB)**
- Chọn ```100```
- Chọn **TB per month**
  
![DIY](/images/8-awspricingcalculator/8.4-diy/00013-diy.png)

14. Chọn **Show calculations**

- Xem và chọn **Add to my estimate**

![DIY](/images/8-awspricingcalculator/8.4-diy/00014-diy.png)

15. Trong giao diện **Web Servers**

- Chọn **Share**

![DIY](/images/8-awspricingcalculator/8.4-diy/00015-diy.png)

16 Trong giao diện **Save estimate**

- Chọn **Copy public link**

![DIY](/images/8-awspricingcalculator/8.4-diy/00016-diy.png)

17. Sau khi **Copy public link**
- Vào giao diện **DIY**
- Dán vào **VALIDATION FORM**
- Chọn **VALIDATE**
- Trên **VALIDATION MESSAGE**, xuất hiện **Great job!...** là hoàn thành **DIY**
- Sau đó chọn **EXIT** để thoát
  
![DIY](/images/8-awspricingcalculator/8.4-diy/00017-diy.png)

18. Sau khi ra giao diện thành phố 

- Vào **ASSIGNMENT**, chọn **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/00018-diy.png)

19. Chọn **NEXT**

![DIY](/images/8-awspricingcalculator/8.4-diy/00019-diy.png)

20. Chọn **COLLECT**

![DIY](/images/8-awspricingcalculator/8.4-diy/00020-diy.png)

21. Chúc mừng người chơi nhận thưởng

![DIY](/images/8-awspricingcalculator/8.4-diy/00021-diy.png)