## Quick Cheatsheet

Collection of Personal Quick Cheatsheet


- [Regex](./REGEX.md)




<details>
<summary>Docker</summary><br> 

1. Stop & remove all containers, volumes, and images in Docker

```bash
docker stop $(docker ps -aq) 2>/dev/null; docker system prune -af --volumes
```

2. Build the image again and recreate the service in a single command using the specified Docker Compose file:
```
docker compose -f docker-compose-staging.yml up -d --build --force-recreate nixopus-staging-api
```

3. Restart the container
```
docker compose -f docker-compose-staging.yml up -d --force-recreate service
```



</details>
