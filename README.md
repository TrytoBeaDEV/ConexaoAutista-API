  # 🤝 Conexão Autista - Aplicativo de Apoio para o TEA 💙
> API RESTful desenvolvida com **Spring Boot** com foco na organização da rotina de pessoas com Transtorno do Espectro Autista (TEA), promovendo autonomia, inclusão e suporte aos responsáveis, profissionais e educadores.

## 📌 Visão Geral
O projeto **Conexão Autista** tem como objetivo principal oferecer um sistema híbrido (Web e Mobile) para:

- 🧠 Registrar o humor da pessoa autista diariamente
- ⏰ Agendar alarmes para medicações
- 📅 Organizar compromissos e sessões com terapeutas
- 👩‍⚕️ Localizar profissionais especializados
- 📊 Compartilhar dados com médicos, terapeutas e educadores

Essa API representa o backend desse sistema.

## 🚀 Tecnologias Utilizadas
- 💻 **Java 17**
- 🌱 **Spring Boot 3**
- 🐬 **MySQL** como banco de dados relacional
- 🔁 **JPA/Hibernate** para persistência
- 🧭 **Swagger UI** para documentação e testes
- ☕ **Maven** como gerenciador de dependências
- 🐙 **GitHub** para versionamento

## 📦 Instalação Local
1. **Clone o repositório**:
```bash

## 🧪 Testando com Swagger
Após iniciar o projeto, acesse:
👉 [`http://localhost:8080/swagger-ui.html`](http://localhost:8080/swagger-ui.html)

Você poderá testar os seguintes endpoints disponíveis:
- `✅ GET /usuarios` → Listar todos os usuários
- `✅ POST /usuarios` → Cadastrar novo usuário
- `✅ PUT /usuarios/{id}` → Atualizar usuário existente
- `✅ DELETE /usuarios/{id}` → Deletar usuário
- `✅ GET /diarios` → Listar registros de diario
- `✅ POST /diarios` → Criar novo registro de diario
- `✅ PUT /diarios/{id}` → Atualizar registro de diario
- `✅ DELETE /diarios/{id}` → Excluir registro de diario

🧱 Estrutura da API
📁 Camadas da aplicação (Padrão MVC)
- **Controller** – Camada responsável por receber e responder às requisições HTTP.
- **Service** – Onde ficam as regras de negócio, validações e lógica da aplicação.
- **Repository** – Responsável por acessar os dados no banco de dados usando JPA.
- **Model** – Representa as entidades (classes) que serão persistidas.

🧑‍💻 Entidades Principais
- `Usuario`  
  Campos: `id`, `nome`, `email`, `senha`, `tipo`  
  Enum: `TipoUsuario { RESPONSAVEL, TERAPEUTA, PROFESSOR }`
- `DiarioHumor` 
  Campos: `id`, `data`, `humor`, `observacoes`, `usuario (relacionado)`

📚 Documentação Técnica
- ✅ Projeto desenvolvido com arquitetura MVC
- ✅ API RESTful com retorno em JSON
- ✅ Persistência com JPA e Hibernate
- ✅ Banco de dados relacional: MySQL
- ✅ Documentação e testes integrados com Swagger/OpenAPI
- ✅ Versionamento de código com GitHub

👩‍💻 Desenvolvedores
| Nome               | RA                   |
|--------------------|----------------------|
| Renata Andrade     | (RA: 2920482321037)  |
| Vitor Rezende      | (RA AQUI)  |
| Priscila Romano    | (RA AQUI)  |
| Higor Carlos       | (RA AQUI)  |
| Davi Barbosa       | (RA AQUI)  |

📃 Licença
Este projeto está licenciado sob os termos da **MIT License** – consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

💙 Por que esse projeto importa?
> “A previsibilidade e a rotina são aspectos essenciais para reduzir crises e melhorar o comportamento adaptativo em pessoas com TEA.”  
> — Temple Grandin


