#Install Certbot CentOS 7 64bit

yum install epel-release -y

yum install certbot-nginx

certbot --nginx
