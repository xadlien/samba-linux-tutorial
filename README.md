# Samba Linux Tutorial
## Description
This repository was created to go along with the post https://danstechjourney.com/connecting-to-windows-share-on-linux-samba. The install instructions will be here but the tutorial will be on that website.
## Installation
docker-compose is required for this tutorial.
```
sudo docker-compose up -d
sudo docker exec -it smb-client bash
```
After install and you run the docker exec command, you can start testing commands as the lucy user.