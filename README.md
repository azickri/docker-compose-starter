How To:

1. Clone Repository

```bash
git clone https://github.com/azickri/docker-compose-starter.git
```

2. Running

```bash
docker compose up -d

or

docker-compose up -d
```

Include:

- RabbitMQ
- Mongo & MongoExpress
- Redis
- PostgreSQL
- MySQL

---

For MySQL

1. After Running

```bash
docker exec -it docker-compose-starter-mysql-1 mysql -u root -p
```

2. Create User

```bash
CREATE USER 'user'@'172.18.0.1' IDENTIFIED BY 'password';
```

3. Check Grants

```bash
SHOW GRANTS FOR 'user'@'172.18.0.1';
```
