LNPM：
====
本软件是基于张宴nginx_php_v7（http://blog.s135.com/nginx_php_v7/）改进而来，是一个用Linux Shell编写的可以为CentOS/RadHat、Debian/Ubuntu VPS(VDS)或独立主机安装LNMP(Nginx、MySQL、PHP、phpMyAdmin)生产环境的Shell程序。

Nginx支持：
====
ngx_cache_purge缓存机制

PHP环境支持：
====
php多线程
oci8
memcache

软件包如下：
====
  autoconf-latest.tar.gz
  freetype-2.4.12.tar.gz
  install.sh
  jpegsrc.v9.tar.gz
  libmcrypt-2.5.8.tar.gz
  libpng-1.6.2.tar.gz
  mcrypt-2.6.8.tar.gz
  memcache-2.2.7.tgz
  mhash-0.9.9.9.tar.gz
  mysql-5.6.10-linux-glibc2.5-x86_64.tar.gz
  nginx-1.5.2.tar.gz
  ngx_cache_purge-2.1.tar.gz
  oci8-2.0.8.tgz
  oracle-instantclient11.1-basic-11.1.0.7.0-1.x86_64.rpm
  oracle-instantclient11.1-devel-11.1.0.7.0-1.x86_64.rpm
  oracle-instantclient11.1-sqlplus-11.1.0.7.0-1.x86_64.rpm
  pcre-8.32.tar.gz
  php-5.5.9.tar.gz
  pthreads.tar.gz
  README


主要软件安装目录：
====
  /usr/local/webserver

默认虚拟主机使用的目录：
====
  /data/wwwroot/localhost

Nginx虚拟主机配置及日志存放目录：
====
  /data/nginx/vhosts
  /data/nginx/logs

MySQL数据日志相关存放目录：
====
  /data/mysql/3306/data/
  /data/mysql/3306/binlog/
  /data/mysql/3306/relaylog/

MySQL root用户初始密码：159357
====

相关服务启动控制脚本：
====
  /data/mysql/3306/mysql {start|stop|restart|kill}
  /usr/local/webserver/php/sbin/php-fpm.sh {start|stop|restart|show}
  /usr/local/webserver/nginx/sbin/nginx


  By Zmor（lure21@gmail.com）
  2014-03-19
