# Sistem Informasi Akademik
SIA is a school management software. It helps school staff to interact with students online.

To use the Docker, you can use this command:
```bash
# First time run
docker compose up --build

docker compose up # start the swarm
docker compose down # stop the swarm

# Init database with fakes.
docker compose run web rails db:reset_faker
```
