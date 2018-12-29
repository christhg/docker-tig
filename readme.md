# TIG Stack
>official web site
* telegraf-使用宿主機
* influxdb-使用docker
* garafana-使用docker
# Docker How to
   - [root@tigsrv]# cd docker-tig
   - [root@tigsrv docker-tig]# docker-compose up -d
# Telegraf How to
1. install telegraf
   * [root@tigsrv docker-tig]# wget https://dl.influxdata.com/telegraf/releases/telegraf-1.6.3-1.x86_64.rpm
   * [root@tigsrv docker-tig]# sudo yum localinstall telegraf-1.6.3-1.x86_64.rpm
2. configuration
   * [root@tigsrv docker-tig]# vi /etc/telegraf/telegraf.conf
3. restart telegraf
   * [root@tigsrv docker-tig]# systemctl restart telegraf
   * [root@tigsrv docker-tig]# systemctl status telegraf
