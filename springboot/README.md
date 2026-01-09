# Spring Boot Desafio Itaú

[![Build Status](https://img.shields.io/badge/build-pending-lightgrey.svg)](https://github.com/) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Projeto exemplo em Spring Boot criado como desafio técnico. Objetivo: demonstrar uma aplicação backend Java com configuração mínima, organização de pacotes e testes básicos.

Sumário
- Sobre
- Tecnologias
- Pré-requisitos
- Executando localmente
- Rodando os testes
- Estrutura do projeto
- Contribuindo
- Licença

Sobre
Este repositório contém uma aplicação Spring Boot (Maven) com endpoints e serviços organizados em `desafio.itau.springboot`.

Tecnologias
- Java (recomendado: Java 17+, plano para Java 21)
- Spring Boot
- Maven (wrapper incluso)

Pré-requisitos
- JDK 17+ instalado (Java 21 planejado)
- Maven ou use o `mvnw` incluído

Execução rápida
- Clonar repositório:

```bash
git clone <repo-url>
cd springboot
```

- Build e empacotamento:

```bash
./mvnw clean package    # Unix/macOS
mvnw.cmd clean package  # Windows
```

- Rodar aplicação:

```bash
./mvnw spring-boot:run  # Unix/macOS
mvnw.cmd spring-boot:run # Windows
```

Rodando testes

```bash
./mvnw test
mvnw.cmd test
```

Estrutura do projeto
- `src/main/java` — código fonte principal
- `src/main/resources` — configurações e assets
- `src/test/java` — testes automatizados

Principais arquivos
- [SpringbootApplication.java](src/main/java/desafio/itau/springboot/SpringbootApplication.java#L1)
- [application.properties](src/main/resources/application.properties)

Contribuindo
- Abra um issue para bugs ou sugestões.
- Fork → branch com feature/bugfix → pull request.
- Siga o estilo do projeto e execute os testes antes de submeter PR.

Licença
Este projeto está, por padrão, marcado como MIT. Atualize o arquivo `LICENSE` conforme necessário.

Contato
Para dúvidas ou contribuições, abra uma issue no repositório.
