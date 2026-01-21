---
title : "DIY"
date : "`r Sys.Date()`"
weight : 4
chapter : false
pre : " <b> 13.4 </b> "
---

{{% notice info %}}

After completing the lab, the player does **DIY**

{{% /notice %}}

1. In the **AWS Console** interface

- Find **Amazon DynamoDB**
- Select **Amazon DynamoDB**
- Select **Create table**

![DIY](/images/13-nosqldatabase/13.4-diy/0001-diy.png)

2. In the **DynamoDB** interface

- Select **Update settings**
- Select **UserVideoHistory**
- Select **Actions**
- Select **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/0002-diy.png)

3. In the **Create item** interface

- In **userId**, enter ```12345-abcd-6785```
- In **lastDateWatched**, enter ```1619156407```

![DIY](/images/13-nosqldatabase/13.4-diy/0003-diy.png)

4. In the **Create item** interface

- Select **Add new attribute**
- Select **Number**

![DIY](/images/13-nosqldatabase/13.4-diy/0004-diy.png)

5. In the **Create item** interface

- **Attribute name**, enter ```Rating``` ** (note to lowercase)**
- **Value**, enter ```5```
- Select **Create item**

![DIY](/images/13-nosqldatabase/13.4-diy/0005-diy.png)

6. In the **DynamoDB** interface

- View **Items returned**

![DIY](/images/13-nosqldatabase/13.4-diy/0006-diy.png)

7. In the **Item editor** interface

- In **Attribute name**, enter ```rating```
- Select **Save changes**

![DIY](/images/13-nosqldatabase/13.4-diy/0007-diy.png)

8. In the **DIY** interface

- Enter **```UserVideoHistory```** into **DynamoDB table name**
- Enter ***```12345-abcd-6785```** in **Item User Id**
- Select **VALIDATE**
- After selecting **VALIDATE**, **VALIDATION MESSAGE** appears **The DynamoDB record has been correctly configured! Good job!...**

![DIY](/images/13-nosqldatabase/13.4-diy/0008-diy.png)

9. In the **DIY** interface

- Select **EXIT** to exit

![DIY](/images/13-nosqldatabase/13.4-diy/0009-diy.png)

10. In the city interface

- Select **ASSIGNMENTS**
- Select **COLLECT**

![DIY](/images/13-nosqldatabase/13.4-diy/00010-diy.png)

11. Select **NEXT**

![DIY](/images/13-nosqldatabase/13.4-diy/00011-diy.png)

12. Select **COLLECT**

![DIY](/images/13-nosqldatabase/13.4-diy/00012-diy.png)

13. Congratulations on completing **DIY**

![DIY](/images/13-nosqldatabase/13.4-diy/00013-diy.png)