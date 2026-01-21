---
title : "Practice"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 15.3 </b> "
---

{{% notice info %}}

After watching **Plan**, the player prepares for **Practice**

{{% /notice %}}

1. In the **Practice** interface

- Read step 1 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select **START LAB**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/0001-practice.png)

2. In the **Practice** interface

- Read step 2 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select **Open AWS Console**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/0002-practice.png)

3. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![Practice](/images/15-highlyavailable/15.3-practice/0003-practice.png)

4. In the **Practice** interface

- Read step 3 of **highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/0004-practice.png)

5. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencuWebServers**
- View details of **Desired capacity**, **Minimum capacity**, **Maximum capacity**

![Practice](/images/15-highlyavailable/15.3-practice/0005-practice.png)

6. In the **Pracitce** interface

- Read step 4 of **highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/0006-practice.png)

7. In the **Auto Scaling groups** interface

- Select **Instance management**
- View instances

![Practice](/images/15-highlyavailable/15.3-practice/0007-practice.png)

8. In the **Practice** interface

- Read step 5 of **highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/0008-practice.png)

9. In the **Auto Scaling groups** interface

- Select **Deatils**

![Practice](/images/15-highlyavailable/15.3-practice/0009-practice.png)

10. In the **Practice** interface

- Read step 6 of **highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00010-practice.png)

11. In the **Auto Scaling groups** interface

- In **Network**, see **Subnet ID**
- In **Load balancing**, select **Edit**


![Practice](/images/15-highlyavailable/15.3-practice/00011-practice.png)

12. In the **Practice** interface

- Read step 7 of **highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps


![Practice](/images/15-highlyavailable/15.3-practice/00012-practice.png)

13. In the **Edit TravleAgencyWebServers** interface

- Select **Add a new load balancer**


![Practice](/images/15-highlyavailable/15.3-practice/00013-practice.png)

14. In the **Practice** interface


- Read step 8 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00014-practice.png)

15. In the **Edit TravleAgencyWebServers** interface

- Select **Application Load Balancer**
- In **Load balancer scheme**, select **Internet-facing**


![Practice](/images/15-highlyavailable/15.3-practice/00015-practice.png)

16. In the **Practice** interface

- Read step 9 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps


![Practice](/images/15-highlyavailable/15.3-practice/00016-practice.png)

17. In the **Availability Zone and subnets** interface

- Select all 3 availability zones
- Select **Public subnet**
- In **Default routing (forward to)**, select **Create a target group**
- Select **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00017-practice.png)

18. In the **Practice** interface

- Read step 10 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps


![Practice](/images/15-highlyavailable/15.3-practice/00018-practice.png)

19. In the **VPC** interface

- Select **Security Groups**
- Select **Create security group**


![Practice](/images/15-highlyavailable/15.3-practice/00019-practice.png)

20. In the **Practice** interface

- Read step 11 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps


![Practice](/images/15-highlyavailable/15.3-practice/00020-practice.png)

21. In the **Create security group** interface

- **Security group name**, enter ```TravelAgencyLoadBalancer```
- **Description**, enter ```Allow access to the Travel Agency Balancer from the Internet```
- Select **VPC**
- In **Inbound rules**, select **Add rule**


![Practice](/images/15-highlyavailable/15.3-practice/00021-practice.png)

22. Results after entering information

![Practice](/images/15-highlyavailable/15.3-practice/00022-practice.png)

23. In the **Practice** interface
    
- Read step 12 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00023-practice.png)

24. In the **Create security group** interface

- In **Inbound rules**, select **HTTP**, select **Source** as **Custom**, select ```0.0.0.0/0```
- In **Outbound rules**, select **HTTP**, select **Destination** as **Custom**, select **Security group**

![Practice](/images/15-highlyavailable/15.3-practice/00024-practice.png)

25. In the **Practice** interface


- Read step 13 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00025-practice.png)

26. In the **Create security group** interface

- Select **Create security group**

![Practice](/images/15-highlyavailable/15.3-practice/00026-practice.png)

27. In the **Practice** interface

- Read step 14 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00027-practice.png)

28. In the **Security Groups** interface

- Select **Security Groups**
- Select **TravelAgencyWebServer**
- Select **Actions**
- Select **Edit inblound rules**

![Practice](/images/15-highlyavailable/15.3-practice/00028-practice.png)

29. In the **Practice** interface

- Read step 15 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00029-practice.png)

30. In the **Inbound rules** interface

- Select **Delete**
- Select **Add rule**

![Practice](/images/15-highlyavailable/15.3-practice/00030-practice.png)

31. In the **Practice** interface


- Read step 16 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00031-practice.png)

32. In the **Edit inbound rules** interface

- Select **HTTP**
- Select **TravelAgencyLoadBalancer** security group
- Select **Save rules**

![Practice](/images/15-highlyavailable/15.3-practice/00032-practice.png)

33. In the **Practice** interface


- Read step 17 of **Highly Available Web Applications**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00033-practice.png)

34. In the **Practice** interface

- Read step 18 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00034-practice.png)

35. In the **VPC** interface

- Select **Load Balancers**
- Select **TravelAgencyWebServers-1 ALB**
- Select **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00035-practice.png)

36. In the **Practice** interface

- Read step 19 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00036-practice.png)

37. In the **Security groups** interface

- Select **Edit security groups**
- Select **TravelAgencyLoadBalancer**
- Uncheck **TravelAgencyWebServer**
- Select **Save**

![Practice](/images/15-highlyavailable/15.3-practice/00037-practice.png)

38. In the **Practice** interface

- Read step 20 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00038-practice.png)

39. In the **VPC** interface

- Select **Load Balancers**
- Select **TravelAgencyWebServer-1 ALB**
- In **Description**, copy **ALB DNS name**

