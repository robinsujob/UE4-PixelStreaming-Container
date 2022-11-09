## UE4 Workshop
This is UE4 Workshop needs container resource ,include: Dockerfile, docker-compose.yaml, tools.sh

### Build image

```
./tools build 
```

### Run Image
```
./tools start 
```

### Stop Image
```
./tools stop 
```

### Multi Project Run
PROJECT_NAME="DEMO01" ./tools.sh start
PROJECT_NAME="DEMO02" ./tools.sh start
PROJECT_NAME="DEMO03" ./tools.sh start
