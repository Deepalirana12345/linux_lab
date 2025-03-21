**Experiment**
Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well. Run the usermod -c command to update the comments of the operator1 user account. Remove 
the operator3 user from the system. 

command to be used

sudo useradd operator2

cat /etc/passwd | grep operator2

sudo passwd operator2

sudo useradd operator3

sudo useradd operator4

cat /etc/passwd | grep operator

sudo passwd operator3

sudo passwd operator4

sudo usermod -c "Primary system operator" operator2

cat /etc/passwd | grep operator2

sudo userdel operator4

sudo userdel -r operator4

cat /etc/passwd | grep operator4

![WhatsApp Image 2025-03-21 at 23 12 50_81a75ddf](https://github.com/user-attachments/assets/3ad1be34-f12f-453f-9b37-499ec11e8c0b)

![WhatsApp Image 2025-03-21 at 23 12 50_e551ffca](https://github.com/user-attachments/assets/9da40be1-6143-48ff-9e48-340151b2d0a2)












