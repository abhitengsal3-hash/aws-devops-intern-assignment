# aws-devops-intern-assignment
Deployed a simple weebsite on an AWS EC2 instance using Nginx

1 EC2 instance setup 
* launced an ubuntu ec2 instance
* created a security group with inbound rules:
* port 22 (SSH)
* port 80 (HTTP)
* Downloaded key pair (.pem) and connected via ssh

2 linux basics
commands used on the instance
* sudo apt update
* sudo apnt install nginx -y
* sudo systemctl start nginx
* sudo systemctl status nginx
* sudo systemcyl restart nginx
* df -h (disk usage)
* free -h (memory usage)
* top ( running processes)

3 website deployment
* removed the default nginx landing page
* added custom index.html containing name, college name, branch, email and date
* deployed it on the web root
*commands used:

  cd /var/www/html
  
  sudo rm index.html
   
  sudo vi index.html
  
  
