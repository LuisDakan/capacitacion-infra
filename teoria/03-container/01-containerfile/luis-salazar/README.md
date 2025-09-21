```
docker volume create
docker run -d -p 80:80 -v conf:/etc/nginx -v static:/var/www/html
```