---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 12.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/12-filesystems/12.4-diy/0001-diy.png)

2. In the **EC2** interface

- Select **Instances**
- View the **instance**

![DIY](/images/12-filesystems/12.4-diy/0002-diy.png)

3. In **EC2** interface

- Select **Security Groups**
- View **Security Groups**
- Select **Create security group**

![DIY](/images/12-filesystems/12.4-diy/0003-diy.png)

4. In the **Create security group** interface

- **Security group name**, enter **PetModels-EFS-1-SG**
- **Description**, enter **Restric access to webservers only**
- Select **PetModels VPC**

![DIY](/images/12-filesystems/12.4-diy/0004-diy.png)

5. In the **Create security group** interface

- Select **Add rule**
- In **Inbound rules**, select **NFS**
- Select **webserver Security group**

![DIY](/images/12-filesystems/12.4-diy/0005-diy.png)

6. In the **Create security group** interface

- Select **Create security group**

![DIY](/images/12-filesystems/12.4-diy/0006-diy.png)

7. In the **Security groups** interface

- View **Security group name**
- View the **Inbound rules**

![DIY](/images/12-filesystems/12.4-diy/0007-diy.png)

8. In the **AWS Console** interface

- Find **EFS**
- Select **EFS**

![DIY](/images/12-filesystems/12.4-diy/0008-diy.png)

9. In the **EFS** interface

- Select **Create file system**

![DIY](/images/12-filesystems/12.4-diy/0009-diy.png)

10. In the **Create file system** interface

- **Name**, enter ```PetModels-EFS-1```
- **VPC**, select **PetModels**
- Select **Regional**
- Select **Customize**

![DIY](/images/12-filesystems/12.4-diy/00010-diy.png)

11. In the **File Systems** interface

- In **Automatic backups**, uncheck **Enable automatic backups**
- In **Transition into A**, select **None**

![DIY](/images/12-filesystems/12.4-diy/00011-diy.png)

12. In the **File systems** interface

- Select **Next**

![DIY](/images/12-filesystems/12.4-diy/00012-diy.png)

13. In the **Network access** interface

- Uncheck **security group** of **us-east-1a**
- Select **Remove** the remaining AZs

![DIY](/images/12-filesystems/12.4-diy/00013-diy.png)

14. In the **Network access** interface

- Select **us-east-1a**
- select **Subnet ID**
- Select **Security group**
- Select **Next**

![DIY](/images/12-filesystems/12.4-diy/00014-diy.png)

15. In the **File system policy** interface

- Select **Next**

![DIY](/images/12-filesystems/12.4-diy/00015-diy.png)

16. In the **Create file system** interface

- Select **Create**

![DIY](/images/12-filesystems/12.4-diy/00016-diy.png)

17. In the **File System** interface

- See the successful file system initialization
- Select **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00017-diy.png)

18. In the **PetModels-EFS-1** interface

- Select **Attach**

![DIY](/images/12-filesystems/12.4-diy/00018-diy.png)

19. In the **Attach** interface

- Copy **EFS mount helper**
- Select **Close**

![DIY](/images/12-filesystems/12.4-diy/00019-diy.png)

20. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/12-filesystems/12.4-diy/00020-diy.png)

21. In the **EC2** interface

- Select **Instances**
- View instances

![DIY](/images/12-filesystems/12.4-diy/00021-diy.png)

22. In the **Instances** interface

- Select **PetModels-A**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00022-diy.png)

23. In the **Connect to instance** interface

- Select **EC2 Instance Connect**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00023-diy.png)

24. In the **PetModels-A** interface

- Type ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00024-diy.png)

25. In the **PetModels-A** interface

- Enter ```mkdir data```
- Enter ```ls```
- Enter the command line of **Using the EFS mount helper** copied in step 19, then change **efs** to **data**
- Enter ```cd data```
- Type ```cat efs-l-setup.log```
- Type ```sudo bash -c "cat >> efs-l-setup.log"```
- Enter ```efs-1-mounted in site B```
- Use **Ctrl + C**
- Type ```cat efs-l-setup.log```
- View results

![DIY](/images/12-filesystems/12.4-diy/00025-diy.png)

26. In the **AWS Console** interface

- Find **EFS**
- Select **EFS**
- Select **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00026-diy.png)

27. In the **PetModels-EFS-1** interface

- Select **Network**
- Select **Manage**

![DIY](/images/12-filesystems/12.4-diy/00027-diy.png)

