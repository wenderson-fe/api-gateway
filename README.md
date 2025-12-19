# API Gateway – Spring Cloud Gateway
Este projeto representa o API Gateway da arquitetura de microsserviços, responsável por centralizar o acesso às APIs, realizar roteamento dinâmico, integrar-se ao Service Discovery (Eureka) e expor informações operacionais via Actuator.

## Papel do Gateway na Arquitetura
O Gateway atua como ponto único de entrada (Single Entry Point) para os clientes, evitando que eles se comuniquem diretamente com os microsserviços.
### Principais responsabilidades:
- Roteamento de requisições para os microsserviços corretos
- Integração com o Eureka Server para descoberta dinâmica de serviços
- Abstração das URLs internas dos microsserviços

# Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Cloud Gateway
- Spring Cloud Netflix Eureka Client
- Spring Boot Actuator
- Maven

