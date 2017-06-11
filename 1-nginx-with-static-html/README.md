# Description

Create a simple nginx server with a static site (index.html).

# Create image 

docker build -t webserver-image:v1 .

# Run image

docker run -d -p 80:80 --name web1 --rm webserver-image:v1

-d : run as a daemin
-p : port mapping
--name : (optional) name the created container
--rm : do not "store" the conatainer

curl -i http://localhost

# Cleanup

docker stop web1

docker rmi webserver-image:v1

