# Template for deploy [Botpress](https://botpress.com) :robot: with docker and nginx

## Steps to deploy

1. Clone this repository
2. Copy .env.example to .env
3. Set up your credentials at .env
4. Run `docker-compose up` or `docker-compose up -d` for daemon

## Some considerations

This project contains:

- BotPress
- Postgres
- Redis
- Nginx

**Important**:

If you want run BotPress in **production mode**, please consider to use external **Redis** and **Postgres**.
