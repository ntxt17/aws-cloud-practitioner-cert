---
title : "Practice"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 15.3 </b> "
---

{{% notice info %}}

Sau khi xem **Plan**, người chơi chuẩn bị cho **Practice**

{{% /notice %}}

1. Trong giao diện **Practice**

- Đọc bước 1 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn **START LAB**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/0001-practice.png)

2. Trong giao diện **Practice**

- Đọc bước 2 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn **Open AWS Console**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/0002-practice.png)

3. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![Practice](/images/15-highlyavailable/15.3-practice/0003-practice.png)

4. Trong giao diện **Practice**

- Đọc bước 3 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/0004-practice.png)

5. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencuWebServers**
- Xem chi tiết về **Desired capacity**, **Minimum capacity**, **Maximum capacity**

![Practice](/images/15-highlyavailable/15.3-practice/0005-practice.png)

6. Trong giao diện **Pracitce**

- Đọc bước 4 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/0006-practice.png)

7. Trong giao diện **Auto Scaling groups**

- Chọn **Instance management**
- Xem instance

![Practice](/images/15-highlyavailable/15.3-practice/0007-practice.png)

8. Trong giao diện **Practice**

- Đọc bước 5 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/0008-practice.png)

9. Trong giao diện **Auto Scaling groups**

- Chọn **Deatils**

![Practice](/images/15-highlyavailable/15.3-practice/0009-practice.png)

10. Trong giao diện **Practice**

- Đọc bước 6 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00010-practice.png)

11. Trong giao diện **Auto Scaling groups**

- Trong **Network**, xem **Subnet ID**
- Trong **Load balancing**, chọn **Edit**


![Practice](/images/15-highlyavailable/15.3-practice/00011-practice.png)

12. Trong giao diện **Practice**

- Đọc bước 7 của **highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/00012-practice.png)

13. Trong giao diện **Edit TravleAgencyWebServers**

- Chọn **Add a new load balancer**


![Practice](/images/15-highlyavailable/15.3-practice/00013-practice.png)

14. Trong giao diện **Practice**


- Đọc bước 8 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00014-practice.png)

15. Trong giao diện **Edit TravleAgencyWebServers**

- Chọn **Application Load Balancer**
- Trong **Load balancer scheme**, chọn **Internet-facing**


![Practice](/images/15-highlyavailable/15.3-practice/00015-practice.png)

16. Trong giao diện **Practice**

- Đọc bước 9 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/00016-practice.png)

17. Trong giao diện **Availability Zone and subnets**

- Chọn tất cả 3 availability zone
- Chọn **Public subnet**
- Trong **Default routing (forward to)**, chọn **Create a target group**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00017-practice.png)

18. Trong giao diện **Practice**

- Đọc bước 10 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/00018-practice.png)

19. Trong giao diện **VPC**

- Chọn **Security Groups**
- Chọn **Create security group**


![Practice](/images/15-highlyavailable/15.3-practice/00019-practice.png)

20. Trong giao diện **Practice**

- Đọc bước 11 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/15-highlyavailable/15.3-practice/00020-practice.png)

21. Trong giao diện **Create security group**

- **Security group name**, nhập ```TravelAgencyLoadBalancer```
- **Description**, nhập ```Allow access to the Travel Agency Balancer from the Internet```
- Chọn **VPC**
- Trong **Inbound rules**, chọn **Add rule**


![Practice](/images/15-highlyavailable/15.3-practice/00021-practice.png)

22. Kết qủa sau khi nhập thông tin

![Practice](/images/15-highlyavailable/15.3-practice/00022-practice.png)

23. Trong giao diện **Practice**
    
- Đọc bước 12 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00023-practice.png)

24. Trong giao diện **Create security group**

- Trong **Inbound rules**, chọn **HTTP**, chọn **Source** là **Custom**, chọn ```0.0.0.0/0```
- Trong **Outbound rules**, chọn **HTTP**, chọn **Destination** là **Custom**, chọn **Security group**

![Practice](/images/15-highlyavailable/15.3-practice/00024-practice.png)

25. Trong giao diện **Practice**


- Đọc bước 13 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00025-practice.png)

