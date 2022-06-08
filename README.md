#### Ansible Playbook ([https://github.com/uralhouse/devops-netology-example-ansible-2/tree/main/playbook](https://github.com/uralhouse/devops-netology-example-ansible-2/tree/main/playbook))

##### Что делает playbook

Playbook производит установку следующих приложений:

- clickhouse-common-static (версия 22.3.3.44)

- clickhouse-client (версия 22.3.3.44)

- clickhouse-server (версия 22.3.3.44)
- vector (версия 0.22.0)

##### Параметры

Параметры playbook отражены в следующих файлах:

- playbook/inventory/prod.yml

  Настраиваются host-машины для запуска playbook

- playbook/group_vars/clickhouse/vars.yml

  Перечень устанавливаемых пакетов clickhouse и их версия.

##### Теги

Tag: 08-ansible-02-playbook установлен на репозиторий с данным playbook.



