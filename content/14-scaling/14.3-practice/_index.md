---
title : "Practice"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 14.3 </b> "
---

{{% notice info %}}

After watching **Plan**, the player prepares for **Practice**

{{% /notice %}}

1. In the **Practice** interface

- Read step 1 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select **START LAB**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/0001-practice.png)

2. In the **Practice** interface

- Read step 2 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select **Open AWS Console**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/0002-practice.png)

3. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![Practice](/images/14-scaling/14.3-practice/0003-practice.png)

4. In the **Practice** interface

- Read step 3 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/0004-practice.png)

5. In the **EC2** interface

- Select **Instances**

![Practice](/images/14-scaling/14.3-practice/0005-practice.png)

6. In the **Practice** interface

- Read step 4 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/0006-practice.png)

7. In the **Instances** interface

- Select **Game Server**

![Practice](/images/14-scaling/14.3-practice/0007-practice.png)

8. In the **Practice** interface

- Read step 5 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/0008-practice.png)

9. In the **Instances** interface

- View details **Game Server**
- Copy **Public IPv4 address**


![Practice](/images/14-scaling/14.3-practice/0009-practice.png)

10. Open the browser

- Paste **Public IPv4 address**
- Select **Enter**
- View results

![Practice](/images/14-scaling/14.3-practice/00011-practice.png)

11. In the **Practice** interface

- Read step 7 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00012-practice.png)

12. In the **EC2** interface

- Select **Instances**
- Select **Game Server**
- Select **Actions**
- Select **Image and templates**
- Select **Create image**

![Practice](/images/14-scaling/14.3-practice/00013-practice.png)

13. In the **Practice** interface

- Read step 8 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00014-practice.png)

14. In the **Create image** interface

