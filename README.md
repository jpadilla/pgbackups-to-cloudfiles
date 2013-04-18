## Install pyrax
```
pip install pyrax
```

## Postgres
```
 sudo apt-get install postgresql
 sudo -u postgres createuser --superuser ubuntu
 createdb ubuntu
```

### Add this to pg_hba.conf

```
local    ubuntu     ubuntu                  trust
```

### Restart

```
sudo /etc/init.d/postgresql restart
```

### Install Heroku Toolbelt

```
wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh
heroku login
```