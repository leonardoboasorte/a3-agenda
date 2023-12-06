# a3-agenda

Descrição do Projeto
O A3 Agenda é uma aplicação web desenvolvida para gerenciar e organizar tarefas e compromissos. Com uma interface amigável e intuitiva, a aplicação permite que os usuários criem, editem e excluam eventos, além de fornecer recursos avançados, como autenticação de usuários.

Tecnologias Utilizadas
O projeto foi construído utilizando as seguintes tecnologias:

Node.js: Ambiente de execução JavaScript do lado do servidor.
Express: Framework para construção de aplicativos web com Node.js.
MongoDB com Mongoose: Banco de dados NoSQL para armazenamento de dados.
EJS: Engine de modelo para geração de páginas HTML.
Nodemon: Utilitário que monitora alterações nos arquivos e reinicia automaticamente o servidor.
Dotenv: Módulo para carregar variáveis de ambiente a partir de um arquivo .env.
CSRF: Middleware para proteção contra ataques CSRF.
Bcryptjs: Biblioteca para hash de senhas.
Connect-Flash: Mensagens flash para Express.
Connect-Mongo: Conector de sessão para armazenamento de sessões no MongoDB.
Validator: Biblioteca para validação de dados.

Como Executar o Projeto
Siga os passos abaixo para executar o projeto localmente:

Clonar o Repositório:


git clone https://github.com/seu-usuario/a3-agenda.git
cd a3-agenda

Instalar as Dependências:


npm install

Configurar as Variáveis de Ambiente:
Crie um arquivo .env na raiz do projeto e configure as variáveis necessárias.

Executar o Servidor em Modo de Desenvolvimento:

npm run dev
Isso iniciará o servidor usando o Nodemon, que reiniciará automaticamente o servidor sempre que houver alterações nos arquivos.

Acessar a Aplicação:
Abra o navegador e acesse http://localhost:3000.

Comandos Disponíveis
npm start: Inicia o servidor em produção.
npm run dev: Inicia o servidor em modo de desenvolvimento com o Nodemon.

Este é um guia básico para executar o projeto localmente. Certifique-se de consultar a documentação específica de cada módulo e ferramenta para obter informações mais detalhadas sobre suas funcionalidades e configurações.

Divirta-se explorando o A3 Agenda!
