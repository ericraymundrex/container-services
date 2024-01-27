Build a Image:

```docker build -t mypostgresimage .```

Run the container
```docker run -d --name mypostgrescontainer -p 5432:5432 mypostgresimage ```

Download the DMG for PGAdmin:
https://www.postgresql.org/ftp/pgadmin/pgadmin4/v8.2/macos/

Give the Host Name:
```localhost```
