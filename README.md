# miniverse-docker
Miniverse Docker edition

Warning: Dataverse database should be installed first:
```
docker exec -it postgres /bin/bash -c 'psql -U dvnapp dvndb -h localhost -f /etc/postgresql/9.3/dump/dvn.sql'
```
