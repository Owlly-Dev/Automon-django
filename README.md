# Automon Django
## Setup instructions(may differ for windows)
### Packages
install all packages
```sh
pip install -r requirements.txt
```
### Files
copy `.env.sample` to `.env`
```sh
cp .env.sample .env
```
edit contents of `.env` accordingly
```sh
DB_NAME=automon_dj
DB_USERNAME=
DB_PASSWORD=
DB_HOST=localhost
DB_PORT=5432
```
### Create DB and migration
login into psql terminal.

create a database for app.
```sql
CREATE DATABASE "automon_dj";
```