# docker-compose mongo db

```sh
# creating swarm cluster
docker swarm init

# deploy stack to docker swarm cluster
docker stack deploy -c docker-compose.yml a

# list of services on docker swarm cluster
docker service ls

# remove stack from docker swarm cluster
docker stack rm a

# delete docker swarm cluster (force because you are manager node)
docker swarm leave --force
```
