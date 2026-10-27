FROM alpine:3.22
CMD ["sh", "-c", "while true; do printf 'HTTP/1.1 200 OK\r\n\r\nhello\n' | nc -l -p 8080; done"]
