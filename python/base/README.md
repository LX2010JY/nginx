>步骤
1. 安装python virtuallenv，在项目文件夹中生成一个虚拟环境的文件夹venu，并且安装各种依赖的库
2. 安装uwsgi `pip install uwsgi`
3. 将配置文件放到指定文件夹里面
4. 重启nginx `sudo service nginx restart`
5. 开启uwsgi `uwsgi --ini /var/www/etc/blog_uwsgi.ini`