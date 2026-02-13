Java Application 

Create An EC2 instance
login EC2 in ssh
#sudo apt install && sudo apt upgrade -y
#sudo apt install net-tools


Install Docker in EC2
#sudo apt install docker.io -y

Add a dokcer group
#groupadd docker
#sudo usermod -aG docker ubuntu
#systemctl enable docker
#systemctl start docker

Connect Github with docker with the hepl of PAT
connect EC2 with github

Goto secret and varibale and create it
NAME: DOCKERHUB_USERNAME
DOCKERHUB_TOKEN   generate a PAT in docker hub
EC2_HOST <PUB IP>
EC2_USER <ubuntu>
EC2_SSH_KEY <PEM KEY>


NOW CREATE YAML FILE
