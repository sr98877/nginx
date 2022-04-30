from nginx:latest
add sr.com /usr/share/nginx/
copy ./sr.com/main.html /usr/share/nginx/sr.com/
copy ./conf/sr.com.conf /etc/nginx/conf.d/sr.com.conf
expose 81
run ls -al /etc/nginx/conf.d/
run ls -al /usr/share/nginx/

