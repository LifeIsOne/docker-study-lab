# FROM ubuntu

# RUN apt-get update && apt-get install -y nginx

# CMD ["nginx","-g","daemon off;"]
FROM ubuntu
# 이거 없으면 환경변수 설정해야 됨.
WORKDIR /etc/init.d

RUN apt-get update && apt-get install -y nginx

CMD ["sh", "-c", "./nginx start && tail -f /dev/null"]