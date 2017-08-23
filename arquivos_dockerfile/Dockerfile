FROM mysql:5.7
RUN service mysql start && \
    mysql -u root -e "CREATE USER 'root'@'172.20.0.2' IDENTIFIED BY '';" && \
    mysql -u root -e "GRANT ALL PRIVILEGES ON *.* TO 'root'@'172.20.0.2';"
EXPOSE 3306
