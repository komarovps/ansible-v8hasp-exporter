# ansible-v8hasp-exporter
v8hasp-exporter ansible playbook

## Требования
* Модуль [win_git](https://github.com/Lagyu/ansible-win_git) для Ansible
Скопировать файлы `win_git.ps1` и `win_git.py` в [каталог модулей](http://docs.ansible.com/ansible/latest/reference_appendices/config.html#default-module-path)

## Запуск
```
ansible-playbook playbook.yml
```

## Заметки
Используется `osweb` из ветки `develop`. Из ветки `master` запуск падает с ошибкой `Unknown database type in configuration`