<img src="/lesson9/img/1.png" alt="Alt text"/>

Swith start config:

<img src="/lesson9/img/2.png" alt="Alt text"/>

Router start config:

<img src="/lesson9/img/3.png" alt="Alt text"/>



interface vlan 1

ipv6 enable 

ipv6 address link-local fe80::b/64

ipv6 address 2001:db8:acad:1::b/64

<img src="/lesson9/img/4.png" alt="Alt text"/>

Naglyadno na routere

<img src="/lesson9/img/5.png" alt="Alt text"/>

Dalee no shutdown na oboih interfeisah

Smotrim naznacheie IP na routere

<img src="/lesson9/img/6.png" alt="Alt text"/>

g/0/0/0 naznacheni gruppi

FE80::202:4AFF:FE02:7901

2001:DB8:ACAD:A::1

Nactroika PC-B

Individualnii adres  ne naznachen, tolko link-local

<img src="/lesson9/img/7.png" alt="Alt text"/>

Vkluchaem IPv6 unicast-routing stavim auto na poluchenie ip na pc-b.

ip poluchen tk PC teper znaet o konfiguracii seti i mozahet na osnovanii etogo vibrat IP

<img src="/lesson9/img/8.png" alt="Alt text"/>

Nastraivaem statiku na PC

<img src="/lesson9/img/9.png" alt="Alt text"/>


Proveryaem ip na routere i kommutatore

<img src="/lesson9/img/10.png" alt="Alt text"/>

Pinga po link-local - net, po global est

<img src="/lesson9/img/11.png" alt="Alt text"/>


Pinga do pc-b toge net i esli mi ne pisali marshrut pochemu on dolgen bit


