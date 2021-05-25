# basicforms
sudo apt-get update

sudo apt upgrade -y

getent group sudo | cut -c11-

sudo apt-get install python3 -y

sudo apt install python3-pip -y

sudo pip3 install virtualenv

sudo apt install supervisor -y

sudo pip3 install django

sudo pip3 install gunicorn

sudo cp gunicorn_supervisor.conf /etc/supervisor/conf.d

sudo supervisorctl update

eval echo ~$USER
(path of home directory)
