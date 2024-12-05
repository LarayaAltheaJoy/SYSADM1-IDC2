
<img width="684" alt="image" src="https://github.com/user-attachments/assets/c9feb06e-4ee0-46da-baeb-1bf3116248be">

1. # SYSADM1 – Managing Services in Linux

2. # Requirement: 

* A virtual machine running Linux 

<img width="399" alt="image" src="https://github.com/user-attachments/assets/b786042f-d1c9-4a44-8722-c60f024dca69">

Complete this lab as follows: 

1. Use the service –status-all command to list all active and inactive services.

List down active and inactive services in the table below. Provide five (5) services for each column.

| Active | Inactive |
| ----- | ----- |
| Alsa-utils | Anacron |
| apparmor | Bluetooth |
| apport | Console-setup.sh |
| Cron | Grub.common |
| cups | Keyboard-setup.sh |

SS:   
<img width="487" alt="image" src="https://github.com/user-attachments/assets/6326c9d4-7a1b-45df-afbf-7b837a53361a">

2. Start the Bluetooth service using the systemctl command. 

Ex. sudo systemctl start httpd

<img width="681" alt="image" src="https://github.com/user-attachments/assets/4ca33990-343e-4c32-ae3b-0b799c8d3072">

3. Check the status of the Bluetooth service. What is its status?  
   2. Bluetooth needs a wireless connection before I can control its services.

SS: 
<img width="681" alt="image" src="https://github.com/user-attachments/assets/a5e77019-76c2-418a-9285-f1961552fcfc">

1. Check the status of the cups services. Since when was it running?  
   2. \- Cups services was running since 09/12/2024 **8:47 AM**

SS:   
<img width="681" alt="image" src="https://github.com/user-attachments/assets/e77ab5f8-d71a-4737-8050-9d47338c7107">

5. Stop cups services.

   SS:

<img width="681" alt="image" src="https://github.com/user-attachments/assets/ae1b214d-859b-4121-bc1c-9417dda84e2b">

   6. Verify if the service was stopped. 

SS: 
<img width="531" alt="image" src="https://github.com/user-attachments/assets/49b7dfef-051d-4eb7-bc86-92b82a5a3764">

7. Restart the cups services

SS:  
<img width="681" alt="image" src="https://github.com/user-attachments/assets/fda1f1e5-02fb-4e8d-a065-628dcf3471c0">

8. Verify if the service was restarted. 

SS:  
<img width="681" alt="image" src="https://github.com/user-attachments/assets/e577a938-0891-4b9d-8b3c-62cd161089b3">

