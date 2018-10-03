# miniverse-docker
Miniverse Docker edition

Warning: Dataverse database should be installed first:
```
git clone https://github.com/Dans-labs/miniverse 
git checkout development
cp config/local_settings.py ./miniverse/config/local_settings.py
docker exec -it postgres /bin/bash -c 'psql -U dvnapp dvndb -h localhost -f /etc/postgresql/9.3/dump/dvn.sql'
docker-compose up
```
