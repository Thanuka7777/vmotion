# vmotion
1.tab Configuration-> Networking

![image](https://cloud.githubusercontent.com/assets/15711984/18395992/e7d4c3c4-76de-11e6-879d-93dd944cfc3c.png)

2.Click on Add Networking to create the vSwitch.

![image](https://cloud.githubusercontent.com/assets/15711984/18396013/0951a698-76df-11e6-8ad6-0b7929216156.png)

3.Select VMKernel and click on Next.

![image](https://cloud.githubusercontent.com/assets/15711984/18396064/44453544-76df-11e6-82ad-9660a0a9e3f6.png)
![image](https://cloud.githubusercontent.com/assets/15711984/18396074/56167990-76df-11e6-9417-3c618987f7ea.png)

4.We set Use this port group for vMotion.

   We wrote a Label Network different if you want (optional) and click on Next. We for example we put Vmotion. 
![image](https://cloud.githubusercontent.com/assets/15711984/18396109/844a9cba-76df-11e6-94bb-2329d6074adf.png)

5.IP Address: 50.50.50.1
Subnet Mask: 255.255.255.252 (Since we will use only 2 ip's).
Click on Next.

![image](https://cloud.githubusercontent.com/assets/15711984/18396154/b83c21ec-76df-11e6-9963-cb21ac7e51fd.png)
6.Click on Finish. 

![image](https://cloud.githubusercontent.com/assets/15711984/18396183/d9b497f0-76df-11e6-85aa-9c06c890c7bb.png)

7.We select the tab Configuration-> Network Adapters and we see that we have visibility of the new connections.

![image](https://cloud.githubusercontent.com/assets/15711984/18396203/f75ab9b0-76df-11e6-9b6b-5cba34f58930.png)

8.Now look at the tab Configuration-> Networking

![image](https://cloud.githubusercontent.com/assets/15711984/18396232/1ecfff78-76e0-11e6-8fd2-215f58bdc92d.png)

9.Click on Add Networking to create the vSwitch. 

![image](https://cloud.githubusercontent.com/assets/15711984/18396246/3c253106-76e0-11e6-98f6-6d2a2bef452e.png)

10.Select VMKernel and click on Next. 

![image](https://cloud.githubusercontent.com/assets/15711984/18396257/5480f780-76e0-11e6-8dc5-3b583428b6a9.png)

11.Use this port group for VMotion.

![image](https://cloud.githubusercontent.com/assets/15711984/18396273/7030cdd4-76e0-11e6-8b24-b2718c94f7a0.png)
![image](https://cloud.githubusercontent.com/assets/15711984/18396281/791ac968-76e0-11e6-9eb5-4e78861edc0b.png)

12.IP Address: 50.50.50.2 (This ip must be different from the server that  configured earlier 1).
Subnet Mask: 255.255.255.252 
Click on Next. 

![image](https://cloud.githubusercontent.com/assets/15711984/18396305/939927ee-76e0-11e6-8fdc-859c38ccede1.png)

13.Click on Finish.

![image](https://cloud.githubusercontent.com/assets/15711984/18396336/b95e2182-76e0-11e6-8b4a-d946a64e834f.png)

Now what we will do to ensure that the entire system is working properly migrate a VM from one ESXi to the other using Vmotion functionality you just configured.

14.Click on Migrate.

![image](https://cloud.githubusercontent.com/assets/15711984/18396368/dddb307c-76e0-11e6-941e-7b6b511204dd.png)
15.Click on Next.

![image](https://cloud.githubusercontent.com/assets/15711984/18396393/f738ab80-76e0-11e6-9766-347959b98be2.png)

16.Select the target server where to move the virtual machine. 
Click on Next.

![image](https://cloud.githubusercontent.com/assets/15711984/18396410/0de41180-76e1-11e6-8f15-72768107c973.png)

17.Click on Next.

![image](https://cloud.githubusercontent.com/assets/15711984/18396424/23402b5e-76e1-11e6-8487-6524593a10f2.png)
![image](https://cloud.githubusercontent.com/assets/15711984/18396429/298115fa-76e1-11e6-901f-c431b999fa9f.png)

Click on Finish to start the migration.

![image](https://cloud.githubusercontent.com/assets/15711984/18396447/435f51b2-76e1-11e6-8e20-62bf2fe8ded5.png)

