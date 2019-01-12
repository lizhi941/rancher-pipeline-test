FROM phpmyadmin/phpmyadmin:4.7

COPY lizhi-phpadmin.txt    /var

EXPOSE 80

ENTRYPOINT [ "/run.sh" ]

CMD ["supervisord", "-n", "-j", "/supervisord.pid"]

