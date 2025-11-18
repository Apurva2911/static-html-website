1. EC2 - ssh | SG (ssh-22, http-80, https-443)
2.
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
cd /var/www/html
sudo chmod 755 /var/www/html
sudo git clone https://github.com/Apurva2911/static-html-website
cd static-html-website
sudo touch index.html


3. http://54.196.247.54/static-html-website
