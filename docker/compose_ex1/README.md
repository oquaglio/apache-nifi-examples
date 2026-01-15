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

https://localhost:8443/nifi


## Status

https://localhost:8443/nifi-api/system-diagnostics


## Add Snowflake Connector

docker exec -it nifi bash

wget -O ./nifi-extensions/nifi-snowflake-processors-nar-2.7.0.nar \
  https://repo1.maven.org/maven2/org/apache/nifi/nifi-snowflake-processors-nar/2.7.0/nifi-snowflake-processors-nar-2.7.0.nar

.. or, just mount into local dir: nifi-extensions
