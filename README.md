## Install Docker
(https://docs.docker.com/get-docker/)

Change permissions to act as root on Docker, otherwise you have to use sudo.
## Building Server3
    - cp .env.example .env
    - (sudo) docker-compose up -d --build
    - sudo vi /etc/hosts
    - Add line => 127.0.0.1 server3.loc
    - visit http://server3.loc
