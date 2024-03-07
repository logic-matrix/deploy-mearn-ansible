# Deploy a MERN Application to a Linux Server

## 1.Create a Directory
Make a directory using this command
### `mkdir "/my_node_app"`

## 2.Git
Install git 
### `sudo apt install git`
Clone git repo
### `git clone https://github.com/Tarikul69/DevOps-Project.git`

## 3.Docker
Install Docker
### `sudo apt install docker.io docker-compose`
Then pull Node image
### `docker pull node:14`
Run NodeJs app in Docker container
### ` docker run -p 3000:3000 -d my_node_app`


 
## 4.Nginx
install Nginx
### `sudo apt install nginx`
Copy nginx config file
### `docker cp /path/to/local/nginx.conf container_name:/etc/nginx/nginx.conf`
Start Nginx
### ` `