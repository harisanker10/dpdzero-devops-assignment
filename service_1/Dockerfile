FROM golang:1.21-alpine
RUN apk add curl

WORKDIR /app
COPY . .
EXPOSE 8001

CMD ["go","run","./main.go"]
