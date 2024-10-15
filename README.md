# Run the docker container
``` docker-compose up -d ``` 

# Run the mongosh shell
```docker exec -it mongodb-shell mongosh "mongodb://root:example@mongo:27017/?authSource=admin" ```

# Use the following URL for connection with TablePlus

- Download tableplus from here(https://tableplus.com/)
  
``` mongodb://root:example@localhost:27017/admin ```