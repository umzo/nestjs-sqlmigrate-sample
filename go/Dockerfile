FROM golang:1.19.2-alpine
RUN apk update && apk add git \
    && apk add musl-dev gcc make g++ file

RUN go install github.com/rubenv/sql-migrate/...@latest