26. Trong giao diện **Create security group**

- Chọn **Create security group**

![Practice](/images/15-highlyavailable/15.3-practice/00026-practice.png)

27. Trong giao diện **Practice**

- Đọc bước 14 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00027-practice.png)

28. Trong giao diện **Security Groups**

- Chọn **Security Groups**
- Chọn **TravelAgencyWebServer**
- Chọn **Actions**
- Chọn **Edit inblound rules**

![Practice](/images/15-highlyavailable/15.3-practice/00028-practice.png)

29. Trong giao diện **Practice**

- Đọc bước 15 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00029-practice.png)

30. Trong giao diện **Inbound rules**

- Chọn **Delete**
- Chọn **Add rule**

![Practice](/images/15-highlyavailable/15.3-practice/00030-practice.png)

31. Trong giao diện **Practice**


- Đọc bước 16 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00031-practice.png)

32. Trong giao diện **Edit inbound rules**

- Chọn **HTTP**
- Chọn **TravelAgencyLoadBalancer** security group
- Chọn **Save rules**

![Practice](/images/15-highlyavailable/15.3-practice/00032-practice.png)

33. Trong giao diện **Practice**


- Đọc bước 17 của **Highly Available Web Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00033-practice.png)

34. Trong giao diện **Practice**

- Đọc bước 18 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00034-practice.png)

35. Trong giao diện **VPC**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServers-1 ALB**
- Chọn **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00035-practice.png)

36. Trong giao diện **Practice**

- Đọc bước 19 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00036-practice.png)

37. Trong giao diện **Security groups**

- Chọn **Edit security groups**
- Chọn **TravelAgencyLoadBalancer**
- Bỏ chọn **TravelAgencyWebServer**
- Chọn **Save**

![Practice](/images/15-highlyavailable/15.3-practice/00037-practice.png)

38. Trong giao diện **Practice**

- Đọc bước 20 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00038-practice.png)

39. Trong giao diện **VPC**

- Chọn **Load Balancers**
- Chọn **TravelAgencyWebServer-1 ALB**
- Trong **Description**, sao chép **ALB DNS name**

![Practice](/images/15-highlyavailable/15.3-practice/00039-practice.png)

40. Trong giao diện **Practice**

- Đọc bước 21 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00040-practice.png)

41. Mở trình duyệt

- Dán **ALB DNS name** vào
- Chọn **Enter**
- Xem kết quả

![Practice](/images/15-highlyavailable/15.3-practice/00041-practice.png)

42. Trong giao diện **Practice**

- Đọc bước 22 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00042-practice.png)

43. Trong giao diện trình duyệt

- Thêm vào cuối **ALB DNS name**: ```/health```
- Xem kết quả

![Practice](/images/15-highlyavailable/15.3-practice/00043-practice.png)

44. Trong giao diện **Practice**

- Đọc bước 23 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00044-practice.png)

45. Trong giao diện **VPC**

- Chọn **Target Groups**
- Chọn **TravelAgencyWebServers-1 target group**
- Chọn **Health checks**
- Chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00045-practice.png)

46. Trong giao diện **Practice**

- Đọc bước 24 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00046-practice.png)

47. Trong giao diện **Edit health check settings**

- Trong **Health check path**, nhập ```/health```
- Chọn **Advanced health checks settings**

![Practice](/images/15-highlyavailable/15.3-practice/00047-practice.png)

48. Trong giao diện **Practice**

- Đọc bước 25 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00048-practice.png)

49. Trong giao diện **Advanced health check settings**

- **Port**, nhập ```80```
- **Healthy threshold**, nhập ```5```
- **Unhealthy threshold**, nhập ```2```
- **Timeout**, nhập ```2```
- **Interval**, nhập ```5```
- **Success code**, nhập ```200```
- Chọn **Save changes**

![Practice](/images/15-highlyavailable/15.3-practice/00049-practice.png)

50. Trong giao diện **Practice**
    
- Đọc bước 26 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00050-practice.png)

51. Trong giao diện **VPC**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers Auto Scaling group**
- Trong **Network**, chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00051-practice.png)

