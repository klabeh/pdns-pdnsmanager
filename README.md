# PowerDNS Docker Images with PDNS Manager

download or use git
```
cd /opt
git clone https://gitlab.com/klabeh/pdns-pdnsmanager.git
```

edit docker-compose.yml and change
```
DB_ENV_MYSQL_ROOT_PASSWORD=changeme
MYSQL_ROOT_PASSWORD=changeme
```

then run with
```
docker-compose up -d
```