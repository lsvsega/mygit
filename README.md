# mygit
learning observability

На виртуальную машину были установлены:
- WordPress
- nginx
- php-fpm
- mysql
- prometheus
- prometheus exporter
- node exporter
- nginx exporter
- php-fpm exporter
- mysql exporter
- blackbox exporter
- alertmanager

В prometheus.yml настроен опрос экспортеров раз в 5 секунд

Настроена отправка оповещений с помощью alertmanager для warning на email, critical в telegram
Установлена victoriametric, настроен период хранения 1 месяц
