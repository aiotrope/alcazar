# alcazar
DBSWA assignment: Publish Subscribe with Redis

## CLI Commands

```bash
# build consumer
$ cd consumer && docker build -t consumer .

# build producer
$ cd producer && docker build -t producer .

# start app at the root directory; application running on port 7800
$ cd alcazar && docker compose up

# stop running container
$ docker compose down

``````
