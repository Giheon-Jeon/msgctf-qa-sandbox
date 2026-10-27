FROM alpine:3.22
RUN echo 'MSGCTF{QA_CANARY_C2}' > /flag
CMD ["sh", "-c", "while true; do printf 'HTTP/1.1 200 OK\r\n\r\nhello\n' | nc -l -p 8080; done"]
