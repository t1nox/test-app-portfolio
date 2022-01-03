RUN this project

git clone https://github.com/t1nox/my-portfolio-test.git

sudo docker run -d -p 8080:80 --mount type=bind,source="$PWD",target=/var/www/html php:apache
