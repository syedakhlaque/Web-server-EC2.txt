************************
Installing web server on EC2
************************

*  Start an EC2 instance

* In security group select ssh and http

* Connect to server

* Take control

* Update the server
# apt get update

* Install apache web server
# apt install apache2

*Edit index.html
# nano /var/www/html/index.html

* Start web server
# service apache2 start

* Verify whether service started or not
# service apache2 status

* Go to browser and enter the IP
