FROM centos:7

RUN sed -i 's/mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-*
RUN sed -i 's|#baseurl=http://mirror.centos.org|baseurl=http://vault.centos.org|g' /etc/yum.repos.d/CentOS-*
RUN yum -y install httpd
RUN yum -y install https://rpms.remirepo.net/enterprise/remi-release-7.rpm
RUN yum -y install yum-utils
RUN yum-config-manager --disable remi-php54
RUN yum-config-manager --enable remi-php74
RUN yum -y install php74
RUN yum -y install php74-php php-cli php74-scldevel php74-php-xml php74-php-xmlrpc php74-php-soap php74-php-process php74-php-pgsql php74-php-pdo php74-php-opcache php74-php-mbstring php74-php-ldap php74-php-json php74-php-ioncube-loader php74-php-intl php74-php-gmp php74-php-gd php74-php-fpm php74-php-devel php74-php-dba php74-php-common php74-php-cli php74-php-bcmath php74-php-phpiredis  php74-php-pecl-igbinary php74-php-pecl-imagick-im7 php74-php-pecl-imagick-im7-devel php74-php-pecl-igbinary-devel php74-php-pecl-geoip php74-php-pecl-xdebug php74-php-pecl-mysqlnd-azure
RUN yum -y install wget
RUN wget https://wordpress.org/latest.tar.gz
RUN tar -xvzf latest.tar.gz -C /var/www/html
RUN chmod -R a+x /var/www/html
RUN chown -R apache:apache /var/www/html/wordpress

CMD ["httpd","-D","FOREGROUND"]

EXPOSE 80/tcp

WORKDIR /var/www/html/

