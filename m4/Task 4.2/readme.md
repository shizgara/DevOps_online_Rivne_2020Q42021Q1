# Task 4.1


##### 1

![project 1](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/1.png)


Building 1 : 
                                
First floor:
PC9: IP:192.168.2.2/24   
PC0: IP:192.168.2.3/24   
PC1: IP:192.168.2.4/24  
PC2: IP:192.168.2.5/24   
PC3: IP:192.168.2.6/24 
Gateway: 192.168.2.1 
 
Second floor:
PC5: IP:192.168.3.2/24  
PC6: IP:192.168.3.3/24   
PC7: IP:192.168.3.4/24
PC8: IP:192.168.3.5/24   
PC20: IP:192.168.3.6/24
Gateway: 192.168.3.1

===========================================

Building 2 :   
    
First floor:
PC15: IP:192.168.5.2/24   
PC16: IP:192.168.5.3/24   
PC17: IP:192.168.5.4/24     
PC18: IP:192.168.5.5/24   
PC19: IP:192.168.5.6/24
Gateway: 192.168.5.1

Second floor:
PC10: IP:192.168.4.2/24   
PC11: IP:192.168.4.3/24   
PC12: IP:192.168.4.4/24
PC13: IP:192.168.4.5/24   
PC14: IP:192.168.4.6/24
Gateway: 192.168.4.1


**Note**: I have configured routing on the Multilayer Switch 3560-PS, all PCs can ping each other.

[Project you can see here](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/tree/master/m4/Task%204.2/projects)



##### 2


![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/2_1.png)
![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/2_2.png)

Floor 1:

PC1/1: IP:192.168.3.2/24   
PC2/1: IP:192.168.3.3/24   
PC3/1: IP:192.168.3.4/24  
Gateway: 192.168.3.1
-------------------------
PC4/1: IP:192.168.2.2/24   
PC5/1: IP:192.168.2.3/24   
PC6/1: IP:192.168.2.4/24   
PC7/1: IP:192.168.2.5/24   
PC8/1: IP:192.168.2.6/24
Gateway: 192.168.2.1

Floor 2:     
 
PC1/2: IP:192.168.4.2/24   
PC2/2: IP:192.168.4.3/24   
PC3/2: IP:192.168.4.4/24  
Gateway: 192.168.4.1
-------------------------
PC4/2: IP:192.168.5.2/24   
PC5/2: IP:192.168.5.3/24   
PC6/2: IP:192.168.5.4/24   
PC7/2: IP:192.168.5.5/24   
PC8/2: IP:192.168.5.6/24
Gateway: 192.168.5.1

Floor 3:

PC6/3: IP:192.168.7.2/24   
PC7/3: IP:192.168.7.3/24   
PC8/3: IP:192.168.7.4/24  
Gateway: 192.168.7.1
-------------------------
PC1/3: IP:192.168.6.2/24   
PC2/3: IP:192.168.6.3/24   
PC3/3: IP:192.168.6.4/24   
PC4/3: IP:192.168.6.5/24   
PC5/3: IP:192.168.6.6/24
Gateway: 192.168.6.1

Floor 4:

PC8/4: IP:192.168.9.2/24   
PC7/4: IP:192.168.9.3/24   
PC6/4: IP:192.168.9.4/24  
Gateway: 192.168.9.1
-------------------------
PC1/4: IP:192.168.8.2/24   
PC2/4: IP:192.168.8.3/24   
PC3/4: IP:192.168.8.4/24   
PC4/4: IP:192.168.8.5/24   
PC5/4: IP:192.168.8.6/24
Gateway: 192.168.8.1

Floor 5:

PC6/5: IP:192.168.11.2/24   
PC7/5: IP:192.168.11.3/24   
PC8/5: IP:192.168.11.4/24  
Gateway: 192.168.11.1
-------------------------
PC1/5: IP:192.168.10.2/24   
PC2/5: IP:192.168.10.3/24   
PC3/5: IP:192.168.10.4/24   
PC4/5: IP:192.168.10.5/24   
PC5/5: IP:192.168.10.6/24
Gateway: 192.168.10.1

**Note**: I have configured routing on the Multilayer Switch 3560-PS, all PCs can ping each other.

[Project you can see here](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/tree/master/m4/Task%204.2/projects)



##### 2

![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/3_1.png)
![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/3_2.png)
![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/3_3.png)
![image](https://github.com/shizgara/DevOps_online_Rivne_2020Q42021Q1/blob/master/m4/Task%204.2/images/3_4.png)



First building : VLAN 2
PC4/1: IP:192.168.2.2/24   
PC5/1: IP:192.168.2.3/24   
PC6/1: IP:192.168.2.4/24   
PC7/1: IP:192.168.2.5/24   
PC8/1: IP:192.168.2.6/24  
PC1/1: IP:192.168.2.7/24
Gateway: 192.168.2.1

Second building :   VLAN 5   
PC4/2: IP:192.168.5.2/24   
PC5/2: IP:192.168.5.3/24   
PC6/2: IP:192.168.5.4/24   
PC7/2: IP:192.168.5.5/24   
PC8/2: IP:192.168.5.6/24  
PC1/2: IP:192.168.5.7/24
Gateway: 192.168.5.1

Third building :    VLAN 6  
PC1/3: IP:192.168.6.2/24   
PC2/3: IP:192.168.6.3/24   
PC3/3: IP:192.168.6.4/24   
PC4/3: IP:192.168.6.5/24   
PC5/3: IP:192.168.6.6/24  
PC6/3: IP:192.168.6.7/24
Gateway: 192.168.6.1

Fourth building :    VLAN 8    
PC1/4: IP:192.168.8.2/24   
PC2/4: IP:192.168.8.3/24   
PC3/4: IP:192.168.8.4/24   
PC4/4: IP:192.168.8.5/24   
PC5/4: IP:192.168.8.6/24   
PC6/4: IP:192.168.8.7/24
Gateway: 192.168.8.1

Fifth building details:    VLAN 10    
PC1/5: IP:192.168.10.2/24   
PC2/5: IP:192.168.10.3/24   
PC3/5: IP:192.168.10.4/24   
PC4/5: IP:192.168.10.5/24   
PC5/5: IP:192.168.10.6/24   
PC8/5: IP:192.168.10.7/24
Gateway: 192.168.10.1










