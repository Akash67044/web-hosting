# web-hosting
firstly create a EC2 instance
connect to ssh key
chmod 400 "delhi.pem"
install apache
sudo yum update -y
sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd
apache default directory move
cd /var/www/html
existing file remove
sudo rm -rf index.html
new html and css file create
sudo nano index.html
sudo nano style.css
fix the permission
sudo chmod -R 755 /var/www/html
sudo chown -R www-data:www-data /var/www/html
restart the apache2
now you will access the website in ip address
http://34.226.246.156/
