# Notes

Gorilla/Mux
Gorm
MySql

```bash
go mod init bookstore
go get "github.com/jinzhu/gorm"
go get "github.com/jinzhu/gorm/dialects/mysql"
go get "github.com/gorilla/mux"

go mod tidy

cd cmd/
go build

go run main.go
```