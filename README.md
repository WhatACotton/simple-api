http://localhost:3000 からのリクエストをよしなに返してくれます。

サーバーを建てるとき
```sh
go mod tidy
go run main.go
```
リクエストを投げるとき
```sh
curl http://localhost:8080
```