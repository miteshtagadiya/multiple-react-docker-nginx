# multiple-react-docker-nginx
Multiple React apps created by CRA in single port through docker containers and nginx.
- Serve multiple react apps in same host but different routes.
### Start Docker

```
docker-compose up -d
```

### Stop Docker
```
docker-compose down
```

- Main app: http://localhost:3000
- Client app: http://localhost:3000/client
- Admin app: http://localhost:3000/admin
