# https://www.dewaweb.com/blog/cara-install-ssl-lets-encrypt-pada-nginx-di-centos-7/

# Install Certbot CentOS 7 64bit

yum install epel-release -y

yum install certbot-nginx

certbot --nginx
