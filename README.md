# Plann.er

Plann.er é um projeto desenvolvido em Java com o objetivo de ajudar os usuários a organizar suas viagens, seja a trabalho ou lazer. Com o Plann.er, é possível criar uma viagem especificando nome, data de início e fim, e planejar atividades para cada dia da viagem.

## Tecnologias Utilizadas

- **Spring Web:** Framework para desenvolvimento de aplicações web.
- **Flyway:** Ferramenta para migração de banco de dados.
- **Spring Dev Tools:** Ferramentas para desenvolvimento ágil.
- **Lombok:** Biblioteca para reduzir boilerplate no código Java.
- **JPA:** Java Persistence API para mapeamento objeto-relacional.
- **H2 Database:** Banco de dados em memória utilizado para desenvolvimento e testes.

## Endpoints

- **/trips:** Lista todas as viagens cadastradas.
- **/{id}/activities:** Detalhes das atividades planejadas para uma viagem específica.
- **/{id}/links:** Links úteis relacionados à viagem identificada pelo ID.
- **/{id}/participants:** Lista de participantes da viagem identificada pelo ID.
- **/{id}/confirm:** Confirmação de participação na viagem identificada pelo ID.
- **/{id}/invite:** Envio de convite para participação na viagem identificada pelo ID.

## Testar os Endpoints
Você pode testar os endpoints utilizando ferramentas como o Insomnia ou Postman.

## Como Executar o Projeto

### Clone o Repositório
```bash
git clone https://github.com/gabrielribeirosimoes/plann.er.git
