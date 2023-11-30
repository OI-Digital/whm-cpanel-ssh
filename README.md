# Setup SSH access in cPanel

* Generate a new public/private pair in cPanel with a password
* Authorise the key pair
* "chmod 600 id_rsa" on your local PC
* Connect in terminal: ssh -p 22 -i /home/user/Documents/Work/id_rsa.pub user@IP

https://docs.cpanel.net/cpanel/security/ssh-access/
