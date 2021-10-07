FROM golang:alpine as builder
WORKDIR /go/src/app 
COPY . .
ADD . .
RUN go mod init
RUN go build -o main

FROM scratch
WORKDIR /go/src/app
COPY --from=builder /go/src/app .
ENTRYPOINT ["./main"]