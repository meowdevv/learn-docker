FROM golang:1.22-alpine

RUN mkdir app
COPY main.go app

EXPOSE 8080

CMD go run app/main.go