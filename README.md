# home_pihole

#to install
sudo apt install docker.io

#add pi to docker group so that dont have to use sudo
sudo usermod -aG docker pi

#to check docker installation
docker info
docker version

#to run docker
chmod u+x ./docker_run.sh 
./docker_run.sh 

#to check
docker ps
