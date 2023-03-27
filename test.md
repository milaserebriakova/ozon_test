Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    C-->D;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
flowchart TD
    A[Start] --> B{Is it?}
    B -->|Yes| C[OK]
    C --> D[Rethink]
    D --> B
    B ---->|No| E[End]
```
# Системность мышления 
[Как вернуть товар](https://docs.ozon.ru/common/otmena-i-vozvrat-zakaza/kak-vernut-tovar/?country=RU). 
## Схема взаимодействия компонентов

```mermaid
flowchart TD
A[Заказы] --> B[Выбор заказа для возврата]
Выбор заказа для возврата --> Выбор товаров для возврата
Выбор товаров для возврата --> Доставка Ozon
Выбор товаров для возврата --> Доставка продавца

```
