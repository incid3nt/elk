# Домашнее задание к занятию «ELK» - Еноктаев Олег


### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

---


### Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

### Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

#### Задание 1.
![Elasticsearch](img/photo_2025-06-21_19-47-14.jpg)
#### Задание 2.
![Elasticsearch1](img/photo_2025-06-21_19-56-53.jpg)
#### Задание 3.
![Elasticsearch1](img/photo_2025-06-21_20-28-09.jpg)
#### Задание 4.
![Elasticsearch1](img/photo_2025-06-21_21-38-41.jpg)