# using-mysql-in-cmd
Commands for using mysql in cmd

## connect to your sql from cmd using the codes below! and enter your codes!
mysql -u root -p;

## use the cmd below to create a new user  (% indicates all ip, meanwhile you can indicate user id you will love to give access to e.g 192.168.1.1)
create user 'username'@'%' identified by 'userpassword';

## grant user access to write, update, delete and lots more
grant all on *." to 'username'@'%';

## then, flush priviledges
flush privileges;

## you can preview required host and user here with the below command or query.
select host, user from mysql.user;

## Comments here if you encounter any error! Always happy to help!
