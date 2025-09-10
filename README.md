## Quick Cheatsheet

Collection of Personal Quick Cheatsheet


- [Regex](./REGEX.md)




<details>
<summary>Docker</summary><br> 

Stop & remove all containers, volumes, and images in Docker

```bash
docker stop $(docker ps -aq) 2>/dev/null; docker system prune -af --volumes
```

</details>
