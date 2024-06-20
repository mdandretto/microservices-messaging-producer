# RabbitMQ Producer

> Demo of a Springboot project that produces RabbitMQ messages of a virtual purchase, like below:
>
> {
    "codigoPedido": "1001",
    "codigoCliente": "1",
    "item": [
        {
            "produto": "lapis",
            "quantidade": 1,
            "preco": 1.10
        },
        {
            "produto": "caderno",
            "quantidade": 1,
            "preco": 1.00
        }
    ]
}

## 💻 Pre-requisites

- JAVA 17
- Springboot 2.6.2
- Maven

## 🚀 Installation instructions

Windows, Linux e macOS:

```
mvn clean install
```

## ☕ Run

```
mvn spring-boot:run
```
