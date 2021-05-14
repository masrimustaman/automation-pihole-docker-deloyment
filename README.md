# home_pihole

### Install

`sudo apt install docker.io`

### Add pi to docker group so that dont have to use sudo

`sudo usermod -aG docker pi`

### Check docker installation
```
docker info
docker version
```

### to run docker
```
chmod u+x ./docker_run.sh
./docker_run.sh
```

### Check status
`docker ps`
