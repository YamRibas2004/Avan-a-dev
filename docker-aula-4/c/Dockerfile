FROM golang:1.15-alpine

WORKDIR /go/src/c

COPY . .

RUN GOOS=linux go build c.go

EXPOSE 9092

ENTRYPOINT [ "./c" ]