# nsr scraper

## docs
 - [aws-lambda-go](https://github.com/aws/aws-lambda-go/blob/main/README.md)

## tools
 - installed zip tool with `go install github.com/aws/aws-lambda-go/cmd/build-lambda-zip`

## build
```
GOOS=linux GOARCH=amd64 go build -o main main.go
build-lambda-zip -o main.zip main
```