52. Trong giao diện **Practice**

- Đọc bước 10 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00052-practice.png)

53. Trong giao diện **Edit TravelAgencyWebServers**

- Chọn **lab/TravelAgencyVpc/PrivateSubnet1 subnet**
- Bỏ chọn **lab/TravelAgencyVpc/PublicSubnet1 subnet**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00053-practice.png)

54. Trong giao diện **Practice**

- Đọc bước 28 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00054-practice.png)

55. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **lab/TravelAgencyWebServers instance**
- Chọn **Networking**
- Xem **Subnet ID**
- Chọn **instance state**
- Chọn **Terminate instance**

![Practice](/images/15-highlyavailable/15.3-practice/00055-practice.png)

56. Trong giao diện **Terminate instance**

- Chọn **Terminate**

![Practice](/images/15-highlyavailable/15.3-practice/00056-practice.png)

57. Trong giao diện **Practice**

- Đọc bước 29 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00057-practice.png)

58. Trong giao diện **EC2**

- Chọn **refresh**
- Chọn **new instance**
- Chọn **Networking**
- Xem **Subnet ID**

![Practice](/images/15-highlyavailable/15.3-practice/00058-practice.png)

59. Trong giao diện **Practice**

- Đọc bước 30 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00059-practice.png)

60. Trong giao diện **VPC**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers Auto Scaling group**
- Chọn **Activity**
- Xem **Activity history**

![Practice](/images/15-highlyavailable/15.3-practice/00060-practice.png)

61. Trong giao diện **Practice**

- Đọc bước 31 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00061-practice.png)

62. Trong giao diện **Activity history**

- Xem **Status**
- Xem **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00062-practice.png)

63. Trong giao diện **Practice**

- Đọc bước 32 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00063-practice.png)

64. Trong trình duyệt **health check**

- Chọn **refesh**
- Xem kết qủa

![Practice](/images/15-highlyavailable/15.3-practice/00064-practice.png)

65. Trong giao diện *Practice**

- Đọc bước 33 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00065-practice.png)

66. Trong giao diện **VPC**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers Auto Scaling group**
- Trong **Network**, chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00066-practice.png)

67. Trong giao diện **Edit TravelAgencyWebServers**

- Chọn **lab/TravelAgency/Vpc/PrivateSubnet2**
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00067-practice.png)

68. Trong giao diện **Practice**

- Đọc bước 35 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00068-practice.png)

69. Trong giao diện **VPC**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers Auto Scaling group**
- Trong **Group details**, chọn **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00069-practice.png)

70. Trong giao diện **Practice**

- Đọc bước 36 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00070-practice.png)

71. Trong giao diện **Group size**

- Trong **Desired capacity**, nhập ```2```
- Trong **Maximum capacity**, nhập ```2```
- Chọn **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00071-practice.png)

72. Trong giao diện **Practice**

- Đọc bước 37 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00072-practice.png)

73. Trong giao diện **EC2**

- Chọn **Auto Scaling Groups**
- Chọn **TravelAgencyWebServers Auto Scaling group**
- Chọn **Activity**
- Kéo xuống **Activity history**

![Practice](/images/15-highlyavailable/15.3-practice/00073-practice.png)

74. Trong giao diện **Practice**

- Đọc bước 38 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00074-practice.png)

75. Trong giao diện **Auto Scaling groups**

- Trong **Activity history**, xem **Status** và **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00075-practice.png)

76. Trong giao diện **Practice**

- Đọc bước 39 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00076-practice.png)

77. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **new instance ID**
- Chọn **Networking**
- Xem **Subnet ID**

![Practice](/images/15-highlyavailable/15.3-practice/00077-practice.png)

78. Trong giao diện **Practice**

- Đọc bước 40 của **Highly Available Web Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/15-highlyavailable/15.3-practice/00078-practice.png)

79. Trong trình duyệt **health check**

- **Refresh**
- Xem kết quả

![Practice](/images/15-highlyavailable/15.3-practice/00079-practice.png)

80. Chúc mừng người chơi đã hoàn thành bài lab

![Practice](/images/15-highlyavailable/15.3-practice/00080-practice.png)
