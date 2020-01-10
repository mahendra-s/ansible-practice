# Setup-Steps

## Installation and configuration section

### Project setup

1) Create empty project directory `ansible-practice`
    
    `mkdir -p ansible-practice`
2) Initialize git repository
    
    `git init`


### Ubuntu setup 

1) Created Docker machine to run docker container systems

    `docker-machine create DockerDesktopVM`

2) Pull Ubuntu based docker image 

    `docker pull ubuntu`

3) Check image available

    `docker images`

4) Run docker

    `docker run -ti ubuntu /bin/bash`
    
 ## Install Ansible
 
 ```
  sudo apt update
  sudo apt install software-properties-common
  sudo apt-add-repository --yes --update ppa:ansible/ansible
  sudo apt install ansible
```

