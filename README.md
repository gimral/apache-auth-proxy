docker build -t apache-reverse-proxy .

docker build --build-arg AUTH_TYPE=file -t gimral/apache-auth-proxy:1.1 .