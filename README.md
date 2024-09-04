```
docker-compose up -d

docker cp nginx.conf docker-cp-test-nginx-1:/etc/nginx/nginx.conf
docker exec docker-cp-test-nginx-1 nginx -s reload
```