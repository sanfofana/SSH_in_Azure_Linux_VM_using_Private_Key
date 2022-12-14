# SSH_in_Azure_Linux_VM_using_Private_Key

- Note: In this project I install a kali linux VM from azure, and SSH in the using a private key (SHA256).
- The virtual machine had been depley on azure.
- The private key should be downlod while deploying the machine or after deployment.
- It is important to know the private key location.

##  1.  Open the client of your choice
  - WSL on windows
  - Terminal on Mac
  - Shell on Linux

<img src="https://github.com/sanfofana/multipurpfiles/blob/main/Kali1.png" height="80%" width="80%" alt=""/>

## 2.  Must have a read only access to the private key file.
   -  use the following command for read only access to the key file.
        - chmod 400 <keyname>.pem
##  3.  Get the path your SSH private file
   -  You can use pwd to get the directory displyed in the shell and copy
4.  Use the following syntax with your private key and connect to he VM.
    - ssh -i <private key path> azureuser@ <IP address>

   
## 5. After confirmation you should get access to your linux Shell.
  
  <img src="https://github.com/sanfofana/multipurpfiles/blob/main/Kali4.png" height="80%" width="80%" alt=""/>
