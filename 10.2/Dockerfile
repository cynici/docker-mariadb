FROM mariadb:10.2
LABEL maintainer "Cheewai Lai <cheewai.lai@gmail.com>"
COPY set-mysql-uid.sh /usr/local/bin/set-mysql-uid.sh
ENTRYPOINT ["/usr/local/bin/set-mysql-uid.sh"]
