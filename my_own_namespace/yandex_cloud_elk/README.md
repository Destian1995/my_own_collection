# Ansible Collection - my_own_namespace.yandex_cloud_elk

* namespace: my_own_namespace
* name: yandex_cloud_elk
* version: 1.0.0
* readme: README.md
* authors: Vladislav Chernyak <lerdonia@mail.ru>
* description: This is a test role for ansible-collection
* repository: https://github.com/Destian1995/my_own_collection

О роли:

My_role
=========

Роль для тестирования коллекций ansible

Requirements
------------

Тестирование осуществлялось на Centos7
Может поддерживаться в большинстве unix-подобных системах

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| test_path | "/tmp/test_remote_01.txt" | Параметр, определяющий путь для нового файла, а также имя нового файла |
| test_content | "Test module in task\nHello, netology!\n" | Строка, которая записывается в новый файл |


Example Playbook
----------------

---
- name: Test my_own_module in yandex.cloud
  hosts:
    - ubuntu-ansible
  roles:
    - my_role


