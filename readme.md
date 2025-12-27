# Задание 1: Базовое подключение

1. Создаю dockerfile.managed в нём будет ssh, на который ansible будет подключатся 

![alt text](1.png)

2. Создаю dockerfile.controller в котором работает ansible, который выполняет playbooks. где будут команды ansible,ansible-playbook 

![alt text](2.png)

3. Создаю docker-compose.yml

![alt text](3.png)

4. Запускаю контенер

![alt text](4.png)

5. Захожу в ansible

![alt text](5.png)

6. Создаю inventory.ini

![alt text](6.png)

7. Генерирую ключ 

![alt text](7.png)

8. копирую публичный ключ в управляемый контенер и приватный

![alt text](8.png)

9. запускаю ключ от хоста

![alt text](9.png)

10. проверяю проверку подключения из нутри контенера

![alt text](10.png)

# Задание 2: Базовые ad-hoc команды

11. выполняем все команды по методичке, (зная что 4 команда работать не будет, поэтому только попытка)

![alt text](11.png)

# Задание 3: Работа с файлами

12. Создадим новый playbook

![alt text](12.png)

13. Запустим playbook

![alt text](12.2.png)

14. Создайте новый playbook task3_files.yml

![alt text](13.png)

15. Запустим playbook. Ожидаемый результат: три директории с файлами, созданные на управляемом хосте

![alt text](14.png)