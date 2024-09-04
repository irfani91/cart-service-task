### Run Migration
```
go run migration.go ./sql "host=localhost port=5432 user=citizix_user dbname=citizix_db password=S3cret sslmode=disable" up
```

### Down Migration
```
go run migration.go ./sql "host=localhost port=5432 user=root dbname=db_order password=fatannajuda sslmode=disable" down
```

### Create new SQL
```
go run migration.go ./sql "host=localhost port=5432 user=root dbname=db_order sslmode=disable" create add_orders_table sql
```