# php-nginx server with mysql
Contains a virtual environment for php + mysql

* Made possible by thilinaperera/nginx-php-server image
* Instructions
Make sure you got docker and docker-compose intalled in your device
* Can host multiple php sites parallel

1) Clone the repository
2) Open terminal from project root and execute docker-compose up
3) Create directory in www with the name of your site (your.site.com)
4) Create a respective conf file ion conf directory (with name your.site.com.conf)
5) Place your php project inside the directory you created in www
6) Make sure you add your domain in /etc/hosts (127.0.0.1  your.site.com)


