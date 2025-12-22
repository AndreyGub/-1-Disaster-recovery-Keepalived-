# -1-Disaster-recovery-Keepalived-
#Задание 1
<img width="1300" height="639" alt="image" src="https://github.com/user-attachments/assets/7cde93e3-a1d8-4455-817c-f13147cef07c" />
1. Настраиваем роутеры для отслеживания состояния интерфейсов Gi0/0 (для первой группы)
   Router1 и Router2:
 configure terminal
interface GigabitEthernet0/0
standby 1 track GigabitEthernet0/0
exit
write memory

<img width="707" height="380" alt="image" src="https://github.com/user-attachments/assets/73a7b42a-218a-4246-a576-2a5d9c92df9f" />


<img width="1242" height="548" alt="image" src="https://github.com/user-attachments/assets/50b62b0a-7143-4265-86b0-54004aefd12a" />



#Задание 2

План выполнения:

1. Установка и настройка веб-сервера (nginx) на двух виртуальных машинах.

2. Создание Bash-скрипта для проверки порта и файла index.html.

3. Настройка Keepalived с использованием vrrp_script.

4. Тестирование переезда VIP при недоступности сервиса.

Ответ:

1. <img width="492" height="89" alt="image" src="https://github.com/user-attachments/assets/938ac0fd-70e6-4af7-b715-97fbf47f18f4" />
2. Создаем файл /usr/local/bin/check_web.sh
  <img width="627" height="255" alt="image" src="https://github.com/user-attachments/assets/253d985b-5e6b-49c3-9fdf-c21f0319a1fe" />


3. Виртуальная №1 <img width="694" height="442" alt="image" src="https://github.com/user-attachments/assets/282a987e-659a-48c5-a197-2ab369826171" />

   Виртуальная №2  <img width="777" height="381" alt="image" src="https://github.com/user-attachments/assets/5a9f2f76-dca0-4943-9eaf-ea6f0646d8e5" />

4. 
