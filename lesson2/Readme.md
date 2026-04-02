<h1>Лабораторная работа. Базовая настройка коммутатора</h1>
<img src="/lesson2/img/1.png" alt="Alt text"/>

1. Коммутатор имеет 26 портов (информация выдается при загрузке).
<img src="/lesson2/img/2.png" alt="Alt text"/>

   a. sh running-config показывает 2 Fast порта
   
   <img src="/lesson2/img/3.png" alt="Alt text"/>

   b. Кол-во портов Gigabit Ethernet = 0-9
   
   Кол-во портов F/E = 0-9
   
   Line vty 0-15

   <img src="/lesson2/img/4.png" alt="Alt text"/>

2. Сообщение появляется потому что коммутатор не сконфигурирован
   
   Switch#show startup-config

   startup-config is not present
