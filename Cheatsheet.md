# Cheatsheet for Quickstart
### Setup default parameters
pwd  
ls -la  
git clone https://github.com/noyanagi/elastdocker.git  
la -la  
cd elastdocker  
ls -la  
vi .env  
cat .env  
### Setup cert and keystore  
sudo sysctl -w vm.max_map_count=262144  
sudo apt install make  
sudo docker login -u noyanagi  
sudo make setup  
### Run Elastic Stack  
sudo make elk  
### Examine Elastic Stack  
sudo docker images  
sudo docker ps  
sudo docker compose ps  
sudo docker compose images  
### Run Filebeat  
sudo make collect-docker-logs  
sudo docker images  
sudo docker ps  
sudo docker compose ps  
sudo docker compose images  
### Visit Kibana
https://HOST-IP:5601  
username: elastic  
password: changeme  
