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

Чтобы исправить ошибку, связанную с файлом /docker/openssl/create.sh небходимо через notepad++ преобразовать символы окончания строки в юниксовские
```Open file create.sh > Edit > EOL Conversion > Unix (LF)```




Более подробная информация и фиксы других возможных ошибок в [исходом репозитории.](https://github.com/RobinLinus/snapdrop)
