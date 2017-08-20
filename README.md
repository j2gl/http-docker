# README

# Apache Docker 

## Build Image

```sh
$ docker build -t web-server:1.0 .
```

## Run image
```
docker run -dit --name my-web-server \
--volume "$PWD"/public-html:/usr/local/apache2/htdocs \
-p 2080:80 httpd:2.4 
 ```

# References 

https://hub.docker.com/_/httpd/