#Ansible Collection - my_own_namespace.yandex_cloud_elk

* namespace: my_own_namespace
* name: yandex_cloud_elk
* version: 1.0.0
* readme: README.md 
* authors: Kirill Karagodin karagodin.kirill.a@ya.ru
    description: This is a test role for ansible-collection
    repository: https://github.com/kirill-karagodin/my_own_collection

##О роли:

###My_role

Роль для тестирования коллекций ansible
Задача: запись на удаленный хост файла с заданным содержанием

###Requirements

Тестирование проводилось на OS CentOS 7

Тестирование осуществлялось на ubuntu 20.04 
Вероятно, поддерживаться будет в большинстве unix-подобных системах (но это не точно)

###Role Variables

| Variable name | Default | Description                                                                                                          |
|-----------------------|---------|----------------------------------------------------------------------------------------------------------------------|
| test_path | "/tmp/test1.txt" | Параметр, определяющий путь для нового файла, а также имя нового файла (при желании можно заменить на свое значение) |
| test_content | "Hello, my freind!\n" | Строка, которая записывается в новый файл (при желании можно заменить на свое значение)                                                                           |