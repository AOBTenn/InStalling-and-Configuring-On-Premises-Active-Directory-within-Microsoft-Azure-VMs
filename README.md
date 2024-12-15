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

First step is to install Active Directory. This is done by remote desktop logining into the DC-1 server with the user and password created in project-1 for this virtual machine. Then click on the start button and click on server manager from the menu pop up. On the server manager dashboard go to "Add Roles and Features," then click next three times to get ot the "sever Roles option sub-window. In this sub window click "Active Directory Domain Services," and then the add feature button. Then click the next button four more times to go to the "Confirm Intallation Selections" sub-window, and in this window check the restart box at the top and yes button to confirm before clicking the install botton.
<p>
</p>
<p>
</p>
Now as Active Diredctory is being installed, go back to Server Manager Dashboard and in the top right corner the window is a flag and a caution  simbol. Click on it and in the drop down menu click on "Promote this sever to domain controller" words  to be take n to  another  window. In this new window "Deployment Configuration," pick add a new forest and for the purpose type whatever domain you want in the textbox and click next. In the next window you type the password of you choosing and then press next, and in the next window "DNS Options" make sure that "Create DNS Delegation" is unchecked. Lastly you click next to cycle to the install button to click on it. The server will atomatically restart and you will have to Remote Destop login back into DC-1, first you needing to select more options, then enter the name of the forset you picked followed by a  backslash and then the original username and then the password. 
