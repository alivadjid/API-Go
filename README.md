### Simple API in Go

[Made with](https://go.dev/doc/tutorial/web-service-gin)

##### add

```
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

##### get all

```
curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET"
```

##### get one

```
curl http://localhost:8080/albums/1
```
