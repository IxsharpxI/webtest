
# testing dockerized websites
This repo is designed to build a docker image based on nginx:alpine to expose web content in /var/nginx/html on port 80. 

The GitHub actions automatically takes the files in the Content folder and copies them into the html location and builds the image out to docker hub. 
