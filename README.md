# SSH_in_Azure_Linux_VM_using_Private_Key

1.  Open the client of your choice
  - WSL on windows
  - Terminal on Mac
  - Shell on Linux
 
2.  Must have a read only access to the private key file.
   -  use the following command for read only access to the key file.
        - chmod 400 <keyname>.pem
3.  Get the path your SSH private file
   -  You can use pwd to get the directory displyed in the shell and copy
4.  Use the following syntax with your private key and connect to he VM.
    - ssh -i <private key path> azureuser@ <IP address>
   