- **Image name**, enter ```Game Server````
- **Image description**, enter ```Regular customer game server```

![Practice](/images/14-scaling/14.3-practice/00015-practice.png)

15. In the **Practice** interface

- Read step 9 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00016-practice.png)

16. In the **Create image** interface

- **Tag**, select **Tag image and snapshots together**
- Select **Create image**

![Practice](/images/14-scaling/14.3-practice/00017-practice.png)

17. In the **Practice** interface

- Read step 10 of **Auto-healing and Scaling Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00018-practice.png)

18. In the **EC2** interface

- Select *AMIs**
- Select **Game Server**
- Select **refresh**
- View **Status**
- Select **Launch Templates**

![Practice](/images/14-scaling/14.3-practice/00019-practice.png)

19. In the **Practice** interface

- Read step 11 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00020-practice.png)

20. In the **EC2 launch templates** interface

- Select **Create launch templates**

![Practice](/images/14-scaling/14.3-practice/00021-practice.png)


21. In the **Practice** interface

- Read step 12 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00022-practice.png)

22. In the interface **Create lauch template**

- **Launch template name**, enter ```GameServerTemplate```
- **Template version description**, enter ```Regular customer game server template```
- Uncheck **Provide guidance to help me set up a template tht I can use with EC2 Auto Scaling**

![Practice](/images/14-scaling/14.3-practice/00023-practice.png)

23. In the **Practice** interface

- Read step 13 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00024-practice.png)

24. In the **Create launch template** interface

- Select **AMIs**
- Select **Owned by me**
- In **Amazon Machine Image (AMI), select **GameServer**

![Practice](/images/14-scaling/14.3-practice/00025-practice.png)

25. In the **Practice** interface

- Read step 14 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00026-practice.png)

26. In the **Create launch template** interface

- In *Instance type**, select **t2.nano**
- Select **Create new key pair**

![Practice](/images/14-scaling/14.3-practice/00027-practice.png)

27. In the **Practice** interface

- Read step 15 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00028-practice.png)

28. In the **Create key pair** interface

- **Key pair name**, enter ```GameServerKeyPair```
- **Key pair type**, select **RSA**
- **Private key file format**, select **.pem**
- Select **Create key pair**

![Practice](/images/14-scaling/14.3-practice/00029-practice.png)

29. In the **Practice** interface

- Read step 16 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00030-practice.png)

30. In the **Create launch template** interface

- In **Network settings**, select **Select existing security group**
- Select **WebServerSecurityGroup**

![Practice](/images/14-scaling/14.3-practice/00031-practice.png)

31. In the **Practice** interface

- Read step 17 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00032-practice.png)

32. In the **Create launch template** interface

- Watch **Sumary**
- Select **Create launch template**

![Practice](/images/14-scaling/14.3-practice/00033-practice.png)

33. Successful template initialization interface

- Select **View launch templates**

![Practice](/images/14-scaling/14.3-practice/00034-practice.png)

34. In the **Launch templates** interface

- View the template just created

![Practice](/images/14-scaling/14.3-practice/00035-practice.png)

35. In the **Pracitce** interface

- Read step 19 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00036-practice.png)

36. In the **Launch templates** interface

- Select **Auto Scaling Groups**

![Practice](/images/14-scaling/14.3-practice/00037-practice.png)

37. In the **Practice** interface

- Read step 20 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00038-practice.png)

38. In the **Amazon EC2 Auto Scaling** interface

- Select **Create Auto Scaling group**

![Practice](/images/14-scaling/14.3-practice/00039-practice.png)

39. In the **Auto Scaling groups** interface

- In **Choose launch template or conriguration**
- **Auto Scaling group name**, enter **```RegularCustomerGameServer```**
- **Launch template**, enter ```GameServerTemplate```

![Practice](/images/14-scaling/14.3-practice/00040-practice.png)

40. In the **Practice** interface

- Read step 21 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00041-practice.png)

41. In the **Auto Scaling** interface

- Select **Next**

![Practice](/images/14-scaling/14.3-practice/00042-practice.png)

42. In the **Practice** interface

- Read step 22 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00043-practice.png)

43. In the **EC2 Auto Scaling Group** interface

- In **Choose instance launch options**
- In **Network**, Select **VPC**
- Select **Availability Zones and subnets

![Practice](/images/14-scaling/14.3-practice/00044-practice.png)

44. In the **Practice** interface

- Read step 23 of **Auto-healing and Scaling Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00045-practice.png)

45. In the **EC2 Auto Scaling Group** interface

- Select **Next**

![Practice](/images/14-scaling/14.3-practice/00046-practice.png)

46. ​​In the **Practice** interface

- Read step 24 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00047-practice.png)

47. In the **EC2 Auto Scaling Group** interface

- In **Load balancing**, select **No load balancer**
- In **health check grace period**, enter ```240``` seconds
- Select **Next**

![Practice](/images/14-scaling/14.3-practice/00048-practice.png)

48. In the **Practice** interface

- Read step 25 of **Auto-healing and Scaling Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00049-practice.png)

49. In the **EC2 Auto Scaling Group** interface

- In **Configure group size and scaling policies**
- In **Group size**
- **Desired capacity**, enter 2
- **Minimum capacity**, enter 2
- **Maximum capacity**, enter 4
- In **Scaling policies**, select **tarfget tracking scaling policy**

![Practice](/images/14-scaling/14.3-practice/00050-practice.png)

50. In the **Practice** interface

- Read step 26 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00051-practice.png)

51. In the **EC2 Auto Scaling** interface

- In **Scaling policy name**, enter ```CPU Utilization```
- **Metric type**, select **Aerage CPU utilization**
- **Target value**, enter ```70```
- Select **Next**

![Practice](/images/14-scaling/14.3-practice/00052-practice.png)

52. In the **Practice** interface

- Read step 27 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00053-practice.png)

53. In the **EC2 Auto Scaling Group** interface

- Select **Skip to review**

![Practice](/images/14-scaling/14.3-practice/00054-practice.png)

54. In the **Practice** interface

- Read step 28 of **Auto-healing and Scaling Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00055-practice.png)

55. In the **Create Auto Scaling group** interface

- Select **Create Auto Scaling group**

![Practice](/images/14-scaling/14.3-practice/00056-practice.png)

56. In the **Practice** interface

- Read step 29 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00057-practice.png)

57. In the **EC2 Auto Scaling group** interface

- View initialization results **RegularCustomerGameServer**

![Practice](/images/14-scaling/14.3-practice/00058-practice.png)

58. In the **Practice** interface

- Read step 30 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00059-practice.png)

59. In the **EC2 Auto Scaling Group** interface

- Select **Activity**
- View **Activity history**

![Practice](/images/14-scaling/14.3-practice/00060-practice.png)

60. In the **Practice** interface

- Read step 3 of **Auto-healing and Scaling Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00061-practice.png)

61. In the **EC2 Auto Scaling Group** interface

- Select **Automatic scaling**

![Practice](/images/14-scaling/14.3-practice/00062-practice.png)

62. In the **Practice** interface

- Read step 32 of **Auto-healing and Scaling Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/14-scaling/14.3-practice/00063-practice.png)

63. In the **EC2 Auto Scaling Group** interface

- Select **Create scheduled action**

![Practice](/images/14-scaling/14.3-practice/00064-practice.png)

64. In the **Practice** interface

- Read step 33 of **Auto-healing and Scaling Applications**
- Select the right arrow to see the next steps

![Practice](/images/14-scaling/14.3-practice/00065-practice.png)

65. In the **Create scheduled action** interface

- **Name**, enter **```SecondWaveOfRegulars```**
- **Desired capacity**, enter ```3```
- **Min**, enter ```3```
- **Max**, enter ```4```
- **Recurrence**, select **Every week**
- **Specific start time**, choose a time in the future
- Select **Create**

![Practice](/images/14-scaling/14.3-practice/00066-practice.png)

66. In the **Practice** interface

- Read step 34 of **Auto-healing and Scaling Applications**
- Select the right arrow to see the next steps

![Practice](/images/14-scaling/14.3-practice/00068-practice.png)

67. Congratulations to the player on completing the lab

![Practice](/images/14-scaling/14.3-practice/00069-practice.png)