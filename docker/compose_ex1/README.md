#

Start:
```sh
docker compose up -d
```

Cleanup:
```sh
docker compose down --volumes --remove-orphans
```

## Conn to UI

http://localhost:8080/
https://localhost:8443/nifi


## Status

http://localhost:8080/nifi-api/system-diagnostics
