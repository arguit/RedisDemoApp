# RedisDemoApp

[Intro to Redis in C# - Caching Made Easy](https://www.youtube.com/watch?v=UrQWii_kfIE)

- .NET Core 3.1
- Blazer Server App
- Redis (Caching)
- Docker (Redis Image)

## Run Redis docker image

```powershell
docker run --name my-redis -p 5002:6379 -d redis
```

## Show running docker images

```powershell
docker ps -a
```

## Execute Redis shell

```powershell
docker exec -it my-redis sh
```

## Stop Redis docker image

```powershell
docker stop <id>
docker rm <id>
```

## Remove Redis docker image

```powershell
docker rmi <id>
```
