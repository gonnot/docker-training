# Description

Create a simple nginx server with a static site (index.html). 
Expose port, and specify image command


# Create image 

```
docker build -t webserver-image:v1 .
```

# Run image

```
docker run -d -p 80:80 --name web1 --rm webserver-image:v1
```

```
curl http://localhost
```

# Cleanup

```
docker stop web1
docker rmi webserver-image:v1
```
