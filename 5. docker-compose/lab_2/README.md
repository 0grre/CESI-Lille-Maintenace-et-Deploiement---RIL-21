# Lab 2

With this docker compose we can show that:

- we can use official images and custom built images (see www4)
- we can see that every container can use the DNS resolution to communicate between them
- even if a port inside a container is not exposed on the host machine, an other container can "curl" it (eg in www1: `curl http://www4/` )
