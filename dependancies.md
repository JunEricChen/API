sudo apt update
sudo apt upgrade
sudo apt-get install python3-pip

sudo apt install python3.12-venv
python3 -m venv ./venv

pip3 install ultralytics boto3
pip install "fastapi[standard]"
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
sudo apt install unzip
unzip awscliv2.zip
sudo ./aws/install
sudo ./venv/bin/python3 main.py