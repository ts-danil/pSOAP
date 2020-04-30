# Лабораторная работа №2.  
# Исследование сетевых параметров публичных DNS серверов
## Цель работы:  
Проанализировать сетевые параметры публичных DNS серверов, сделать мотивированный вывод о предпочтительных серверах.  
### Исследуемые провайдеры DNS:  
  1. Google Public DNS
  2. Cloudflare DNS
  3. OpenDNS
  4. DNS провайдера
## Исходные данные:  
### Конфигурация аппаратного обеспечения и общесистемного ПО:  
Процессор: 4 × Intel® Core™ i5-3230M CPU @ 2.60GHz  
Память: 7,89 Гб ОЗУ  
ОС: Windows 10 x64   

### Используемое ПО:  
+ Google Chrome 81.0.4044.122  
+ Rstudio IDE 

### Используемые команды для командной строки:  
+ ping
+ tracert

### Используемые интернет-ресурсы: 
+ Whois

## Варианты решения задачи:  
1. Выполнение работы с ипользованием командной строки и интернет ресурсов  
В данной работе используется первый и единственный вариант решения задачи. 
## Общий план выполнения:  
  1. По исследуемым серверам собрать следующие данные:  
    1) Маршрут  
    2) Местоположение каждого узла маршрута к DNS-серверу  
    3) Организацию, владеющую каждым узлом маршрута к DNS-серверу  
    4) Среднюю RTT (round trip time) к DNS-серверу  
  2. Выделить те узлы маршрута, которые вносят наибольшую временную задержку при передаче
  3. Сравнить сетевые параметры DNS серверов