28. In the **Network access** interface

- Select **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/00028-diy.png)

29. In the **Network access** interface

- Select **us-east-1b**
- Select **Subnet ID**

![DIY](/images/12-filesystems/12.4-diy/00029-diy.png)

30. In the **Network access** interface

- Select **PetModels-EFS-1-SG**
- Select **Save**

![DIY](/images/12-filesystems/12.4-diy/00030-diy.png)

31. In the **PetModels-EFS-1** interface

- View **Mount target state**
- Select **refresh**

![DIY](/images/12-filesystems/12.4-diy/00031-diy.png)

32. In the **AWS Console** interface
- Find **EC2**
- Select **EC2**
- Select **Instances**

![DIY](/images/12-filesystems/12.4-diy/00032-diy.png)

33. In the **Instances** interface

- Select **PetMdels-B**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00033-diy.png)

34. In the **Connect to instance** interface

- Select **EC2 Instance Connect**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00034-diy.png)

35. In the **PetModels-B** interface

- Type ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00035-diy.png)

36. In the **PetModels-B** interface

- Enter ```mkdir data```
- Enter ```ls```
- Enter the command line of **Using the EFS mount helper** copied in step 19, then change **efs** to **data**
- Enter ```cd data```
- Type ```cat efs-l-setup.log```
- Type ```sudo bash -c "cat >> efs-l-setup.log"```
- Enter ```efs-1-mounted in site B```
- Use **Ctrl + C**
- Type ```cat efs-l-setup.log```
- View results

![DIY](/images/12-filesystems/12.4-diy/00036-diy.png)

37. In the **File systems** interface

- Select **PetModels-EFS-1**

![DIY](/images/12-filesystems/12.4-diy/00037-diy.png)

38. In the **PetModels-EFS-1** interface

- Select **Network**
- Select **Manage**

![DIY](/images/12-filesystems/12.4-diy/00038-diy.png)

39. In the **Network access** interface

- Select **Add mount target**

![DIY](/images/12-filesystems/12.4-diy/00039-diy.png)

40. In the **Network access** interface

- Select **us-east-1c**
- Select **Subnet ID**

![DIY](/images/12-filesystems/12.4-diy/00040-diy.png)

41. In the **Network access** interface

- Select **security group**
- Select **Save**

![DIY](/images/12-filesystems/12.4-diy/00041-diy.png)

42. In the **File system** interface

- Select **Network**
- View **Mount target state**
- Select **refresh**

![DIY](/images/12-filesystems/12.4-diy/00042-diy.png)

43. In the **EC2** interface

- Find **EC2**
- Select **EC2**
- Select **Instances**
- Select **PetModels-C**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00043-diy.png)

44. In the **Connect to instance** interface

- Select **EC2 Instance Connect**
- Select **Connect**

![DIY](/images/12-filesystems/12.4-diy/00044-diy.png)

45. In the **PetModels-C** interface

- Type ```sudo yum install -y amazon-efs-utils```

![DIY](/images/12-filesystems/12.4-diy/00045-diy.png)

46. ​​In the **PetModels-C** interface

- Enter ```mkdir data```
- Enter ```ls```
- Enter the command line of **Using the EFS mount helper** copied in step 19, then change **efs** to **data**
- Enter ```cd data```
- Type ```cat efs-l-setup.log```
- Type ```sudo bash -c "cat >> efs-l-setup.log"```
- Enter ```efs-1-mounted in site B```
- Use **Ctrl + C**
- Type ```cat efs-l-setup.log```
- View results

![DIY](/images/12-filesystems/12.4-diy/00046-diy.png)

47. In delivery **DIY**

- Paste **Amazon EFS File System id** into **VALIDATION FORM**
- Select **VALIDATE**

![DIY](/images/12-filesystems/12.4-diy/00047-diy.png)
48. In the **DIY** interface

- After selecting **VALIDATE**, **VALIDATION MESSAGE** appears **Success...**
- Select **EXIT**

![DIY](/images/12-filesystems/12.4-diy/00048-diy.png)

49. In the city view

- Select **ASSIGNMENT**
- Select **COLLECT**

![DIY](/images/12-filesystems/12.4-diy/00049-diy.png)

50. Select **NEXT**

![DIY](/images/12-filesystems/12.4-diy/00050-diy.png)

51. Select **COLLECT**

![DIY](/images/12-filesystems/12.4-diy/00051-diy.png)