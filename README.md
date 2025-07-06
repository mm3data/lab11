# Настройки протокола OSPFv2 для одной области  
## Топология  
![image](https://github.com/user-attachments/assets/88f6ee1d-8d41-427e-9f47-91c1fa50215a)  
## Таблица адресации  
Устройство | Интерфейс | IP-адрес | Маска подсети  
--- | ---  | ---- | ---- 
R1 | G0/0/1 | 10.53.0.1 | 255.255.255.0  
--- |Loopback1 | 172.16.1.1 | 255.255.255.0  
R2 | G0/0/1 | 10.53.0.2 | 255.255.255.0
---|  Loopback1 | 192.168.1.1 |255.255.255.0  
* Создание сети и настройка основных параметров устройства
* Настройка и проверка базовой работы протокола  OSPFv2 для одной области
* Оптимизация и проверка конфигурации OSPFv2 для одной области
 
**Базовая настройка маршрутизаторов**  
![image](https://github.com/user-attachments/assets/fb251518-0688-4fed-88d8-c98aaaa00c46)  
![image](https://github.com/user-attachments/assets/f756ef90-5c42-49e1-a51c-9e3b452073b1)  
**Настройка базовых параметров коммутаторов**  
![image](https://github.com/user-attachments/assets/6d79f9e2-de68-4393-a2ff-f08bfbbf1a58)  
![image](https://github.com/user-attachments/assets/1d16c288-10ee-4b8c-89d2-7e213d924a92)  

**Настройка фдреса интрефейса и базового OSPFv2 на маршрутизаторах**  
![image](https://github.com/user-attachments/assets/567a7e5c-8da4-4047-bf1b-0ddfbb3bfd68)  
![image](https://github.com/user-attachments/assets/88431415-423c-4c5f-af22-2a67ed7a8a80)  
![image](https://github.com/user-attachments/assets/40ad4bc7-615a-4811-bc4a-1d597dad1f48)   
![image](https://github.com/user-attachments/assets/d32946e7-e240-490a-936e-7a2b74f12388)  
**R2**  
![image](https://github.com/user-attachments/assets/debad655-597a-47ee-93ab-3673641da038)  
![image](https://github.com/user-attachments/assets/cf841974-9a9e-4c54-84a8-06917a79eca5)  
![image](https://github.com/user-attachments/assets/6f6c9e04-48fc-4e25-9e10-213178a6639e)  

**Какой маршрутизатор является DR?**  
![image](https://github.com/user-attachments/assets/aa754282-5f0c-4ce8-9cfa-94ca10728105)  
_R1_   

**Какой маршрутизатор является BDR?**  
![image](https://github.com/user-attachments/assets/9382546d-1b11-450c-9dee-09651dd64b10)  
_R2_    

**Каковы критерии отбора?**  
_По приоритету, здесь по умолчанию 1_  
_При равенстве приоритетов выбираеться маршрутизатор с наибольшим Router ID_  

**Оптимизация и проверка конфигурации OSPFv2**  
![image](https://github.com/user-attachments/assets/bfa797d2-0703-4a09-b77d-73b576cd4854)  
![image](https://github.com/user-attachments/assets/e2f468e3-fd99-47db-89f8-abe3177dad39)  
![image](https://github.com/user-attachments/assets/ba21d236-5823-4ef1-a55a-42e3764fb864)  
![image](https://github.com/user-attachments/assets/8bfe9a7b-de9a-4768-b2e7-367358843e8b)  
![image](https://github.com/user-attachments/assets/230a2097-503d-4aaa-96d5-91eb1043fcf6)  
![image](https://github.com/user-attachments/assets/92d42ce3-34cb-4093-99ff-85e837a66073)  
![image](https://github.com/user-attachments/assets/9db51dd1-2dea-49c4-b76a-c11cb135ee5b)
![image](https://github.com/user-attachments/assets/f2a0b49d-4ebd-415e-a978-b9838b4076e7)   
![image](https://github.com/user-attachments/assets/7ddd028e-0de9-4c27-b9bd-2170ed4203bb)  
![image](https://github.com/user-attachments/assets/67697865-0e03-4a21-a05c-6058c5b369f7)  
![image](https://github.com/user-attachments/assets/f540d278-f829-4769-bbb2-7d1b0be722f1)  
![image](https://github.com/user-attachments/assets/d44b7ba0-7062-49c6-9ff3-4e50f29fc7b9)  
Поменял dead interval на 120  
![image](https://github.com/user-attachments/assets/b226fe37-1ae3-4907-a15f-6f7d16c62a22)  
![image](https://github.com/user-attachments/assets/28534352-a20a-401e-8cfa-646559cdd1e3)  
![image](https://github.com/user-attachments/assets/de348df1-79bd-4040-8b0b-82eee5d3c098)
























  

