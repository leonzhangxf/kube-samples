mysql ha 
===========

## test

kubectl run mysql-client --image=mysql:5.7 -it --rm --restart=Never -- mysql -h mysql-0.mysql.mysql
