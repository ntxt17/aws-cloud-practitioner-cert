---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 15.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **DIY**

- Đọc **DIY ACCTIVITIES**
- Đọc **SOLUTION VALIDATION METHOD**

![DIY](/images/15-highlyavailable/15.4-diy/0001-diy.png)

2. Trong giao diện **DIY**

- Chọn **START LAB**

![DIY](/images/15-highlyavailable/15.4-diy/0003-diy.png)

3. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/15-highlyavailable/15.4-diy/0004-diy.png)

4. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **lab/TravelAgencyWebServers**
- Chọn **Details** để xem chi tiết instance


![DIY](/images/15-highlyavailable/15.4-diy/0005-diy.png)

5. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** auto scaling group
- Chọn **Details** để xem chị tiết auto scaling group


![DIY](/images/15-highlyavailable/15.4-diy/0006-diy.png)

6. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Chọn **Instance management**
- Xem thông tin instance

![DIY](/images/15-highlyavailable/15.4-diy/0007-diy.png)

7. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers**
- Chọn **Details** xem **Desired capacity**, **Minimum capacity**, **Maximum capacity**

![DIY](/images/15-highlyavailable/15.4-diy/0008-diy.png)

8. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Trong **Network**, xem thông tin **Subnet ID**
- Trong **Load balancing**, chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/0009-diy.png)

9. Trong giao diện **Edit TravelAgencyWebServers**

- Chọn **Add a new load balancer**

![DIY](/images/15-highlyavailable/15.4-diy/00010-diy.png)

10. Trong giao diện **Load balancing**

- **Load balancer type**, chọn **Application Load Balancer**
- **Load balancer scheme**, chọn **Internet-facing**

![DIY](/images/15-highlyavailable/15.4-diy/00011-diy.png)

11. Tron giao diện **Edit TravelAgencyWebServers**

- **Availability Zones and subnets**, chọn cả 3 *AZ** và subnet
- Trong **Default routing (forward to)**, chọn **Create a target group**
- Chọn **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00012-diy.png)

12. Trong giao diện **Auto Scaling Groups**

- Xem kết quả update
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Chọn **Details** để xem chi tiết

![DIY](/images/15-highlyavailable/15.4-diy/00013-diy.png)

13. Trong giao diện **EC2**

- Chọn **Security Groups**
- Chọn **Create security group**

![DIY](/images/15-highlyavailable/15.4-diy/00014-diy.png)

14. Trong giao diện **Create security group**

- **Security group name**, nhập ```TravelAgencyLoadBalancer```
- Trong **Decription**, nhập ```Allow access to the Travel Agency Load Balancer from the Internet```
- Trong **VPC**, chọn **lab/TravelAgencyVpc**
- Chọn **Add rule**


![DIY](/images/15-highlyavailable/15.4-diy/00015-diy.png)

15. Trong giao diện **Create Security group**

- **Inbound rules**, chọn **HTTP**
- **Oubound rules**, chọn **HTTP**
- Chọn **Create security group**

![DIY](/images/15-highlyavailable/15.4-diy/00016-diy.png)

16. Trong giao diện **EC2**

- Chọn **Security Groups**
- Chọn **TravelAgencyWebServer** security group*
- Chọn **Actions**
- Chọn **Edit inbound rules**

![DIY](/images/15-highlyavailable/15.4-diy/00017-diy.png)

17. Trong giao diện **Edit inbound rules**

- Chọn **Delete**
- Chọn **Add rule**

![DIY](/images/15-highlyavailable/15.4-diy/00018-diy.png)

18. Trong giao diện **Edit Inbound rules**

- Chọn **HTTP**
- **Source** chọn **Custom**, chọn **TravelAgencyLoadBalancer**
- Chọn **Sae rules**

![DIY](/images/15-highlyavailable/15.4-diy/00019-diy.png)

19. Trong giao diện **EC2**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServers-1** Load Balancer
- Chọn **Description** để xem thông tin mô tả

![DIY](/images/15-highlyavailable/15.4-diy/00020-diy.png)

20. Trong giao diện **Load Balancer**

- Chọn **Edit security groups**
- Chọn **TravelAgencyLoadBalancer** security group
- Bỏ chọn **TravelAgencyWebServer** security group


![DIY](/images/15-highlyavailable/15.4-diy/00021-diy.png)

21. Trong giao diện **EC2**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServer-1** Load Balancer
- Trong **Description**, xem và sao chép **DNS name**

![DIY](/images/15-highlyavailable/15.4-diy/00022-diy.png)

22. Mở trình duyệt

- Dán **DNS name** vào trình duyệt
- Chọn **Enter** và xem giao diện

![DIY](/images/15-highlyavailable/15.4-diy/00023-diy.png)

23. Trong trình duyệt 

- Theo vào cuối **DNS name**: ```/health```
- Xem kết quả

![DIY](/images/15-highlyavailable/15.4-diy/00024-diy.png)

24. Trong giao diện **EC2**'

- Chọn **Target Groups**
- Chọn **TravelAgencyWebServers** target group
- Chọn **Health checks**

![DIY](/images/15-highlyavailable/15.4-diy/00025-diy.png)

25. Trong giao diện **Edit health check settings**

- Trong **Health check path**, nhập ```/health```
- Chọn **Advanced health check settings**

![DIY](/images/15-highlyavailable/15.4-diy/00026-diy.png)

26. Trong giao diện **Advanced health check settings**

- Trong **Unhealthly threshold**, nhập ```2```
- Trong **Timeout**, nhập ```2```
- Trong **Interval**, nhập ```5```
- Chọn **Save changes**

