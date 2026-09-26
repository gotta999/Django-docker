# Django-docker

Setting up django using docker containerization

first thing launch ec2 from aws ubuntu then using mobaxterm launch it in local
now create ssh key to clone git repo 
ssh-keygen -t rsa -b 4096 -C "example@gmail.com"
then cat rsa.pub and copy and paste it setting of github sshand gpg keys
now git clone repo 
now install docker
sudo apt update 
sudo apt install docker.io -y
# install python for django setup
sudo apt install python3 python3-pip python3-venv -y
python3 --version
pip3 --version
mkdir Django
ubuntu@ip:~/Django-docker$ cd Django

Create and Activate the Virtual EnvironmentCreate an isolated environment named venv. This ensures that your Django dependencies do not conflict with other Python software on Ubuntu:bashpython3 -m venv venv

source venv/bin/activate
Use code with caution.Note: Once activated, your terminal prompt will change to show (venv) at the beginning.

Upgrade pip to the latest version and install Django:bashpip install --upgrade pip
pip install django
#
Confirm that Django is installed correctly by checking the framework version:bashdjango-admin --version



