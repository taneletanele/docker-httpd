# docker-httpd

docker build -t my-apache2 . && 
docker run --name my-app -p 80:80 my-apache2

In httpd.conf file change domain in the end, ServerName!
Add same domain to Windows Hosts file!
Expects locally running apps on ports 3000 and 8080.
