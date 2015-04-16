## List containers
```bash
docker ps
```

## Attach to a running container
```bash
docker attach XXX
```
(where XXX are the first three characters of the Container ID)

## Running an interactive shell in an existing container
```bash
docker run -it XXX bash
```

## Detach from a container 
```bash
CTRL-p CTRL-q
```
(this will keep the container running)

# References

[https://docs.docker.com/reference/commandline/cli/]
[http://docs.docker.com/articles/basics/]
