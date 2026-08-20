
# PostgreSQL

## Tested Database

```text
Database : baeckrad
Role     : baeckrad_radius
Host     : 127.0.0.1
Port     : 5432
```

## RADIUS Tables

```text
Database yang digunakan untuk pengujian memiliki tabel:

- radcheck
- radreply
- radacct
- radpostauth
- radgroupcheck
- radgroupreply
- radusergroup
- nas
- nasreload
```

## Authentication

```text
User pengujian:
```

```bash
Username : budi
Attribute: Cleartext-Password
Operator : :=
Password : 123456
```

```text
User tersebut berada di tabel radcheck.
```

## SQL Driver

BaecKrad menggunakan:

```bash
rlm_sql
rlm_sql_postgresql
```

## Security

```text
Password database tidak boleh dimasukkan ke Git repository.
Credential development disimpan dalam konfigurasi lokal yang di-ignore Git.
EOF
```
