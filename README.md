# <p align="center">Installing and Configuring On Premises Active Directory within Microsoft Azure VM
![image](https://github.com/user-attachments/assets/e4f41676-9505-49cf-82a1-c1ad2d5cf390)


In this third part of the project, Active Directory will be installed and configured to simulated real world user conditions within a working environment using previously created virtual machines in projects part-1 https://github.com/AOBTenn/Preparing-Active-Directory-Environment-within-Azure-VMs-Part1.git  and part-2 https://github.com/AOBTenn/Preparing-Active-Directory-Environment-within-Azure-VMs-Part2.git .<br />


<h2>Environments and Technologies Used</h2>

- Desktop Pc
- Internet
- Microsoft Azure VMs 

<h2>Operating Systems Used </h2>

- Windows 11 Home</b>

<h2>List of Prerequisites</h2

- Laptop or Desktop Pc                                                                                                                                 
- Internet Access
- Microsoft Azure Account

<h2>Procedure Steps</h2>

First step is to install Active Directory. This is done by remote desktop logining into the DC-1 server with the user and password created in project-1 for this virtual machine. Then click on the start button and click on server manager from the menu pop up (refer to image 1). On the server manager dashboard go to "Add Roles and Features"(refer to image 2 and 3) then click next three times to get ot the "sever Roles option sub-window. In this sub window click "Active Directory Domain Services" and then the add feature button (refer to image 4). Then click the next button four more times to go to the "Confirm Intallation Selections" sub-window, and in this window check the restart box at the top and yes button to confirm before clicking the install botton.

![image](https://github.com/user-attachments/assets/f96ee540-a3f5-4838-819d-52a921eccd39)
<p>Image 1
</p>

![image](https://github.com/user-attachments/assets/8535b58b-9377-459c-8399-75cfba35310b)
<p>Image 2
</p>

![image](https://github.com/user-attachments/assets/0a6446ac-f122-4815-8850-c18033632abf)
<p>Image 3
</p>

![image](https://github.com/user-attachments/assets/4da2dad9-e086-4376-bb25-527d5b85147c)
<p>Image 4
</p>


Now as Active Diredctory is being installed, go back to Server Manager Dashboard. In the top right corner the window is a flag and a caution symbol, click on it and in the drop down menu click on "Promote this sever to domain controller" words (refer to image 5) to be taken to another window. In this "Deployment Configuration" window, pick add a "New Forest" and type whatever domain name you want in the textbox and click next (refer to image 6). In the next window you type the password of you choosing (refer to image 7) and then press next again. In this other "DNS Options" window make sure that "Create DNS Delegation" is unchecked (refer to image 8). Lastly you click next to cycle to the install button to click on it (refer to image 9). The server will atomatically restart (refer to image 10) and you will have to Remote Destop login back into DC-1. This is done by selecting "Show Options" in the bottom left corner of the Remote destop window (refer to image 11), then enter the name of the forset you picked followed by a backslash and then the original username in the username bar (refer to image 12), and then the password (refer to image 13). 

![image](https://github.com/user-attachments/assets/370321dd-1b99-411e-b572-6a338c15806c)
<p>Image 5
</p>

![image](https://github.com/user-attachments/assets/8a72ba4f-d1ad-48e6-ab42-0e69c90cb757)
<p>Image 6
</p>

![image](https://github.com/user-attachments/assets/0da27eb7-dfe0-4cea-93ef-09557cf8261e)
<p>Image 7
</p>

![image](https://github.com/user-attachments/assets/9d314823-9ff3-4474-85ef-54f025fbc44e)
<p>Image 8
</p>

![image](https://github.com/user-attachments/assets/7dfe46d9-296e-4425-bfa1-803c1ef2d76d)
<p>Image 9
</p>

![image](https://github.com/user-attachments/assets/53c58aa7-86e6-4e30-b487-89142778f068)
<p>Image 10
</p>

![image](https://github.com/user-attachments/assets/e4b4cd22-c26d-4215-b073-d3048ec58e42)
<p>Image 11
</p>

![image](https://github.com/user-attachments/assets/264cb0cd-abf7-4e12-8ca0-ffc10c11c394)
<p>Image 12
</p>

![image](https://github.com/user-attachments/assets/1fd2144e-4f19-46dd-8b39-72b76fb47046)
<p>Image 13
</p>
<p>
</p>




