<img src="/lesson9/img/1.png" alt="Alt text"/>

Стартовый конфиг коммутатора (настроен):

<img src="/lesson9/img/2.png" alt="Alt text"/>

Стартовый конфиг роутера (настроен):

<img src="/lesson9/img/3.png" alt="Alt text"/>


Назначаем ipv6

interface vlan 1

ipv6 enable 

ipv6 address link-local fe80::b/64

ipv6 address 2001:db8:acad:1::b/64

<img src="/lesson9/img/4.png" alt="Alt text"/>

Наглядно на роутере:

<img src="/lesson9/img/5.png" alt="Alt text"/>

Далее no shutdown на обоих интерфейсах

Смотрим наззначение ip на роутере

<img src="/lesson9/img/6.png" alt="Alt text"/>

g/0/0/0 назначены группы

FE80::202:4AFF:FE02:7901

2001:DB8:ACAD:A::1

Натройка PC-B

Индивидуального адреса нет только линк-локал

<img src="/lesson9/img/7.png" alt="Alt text"/>

Включаем IPv6 unicast-routing ставим auto на получение ip на pc-b.

ip получен тк  PC теперь значет о конфигурации сети и может на основании этого выбрать ip

<img src="/lesson9/img/8.png" alt="Alt text"/>

Настраиваем статику на ПК

<img src="/lesson9/img/9.png" alt="Alt text"/>


Проверяем IP на роутере и коммутатору

<img src="/lesson9/img/10.png" alt="Alt text"/>

Пинга по link-local - нет, по global есть

Пинга до PC-B тоже нет, шлюз(пинг) по линк локал не доступен(в общем-то ничего по ЛЛ не пингуется), почему не понимаю, прошу помощи.

<img src="/lesson9/img/11.png" alt="Alt text"/>

Пинг пол link-local появился после назначения адресов на интерфейсы роутера с помощью ipv6 address АДРЕС link-local

<img src="/lesson9/img/12.png" alt="Alt text"/>

Пинг до интерфейсов роутера с обеих сторон есть, дальше пинг не идет, что с PC-a, что с PC-b. Прошу помощи.




