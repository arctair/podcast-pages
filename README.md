# podcast-pages
Template for Golang HTTP APIs
## Run the tests
```
$ go test github.com/arctair/podcast-pages/v1
$ go test -tags acceptance
```
or
```
$ nodemon
```
### Run the tests against a deployment
```
$ BASE_URL=https://your_deployment.com go test
```
## Run the server
```
$ go run .
$ curl localhost:5000
```
## Build a docker image
```
$ go build -o bin/podcast-pages
$ docker build -t arctair/podcast-pages .
```
