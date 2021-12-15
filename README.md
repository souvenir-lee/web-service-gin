## README
Practice for gin framework in go language

### GET
```bash
curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET"
```

### GET by ID
```bash
curl http://localhost:8080/albums/:id \
    --header "Content-Type: application/json" \
    --request "GET"`
```

### POST
```bash
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

### Reference
go docs : https://go.dev/doc/tutorial/web-service-gin
