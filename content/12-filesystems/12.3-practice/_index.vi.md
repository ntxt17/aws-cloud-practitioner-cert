---
title : "Practice"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 12.3 </b> "
---

{{% notice info %}}

Sau khi xem **Plan**, người chơi chuẩn bị cho **Practice**

{{% /notice %}}

1. Trong giao diện **Practice**

- Đọc bước 1 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn **START LAB**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/0001-practice.png)

2. Trong giao diện **Practice**

- Đọc bước 2 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn **Open AWS Console**
- Chọn mũi tên sang phải xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/0002-practice.png)

3. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**


![Practice](/images/12-filesystems/12.3-practice/0003-practice.png)

4. Trong giao diện **Practice**

- Đọc bước 3 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/12-filesystems/12.3-practice/0004-practice.png)

5. Trong giao diện **EC2**

- Chọn **Instances**
- Xem các instance

![Practice](/images/12-filesystems/12.3-practice/0005-practice.png)


6. Trong giao diện **Practice**

- Đọc bước 5 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/0006-practice.png)

7. Trong giao diện **EC2**

- Xem các **Availability Zone**
- Chọn **Security Groups**

![Practice](/images/12-filesystems/12.3-practice/0007-practice.png)

8. Trong giao diện **Practice**

- Đọc bước 6 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/12-filesystems/12.3-practice/0008-practice.png)

9. Trong giao diện **Security Groups**

- Xem **Web Server Security Group**
- Chọn **Create security group**

![Practice](/images/12-filesystems/12.3-practice/0009-practice.png)

10. Trong giao diện **Practicce**

- Đọc bước 7 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00010-practice.png)

11. Trong giao diện **Create security group**

- **Security group name**, nhập ```PetModels-EFS-1-SG```
- **Description**, nhập ```Restrict access to webservers only```
- Chọn **VPC PetModels**
- Chọn **Add rule**

![Practice](/images/12-filesystems/12.3-practice/00011-practice.png)

12. Trong giao diện **Practice**

- Đọc bước 8 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00012-practice.png)

13. Trong giao diện **Create security group**

- Trong **Inbound rules**, chọn **NFS**
- Chọn **Security group**, chọn **webserver**

![Practice](/images/12-filesystems/12.3-practice/00013-practice.png)

14. Trong giao diện **Practice**

- Đọc bước 9 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00014-practice.png)

15. Trong giao diện **Create security group**

- Chọn **Create security group**

![Practice](/images/12-filesystems/12.3-practice/00015-practice.png)

16. Trong giao diện **Practice**

- Đọc bước 10 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00016-practice.png)

17. Trong giao diện **Security group**

- Xem **Security group name** vừa tạo

![Practice](/images/12-filesystems/12.3-practice/00017-practice.png)

18.  Trong giao diện **Practice**

- Đọc bước 11 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00018-practice.png)

19. Trong giao diện **AWS Console**

- Tìm **EFS**
- Chọn **EFS**

![Practice](/images/12-filesystems/12.3-practice/00019-practice.png)

20. Trong giao diện **Practice**

- Đọc bước 12 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/12-filesystems/12.3-practice/00020-practice.png)

21. Trong giao diện **EFS**

- Chọn **Create file system**

![Practice](/images/12-filesystems/12.3-practice/00021-practice.png)

22. Trong giao diện **Practice**

- Đọc bước 13 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00022-practice.png)

23. Trong giao diện **Create file system**

- Trong **Name your file system**, nhập ```PetModels-EFS-1```
- Trong **VPC**, chọn **VPC PetModels**
- Trong **Availability and durability**, chọn **Regional**
- Chọn **Customize**

![Practice](/images/12-filesystems/12.3-practice/00023-practice.png)

24. Trong giao diện **Practice**

- Đọc bước 14 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00024-practice.png)

25. Trong giao diện **EFS**

- Trong **Automatic backups**, bỏ chọn **Enable automatic backups**
- Trong **Transition into IA**, chọn **None**

![Practice](/images/12-filesystems/12.3-practice/00025-practice.png)

26. Trong giao diện **Practice**

- Đọc bước 15 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo


![Practice](/images/12-filesystems/12.3-practice/00026-practice.png)

27. Trong giao diện **EFS**

- Chọn **Next**

![Practice](/images/12-filesystems/12.3-practice/00027-practice.png)

28. Trong giao diện **Practice**

- Đọc bước 16 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00028-practice.png)

29. Trong giao diện **Network Access**

- Thực hiện bỏ **security của AZ us-east-1a**
- Chọn **Remove** 2 AZ còn lại
- Chọn **Next**

![Practice](/images/12-filesystems/12.3-practice/00029-practice.png)

30. Trong giao diện **Practice**

- Đọc bước 17 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00030-practice.png)

31. Trong giao diện **Network access**

- Trong **Security group**, chọn **PetModels-EFS-1-SG**
- Chọn *Next**

![Practice](/images/12-filesystems/12.3-practice/00031-practice.png)

32. Trong giao diện **Practice**

- Đọc bước 18 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00032-practice.png)

33. Trong giao diện **File system policy**

- Chọn **Next**

![Practice](/images/12-filesystems/12.3-practice/00033-practice.png)

34. Trong giao diện **Practice**

- Đọc bước 19 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00034-practice.png)

35. Trong giao diện **Create file system**

- Chọn **Create**

![Practice](/images/12-filesystems/12.3-practice/00035-practice.png)

36. Trong giao diện **Practice**

- Đọc bước 20 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00036-practice.png)

37. Trong giao diện **EFS**

- Xem file system đã tạo thành công
- Chọn **File system** đã tạo

![Practice](/images/12-filesystems/12.3-practice/00037-practice.png)

