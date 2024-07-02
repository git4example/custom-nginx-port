# custom-nginx-port

Here we are exposing nginx image to port 8080. You can choose your own port.

```
docker build -t my-nginx . 
docker run -d -p 8080:8080 my-nginx
curl localhost:8080
```
