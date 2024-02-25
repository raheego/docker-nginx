## study docker 
https://github.com/beyond-sw-camp/be01-101/issues/27

![image](https://github.com/raheego/docker-nginx/assets/54056684/72d175a6-cda7-434c-941f-337e60bc2795)

## Version
### v0.2.0
- [x] push my index.html docker hub

### dockerHub
- https://hub.docker.com/r/gohrahee/nginx-my-html

### v0.3.0
- fly deploy


## ref
```
https://hub.docker.com/_/nginx
https://nginx.org/
https://www.nginx.com/
```

## 도커 컨테이너 및 이미지 삭제
```
# 컨테이너 확인
$ sudo docker ps -a
$ sudo docker ps

# 컨테이너 삭제
$ sudo docker rm <name>

# 이미지 확인
$ sudo docker images

# 이미지 삭제
$ sudo docker rmi a8758716bb6a
$ sudo docker rmi hello-world
```

## 도커 명령어 - 커맨드 - 공식가이드
- https://docs.docker.com/engine/reference/run/

## 도커 컨테이너 RUN & 접속
```
$ sudo docker run --name some-nginx-1-p 9051:80 -v <경로>:/usr/share/nginx/html:ro -d nginx

$ sudo docker exec -it some-nginx-1 bash
```