38. Trong giao diên **Practice**

- Đọc bước 21 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00038-practice.png)

39. Trong giao diện **file systems**

- Chọn **Attach**

![Practice](/images/12-filesystems/12.3-practice/00039-practice.png)

40. Trong giao diện **Practice**

- Đọc bước 22 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00040-practice.png)

41. Trong giao diện **Attach**

- Trong **Using the EFS mount helper**, sao chép dòng lệnh
- Chọn **Close**

![Practice](/images/12-filesystems/12.3-practice/00041-practice.png)

42. Trong giao diện **Practice**

- Đọc bước 23 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00042-practice.png)

43. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![Practice](/images/12-filesystems/12.3-practice/00043-practice.png)

44. Trong giao diện **Practice**

- Đọc bước 24 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00044-practice.png)

45. Trong giao diện **EC2**

- Chọn **Instances**

![Practice](/images/12-filesystems/12.3-practice/00045-practice.png)

46. Trong giao diện **Practice**

- Đọc bước 25 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00046-practice.png)

47. Trong giao diện **Instances**

- Chọn **PetModels-A instance**
- Chọn **Connect**

![Practice](/images/12-filesystems/12.3-practice/00047-practice.png)

48. Trong giao diện **Practice**

- Đọc bước 26 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00048-practice.png)

49. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![Practice](/images/12-filesystems/12.3-practice/00049-practice.png)

50. Trong giao diện **Practice**

- Đọc bước 27 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00050-practice.png)

51. Trong giao diện **PetModels-A**

- Nhập ```sudo yum install -y amazon-efs-utils```
- Sau đó, nhấn **Enter**

![Practice](/images/12-filesystems/12.3-practice/00051-practice.png)

52. Trong giao diện **Practice**

- Đọc bước 28 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00052-practice.png)

53. Trong giao diện **PetModels-A**

- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập **Using the EFS mount helper** đã sao chép ở bước 41, và thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"
- Nhập ```efs-l mount in site A```
- Sử dụng **Ctrl + C**

![Practice](/images/12-filesystems/12.3-practice/00053-practice.png)

54. Trong giao diện **Practice**

- Đọc bước 29 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00054-practice.png)

55. Trong giao diện **AWS Console**

- Tìm **EFS**
- Chọn **EFS**

![Practice](/images/12-filesystems/12.3-practice/00055-practice.png)

56. Trong giao diện **Practice**

- Đọc bước 30 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00056-practice.png)

57. Trong giao diện **Practice**

- Đọc bước 31 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00057-practice.png)

58. Trong giao diện **EFS**

- Chọn **Network**
- Chọn **Manage**

![Practice](/images/12-filesystems/12.3-practice/00058-practice.png)

59. Trong giao diện **Practice**

- Đọc bước 32 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00059-practice.png)

60. Trong giao diện **Network access**

- Chọn **Add mount target**

![Practice](/images/12-filesystems/12.3-practice/00060-practice.png)

61. Trong giao diện **Practice**

- Đọc bước 33 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00061-practice.png)

62. Trong giao diện **Network access**

- Sau khi chọn **Add mount target**, chọn **us-east-1b** và chọn **subnet**

![Practice](/images/12-filesystems/12.3-practice/00062-practice.png)

63. Trong giao diện **Practice**

- Đọc bước 34 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00063-practice.png)

64. Trong giao diện **Network access**

- Chọn **Save**

![Practice](/images/12-filesystems/12.3-practice/00064-practice.png)

65. Trong giao diện **Practice**

- Đọc bước 35 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00065-practice.png)

66. Trong giao diện **EFS**

- Xem **Mount target state**
- Sau đó chọn **refresh**

![Practice](/images/12-filesystems/12.3-practice/00066-practice.png)

67. Trong giao diện **Practice**

- Đọc bước 36 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00067-practice.png)

68. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![Practice](/images/12-filesystems/12.3-practice/00068-practice.png)

69. Trong giao diện **Practice**

- Đọc bước 37 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00069-practice.png)

70.  Trong giao diện **EC2**

- Chọn **Instances**

![Practice](/images/12-filesystems/12.3-practice/00070-practice.png)

71. Trong giao diện **Practice**

- Đọc bước 38 của **File Systems in the Cloud**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00071-practice.png)

72. Trong giao diện **Instances**

- Chọn **PetModels-B**

![Practice](/images/12-filesystems/12.3-practice/00072-practice.png)

73. Trong giao diện **Practice**

- Đọc bước 39 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00073-practice.png)

74. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![Practice](/images/12-filesystems/12.3-practice/00074-practice.png)

75. Trong giao diện **Practice**

- Đọc bước 40 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00075-practice.png)

76. Trong giao diện **PetModels-B**

- Nhập ```sudo yum install -y amazon-efs-utils```

![Practice](/images/12-filesystems/12.3-practice/00076-practice.png)

77. Trong giao diện **Practice**

- Đọc bước 41 của **File Systems in the Cloud**
- Đọc **CONCEPT**
- Chọn mũi tên sang phải để xem các bước tiếp theo

![Practice](/images/12-filesystems/12.3-practice/00077-practice.png)

78. Trong giao diện **PetModels-B**

- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập dòng lệnh của **Using the EFS mount helper** đã sao chép ở bước 41, sao đó thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```cat efs-l-setup.log```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"```
- Nhập ```efs-1-mounted in site B```
- Sử dụng **Ctrl + C**
- Nhập ```cat efs-l-setup.log```
- Xem kết quả

![Practice](/images/12-filesystems/12.3-practice/00078-practice.png)

78. Chúc mừng người chơi đã hoàn thành bài lab

![Practice](/images/12-filesystems/12.3-practice/00079-practice.png)
