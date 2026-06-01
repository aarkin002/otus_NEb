<img src="/lesson18/img/1.png" alt="Alt text"/>

Настройка коммутаторов

<img src="/lesson18/img/2.png" alt="Alt text"/>
<img src="/lesson18/img/3.png" alt="Alt text"/>
<img src="/lesson18/img/4.png" alt="Alt text"/>

Пинг

<img src="/lesson18/img/5.png" alt="Alt text"/>

Выключаем порты

<img src="/lesson18/img/6.png" alt="Alt text"/>

Делаем подключенные транковыми

<img src="/lesson18/img/7.png" alt="Alt text"/>

Включаем 2 и 4 порты

<img src="/lesson18/img/8.png" alt="Alt text"/>

Смотрим show spanning-tree

<img src="/lesson18/img/9.png" alt="Alt text"/>

Корнем является S2 потомму что имеет наименьший мак, никакие порты не являются корневыми потому что он сам корень. Все остальные назначенные. На коммутаторе с1 порт 2 является корневым порт 4 заблокирован (тк имеет более высокий номер приоритета).

Меняем стоимость корневого порта на коммутаторе с заблокированным портом

<img src="/lesson18/img/10.png" alt="Alt text"/>

Порт меняется потому что стоимость до корневого коммутатора на порту стала меньше, соответственно тем путем быстрее добраться.


