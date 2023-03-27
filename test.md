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

```mermaid
flowchart TD
A[Заказы] --> B[Заказ]
B[Заказ] --> C[Товар]
C[Товар] --> D[Доставка Ozon]
C[Товар] --> E[Доставка продавца]
D[Доставка Ozon] --> F[Возврат Ozon]
E[Доставка продавца] --> G[Возврат продавца]
F[Возврат Ozon] --> H[Заявка]
G[Возврат продавца] --> H[Заявка]
H[Заявка] --> I[Передача товара]
```
