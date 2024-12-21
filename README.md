# <p align="center">Installing and Configuring On Premises Active Directory within Microsoft Azure VM
![image](https://github.com/user-attachments/assets/e4f41676-9505-49cf-82a1-c1ad2d5cf390)


In this third and final project, Active Directory will be installed and configured to simulated real world user conditions within a working environment using previously created virtual machines in projects part-1 https://github.com/AOBTenn/Preparing-Active-Directory-Environment-within-Azure-VMs-Part1.git  and part-2 https://github.com/AOBTenn/Preparing-Active-Directory-Environment-within-Azure-VMs-Part2.git .<br />


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


Now as Active Diredctory is being installed, go back to Server Manager Dashboard and in the top right corner the window is a flag and a caution  simbol. Click on it and in the drop down menu click on "Promote this sever to domain controller" words  to be take n to  another  window. In this new window "Deployment Configuration," pick add a new forest and for the purpose type whatever domain you want in the textbox and click next. In the next window you type the password of you choosing and then press next, and in the next window "DNS Options" make sure that "Create DNS Delegation" is unchecked. Lastly you click next to cycle to the install button to click on it. The server will atomatically restart and you will have to Remote Destop login back into DC-1, first you needing to select more options, then enter the name of the forset you picked followed by a backslash and then the original username and then the password. 


<p>Image 1
</p>

(refer to image 3)
