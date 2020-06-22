# docker-shell

## Create a container

```bash
dockershell create --image ubuntu:20.04 --shared-dir /tmp/shared mycontainer
```

## List all containers

```bash
dockershell list
```

## Open a shell in the container

```bash
dockershell open mycontainer
dockershell open --root mycontainer
```

## Start/stop the container

```bash
dockershell start mycontainer
dockershell stop mycontainer
```

## Delete the container

```bash
dockershell delete mycontainer
```
