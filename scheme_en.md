# Системность мышления
[Как вернуть товар](https://docs.ozon.ru/common/otmena-i-vozvrat-zakaza/kak-vernut-tovar/?country=RU). 
## Схема взаимодействия компонентов

```mermaid
graph TD;
Orders --> Order for return;
Order for return --> Item(-s) for return;
Item(-s) for return --> Ozon Delivery;
Item(-s) for return --> Seller Delivery;
Ozon Delivery --> How to return (Ozon);
Seller Delivery --> How to return (Seller);
How to return (Ozon) --> Approved;
How to return (Seller) --> Approved;
Approved --> Item(-s) Shipment
```



