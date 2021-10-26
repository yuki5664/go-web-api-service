# go-web-api-service
go aip-server

## 起動方法
＜まずPostgreSQLを起動＞
```
$ psql -f install.sql
$ psql -f setup.sql
$ go build
$ ./14web_service &
$ ./script_create
$ psql -U gwp -d gwp -c "select * from posts;"
```
