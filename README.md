# wp-theme-example
Convert an HTML Template to a WordPress Theme

# How to run (local)
1. run `up_server.sh`
2. initialize db: `db_import.sh <dump_file_name.sql>` (ex: `db_import.sh db_1594877266.sql`)
3. confirm at: https://localhost. and https://localhost/wp-login.php (user/bitnami)

# Backup database
1. run `db_export.sh` to dump current db and save to `app/sql`
2. run `db_import.sh <dump_file_name.sql>` to import sepecifed sql to db
