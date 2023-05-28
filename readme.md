# CMDs

## Start Container
`MYSQL_ROOT_PASSWORD=secure docker-compose up -d.`

## Connect to MySql Shell
`docker exec -it my-mysql mysql -p`

## Import Database from File
`docker exec -it my-mysql mysql -psecret database_name < path-to-file.sql`

# Other Shit

## Seed Files

Put files u wanna run from the start on /docker-entrypoint-initdb.d
