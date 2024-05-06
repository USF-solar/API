# Non-ML API
## Start Server
```bash
$ go run main.go solarData.go
# Or build the code first (preferred)
$ go build main.go solarData.go -o api
$ ./api
```
## Call Server
```bash
# replace 0.0.0.0 with device ip
$ curl "http://0.0.0.0:8080/getSolarData?address=123%20Example%20Address"
```
