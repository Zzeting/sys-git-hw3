# Домашнее задание к занятию "`ELK`" - `Мамонтов Александр`


### Задание 1. Elasticsearch


Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

Скриншот-1 к заданию 1:

![Скриншот-1](https://github.com/Zzeting/sys-git-hw3/blob/main/img/1.PNG)

Скриншот-2 к заданию 1:

![Скриншот-2](https://github.com/Zzeting/sys-git-hw3/blob/main/img/2.PNG)

### Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

Скриншот-3 к заданию 2:

![Скриншот-3](https://github.com/Zzeting/sys-git-hw3/blob/main/img/3.PNG)


### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

Скриншот-4 к заданию 3:

![Скриншот-4](https://github.com/Zzeting/sys-git-hw3/blob/main/img/4.PNG)


### Задание 4. Filebeat.

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

Скриншот-5 к заданию 4:

![Скриншот-5](https://github.com/Zzeting/sys-git-hw3/blob/main/img/5.PNG)

