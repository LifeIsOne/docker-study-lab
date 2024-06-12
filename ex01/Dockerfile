FROM httpd:2.4

COPY ./www /usr/local/apache2/htdocs

# 80을 진짜로 방화벽으로 OPEN하는게 아니라, 80을이 열려있다고 표시
EXPOSE 80

CMD ["httpd-foreground"]