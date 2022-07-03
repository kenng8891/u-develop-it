# u-develop-it

UPDATE mysql.user SET authentication_string = PASSWORD('root1234')
WHERE User = 'user-name' AND Host = 'localhost';
FLUSH PRIVILEGES;