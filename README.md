Install Certbot
Kemudian kamu perlu menginstal Let’s Encrypt Client, yaitu Certbot. Namun sebelum itu, kamu memerlukan repositori bernama EPEL Repository. Ikuti perintah berikut:

$ yum install epel-release -y

$ yum install certbot-nginx

$ certbot --nginx
