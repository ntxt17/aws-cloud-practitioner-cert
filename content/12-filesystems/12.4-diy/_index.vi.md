---
title : "DIY"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 12.4 </b> "
---

{{% notice info %}}

Sau khi hoàn thành bài lab, người chơi thực hiện **DIY**

{{% /notice %}}

1. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/12-filesystems/12.4-diy/0001-diy.png)

2. Trong giao diện **EC2**

- Chọn **Instances**
- Xem các **instance**

![DIY](/images/12-filesystems/12.4-diy/0002-diy.png)

3. Trong giao diện **EC2**

- Chọn **Security Groups**
- Xem các **Security Groups**
- Chọn **Create security group**

![DIY](/images/12-filesystems/12.4-diy/0003-diy.png)

4. Trong giao diện **Create security group**

- **Security group name**, nhập **PetModels-EFS-1-SG**
- **Description**, nhập **Restric access to webservers only**
- Chọn **PetModels VPC**

![DIY](/images/12-filesystems/12.4-diy/0004-diy.png)

5. Trong giao diện **Create security group**

- Chọn **Add rule**
- Trong **Inbound rules**, chọn **NFS**
- Chọn **webserver Security group**

![DIY](/images/12-filesystems/12.4-diy/0005-diy.png)

6. Trong giao diện **Create security group**

- Chọn **Create security group**

![DIY](/images/12-filesystems/12.4-diy/0006-diy.png)

7. Trong giao diện **Security groups**

- Xem **Security group name**
- Xem các **Inbound rules**

![DIY](/images/12-filesystems/12.4-diy/0007-diy.png)

8. Trong giao diện **AWS Console**

- Tìm **EFS**
- Chọn **EFS**

![DIY](/images/12-filesystems/12.4-diy/0008-diy.png)

9. Trong giao diện **EFS**

- Chọn **Create file system**

![DIY](/images/12-filesystems/12.4-diy/0009-diy.png)

10. Trong giao diện **Create file system**

- **Name**, nhập ```PetModels-EFS-1```
- **VPC**, chọn **PetModels**
- Chọn **Regional**
- Chọn **Customize**

![DIY](/images/12-filesystems/12.4-diy/00010-diy.png)

11. Trong giao diện **File Systems**

- Trong **Automatic backups**, bỏ chọn **Enable automatic backups**
- Trong **Transition into A**, chọn **None**

![DIY](/images/12-filesystems/12.4-diy/00011-diy.png)

12. Trong giao diện **File systems**

- Chọn **Next**

![DIY](/images/12-filesystems/12.4-diy/00012-diy.png)

13. Trong giao diện **Network  access**

- Bỏ chọn **security group** của **us-east-1a**
- Chọn **Remove** các AZ còn lại

![DIY](/images/12-filesystems/12.4-diy/00013-diy.png)

14. Trong giao diện **Network access**

- Chọn **us-east-1a**
- chọn **Subnet ID**
- Chọn **Security group**
- Chọn **Next**

![DIY](/images/12-filesystems/12.4-diy/00014-diy.png)

15. Trong giao diện **File system policy**

- Chọn **Next**

![DIY](/images/12-filesystems/12.4-diy/00015-diy.png)

16. Trong giao diện **Create file system**

- Chọn **Create**

![DIY](/images/12-filesystems/12.4-diy/00016-diy.png)

17. Trong giao diện **File System**

- Xem khởi tạo file system thành công
- Chọn **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00017-diy.png)

18. Trong giao diện **PetModels-EFS-1**

- Chọn **Attach**

![DIY](/images/12-filesystems/12.4-diy/00018-diy.png)

19. Trong giao diện **Attach**

- Sao chép **EFS mount helper**
- Chọn **Close**

![DIY](/images/12-filesystems/12.4-diy/00019-diy.png)

20. Trong giao diện **AWS Console**

- Tìm **EC2**
- Chọn **EC2**

![DIY](/images/12-filesystems/12.4-diy/00020-diy.png)

21. Trong giao diện **EC2**

- Chọn **Instances**
- Xem các instance

![DIY](/images/12-filesystems/12.4-diy/00021-diy.png)

22. Trong giao diện **Instances**

- Chọn **PetModels-A**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00022-diy.png)

23. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00023-diy.png)

24. Trong giao diện **PetModels-A**

- Nhập ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00024-diy.png)

25. Trong giao diện **PetModels-A**

- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập dòng lệnh của **Using the EFS mount helper** đã sao chép ở bước 19, sao đó thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```cat efs-l-setup.log```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"```
- Nhập ```efs-1-mounted in site B```
- Sử dụng **Ctrl + C**
- Nhập ```cat efs-l-setup.log```
- Xem kết quả

![DIY](/images/12-filesystems/12.4-diy/00025-diy.png)

