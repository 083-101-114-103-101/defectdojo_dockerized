# defectdojo_dockerized

cd defectdojo_dockerized

docker compose up -d

Username: admin
Get password
docker compose logs initializer | grep -i "Admin password"
