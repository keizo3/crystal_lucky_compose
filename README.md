# crystal Lucky Development Environment

## Overview

### container
Use the following group of containers  
- crystal  
- crystal.postgres


## Getting started

#### install docker
https://www.docker.com/docker-mac

### clone this repository and crystal lucky project repository
```
git clone git@github.com:keizo3/crystal_lucky_compose.git
git clone git@github.com:keizo3/crystal_mfa.git
```

#### up
in the cloned directory
```
cd crystal_lucky_compose
docker-compose up -d
```

access to  
[http://127.0.0.1:3001](http://127.0.0.1:3001)

#### docker containers stop
```
docker-compose stop
```

#### docker containers clean
in the cloned directory
```
docker-compose down
```
