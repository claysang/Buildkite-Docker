```bash
docker swarm init

docker service create --name registry --publish published=5000,target=5000 registry:2

printf "leichao" | docker secret create POSTGRES_USER -

printf "ninhao" | docker secret create POSTGRES_PASSWORD -
```