![DIY](/images/15-highlyavailable/15.4-diy/00027-diy.png)

27. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServer** Auto Scaling Group
- Trong **Network**, xem **Subnet ID**
- Chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00028-diy.png)

28. Trong giao diện **Edit TravelAgencyWebServers**

- Trong **Availability Zones and subnets**, chọn **lab/TravelAgencyVpc/PrivateSubnet1**

![DIY](/images/15-highlyavailable/15.4-diy/00029-diy.png)

29. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **lab/TravelAgencyWebServers** instance
- Chọn **Networking**
- Xem **Subnet ID** vừa chỉnh sửa
- Chọn **Instance state**
- Chọn **Terminate instance**

![DIY](/images/15-highlyavailable/15.4-diy/00030-diy.png)

30. Trong giao diện **Terminate instance**

- Chọn **Terminate**

![DIY](/images/15-highlyavailable/15.4-diy/00031-diy.png)

31. Trong giao diện **Instances**

- Chọn **refresh**
- Chọn **lab/TravelAgencyWebServers** instance
- Chọn **Networking**
- Xem **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00032-diy.png)

32. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Xem **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00033-diy.png)

33. Trong trình duyệt **health check**

- Chọn **Refresh**
- Xem kết quả

![DIY](/images/15-highlyavailable/15.4-diy/00034-diy.png)

34. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TraveAgencyWebServers**
- Trong **Network**, chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00035-diy.png)

35. Trong giao diện **Edit TravelAgencyWebServers**

- Trong **Availability Zones and sunets**, chọn **lab/TravelAgencyVpc/PrivateSubnet2**
- Chọn **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00036-diy.png)

36. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Xem kết quả update
- Chọn **TravelAgencyWebServers** Auto Scaling group
- Chọn **Details** để xem chi tiết
- Trong **Group details** chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00037-diy.png)

37. Trong giao diện **Group size**

- **Desired capacity**, nhập ```2```
- **Minimum capacity**, nhập ```1```
- **Maximum capacity**, nhập ```2```
- Chọn **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00038-diy.png)

38. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravleAgencyWebServers** Auto Scaling Group
- Xem **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00039-diy.png)

39. Trong giao diện **EC2**

- Chọn **Instance**
- Chọn **lab/TravelAgencyWebServers**
- Chọn **Networking**
- Xem **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00040-diy.png)

40. Trong trình duyệt **health check**

- Chọn **Refresh**
- Xem kết quả 

![DIY](/images/15-highlyavailable/15.4-diy/00041-diy.png)

41. Trong giao diện **EC2*

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling group
- Trong **Network**, xem **Subnet ID**
- Chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00042-diy.png)

42. Trong giao diện **Edit TravelAgencyWebServers**

- Trong **Availability Zones and subnets**, chọn **lab/TravelAgencyVpc/PrivateSubnet3**

![DIY](/images/15-highlyavailable/15.4-diy/00043-diy.png)

43. Tron giao diện **Edit TravelAgencyWebServers**

- Trong **Network** gồm 3 subnet:
	- **lab/TravelAgencyVpc/PrivateSubnet1**
	- **lab/TravelAgencyVpc/PrivateSubnet2**
	- **lab/TravelAgencyVpc/PrivateSubnet3**

- Chọn **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00044-diy.png)

44. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Chọn **Details**, xem chi tiết **Group details**
- Chọn **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00045-diy.png)

45. Trong giao diện **Group size**

- **Desired capacity**, nhập ```3```
- **Minimum capacity**, nhập ```1```
- **Maximum capacity**, nhập ```3```
- Chọn **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00046-diy.png)

46. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Xem **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00047-diy.png)

47. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **lab/TravelAgencyWebServers** instance
- Chọn **Networking**
- Xem **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00048-diy.png)

48. Trong trình duyệt **health check**

- Chọn **Refesh**
- Xem kết quả

![DIY](/images/15-highlyavailable/15.4-diy/00049-diy.png)

49. Trong giao diện **Auto Scaling Group**

- Chọn **TravelAgencyWebServers** Auto Scaling Group
- Chọn **Details**
- Xem chi tiết **Group details**

![DIY](/images/15-highlyavailable/15.4-diy/00050-diy.png)

50. Trong giao diện **EC2**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServers-1** Load Balancer
- Chọn **Description** và xem thông tin mô tả
- Sao chép **Name** ALB
- Sao chép **Auto Scaling group name**

![DIY](/images/15-highlyavailable/15.4-diy/00051-diy.png)

51. Trong giao diện **DIY**

- Dán ```TravelAgencyWebServers-1``` vào **Your ALB name**
- Dán ```TravelAgencyWebSersers``` vào **Your Auto Scaling group name**
- Chọn **VALIDATE**

![DIY](/images/15-highlyavailable/15.4-diy/00052-diy.png)

52. Trong giao diện **DIY**

- Trong **VALIDATION MESSAGE** xuất hiện **Success! All 3 Availability Zones are covered by instances behind a Load Balancer**
- Chọn **EXIT** để về giao diện thành phố

![DIY](/images/15-highlyavailable/15.4-diy/00053-diy.png)

53. Trong giao diện thành phố

- Chọn **ASSIGNMENTS**
- CHọn **COLLECT**

![DIY](/images/15-highlyavailable/15.4-diy/00054-diy.png)

54. Chọn **NEXT**

![DIY](/images/15-highlyavailable/15.4-diy/00055-diy.png)

55. Chọn **COLLECT**

![DIY](/images/15-highlyavailable/15.4-diy/00056-diy.png)

56. Chúc mừng người chơi nhận thưởng


