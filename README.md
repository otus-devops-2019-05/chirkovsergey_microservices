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


# Выполнено ДЗ № 15

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Установили в контейнере Gitlab
 
 - Пункт 2
   Добавили Runner 
 
 - Пункт 3
   Описали окружение и этапы пайплайна 
  
## Как запустить проект:

 -  Добавляем несколько веток в репозиторий и смотрим выпонение пайплайна.

## Как проверить работоспособность:
 - для каждой ветки отличной от masrter должен создаться отдельное окружение, деплой сред stage & prod доступен только при использовании тега.  

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания


# Выполнено ДЗ № 16

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Запустили Prometheus в контейнере
 - Пункт 2
   настроили node экспортер на сбор метрик
  - Пункт 2
   залили образы в docker hub, лежат тут: https://cloud.docker.com/u/student91/


## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с номером домашнего задания

# Выполнено ДЗ № 17

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:

 - Пункт 1
   Мониторинг контейнеров

 - Пункт 2
   Сбор и визуализациция метрик 

 - Пункт 3
   Алертинг: настройка, проверка.
## В процессе работы добавили сл компоненты:

 -  cAdvisor используется для мониторинга контейнеров

 - Grafana используется для визуализации метрик. 
 
 - Alertmanager используется для уведомлений о сбоях 

## Как проверить работоспособность:
 - URL к проектам https://cloud.docker.com/u/student91/repository/list

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания



# Выполнено ДЗ №18

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Сбор структурированных логов
 
 - Пункт 2
   Сбор неструктурированных логов (парсинг неструктурированных логов)
 
 - Пункт 3
   Визуализация логов (Kibana)
 
 - Пункт 4
   Трасировка
## Как запустить проект:
 - Перед стартом контейнера с  elasticsearch необходимо изменить значение: vm.max_map_count путь к файлу: /etc/sysctl.conf 
   либо выполнив sysctl -w vm.max_map_count=262144


## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания

# Выполнено ДЗ №19

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Запуск и удаление  кластера kubernetus

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания

# Выполнено ДЗ №20

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Развернули kubernetes  в локальном окружении и в нем же запустили приложение
 - Пункт 2
   Развернули кластер в GCE и так же запустили приложение.
## Как запустить проект:
   Запускать миникуб minikube start --vm-driver kvm2

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания


# Выполнено ДЗ №21

 - [x] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:
 - Пункт 1
   Посмотрели балансировки: LoadBalancer && Ingress
 - Пункт 2
   Network Policies 
 - Пункт 3
   Работа с хранилищем (PersistentVolumes, )
## Как запустить проект:
 - * Включим network-policy для GKE - не хотел включаться пока в параметрах не указал проект.

## PR checklist
 - [x] Выставил label с номером домашнего задания
 - [x] Выставил label с темой домашнего задания

