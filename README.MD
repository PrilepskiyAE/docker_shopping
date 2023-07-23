docker-compose file for shopping backend
service
 1) web spring
   1.1) Spring Reactive Web
   1.2) Spring Data Reactive MongoDB
 2) mongodp

COMMAND START SERVICE 
docker-compose up -d
COMMAND CONNECT SERVICE
docker exec -it [container_id] mongosh
