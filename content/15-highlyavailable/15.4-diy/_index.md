---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 15.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **DIY** interface

- Read **DIY ACCTIVITIES**
- Read **SOLUTION VALIDATION METHOD**

![DIY](/images/15-highlyavailable/15.4-diy/0001-diy.png)

2. In the **DIY** interface

- Select **START LAB**

![DIY](/images/15-highlyavailable/15.4-diy/0003-diy.png)

3. In the **AWS Console** interface

- Find **EC2**
- Select **EC2**

![DIY](/images/15-highlyavailable/15.4-diy/0004-diy.png)

4. In the **EC2** interface

- Select **Instances**
- Select **lab/TravelAgencyWebServers**
- Select **Details** to view instance details


![DIY](/images/15-highlyavailable/15.4-diy/0005-diy.png)

5. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** auto scaling group
- Select **Details** to see the details of the auto scaling group


![DIY](/images/15-highlyavailable/15.4-diy/0006-diy.png)

6. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling Group
- Select **Instance management**
- View instance information

![DIY](/images/15-highlyavailable/15.4-diy/0007-diy.png)

7. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers**
- Select **Details** to view **Desired capacity**, **Minimum capacity**, **Maximum capacity**

![DIY](/images/15-highlyavailable/15.4-diy/0008-diy.png)

8. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling Group
- In **Network**, see **Subnet ID** information
- In **Load balancing**, select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/0009-diy.png)

9. In the **Edit TravelAgencyWebServers** interface

- Select **Add a new load balancer**

![DIY](/images/15-highlyavailable/15.4-diy/00010-diy.png)

10. In the **Load balancing** interface

- **Load balancer type**, select **Application Load Balancer**
- **Load balancer scheme**, select **Internet-facing**

![DIY](/images/15-highlyavailable/15.4-diy/00011-diy.png)

11. In the interface **Edit TravelAgencyWebServers**

- **Availability Zones and subnets**, select all 3 *AZ** and subnets
- In **Default routing (forward to)**, select **Create a target group**
- Select **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00012-diy.png)

12. In the **Auto Scaling Groups** interface

- View update results
- Select **TravelAgencyWebServers** Auto Scaling Group
- Select **Details** to see details

![DIY](/images/15-highlyavailable/15.4-diy/00013-diy.png)

13. In the **EC2** interface

- Select **Security Groups**
- Select **Create security group**

![DIY](/images/15-highlyavailable/15.4-diy/00014-diy.png)

14. In the **Create security group** interface

- **Security group name**, enter ```TravelAgencyLoadBalancer```
- In **Decription**, enter ```Allow access to the Travel Agency Load Balancer from the Internet```
- In **VPC**, select **lab/TravelAgencyVpc**
- Select **Add rule**


![DIY](/images/15-highlyavailable/15.4-diy/00015-diy.png)

15. In the **Create Security group** interface

- **Inbound rules**, select **HTTP**
- **Oubound rules**, select **HTTP**
- Select **Create security group**

![DIY](/images/15-highlyavailable/15.4-diy/00016-diy.png)

16. In the **EC2** interface

- Select **Security Groups**
- Select **TravelAgencyWebServer** security group*
- Select **Actions**
- Select **Edit inbound rules**

![DIY](/images/15-highlyavailable/15.4-diy/00017-diy.png)

17. In the **Edit inbound rules** interface

- Select **Delete**
- Select **Add rule**

![DIY](/images/15-highlyavailable/15.4-diy/00018-diy.png)

18. In the **Edit Inbound rules** interface

- Select **HTTP**
- **Source** select **Custom**, select **TravelAgencyLoadBalancer**
- Select **Sae rules**

![DIY](/images/15-highlyavailable/15.4-diy/00019-diy.png)

19. In the **EC2** interface

- Select **Load Balancers**
- Select **TravelAgencyWebServers-1** Load Balancer
- Select **Description** to view description information

![DIY](/images/15-highlyavailable/15.4-diy/00020-diy.png)

20. In the **Load Balancer** interface

- Select **Edit security groups**
- Select **TravelAgencyLoadBalancer** security group
- Uncheck **TravelAgencyWebServer** security group


![DIY](/images/15-highlyavailable/15.4-diy/00021-diy.png)

21. In the **EC2** interface

- Select **Load Balancers**
- Select **TravelAgencyWebServer-1** Load Balancer
- In **Description**, view and copy **DNS name**

![DIY](/images/15-highlyavailable/15.4-diy/00022-diy.png)

22. Open a browser

- Paste **DNS name** into the browser
- Select **Enter** and see the interface

![DIY](/images/15-highlyavailable/15.4-diy/00023-diy.png)

23. In the browser

- Follow the end of **DNS name**: ```/health```
- View results

![DIY](/images/15-highlyavailable/15.4-diy/00024-diy.png)

24. In the **EC2**' interface

- Select **Target Groups**
- Select **TravelAgencyWebServers** target group
- Select **Health checks**

![DIY](/images/15-highlyavailable/15.4-diy/00025-diy.png)

25. In the interface **Edit health check settings**

- In **Health check path**, enter ```/health```
- Select **Advanced health check settings**

![DIY](/images/15-highlyavailable/15.4-diy/00026-diy.png)

26. In the **Advanced health check settings** interface

- In **Unhealthly threshold**, enter ```2```
- In **Timeout**, enter ```2```
- In **Interval**, enter ```5```
- Select **Save changes**

![DIY](/images/15-highlyavailable/15.4-diy/00027-diy.png)

27. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServer** Auto Scaling Group
- In **Network**, see **Subnet ID**
- Select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00028-diy.png)

28. In the **Edit TravelAgencyWebServers** interface

- In **Availability Zones and subnets**, select **lab/TravelAgencyVpc/PrivateSubnet1**

![DIY](/images/15-highlyavailable/15.4-diy/00029-diy.png)

29. In the **EC2** interface

- Select **Instances**
- Select **lab/TravelAgencyWebServers** instance
- Select **Networking**
- View edited **Subnet ID**
- Select **Instance state**
- Select **Terminate instance**

![DIY](/images/15-highlyavailable/15.4-diy/00030-diy.png)

30. In the **Terminate instance** interface

- Select **Terminate**

![DIY](/images/15-highlyavailable/15.4-diy/00031-diy.png)

31. In the **Instances** interface

- Select **refresh**
- Select **lab/TravelAgencyWebServers** instance
- Select **Networking**
- View **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00032-diy.png)

32. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling Group
- View **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00033-diy.png)

33. In the browser **health check**

- Select **Refresh**
- View results

![DIY](/images/15-highlyavailable/15.4-diy/00034-diy.png)

34. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TraveAgencyWebServers**
- In **Network**, select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00035-diy.png)

35. In the **Edit TravelAgencyWebServers** interface

- In **Availability Zones and sunets**, select **lab/TravelAgencyVpc/PrivateSubnet2**
- Select **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00036-diy.png)

36. In the **EC2** interface

- Select **Auto Scaling Groups**
- View update results
- Select **TravelAgencyWebServers** Auto Scaling group
- Select **Details** to see details
- In **Group details** select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00037-diy.png)

37. In the **Group size** interface

- **Desired capacity**, enter ```2```
- **Minimum capacity**, enter ```1```
- **Maximum capacity**, enter ```2```
- Select **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00038-diy.png)

38. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravleAgencyWebServers** Auto Scaling Group
- View **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00039-diy.png)

39. In the **EC2** interface

- Select **Instance**
- Select **lab/TravelAgencyWebServers**
- Select **Networking**
- View **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00040-diy.png)

40. In the browser **health check**

- Select **Refresh**
- View results

![DIY](/images/15-highlyavailable/15.4-diy/00041-diy.png)

41. In the **EC2* interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling group
- In **Network**, see **Subnet ID**
- Select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00042-diy.png)

42. In the **Edit TravelAgencyWebServers** interface

- In **Availability Zones and subnets**, select **lab/TravelAgencyVpc/PrivateSubnet3**

![DIY](/images/15-highlyavailable/15.4-diy/00043-diy.png)

43. Tron interface **Edit TravelAgencyWebServers**

- In **Network** there are 3 subnets:
- **lab/TravelAgencyVpc/PrivateSubnet1**
- **lab/TravelAgencyVpc/PrivateSubnet2**
- **lab/TravelAgencyVpc/PrivateSubnet3**

- Select **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00044-diy.png)

44. In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling Group
- Select **Details**, see details **Group details**
- Select **Edit**

![DIY](/images/15-highlyavailable/15.4-diy/00045-diy.png)

45. In the **Group size** interface

- **Desired capacity**, enter ```3```
- **Minimum capacity**, enter ```1```
- **Maximum capacity**, enter ```3```
- Select **Update**

![DIY](/images/15-highlyavailable/15.4-diy/00046-diy.png)

46. ​​In the **EC2** interface

- Select **Auto Scaling Groups**
- Select **TravelAgencyWebServers** Auto Scaling Group
- View **Activity history**

![DIY](/images/15-highlyavailable/15.4-diy/00047-diy.png)

47. In the **EC2** interface

- Select **Instances**
- Select **lab/TravelAgencyWebServers** instance
- Select **Networking**
- View **Subnet ID**

![DIY](/images/15-highlyavailable/15.4-diy/00048-diy.png)

48. In the browser **health check**

- Select **Refresh**
- View results

![DIY](/images/15-highlyavailable/15.4-diy/00049-diy.png)

49. In the **Auto Scaling Group** interface

- Select **TravelAgencyWebServers** Auto Scaling Group
- Select **Details**
- View details **Group details**

![DIY](/images/15-highlyavailable/15.4-diy/00050-diy.png)

50. In the **EC2** interface

- Select **Load Balancers**
- Select **TravelAgencyWebServers-1** Load Balancer
- Select **Description** and view description information
- Copy **Name** ALB
- Copy **Auto Scaling group name**

![DIY](/images/15-highlyavailable/15.4-diy/00051-diy.png)

51. In the **DIY** interface

- Paste ```TravelAgencyWebServers-1``` into **Your ALB name**
- Paste ```TravelAgencyWebSersers``` into **Your Auto Scaling group name**
- Select **VALIDATE**

![DIY](/images/15-highlyavailable/15.4-diy/00052-diy.png)

52. In the **DIY** interface

- In **VALIDATION MESSAGE** appears **Success! All 3 Availability Zones are covered by instances behind a Load Balancer**
- Select **EXIT** to return to the city interface

![DIY](/images/15-highlyavailable/15.4-diy/00053-diy.png)

53. In the city interface

- Select **ASSIGNMENTS**
- Select **COLLECT**

![DIY](/images/15-highlyavailable/15.4-diy/00054-diy.png)

54. Select **NEXT**

![DIY](/images/15-highlyavailable/15.4-diy/00055-diy.png)

55. Select **COLLECT**

![DIY](/images/15-highlyavailable/15.4-diy/00056-diy.png)

56. Congratulations to the player receiving the reward

