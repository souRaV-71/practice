Step 1 — Setting Up Python 3

sudo apt-get update && sudo apt-get install -fy python3-pip build-essential libssl-dev libffi-dev python3-dev python3-venv

###### OPTIONAL #######

Step 2 — Setting Up a Virtual Environment

mkdir environments
cd environments

python3.9 -m venv my_env

ls my_env

source my_env/bin/activate