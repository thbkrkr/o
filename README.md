# o

```
> o help
Usage: o COMMAND [arg...]

Commands:
  machine   Manage machines
  dns       Manage DNS
  logs      Manage logs
  metrics   Manage metrics
  services  Manage services
```

## Example

```
o machine create
o dns add bim
o logs up -d
o logs stream
o metrics up -d
o metrics list
o metrics query telegraf.docker_container_mem_usage
o service init
o service scale api=2
```