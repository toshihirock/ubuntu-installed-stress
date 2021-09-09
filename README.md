
# Build

```
docker build-t ubuntu-installed-stress .
```

# Run

```
docker run -it ubuntu-installed-stress /bin/bash
```

# Execute stress command

## vCPU = 1

```
docker exec -it xxxxxx
stress -c 1 -q &
```

## vCPU = 2

```
docker exec -it xxxxxx
stress -c 2 -q &
```
