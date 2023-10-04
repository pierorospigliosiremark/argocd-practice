FROM golang
COPY main.go .
RUN go build -o main main.go
EXPOSE 8082
CMD ["./main"]
