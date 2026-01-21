---
title : "Practice"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 14.3 </b> "
---

{{% notice info %}}

Sau khi xem **Plan**, người chơi chuẩn bị cho **Practice**

{{% /notice %}}

1. Trong giao diện **Practice**

- Đọc bước 1 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn **START LAB**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/0001-practice.png)

2. Trong giao diện **Practice**

- Đọc bước 2 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn **Open AWS Console**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/0002-practice.png)

3. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![Practice](/images/14-scaling/14.3-practice/0003-practice.png)

4. Trong giao diện **Practice**

- Đọc bước 3 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/0004-practice.png)

5. Trong giao diện **EC2**

- Chọn **Instances**

![Practice](/images/14-scaling/14.3-practice/0005-practice.png)

6. Trong giao diện **Practice**

- Đọc bước 4 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/0006-practice.png)

7. Trong giao diện **Instances**

- Chọn **Game Server**

![Practice](/images/14-scaling/14.3-practice/0007-practice.png)

8. Trong giao diện **Practice**

- Đọc bước 5 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/0008-practice.png)

9. Trong giao diện **Instances**

- Xem chi tiết **Game Server**
- Sao chép **Public IPv4 address**


![Practice](/images/14-scaling/14.3-practice/0009-practice.png)

10. Mở trình duyệt

- Dán **Public IPv4 address**
- Chọn **Enter**
- Xem kết quả 

![Practice](/images/14-scaling/14.3-practice/00011-practice.png)

11. Trong giao diện **Practice**

- Đọc bước 7 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00012-practice.png)

12. Trong giao diện **EC2**

- Chọn **Instances**
- Chọn **Game Server**
- Chọn **Actions**
- Chọn **Image and templates**
- Chọn **Create image**

![Practice](/images/14-scaling/14.3-practice/00013-practice.png)

13. Trong giao diện **Practice**

- Đọc bước 8 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00014-practice.png)

14. Trong giao diện **Create image**

- **Image name**, nhập ```Game Server```
- **Image description**, nhập ```Regular customer game server```

![Practice](/images/14-scaling/14.3-practice/00015-practice.png)

15. Trong giao diện **Practice**

- Đọc bước 9 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00016-practice.png)

16. Trong giao diện **Create image**

- **Tag**, chọn **Tag image and snapshots together**
- Chọn **Create image**

![Practice](/images/14-scaling/14.3-practice/00017-practice.png)

17. Trong giao diện **Practice**

- Đọc bước 10 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00018-practice.png)

18. Trong giao diện **EC2**

- Chọn *AMIs**
- Chọn **Game Server**
- Chọn **refresh**
- Xem **Status**
- Chọn **Launch Templates**

![Practice](/images/14-scaling/14.3-practice/00019-practice.png)

19. Trong giao diện **Practice**

- Đọc bước 11 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00020-practice.png)

20. Trong giao diện **EC2 launch templates**

- Chọn **Create launch templates**

![Practice](/images/14-scaling/14.3-practice/00021-practice.png)


21. Trong giao diện **Practice**

- Đọc bước 12 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00022-practice.png)

22. Trong giao diện **Create lauch template**

- **Launch template name**, nhập ```GameServerTemplate```
- **Template version description**, nhập ```Regular customer game server templagte```
- Bỏ chọn **Provide guidance to help me set up a template tht I can use with  EC2 Auto Scaling**

![Practice](/images/14-scaling/14.3-practice/00023-practice.png)

23. Trong giao diện **Practice**

- Đọc bước 13 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00024-practice.png)

24. Trong giao diện **Create launch template**

- Chọn **AMIs**
- Chọn **Owned by me**
- Trong **Amazon Machine Image (AMI), chọn **GameServer**

![Practice](/images/14-scaling/14.3-practice/00025-practice.png)

25. Trong giao diện **Practice**

- Đọc bước 14 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00026-practice.png)

26. Trong giao diện **Create launch template**

- Trong *Instance type**, chọn **t2.nano**
- Chọn **Create new key pair**

![Practice](/images/14-scaling/14.3-practice/00027-practice.png)

27. Trong giao diện **Practice**

- Đọc bước 15 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00028-practice.png)

28. Trong giao diện **Create key pair**

- **Key pair name**, nhập ```GameServerKeyPair```
- **Key pair type**, chọn  **RSA**
- **Private key file format**, chọn **.pem**
- Chọn **Create key pair**

![Practice](/images/14-scaling/14.3-practice/00029-practice.png)

29. Trong giao diện **Practice**

- Đọc bước 16 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00030-practice.png)

30. Trong giao diện **Create launch template**

- Trong **Network settings**, chọn **Select existing security group**
- Chọn **WebServerSecurityGroup**

![Practice](/images/14-scaling/14.3-practice/00031-practice.png)

31. Trong giao diện **Practice**

- Đọc bước 17 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00032-practice.png)

32. Trong giao diện **Create launch template**

- Xem **Sumary**
- Chọn **Create launch template**

![Practice](/images/14-scaling/14.3-practice/00033-practice.png)

33. Giao diện khởi tạo template thành công 

- Chọn **View launch tempaltes**

![Practice](/images/14-scaling/14.3-practice/00034-practice.png)

34. Trong giao diện **Launch templates**

- Xem template vừa khởi tạo

![Practice](/images/14-scaling/14.3-practice/00035-practice.png)

35. Trong giao diện **Pracitce**

