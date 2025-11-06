# pythonflaskapp
```
ec2 - ssh 
// reference https://github.com/atulkamble/pythonflaskapp#

sudo yum update -y 
sudo yum install git -y 
git config --global user.name "Atul Kamble"
git config --global user.email "atul_kamble@hotmail.com"
git config --list 

sudo yum install docker -y 
sudo systemctl start docker 
sudo systemctl enable docker 
sudo docker login 

sudo yum install python -y 
python --version
sudo yum install pip -y 
pip --version
pip install flask
flask --version

git clone https://github.com/atulkamble/pythonflaskapp.git
cd pythonflaskapp

python app.py 

http://3.89.60.200:5000/

sudo docker build -t atuljkamble/pythonflaskapp .
sudo docker images
sudo docker run -d -p 5000:5000 atuljkamble/pythonflaskapp
sudo docker container ls

// install docker compose 

sudo mkdir -p /usr/local/lib/docker/cli-plugins
sudo curl -SL https://github.com/docker/compose/releases/download/v2.27.0/docker-compose-linux-x86_64 -o /usr/local/lib/docker/cli-plugins/docker-compose
sudo chmod +x /usr/local/lib/docker/cli-plugins/docker-compose

docker compose version 

docker compose up -d



```
