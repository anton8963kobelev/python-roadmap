# Linux. Консольные команды. Docker
* Что такое Linux? Что такое дистрибутив? Почему back-разработчик должен знать Linux?
* Работа с файлами и директориями:
  * `pwd`
  * `ls` и `ls -l`
  * `cd`. В чем отличие абсолютного пути от относительного?
  * `mkdir`
  * `touch`
  * `cat`
  * `nano`
  * `cp` и `cp -r`
  * `mv`
  * `rm` и `rm -r`
  * `man ls`
* Что такое `sudo`? Что делают следующие команды (Ubuntu):
  * `sudo apt-get update`
  * `sudo apt-get install <>`
***
* Что такое образ в Docker? Что такое контейнер? Сколько контейнеров можно создать на основе одного образа?
* Что такое `Dockerfile`? Что такое базовый слой?
* Что такое DockerHub? Для чего он нужен?
* Что такое Docker compose? Что такое `volume`?
* Работа с Docker:
  * `docker build -t <имя> .`
  * `docker run --name <имя образа> -it -p 8000:8000 <имя контейнера>`
  * `docker image ls`
  * `docker rmi <имя образа>`
  * `docker container ls`
  * `docker start/stop/restart <имя контейнера>`
  * `docker stop <имя контейнера> && docker rm <имя контейнера>`
  * `docker rm <имя контейнера>` и `docker rm -v <имя контейнера>`
  * `docker image prune -a`
* Работа с Docker Compose:
  * `docker-compose build`
  * `docker-compose up`
  * `docker-compose down` и `docker-compose down -v`
  * `docker-compose ps`
  * `docker-compose exec <service name> <command>`
  * `docker-compose images`

### Ресурсы
* [Linux и дистрибутив Linux](https://blog.skillfactory.ru/glossary/linux/)
* [Основные linux-команды](https://habr.com/ru/post/501442/)
* [Администратор в Ubuntu (sudo)](https://help.ubuntu.ru/wiki/суперпользователь_в_ubuntu)
* [Установка программ в Ubuntu](https://help.ubuntu.ru/wiki/установка_программ)
* [Как устроен Docker](https://cloud.yandex.ru/blog/posts/2022/03/docker-containers)
* [Изучаем Docker. Dockerfile](https://habr.com/ru/company/ruvds/blog/439980/)
* [Основные инструкции Dockerfile](https://tproger.ru/translations/docker-instuction/)
* [Шпаргалка с командами Docker](https://habr.com/ru/company/flant/blog/336654/)
* [Руководство по Docker Compose](https://habr.com/ru/company/ruvds/blog/450312/)

