# PowerDNS Docker Images with PDNS Manager

# PowerDNS & PowerDNS Backend mySQL

# PDNS Manager
[PDNS Manager](https://pdnsmanager.lmitsystems.de) is a simple yet powerful free administration tool for the
Powerdns authoritative nameserver. It supports master and native zones.
PNDS Manager was developed from scratch to achieve a user-friendly
and pretty looking interface.

## More information
You can find more information and documentation as well as contact information on [pdnsmanager.lmitsystems.de](https://pdnsmanager.lmitsystems.de).

# Howto use it

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