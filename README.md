## Simple web app for demonstrating docker-compose purpose

Includs services:
- databse: postgres
- webapp: react
- cache: redis
- worker: node app for computing-heavy jobs
- nginx in front of every services

default.conf 专门为nginx用的

docker-compose up