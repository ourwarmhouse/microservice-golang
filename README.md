## Commands

### Build and run image of docker

```bash
docker-compose up  --build  -d
```

### Swagger Implementation

```bash
swag init -g src/infrastructure/rest/routes/routes.go
```

To visualize the swagger documentation on local use

http://localhost:8080/v1/swagger/index.html

To see the postman collection use 
  
https://www.postman.com/kts-mexico/workspace/boilerplategomicroservice


### Unit test command

```bash
# run recursive test
go test  ./test/unit/...
# clean go test results in cache
go clean -testcache
```

### Lint inspection of go

```bash
golangci-lint run ./...
```