26. Trong giao diện **AWS Console**

- Tìm **EFS**
- Chọn **EFS**
- Chọn **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00026-diy.png)

27. Trong giao diện **PetModels-EFS-1**

- Chọn **Network**
- Chọn **Manage**

![DIY](/images/12-filesystems/12.4-diy/00027-diy.png)

28. Trong giao diện **Network access**

- Chọn **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/00028-diy.png)

29. Trong giao diện **Network access**

- Chọn **us-east-1b**
- Chọn **Subnet ID**

![DIY](/images/12-filesystems/12.4-diy/00029-diy.png)

30. Trong giao diện **Network access**

- Chọn **PetModels-EFS-1-SG**
- Chọn **Save**

![DIY](/images/12-filesystems/12.4-diy/00030-diy.png)

31. Trong giao diện **PetModels-EFS-1**

- Xem **Mount target state**
- Chọn **refresh**

![DIY](/images/12-filesystems/12.4-diy/00031-diy.png)

32. Trong giao diện **AWS Console**
- Tìm **EC2**
- Chọn **EC2**   
- Chọn **Instances**

![DIY](/images/12-filesystems/12.4-diy/00032-diy.png)

33. Trong giao diện **Instances**

- Chọn **PetMdels-B**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00033-diy.png)

34. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00034-diy.png)

35. Trong giao diện **PetModels-B**

- Nhập ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00035-diy.png)

36. Trong giao diện **PetModels-B**

- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập dòng lệnh của **Using the EFS mount helper** đã sao chép ở bước 19, sao đó thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```cat efs-l-setup.log```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"```
- Nhập ```efs-1-mounted in site B```
- Sử dụng **Ctrl + C**
- Nhập ```cat efs-l-setup.log```
- Xem kết quả

![DIY](/images/12-filesystems/12.4-diy/00036-diy.png)

37. Trong giao diện **File systems**

- Chọn **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00037-diy.png)

38. Trong giao diện **PetModels-EFS-1**

- Chọn **Network**
- Chọn **Manage**

![DIY](/images/12-filesystems/12.4-diy/00038-diy.png)

39.  Trong giao diện **Network access**

- Chọn **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/00039-diy.png)

40. Trong giao diện **Network access**

- Chọn **us-east-1c**
- Chọn **Subnet ID**

![DIY](/images/12-filesystems/12.4-diy/00040-diy.png)

41. Trong giao diện **Network access**

- Chọn **security group**
- Chọn **Save**

![DIY](/images/12-filesystems/12.4-diy/00041-diy.png)

42. Trong giao diện **File system**

- Chọn **Network**
- Xem **Mount target state**
- Chọn **refresh**

![DIY](/images/12-filesystems/12.4-diy/00042-diy.png)

43. Trong giao diện **EC2**

- Tìm **EC2**
- Chọn **EC2**
- Chọn **Instances**
- Chọn **PetModels-C**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00043-diy.png)

44. Trong giao diện **Connect to instance**

- Chọn **EC2 Instance Connect**
- Chọn **Connect**

![DIY](/images/12-filesystems/12.4-diy/00044-diy.png)

45. Trong giao diện **PetModels-C**

- Nhập ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00045-diy.png)

46. Trong giao diện **PetModels-C**

- Nhập ```mkdir data```
- Nhập ```ls```
- Nhập dòng lệnh của **Using the EFS mount helper** đã sao chép ở bước 19, sao đó thay **efs** thành **data**
- Nhập ```cd data```
- Nhập ```cat efs-l-setup.log```
- Nhập ```sudo bash -c "cat >> efs-l-setup.log"```
- Nhập ```efs-1-mounted in site B```
- Sử dụng **Ctrl + C**
- Nhập ```cat efs-l-setup.log```
- Xem kết quả

![DIY](/images/12-filesystems/12.4-diy/00046-diy.png)

47. Trong giao **DIY**

- Dán **Amazon EFS File System id** vào **VALIDATION FORM**
- Chọn **VALIDATE**

![DIY](/images/12-filesystems/12.4-diy/00047-diy.png)
48. Trong giao diện **DIY**

- Sau khi chọn **VALIDATE**, **VALIDATION MESSAGE** xuất hiện **Success...**
- Chọn **EXIT**

![DIY](/images/12-filesystems/12.4-diy/00048-diy.png)

49. Trong giao diện thành phố 

- Chọn **ASSIGNMENT**
- Chọn **COLLECT**

![DIY](/images/12-filesystems/12.4-diy/00049-diy.png)

50. Chọn **NEXT**

![DIY](/images/12-filesystems/12.4-diy/00050-diy.png)

51. Chọn **COLLECT**

![DIY](/images/12-filesystems/12.4-diy/00051-diy.png)
