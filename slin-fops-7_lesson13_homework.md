# Домашнее задание к занятию "Управление пакетами"


### Кейс 1.

Основные достоинства: решение проблем с зависимостями, автоматическая установка пакета, проще следить за обновлениями.
Недостатки: нет проверки на совместимость со старой версией ОС.

---

### Кейс 2.

Для того чтобы иметь возможность устанавливать ПО из сторонних репозиториев, их надо указать в source.list вашего пакетного менеджера и скачать gpg-ключ для него. 
Опасность такого способа распростанения ПО в следующем: ПО не тестируется на совместимость с вашей ОС, ПО может иметь вредоносный характер.
ПО из таких репозиториев должно ставиться на тестовую машину и проверяться на совместимость, после чего возможно производить установку и настройку на рабочий сервер.

---

### Кейс 3.

Depends: libc6 (>= 2.34), libncursesw6 (>= 6), libnl-3-200 (>= 3.2.7), libnl-genl-3-200 (>= 3.2.7), libtinfo6 (>= 6)

    apt show htop
    
![P1](https://github.com/geniusnsk/netology/blob/main/lesson13_1.png)

---

### Кейс 4.

![P2](https://github.com/geniusnsk/netology/blob/main/lesson13_2.png)

![P3](https://github.com/geniusnsk/netology/blob/main/lesson13_3.png)

---

### Кейс 5.


![P4](https://github.com/geniusnsk/netology/blob/main/lesson13_4.png)

![P5](https://github.com/geniusnsk/netology/blob/main/lesson13_5.png)

![P6](https://github.com/geniusnsk/netology/blob/main/lesson13_6.png)
