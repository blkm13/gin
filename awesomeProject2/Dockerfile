FROM golang:1.16
WORKDIR /usr/app
COPY . .
RUN go get github.com/gin-gonic/gin
RUN go build src/main.go

EXPOSE 8080

CMD go run src/main.go


