# 08-ansible-02-playbook

![image](https://github.com/user-attachments/assets/4d4b0ac5-4de1-457f-96bd-d0e86311fb71)

Плейбук переделал для Ubuntu
![image](https://github.com/user-attachments/assets/0565022a-7a05-4750-a39f-597122e70eb6)

Добавил установку vector 0.39.0-1
![image](https://github.com/user-attachments/assets/4ccd65c3-602c-4fee-9147-32cefe172bf6)

На целевой машине 
![image](https://github.com/user-attachments/assets/a344a43c-f243-4997-8b4d-383222657cdc)

Запуск ansible-lint site.yml
![image](https://github.com/user-attachments/assets/dc4a7ac4-3273-49da-b5e7-a76e99bd8785)

Установка с ключем --diff
![image](https://github.com/user-attachments/assets/8f453c54-769b-47ee-8c3a-af7482e2c24f)
![image](https://github.com/user-attachments/assets/fdedf586-d979-45c1-8351-9c96322dc732)
Повторный запуск с ключем --diff
![image](https://github.com/user-attachments/assets/fa2d27cc-388b-4b6f-9b30-b1a0d6b33eff)

В плейбуке используются модули:
ansible.builtin.get_url - получение адреса
ansible.builtin.apt - менеджер пакетов apt
ansible.builtin.command - выполнение команды на удаленной машине
ansible.builtin.service - модуль работы с сервисами
