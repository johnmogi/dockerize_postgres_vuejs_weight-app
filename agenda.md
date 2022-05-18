running the postgresql vue nodejs weight app inside a docker container.

step 1 - make it work.
https://tecadmin.net/install-nodejs-with-nvm/
nvm install 14 // current working version

https://www.youtube.com/results?search_query=mosh+docker

step 2 - wrap it up.

<!-- docker image prune -a -->

build a machine-
alpine
node 14
docker

docker-compose up -d

<!-- --name postweight -->

<!-- docker run [OPTIONS] IMAGE [COMMAND] [ARG...] -->
<!-- sudo docker run ––name post-weight -d /bin/bash -->

docker exec -it docker_postgres_webserver_1 /bin/bash
sudo docker exec –it nginx-test /bin/bash
sudo docker exec docker_postgres_webserver_1 /bin/bash

https://faun.pub/how-to-build-a-node-js-application-with-docker-f596fbd3a51

docker build -t johnmogi .
