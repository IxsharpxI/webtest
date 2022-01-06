
# testing dockerized websites
This repo is designed to build a docker image based on nginx:alpine to expose web content in /usr/share/nginx/html on port 80. 

The Dockerfile actions automatically takes the files in the Content folder and copies them into /usr/share/nginx/html and the GitHub Actions builds the image out to docker hub. 

#Nginx Conf
Included is configuration of the nginx.conf file in the conf folder. This too gets automatically added into the docker image.

content and conf folders must be organized accordingly unless you modify the dockerfile to the correct locations.
