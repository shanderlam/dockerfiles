FROM       ubuntu:12.04
MAINTAINER Shander Lam <shanderlam@gmail.com>

RUN apt-get update && apt-get install -qy php5-fpm
RUN sed -i -e"s/^;\s*daemonize\s*=\s*yes/daemonize = no/" /etc/php5/fpm/php-fpm.conf

CMD ["php5-fpm"]
