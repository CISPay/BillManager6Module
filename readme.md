# BillManager6 Module
> Модуль, разработанный для биллинга BillManager 6, который позволяет создавать платежи и проверять их статус (осуществлять выдачу)

---
#### Инструкция
##### 1. Перед скачиванием
- 1.1. Убедитесь, что у вас установлены следующие расширения: **php-common**, **php-xml**, **unzip**
Если нет, то установите их, используя пакетный менеджер своего дистрибутива. **apt** - для Ubuntu, **yum** - для CentOS
##### 2. Скачивание и установка
- 2.1. В консоли на сервере выполните команду, которая скачает установочный скрипт: ```curl -O https://proxy.cispay.pro/modules/install.sh```
- 2.2. Предоставьте скрипту права на выполнение: ```chmod 755 install.sh```
- 2.3. Запустите скрипт, указав через пробел название модуля (BillManager): ```./install_module.sh BillManager```
##### 3. Настройка модуля
- 3.1. Зайдите в BillManager от имени **администратора** и перейдите в раздел **Провайдер > Методы оплаты**
![image](https://github.com/CISPay/BillManager6Module/assets/102430482/666851de-3912-405a-a53d-fe2870f7993e)
- 3.2. Выберите модуль **CISPay** (появится в самом низу списка), и перейдите к его настройке
- 3.3. Укажите UUID мерчанта, который можно получить нажав на "?" в панели мерчанта
![image](https://github.com/CISPay/BillManager6Module/assets/102430482/ed39a026-aee6-4470-87fc-38999155fd97)
![image](https://github.com/CISPay/XenForoModule/assets/102430482/4c5f09cf-de1e-4c6b-842f-e0369764eaf0)
- 3.4. Введите название для модуля, можно любое, и **обязательно укажите** минимальную сумма платежа минимум в **1 руб**, иначе платеж не будет создаваться и будет выдавать ошибку создания

---

## Лицензия

Copyright © 2023 [CISPay](https://github.com/CISPay)

Проект распространяется под лицензией [MIT](license)