- Đọc bước 19 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00036-practice.png)

36. Trong giao diện **Launch templates**

- Chọn **Auto Scaling Groups**

![Practice](/images/14-scaling/14.3-practice/00037-practice.png)

37. Trong giao diện **Practice**

- Đọc bước 20 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00038-practice.png)

38. Trong giao diện **Amazon EC2 Auto Scaling**

- Chọn **Create Auto Scaling group**

![Practice](/images/14-scaling/14.3-practice/00039-practice.png)

39. Trong giao diện **Auto Scaling groups**

- Trong **Choose launch template or conriguration**
- **Auto Scaling group name**, nhập **```RegularCustomerGameServer```**
- **Launch template**, nhập ```GameServerTemplate```

![Practice](/images/14-scaling/14.3-practice/00040-practice.png)

40. Trong giao diện **Practice**

- Đọc bước 21 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00041-practice.png)

41. Trong giao diện **Auto Scaling**

- Chọn **Next**

![Practice](/images/14-scaling/14.3-practice/00042-practice.png)

42. Trong giao diện **Practice**

- Đọc bước 22 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00043-practice.png)

43. Trong giao diện **EC2 Auto Scaling Group**

- Trong **Choose instance launch options**
- Trong **Network**, Chọn **VPC**
- Chọn **Availability Zones và subnet

![Practice](/images/14-scaling/14.3-practice/00044-practice.png)

44. Trong giao diện **Practice**

- Đọc bước 23 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00045-practice.png)

45. Trong giao diện **EC2 Auto Scaling Group**

- Chọn **Next**

![Practice](/images/14-scaling/14.3-practice/00046-practice.png)

46. Trong giao diện **Practice**

- Đọc bước 24 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00047-practice.png)

47. Trong giao diện **EC2 Auto Scaling Group**

- Trong **Load balancing**, chọn **No load balancer**
- Trong **health check grace period**, nhập ```240``` seconds
- Chọn **Next**

![Practice](/images/14-scaling/14.3-practice/00048-practice.png)

48. Trong giao diện **Practice**

- Đọc bước 25 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00049-practice.png)

49. Trong giao diện **EC2 Auto Scaling Group**

- Trong **Configure group size and scaling policies**
- Trong **Group size**
- **Desired capacity**, nhập 2
- **Minimum capacity**, nhập 2
- **Maximum capacity**, nhập 4
- Trong **Scaling policies**, chọn **tarfget tracking scaling policy**

![Practice](/images/14-scaling/14.3-practice/00050-practice.png)

50. Trong giao diện **Practice**

- Đọc bước 26 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00051-practice.png)

51. Trong giao diện **EC2 Auto Scaling**

- Trong **Scaling policy name**, nhập ```CPU Utilization```
- **Metric type**, chọn **Aerage CPU utilization**
- **Target value**, nhập ```70```
- Chọn **Next**

![Practice](/images/14-scaling/14.3-practice/00052-practice.png)

52. Trong giao diện **Practice**

- Đọc bước 27 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00053-practice.png)

53. Trong giao diện **EC2 Auto Scaling Group**

- Chọn **Skip to review**

![Practice](/images/14-scaling/14.3-practice/00054-practice.png)

54. Trong giao diện **Practice**

- Đọc bước 28 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00055-practice.png)

55. Trong giao diện **Create Auto Scaling group**

- Chọn **Create Auto Scaling group**

![Practice](/images/14-scaling/14.3-practice/00056-practice.png)

56. Trong giao diện **Practice**

- Đọc bước 29 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00057-practice.png)

57. Trong giao diện **EC2 Auto Scaling group**

- Xem kết quả khởi tạo **RegularCustomerGameServer**

![Practice](/images/14-scaling/14.3-practice/00058-practice.png)

58. Trong giao diện **Practice**

- Đọc bước 30 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00059-practice.png)

59. Trong giao diện **EC2 Auto Scaling Group**

- Chọn **Activity**
- Xem **Activity history**

![Practice](/images/14-scaling/14.3-practice/00060-practice.png)

60. Trong giao diện **Practice**

- Đọc bước 3 của **Auto-healing and Scaling Applications**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00061-practice.png)

61. Trong giao diện **EC2 Auto Scaling Group**

- Chọn **Automatic scaling**

![Practice](/images/14-scaling/14.3-practice/00062-practice.png)

62. Trong giao diện **Practice**

- Đọc bước 32 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00063-practice.png)

63. Trong giao diện **EC2 Auto Scaling Group**

- Chọn **Create scheduled action**

![Practice](/images/14-scaling/14.3-practice/00064-practice.png)

64. Trong giao diện **Practice**

- Đọc bước 33 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00065-practice.png)

65. Trong giao diện **Create scheduled action**

- **Name**, nhập **```SecondWaveOfRegulars```**
- **Desired capacity**, nhập ```3```
- **Min**, nhập ```3```
- **Max**, nhập ```4```
- **Recurrence**, chọn **Every week**
- **Specific start time**, chọn 1 thời gian trong tương lai
- Chọn **Create**

![Practice](/images/14-scaling/14.3-practice/00066-practice.png)

66.  Trong giao diện **Practice**

- Đọc bước 34 của **Auto-healing and Scaling Applications**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/14-scaling/14.3-practice/00068-practice.png)

67. Chúc mừng người chơi đã hoàn thành bài lab

![Practice](/images/14-scaling/14.3-practice/00069-practice.png)



