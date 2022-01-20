### Install

* install docker
    ```sh
    curl -fsSL https://get.docker.com -o get-docker.sh
    sh get-docker.sh
    ```
* install docker-compose
   ```sh
    sudo curl -L "https://github.com/docker/compose/releases/download/1.28.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
    ```
### Quick start
Step by step:
* clone classroom source to folder app/
```git clone https://github.com/pwnyniche/classroom```
* clone classroom-api source to folder api/
```git clone https://github.com/pwnyniche/classroom-api```
* docker compose up 
* run docker shell to build and deploy app