# Prisma Sample

## Start

```bash
$ docker-compose up -d
$ prisma deploy --env-file .env.dev
```

## Test

```bash
http://localhost:4466

wrk -c 100 -d 1s -s post.lua http://localhost:4466/
```
