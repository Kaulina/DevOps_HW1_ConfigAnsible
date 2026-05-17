# Домашнее задание к занятию 3 «Использование Ansible»
создала структуру проекта
![1](screnshots//1.2.tree.png)

создала ligthouse и проверила что playbook рабочий

![1](screnshots/1.3.лайтхаусконфиг.png)

![1](screnshots/1.4.png)

далее создала prod.yml, и проверила ping всех 3х ВМ

![1](screnshots/1.5.connect.png)

lfktt cltkfkf play для ligthouse, шаблон для nginx, проверила ansible-lint и запустила в режиме --check. Чтобы посмотреть какие изменения будут внесены. 

![1](screnshots/1.6.1.check1.png)

![1](screnshots/1.6.1.check2.png)

первый запуск с --diff

![1](screnshots/1.6.вшаа1.png)

и проверка идемпотентности: второй запуск с той же командой --diff. Где видно, что изменений=0.

![1](screnshots/1.7.diff2.png)

проверка ligthouse:

![1](screnshots/1.8.site.png)