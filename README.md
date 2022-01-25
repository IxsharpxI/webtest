
## testing dockerized websites
This repo is designed to build a docker image based on nginx:alpine to expose web content in /usr/share/nginx/html on port 80. 

##Website Content
The Dockerfile actions automatically takes the files in the Template folder and copies them into /usr/share/nginx/html and the GitHub Actions builds the image out to docker hub. 

To host your own content, simply add your html files in the template folder as you normally would in /user/share/nginx/html.

##Nginx Conf
Included is configuration of the nginx.conf file in the Conf folder. This too gets automatically added into the docker image.

content and conf folders must be organized accordingly unless you modify the dockerfile to the correct locations.
