**Experiment**
Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions.  Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. 
Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

command to be used

sudo mkdir -p /home/consultants

sudo chmod g+w /home/consultants

sudo chgrp consultants /home/consultants

sudo chmod 770 /home/consultants

sudo nano /home/operator1/.bashrc

umask 007

source /home/operator1/.bashrc

umask

output: 0007

![WhatsApp Image 2025-03-21 at 21 59 31_abab4a9a](https://github.com/user-attachments/assets/22b20c47-8e97-4f63-b61a-2d32439e5bf4)

![WhatsApp Image 2025-03-21 at 21 59 31_7f545553](https://github.com/user-attachments/assets/d97b0b19-db64-434f-827f-78f2f6c41d29)




