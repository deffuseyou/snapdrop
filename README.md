# Snapdrop 

Форк, переведенный на русский язык и адаптированный по именам пользователей для детского лагеря.

## Установка

Для начала, [установи docker вместе с docker-compose.](https://docs.docker.com/compose/install/)

Клонируй репозиторий:
```
git clone https://github.com/deffuseyou/snapdrop.git
cd snapdrop
docker-compose up -d
```
## Дополнительная настройка на Windows

Чтобы исправить ошибку, связанную с файлом ```/docker/openssl/create.sh``` небходимо в этом файле преобразовать символы окончания строки в юниксовские (из CR LF в LF).

Это можно сделать через notepad++
```Edit > EOL Conversion > Unix (LF)```

## Дополнительная настройка на Linux

Исправить ошибку, связанную с npm
```
sudo chown -R $USER ./server
sudo chmod -R 777 ./server
```
