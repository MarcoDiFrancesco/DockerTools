# Docker tools
Docker tools is a collections of tools that's possible to use with the raspberry.  
The programs are installed via docker and Docker Compose is needed.

## How to install
Get docker:
```
curl -sSL https://get.docker.com | sh
```

Install proper dependencies and docker-compose:
```
sudo apt-get install libffi-dev libssl-dev
sudo apt-get install -y python python-pip
sudo apt-get remove python-configparser
sudo pip install docker-compose
```

Clone the repo and run:
```
docker-compose up -d
```

![Server DNS](https://i.imgur.com/6w6EI0e.png)

## Setup DNS Server
Add this configuration to the router to use the raspberry as DNS server.

![Router settings](https://i.imgur.com/Cxgbm3t.png)

## Done!