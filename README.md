# basicforms
sudo apt-get update
sudo apt upgrade -y
sudo apt-get install python3 -y
sudo apt install python3-pip -y
sudo apt install supervisor -y
sudo pip3 install django
sudo pip3 install gunicorn
sudo cp gunicorn_supervisor.conf /etc/supervisor/conf.d
sudo supervisorctl update
