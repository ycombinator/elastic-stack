## Elastic Stack Quick Setup

Spins up a 1-node ES cluster and Kibana. Kibana is accessible on http://localhost:5601.

The trial license is installed and Security is enabled.

### Running the latest version

```
$ docker-compose up
```

### Running an older version

```
$ STACK_VERSION=7.7.0 docker-compose up
```

### Stopping

```
$ docker-compose stop
```
 