Install
-------

 sudo apt-get install libfcgi-dev
sudo apt-get install spawn-fcgi
sudo apt-get install nginx
sudo apt-get install curl



Running the service
-------------------

 sudo mv /etc/nginx/nginx.conf /etc/nginx/old_nginx.conf.bk
 
 sudo ln -s `pwd`/nginx.conf /etc/nginx/nginx.conf
 
 sudo /etc/init.d/nginx restart

 ./make
 
 ./start

 ('pwd'代表你代码代码文件的路径)
 (remove the -n switch from the start executable if you want it to run in the background)


Benchmarks/Testing
------------------

 curl http://localhost/


Code from this article
----------------------

 http://chriswu.me/blog/writing-hello-world-in-fcgi-with-c-plus-plus/
