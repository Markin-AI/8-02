# Домашнее задание к занятию "`Что такое DevOps. СI/СD`" - `Маркин Алексей`

---

### Задание 1

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 1

![Скриншот 1](https://github.com/Markin-AI/8-02/blob/main/img/1-1.png)

![Скриншот 2](https://github.com/Markin-AI/8-02/blob/main/img/1-2.png)

![Скриншот 3](https://github.com/Markin-AI/8-02/blob/main/img/1-3.png)

![Скриншот 4](https://github.com/Markin-AI/8-02/blob/main/img/1-4.png)

### Завершилось с ошибкой так как еще не поднят Nexsus

![Скриншот 5](https://github.com/Markin-AI/8-02/blob/main/img/1-5.png)

### Завершилось удачно, Nexsus активен

![Скриншот 6](https://github.com/Markin-AI/8-02/blob/main/img/1-6.png)

---

### Задание 2

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 2

![Скриншот 1](https://github.com/Markin-AI/8-02/blob/main/img/2-1.png)

![Скриншот 2](https://github.com/Markin-AI/8-02/blob/main/img/2-2.png)

![Скриншот 3](https://github.com/Markin-AI/8-02/blob/main/img/2-3.png)

### Завершилось с ошибкой так как еще не поднят Nexsus

![Скриншот 4](https://github.com/Markin-AI/8-02/blob/main/img/2-4.png)

### Завершилось удачно, Nexsus активен

![Скриншот 5](https://github.com/Markin-AI/8-02/blob/main/img/2-5.png)

---

### Задание 3

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 3

![Скриншот 1](https://github.com/Markin-AI/8-02/blob/main/img/3-1.png)
![Скриншот 2](https://github.com/Markin-AI/8-02/blob/main/img/3-2.png)
![Скриншот 3](https://github.com/Markin-AI/8-02/blob/main/img/3-3.png)


---
