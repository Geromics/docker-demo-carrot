## Start the project using Docker

```bash
docker run --rm -p 8081:80 \
   -v ${PWD}/site:/srv \
   -v caddy_data:/data \
   caddy caddy file-server
```
