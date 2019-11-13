## Project setup

1. Build & run docker images: `docker-compose up`
2. Create DBs: `docker-compose exec backend rake db:create`
3. Run migrations: `docker-compose exec backend rake db:migrate`

Frontend app will be available under `http://localhost:8080`.

Backend API under `http://localhost:3000`.