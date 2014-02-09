installation

    apt-get install nginx
    cd /etc/nginx
    rm nginx.conf
    {{replace with our nginx.conf}}
    adduser --system --no-create-home --disabled-login --disabled-password --group nginx
    mkdir ~/logs
    {{start server or supervisord}}
    /etc/init.d/nginx start

configuration

    /etc/init.d/nginx reload or service nginx restart
    /etc/init.d/nginx start
