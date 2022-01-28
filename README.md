
Steps to run this project:

1. Run `npm i` command
2. Setup database settings 

docker run --name eray-mysql -e MYSQL_ROOT_PASSWORD=test -e MYSQL_USER=test -e MYSQL_PASSWORD=test -e MYSQL_DATABASE=test -p 3306:3306 -d mysql:latest --default-authentication-plugin=mysql_native_password

3. Run `npm start` command