![Practice](/images/15-highlyavailable/15.3-practice/00039-practice.png)

40. In the **Practice** interface

- Read step 21 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00040-practice.png)

41. Open a browser

- Paste **ALB DNS name** in
- Select **Enter**
- View results

![Practice](/images/15-highlyavailable/15.3-practice/00041-practice.png)

42. In the **Practice** interface

- Read step 22 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00042-practice.png)

43. In the browser interface

- Add at the end **ALB DNS name**: ```/health```
- View results

![Practice](/images/15-highlyavailable/15.3-practice/00043-practice.png)

44. In the **Practice** interface

- Read step 23 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00044-practice.png)

45. In the **VPC** interface

- Select **Target Groups**
- Select **TravelAgencyWebServers-1 target group**
- Select **Health checks**
- Select **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00045-practice.png)

46. ​​In the **Practice** interface

- Read step 24 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00046-practice.png)

47. In the **Edit health check settings** interface

- In **Health check path**, enter ```/health```
- Select **Advanced health check settings**

![Practice](/images/15-highlyavailable/15.3-practice/00047-practice.png)

48. In the **Practice** interface

- Read step 25 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00048-practice.png)

49. In the **Advanced health check settings** interface

- **Port**, enter ```80```
- **Healthy threshold**, enter ```5```
- **Unhealthy threshold**, enter ```2```
- **Timeout**, enter ```2```
- **Interval**, enter ```5```
- **Success code**, enter ```200```
- Select **Save changes**

![Practice](/images/15-highlyavailable/15.3-practice/00049-practice.png)

50. In the **Practice** interface
    
- Read step 26 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00050-practice.png)

51. In the **VPC** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers Auto Scaling group**
- In **Network**, select **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00051-practice.png)

52. In the **Practice** interface

- Read step 10 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00052-practice.png)

53. In the **Edit TravelAgencyWebServers** interface

- Select **lab/TravelAgencyVpc/PrivateSubnet1 subnet**
- Uncheck **lab/TravelAgencyVpc/PublicSubnet1 subnet**
- Select **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00053-practice.png)

54. In the **Practice** interface

- Read step 28 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00054-practice.png)

55. In the **EC2** interface

- Select **Instances**
- Select **lab/TravelAgencyWebServers instance**
- Select **Networking**
- View **Subnet ID**
- Select **instance state**
- Select **Terminate instance**

![Practice](/images/15-highlyavailable/15.3-practice/00055-practice.png)

56. In the **Terminate instance** interface

- Select **Terminate**

![Practice](/images/15-highlyavailable/15.3-practice/00056-practice.png)

57. In the **Practice** interface

- Read step 29 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00057-practice.png)

58. In the **EC2** interface

- Select **refresh**
- Select **new instance**
- Select **Networking**
- View **Subnet ID**

![Practice](/images/15-highlyavailable/15.3-practice/00058-practice.png)


59. In the **Practice** interface

- Read step 30 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00059-practice.png)

60. In the **VPC** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers Auto Scaling group**
- Select **Activity**
- View **Activity history**

![Practice](/images/15-highlyavailable/15.3-practice/00060-practice.png)

61. In the **Practice** interface

- Read step 31 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00061-practice.png)

62. In the **Activity history** interface

- View **Status**
- View **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00062-practice.png)

63. In the **Practice** interface

- Read step 32 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00063-practice.png)

64. In the browser **health check**

- Select **refesh**
- View the results

![Practice](/images/15-highlyavailable/15.3-practice/00064-practice.png)

65. In the *Practice** interface

- Read step 33 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00065-practice.png)

66. In the **VPC** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers Auto Scaling group**
- In **Network**, select **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00066-practice.png)

67. In the **Edit TravelAgencyWebServers** interface

- Select **lab/TravelAgency/Vpc/PrivateSubnet2**
- Select **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00067-practice.png)

68. In the **Practice** interface

- Read step 35 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00068-practice.png)

69. In the **VPC** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers Auto Scaling group**
- In **Group details**, select **Edit**

![Practice](/images/15-highlyavailable/15.3-practice/00069-practice.png)

70. In the **Practice** interface

- Read step 36 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00070-practice.png)

71. In the **Group size** interface

- In **Desired capacity**, enter ```2```
- In **Maximum capacity**, enter ```2```
- Select **Update**

![Practice](/images/15-highlyavailable/15.3-practice/00071-practice.png)

72. In the **Practice** interface

- Read step 37 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00072-practice.png)

73. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers Auto Scaling group**
- Select **Activity**
- Scroll down **Activity history**

![Practice](/images/15-highlyavailable/15.3-practice/00073-practice.png)

74. In the **Practice** interface

- Read step 38 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00074-practice.png)

75. In the **Auto Scaling groups** interface

- In **Activity history**, see **Status** and **Description**

![Practice](/images/15-highlyavailable/15.3-practice/00075-practice.png)

76. In the **Practice** interface

- Read step 39 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00076-practice.png)

77. In the **EC2** interface

- Select **Instances**
- Select **new instance ID**
- Select **Networking**
- View **Subnet ID**

![Practice](/images/15-highlyavailable/15.3-practice/00077-practice.png)

78. In the **Practice** interface

- Read step 40 of **Highly Available Web Applications**
- Read **CONCEPT**
- Select the arrow to the right to see the next steps

![Practice](/images/15-highlyavailable/15.3-practice/00078-practice.png)

79. In the browser **health check**

- **Refresh**
- View results

![Practice](/images/15-highlyavailable/15.3-practice/00079-practice.png)

80. Congratulations to the player on completing the lab

![Practice](/images/15-highlyavailable/15.3-practice/00080-practice.png)
