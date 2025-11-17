# x96

```bash
docker-compose run --rm certbot certonly \
  --webroot \
  -w /var/www/certbot \
  -d $DOMAIN \
  --email "$CERTBOT_EMAIL" \
  --agree-tos \
  --non-interactive
```

```bash
docker exec -it gitlab-runner bash
```

```bash
gitlab-runner register
```
