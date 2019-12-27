# DmitryErshov Platform repository

## Toolkit

- kubectl
- kind
- minikube
- Dashboard
- K9s
- Kube Forwarder

## kubernetes-intro

1. Разворачивание и тестирование кластера на базе kind
1. Разворачивание и тестирование кластера на базе minikube
1. Тестирование восстановления контейнеров и Pod'ов после удаления
1. Подготовка образа веб-сервера, удовлетворяющего тех.заданию
1. Создание Pod с веб-сервером
1. Добавление init-контейнера
1. Добавление в контейнер данных с помощью init-контейнера c использованием томов
1. Подготовка образа dmitryershov/microservices-demo:frontend
1. Создание Pod frontend
1. Диагностика и исправление ошибки запуска Pod frontend

## kubernetes-controllers

1. Добавление манифеста ReplicaSet
1. Увеличение количества реплик до 3
1. Изменение тега образа на v0.0.2. При применении обновления в ReplicaSet версия образа обновляется сразу,
в Pod'ах - нет, только после создания заново, т.к. ReplicaSet не проверяет соответствие запущенных Pod'ов шаблону.
1. Добавление манифеста ReplicaSet для paymentservice
1. Добавление манифеста Deployment для paymentservice
1. Изменение тега образа на v0.0.2-paymentservice в манифесте Deployment
1. Стратегия Blue-Green
