# chirkovsergey_microservices
chirkovsergey microservices repository


# Выполнено ДЗ № 11

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:

 - Пункт 1
   Произвели установку docker и docker-machine
 - Пункт 2
   Создали новый проект в В GCP 
 - Пункт 3
   Создали контейнер с приложением в GCP 
 - Пункт 4
   Сделали образ контейнера и запушили его в https://hub.docker.com/ 
   ---
## Как запустить проект:
   для запуска необходимо:
   * собрать контейнер: docker build -t reddit:latest .
   * пушим/запускаем контейнер: docker run --name reddit -d --network=host reddit:latest
    
## Как проверить работоспособность:
   из вывода команды: docker-machine ls берем ip адрес контейнера, и из него формируем УРЛ вида: http://ip_addres:9292
  
## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания

 
# Выполнено ДЗ № 12

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Разобрали молит на 3 контейнера post-py, comment и ui
 - Пункт 2
   Подключили вольюм к контейнеру

## Как проверить работоспособность:
 - Перейти по УРЛ ip_vm:9292 написать пост, перезапустить конетейнеры и проверить что пост сохранился

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания


# Выполнено ДЗ №13

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   работали с сетями в Docker
 - Пункт 2
   использовали docker-compose
## Как запустить проект:
 - запуск осуществляется docker-compose up -d 

## Как проверить работоспособность:
 - для проверки необходимо перейти по урл: http://ip_addres_docker-machine_ip:9292

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания

