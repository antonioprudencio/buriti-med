# 🏥 Buriti Med

Neste projeto, trabalhei em parceria com a fictícia empresa "Buriti Med", uma rede de clínicas médicas amplamente 
distribuída
pelo território brasileiro. Objetivo foi desenvolver um sistema completo e integrado para a gestão eficiente do 
cadastro de médicos,
pacientes e o agendamento de consultas.

## 💎 Principais Recursos

* **Cadastro de Médicos e Pacientes**: O sistema permite o cadastro detalhado de médicos, incluindo suas especializações e
  informações de contato.

* **Agendamento de consulta**: O sistema permite agendar consultas filtrando por médico e sua especialização. Também 
  é possível cancelar consultas agendadas.


## 🎯 Funcionalidades
1. **Operações CRUD**: A API oferece endpoints para criar, ler, atualizar e deletar recursos no banco de dados. 
2. **Banco de Dados:** Utiliza o banco de dados MySQL para armazenar os dados da aplicação.
3. **Validações com Bean Validation:** Realiza validações nas entradas da API usando o Bean Validation, garantindo a integridade dos dados.
4. **Paginação de Dados:** Implementa paginação nos endpoints que retornam listas de recursos, melhorando a performance e a experiência do usuário.
5. **Padronização de Retornos:** Todos os retornos dos controllers seguem um padrão consistente, facilitando o entendimento por parte dos consumidores da API.
6. **Seguraça:**  Endpoints protegidos com token JWT.
7. **Testes Unitários:** Foram implementados testes unitários para os controllers e services.
8. **Documentação:** Todos os controllers foram mapeados com o swagger, para fácil interação com a aplicação 
   front-end/mobile.


## ⚙️ Configuração
1. Clone este repositório para sua máquina local.
2. Importe o projeto em sua IDE.
3. Configure as informações de conexão com o banco de dados no arquivo application.properties.
4. Inicie a aplicação Spring Boot.


## 📋 Requisitos

* Java 17
* MySQL
* Spring Boot 3
* Maven

## 🛠️ Tecnologias
* Spring Boot
* Spring Data
* Spring Security
* Bean Validation
* MySQL
* JPA/Hibernate
* Maven
