
We're following this tutorial: https://tech.osteel.me/posts/docker-for-local-web-development-part-1-a-basic-lemp-stack


## How to Use

Run your Docker commands in a Powershell terminal on Windows, or a terminal configured to use UTF-8 as the default encoding (Python doesn't like CP65001.)

Copy `.env.example` to `.env`:

```
$ cp .env.example .env
```

Run the following command:

```
$ docker-compose up -d
```

This may take a little bit of time, as some Docker images might need downloading.


## Useful Command Reference

- `docker-compose stop`: stop the running image.
- `docker-compose down -v`: destroy the images.
- `docker-compose exec php bash`: get into the php bash environment.
