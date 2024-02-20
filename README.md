# Docker + MongoDB

* *เพิ่ม .env หรือแก้ไข docker-compose.yml*

* ตัวอย่าง .env

```
DB_LIVE_CONTAINER_NAME=live
DB_LIVE_PORT=27017
DB_LIVE_NAME=admin
DB_LIVE_PASSWORD=admin
DB_LIVE_VOLUMES=database
```

* แล้วใช้คำสั่ง

```
docker compose up -d --build
```

เพื่อสร้าง project ได้เลย