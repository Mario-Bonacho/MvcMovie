code for the container:

sudo docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=YourStrong@Passw0rd" \
   -p 1434:1433 --name sql_MvcMovie -d \
   mcr.microsoft.com/mssql/server:2019-latest