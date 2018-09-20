# Gitea+Mysql+Caddy by using Docker

## start

```
docker-compose up -d
```

## setting in gitea

connect to localhost:8880

![](https://i.imgur.com/epc48fO.png)

![](https://i.imgur.com/MG2n2Py.png)
## customize

change your port in docker-compose.yml

```
http:
    build:
     ...      
    ports:
      - "443:443" // change port here
      - "8880:80" // change port here
    ...
```
## refs

https://andrewzah.com/posts/selfhosting-git-with-gitea-docker-caddy/

https://docs.gitea.io/en-us/install-with-docker/

https://onlyhavecans.works/amy/gitea-docker


