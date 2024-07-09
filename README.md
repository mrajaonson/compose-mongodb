# compose-mongodb
Docker compose mongodb

* https://www.mongodb.com/docs/manual/tutorial/install-mongodb-community-with-docker/#std-label-docker-mongodb-community-install

## Requirements
* Docker
* Mongosh (https://www.mongodb.com/docs/mongodb-shell/install/)

```shell
# start
docker compose up -d

# stop 
docker compose down
```

## Mongosh
* https://www.mongodb.com/docs/mongodb-shell/

```shell
mongosh --port 27017

mongosh --port 27017 --username <username>
```

## Compass (GUI)
* https://www.mongodb.com/docs/compass/master/
