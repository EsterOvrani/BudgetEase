FROM mysql:latest

# Setting environment variables
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=BudgetEase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword

# Copy the init.sql file into the MySQL startup folder, where it will run automatically at boot time
COPY ./init.sql /docker-entrypoint-initdb.d/

# mysql port
EXPOSE 3306
