# load-balancer

Simple load balancer

# How to use

```
Usage:
  -backends string
        Load balanced backends, use commas to separate
  -port int
        Port to serve (default 3030)
```

```
go run main.go --backends=http://localhost:3031,http://localhost:3032,http://localhost:3033,http://localhost:3034
```
