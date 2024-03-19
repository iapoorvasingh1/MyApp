FROM golang:latest

WORKDIR /go/src/app

COPY ..

RUN go build -o MyApp

EXPOSE 8080

CMD ["./MyApp"]


