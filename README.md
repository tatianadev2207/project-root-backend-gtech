# 🛒 Project Root Backend - GTech

**Node.js | Express.js | JavaScript**

Esta é a API backend oficial do ecossistema GTech, desenvolvida para fornecer uma base sólida e escalável para operações de produtos, usuários e categorias. O projeto segue os padrões REST e boas práticas de desenvolvimento, garantindo manutenibilidade e clareza no código.

---

## 📋 Funcionalidades

- **Autenticação de Usuários**: Registro e login seguros.
- **Gestão de Produtos**: CRUD completo (Criar, Ler, Atualizar e Deletar).
- **Categorias**: Organização de produtos por tipos.
- **Validação de Dados**: Entradas validadas antes do processamento.
- **Tratamento de Erros Centralizado**: Respostas consistentes em toda a API.
- **Organização em Camadas**: Separation of Concerns (Controller, Service, Model).

---

## 🛠️ Tecnologias e Ferramentas

| Categoria | Tecnologia |
|-----------|------------|
| Runtime | Node.js |
| Framework | Express.js |
| Persistência | *(a definir: MySQL / PostgreSQL / MongoDB)* |
| ORM/ODM | *(a definir: Prisma / Sequelize / Mongoose)* |
| Documentação | Swagger |
| Testes | Jest |

---

## 🚀 Como instalar e rodar

### 1. Clonar o repositório

```bash
git clone https://github.com/tatianadev2207/project-root-backend-gtech.git
2. Acessar o diretório do projeto
bash
cd project-root-backend-gtech
3. Instalar as dependências
bash
npm install
4. Configurar variáveis de ambiente
Crie um arquivo .env na raiz do projeto com base no exemplo:

bash
cp .env.example .env
Preencha as variáveis conforme necessário:

text
PORT=3000
DATABASE_URL=seu_link_do_banco_aqui
JWT_SECRET=sua_chave_secreta
5. Iniciar a aplicação
bash
# Desenvolvimento (com auto-reload)
npm run dev

# Produção
npm start
📜 Scripts Disponíveis
Comando	Descrição
npm run dev	Inicia o servidor em modo desenvolvimento (nodemon)
npm start	Inicia o servidor em modo produção
npm test	Executa os testes automatizados
📁 Estrutura do Projeto
text
project-root-backend-gtech/
│
├── src/
│   ├── config/          # Configurações (Swagger, banco, etc)
│   ├── controllers/     # Controladores (lógica de requisições)
│   ├── services/        # Camada de serviços (regras de negócio)
│   ├── models/          # Modelos de dados
│   ├── routes/          # Definição das rotas da API
│   ├── middlewares/     # Middlewares (autenticação, validação)
│   └── app.js           # Configuração do Express
│
├── tests/               # Testes automatizados
├── .env.example         # Exemplo de variáveis de ambiente
├── .gitignore
├── package.json
└── README.md
✅ Boas Práticas Aplicadas
Separação de responsabilidades (MVC adaptado)

Código modular e organizado

Uso de variáveis de ambiente

Padronização de respostas da API

Tratamento de exceções centralizado

🤝 Contribuição
Contribuições são bem-vindas! Siga os passos abaixo:

Fork o projeto

Crie uma branch para sua feature:

bash
git checkout -b feature/nova-feature
Commit suas alterações:

bash
git commit -m 'Adiciona nova feature'
Push para a branch:

bash
git push origin feature/nova-feature
Abra um Pull Request

👥 Autoria
Projeto acadêmico - Geração Tech 3.0
Foco em desenvolvimento Back-end

Desenvolvido por:

Tatiana dos Santos Lima

Mickaelly da Silva Costa

Kássia Moreira Santos

© 2026 - Todos os direitos reservados.

📄 Licença
Este projeto está sob a licença MIT. 
