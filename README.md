# Upload PF

ENVUploadPF - содержит в себе виртуальную среду с необходимыми пакетами, они описанны в файле uploadpf/requirements.txt
uloadpf - это само приложение, запускаеться как обычно сначала виртуальную среду, потом запускаем команду runserver

1 шаг
$ cd ENVUploadPF/bin/

$ activate

2 шаг
(ENVUploadPF) $ cd /uploadpf

(ENVUploadPF) $ python manage.py runserver

Сервер запускаеться на http://127.0.0.1:8000/

Вход в админку http://127.0.0.1:8000/admin
