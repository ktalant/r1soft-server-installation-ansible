# r1soft-server-installation-ansible

1. Make sure volumes attached to R1Soft-Server
  - login to R1Soft  EC2
  - # lsblk
  
2. Get the appropriate volume to create filesystem and mount, might be /dev/xvdf or different
   Once you get appropriate volume change the name in VARS section of deployment
  - # lsblk
    
