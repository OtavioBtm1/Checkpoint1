
markdown
Copy
Edit
# CPCRUD - Sistema de Pedidos

Projeto simples em Spring Boot para gerenciamento de pedidos com estrutura MVC (Model-View-Controller).

## 👨‍💻 Integrantes

- **Otávio Vitoriano da Silva**
- **Maitê Menezes**
- **Murilo Obinata**

## 🛠️ Tecnologias utilizadas

- Java 17
- Spring Boot 3.1+
- Maven
- VS Code
- JPA / Spring Data
- H2 Database (ou outro definido)
  
## 📁 Estrutura do projeto
src
├── main
│ ├── java
│ │ └── com.fiap.checkpoint1
│ │ ├── controller
│ │ │ └── PedidoController.java
│ │ ├── model
│ │ │ └── Pedido.java
│ │ ├── repository
│ │ │ └── PedidoRepository.java
│ │ ├── service
│ │ │ └── PedidoService.java
│ │ └── PedidoApp.java
│ └── resources
└── test

## ▶️ Como rodar o projeto

### Pré-requisitos

- Ter o Java 17 instalado
- Ter o Maven instalado ou usar os arquivos `mvnw`

### Rodando com Maven

No terminal, dentro da pasta do projeto:

```bash
mvn spring-boot:run
```

O servidor será iniciado em:
http://localhost:8080

Se o controlador estiver mapeado como /pedidos, por exemplo:
http://localhost:8080/pedidos                  
