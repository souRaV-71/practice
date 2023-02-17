Step 1 — Setting Up Python 3

sudo apt update
sudo apt -y upgrade

python3 -V

sudo apt install -y python3-pip

pip3 install package_name

sudo apt install build-essential libssl-dev libffi-dev python3-dev

###### OPTIONAL #######

Step 2 — Setting Up a Virtual Environment

sudo apt install -y python3-venv

mkdir environments
cd environments

python3.9 -m venv my_env

ls my_env

source my_env/bin/activate