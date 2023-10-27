# TOTOLINK A3300R V17.0.0cu.557_B20221024 Command Injection



## Product Information

Product: TOTOLINK A3300R
Firmware Version: V17.0.0cu.557_B20221024
Manufacturer's website information：https://www.totolink.net/
Firmware download address ：https://www.totolink.net/home/menu/detail/menu_listtpl/download/id/241/ids/36.html



![](images/0.png)



## Attack Type

remote



## Description

TOTOLINK A3300R V17.0.0cu.557_B20221024 is vulnerable to Incorrect Access Control. Attackers are able to reset serveral critical passwords without authentication by visiting specific pages.



### POC

Visit /wizard.html directly



## Analyse

The home page that shows original passwords.

![1](images/1.png)

Visit /wizard.html directly

![2](images/2.png)

Reset the passwords & Submit

 ![3](images/3.png)

![4](images/4.png)

![5](images/5.png)

![6](images/6.png)

Check the result

![7](images/7.png)

Login password can be changed at another page only if entering the right original one

![8](images/8.png)

![9](images/9.png)

![10](images/10.png)

![11](images/11.png)