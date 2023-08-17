# NextCloud-DockerCompose

# Init
Create `.env` file. 

```ini
# MYSQL/MariaDB
MYSQL_ROOT_PASS=root_password
MYSQL_PASS=password
MYSQL_USERNAME=nextcloud

# REDIS
REDIS_PASS=redis_password

# NEXTCLOUD
TRUSTED_DOMAINS=nextcloud.example.com
PHONE_REGION=JP
## MAIL (optional)
SMTP_HOST=smtp.example.com
SMTP_PORT=587
SMTP_NAME=smtp_username
SMTP_PASSWORD=smtp_password
MAIL_FROM_ADDRESS=nextcloud
MAIL_DOMAIN=example.com  # ex: [MAIL_FROM_ADDRESS]@[MAIL_DOMAIN]
## Reverse Proxy override (optional)
# OVERWRITE_HOST=nextcloud.example.com
# OVERWRITE_PROTOCOL=https # https or http
```

# Run
```bash
docker compose up
```
