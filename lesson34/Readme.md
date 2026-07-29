<img src="/lesson34/img/1.png" alt="Alt text"/>

Насторйка коммутаторов и маршрутизаторов

<img src="/lesson34/img/2.png" alt="Alt text"/>
<img src="/lesson34/img/3.png" alt="Alt text"/>

Создание ACL и nat pool PUBLIC_ACCESS, привязываем к интерфейсу

<img src="/lesson34/img/4.png" alt="Alt text"/>

В задании указано настроить маршрут с р2 на р1, но я решил что это ошибка. Смотрим пинги с ПС-Б:

<img src="/lesson34/img/5.png" alt="Alt text"/>

Смотрим что пинг возможен только с 3 устройств, с 4 не пингуется

<img src="/lesson34/img/8.png" alt="Alt text"/>

Чистим, смотрим что с того которого не получалось - получилось, но не получилось с ПС-А:

<img src="/lesson34/img/9.png" alt="Alt text"/>

Настраиваем ПАТ смотрим пинг, смотрим что преобразуется только в 1 адрес:

<img src="/lesson34/img/10.png" alt="Alt text"/>

Настраиваем ПАТ с перегрузкой привязываем к интерфейсу:

<img src="/lesson34/img/11.png" alt="Alt text"/>

Настраиваем статический НАТ смотрим пинги

<img src="/lesson34/img/12.png" alt="Alt text"/>
<img src="/lesson34/img/13.png" alt="Alt text"/>

