>######1. 安装nginx
`sudo apt-get install nginx`
>#####2. 安装php wget http://php.address
    1. tar -xvzf php.tar.gz
    2. 进入解压后文件夹 ./configure --prefix=/usr/local/php/bin
    3. sudo make ; sudo make install
>#####3. 修改   

 1. `/usr/local/php/etc/php-fpm.conf.*** 为 php-fpm.conf `
 2. `./php/etc/php-fpm.d/www.conf.default 改为 www.conf`
 3. `将php_nginx.conf 放入 /etc/nginx/conf.d中`
>####4. 将php加入环境变量
>####5. 执行 php/sbin/php-gpm
>####6. 打开localhost:8080`
    
    
    
  