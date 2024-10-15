# Run the docker container
``` docker-compose up -d ``` 

# Run the mongosh shell
```docker exec -it mongodb-shell mongosh "mongodb://root:example@mongo:27017/?authSource=admin" ```
