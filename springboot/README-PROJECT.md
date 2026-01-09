# Documentação Técnica — Projeto Spring Boot

Este arquivo contém instruções mais técnicas e focadas no desenvolvimento local e manutenção do projeto.

Requisitos de desenvolvimento
- JDK 17+ (recomendado). O upgrade para Java 21 está planejado.
- Maven 3.x (ou use o wrapper `mvnw` / `mvnw.cmd`)

Configuração local
1. Clone o repositório e entre na pasta do projeto:

```bash
git clone <repo-url>
cd springboot
```

2. Configure variáveis de ambiente se necessário (ex.: banco de dados, credenciais). Ver `src/main/resources/application.properties`.

Build e execução

```bash
./mvnw clean package
./mvnw spring-boot:run
```

No Windows use `mvnw.cmd`.

Testes

```bash
./mvnw test
```

Estrutura do código
- `desafio.itau.springboot` — pacote principal
- `Service` — serviços de negócio (ex.: `TransactionService`)
- `controller` — controladores REST (se existirem)

Boas práticas
- Escreva testes unitários para novos serviços.
- Use `mvnw` para consistência entre ambientes.

Tarefas pendentes
- Formalizar upgrade para Java 21 (gerar plano de upgrade e executar).
- Adicionar CI (GitHub Actions) para build e testes automáticos.
