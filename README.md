# Product Microservice

## Dev
1. Clone repository
2. Install dependencies
3. Create file `.env` base on `env.template`
4. Exceute prisma migration `npx prisma migrate dev`
5. Start nats server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Execute `npm run start:dev`