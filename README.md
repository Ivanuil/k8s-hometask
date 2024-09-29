
## Minikube status

![alt text](image.png)

## Configmap

![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

## Cronjob

![alt text](image-5.png)
=> Меняем `apiVersion: batch/v1beta1` на `apiVersion: batch/v1`
![alt text](image-6.png)
Ждем минуту
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)

## Daemonset

![alt text](image-11.png)

## Deployment

![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)
Версия контейнера выделена
![alt text](image-15.png)

## Job

![alt text](image-17.png)
![alt text](image-20.png)

### backoffLimit

![alt text](image-21.png)
![alt text](image-22.png)
![alt text](image-23.png)

### activeDeadlineSeconds

![alt text](image-25.png)
![alt text](image-26.png)
Ждем 100 секунд
![alt text](image-27.png)

## Pod

![alt text](image-28.png)
![alt text](image-29.png)
![alt text](image-30.png)
![alt text](image-32.png)
![alt text](image-31.png)
![alt text](image-33.png)
![alt text](image-34.png)

## ReplicaSet

![alt text](image-35.png)

### Скейлим

![alt text](image-36.png)

### Удаляем один из Pod

![alt text](image-37.png)

### Добавляем лишний Pod

![alt text](image-38.png)
![alt text](image-39.png)

### Обновляем версию Image для container

![alt text](image-40.png)
![alt text](image-41.png)
![alt text](image-42.png)
![alt text](image-43.png)

## Secret

![alt text](image-44.png)
![alt text](image-45.png)
![alt text](image-46.png)

## Service

Возвращаемся на шаг Secret и повторяем все шаги (но ничего не удаляем в конце :)
![alt text](image-49.png)
![alt text](image-50.png)
![alt text](image-51.png)
![alt text](image-52.png)
