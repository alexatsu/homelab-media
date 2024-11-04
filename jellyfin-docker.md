```
docker run --name jellyfin \
 --user 1000:1000 \
 --volume /config:/config \
 --net=host \
 --volume /cache:/cache \
 --mount type=bind,source=/home/alex/Downloads,target=/media \
 --restart=unless-stopped \
 jellyfin/jellyfin
 ```

 /home/alex/Downloads

 ## to start
 ```
 docker restart jellyfin
 ```
