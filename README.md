# envy

## install

### manually

build envy locally: 
```bash
git clone https://github.com/progrium/envy.git
cd envy
make build
```

start envy: 

```bash
make dev
```

## getting started


### check that envy is running

```bash
$ docker ps
CONTAINER ID        IMAGE               COMMAND                CREATED             STATUS              PORTS                                        NAMES
e242f185aea2        progrium/envy       "codep '/bin/execd -   2 seconds ago       Up 1 seconds        0.0.0.0:2222->22/tcp, 0.0.0.0:8000->80/tcp   envy.dev            
```

### get the ip address

```bash
$ docker inspect --format '{{ .NetworkSettings.IPAddress }}'  e242f185aea2 
172.17.0.7
```

### access per ssh

```bash
$ ssh <github_username>@172.17.0.7
```

### 

```bash

```
