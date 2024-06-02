# devops-ex01

## docker mariadb initialize

```bash
docker run -d -p 3306:3306 --name dbserver -e MARIADB_ROOT_PASSWORD=bool112235 -e MARIADB_USER=booldook -e MARIADB_PASSWORD=bool1122 -e MARIADB_DATABASE=booldook -v ~/db/devops:/var/lib/mysql:rw mariadb
```

### title 1_1


