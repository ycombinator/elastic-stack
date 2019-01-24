## Elastic Stack Quick Setup

Spins up a 1-node ES cluster and Kibana. Kibana is accessible on http://localhost:5601.

### Running the latest version

```
$ docker-compose up
```

### Running an older version

```
$ STACK_VERSION=6.5.0 docker-compose up
```

### Stopping

```
$ docker-compose stop
```
 