FROM phpmyadmin/phpmyadmin:4.7

COPY /phpadmin/lizhi-phpadmin.txt    /var
EXPOSE 80
CMD ["supervisord", "-n", "-j", "/supervisord.pid"]

