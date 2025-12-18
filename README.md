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



