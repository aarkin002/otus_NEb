<img src="/lesson5/img/1.png" alt="Alt text"/>

**Строим схему, стираем стартовый конфиг на 2 коммутаторах**

<img src="/lesson5/img/2.png" alt="Alt text"/>

Перезагружаем с помощью reload

Настраиваем ПК

<img src="/lesson5/img/3.png" alt="Alt text"/>

Настроили коммутаторы (сначала непровильно сохранил конфигурацию, но потом понял что нужно просто ENTER для подтверждения copy running-config startup-config нажать, а не Y)

<img src="/lesson5/img/4.png" alt="Alt text"/>

Маки компьютеров 

<img src="/lesson5/img/5.png" alt="Alt text"/>

Маки коммутаторов

<img src="/lesson5/img/6.png" alt="Alt text"/>

Наблюдаем построение таблицы МАК адресов с помощью пинг(вначале выполняется команда на 2 свитче, потом включается 1 влан на первом и опять выполняются команды)

<img src="/lesson5/img/7.png" alt="Alt text"/>

После clear mac address-table dynamic таблица очистилась, через секунд 20, в таблице появился мак второго коммутатора

<img src="/lesson5/img/8.png" alt="Alt text"/>

На ПК Б сначала видны только коммутаторы в таблице мак, после пинга ПК а появляется и его мак тоже.

<img src="/lesson5/img/9.png" alt="Alt text"/>
