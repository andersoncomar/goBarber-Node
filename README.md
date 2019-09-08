# Go Barber

Projeto desenvolvido em nodeJS para ser o Backend da aplicação de Barbearia onde poderão ser feitos escolhas de datas e horas livres para poder ser feito assim o agendamento do mesmo.

Nesse projeto foi utilizado 3 bancos de dados:

- [PostgreSQL](https://www.postgresql.org/)
  Para armazenar usuários, fornecedores do serviço, agendamentos.

- [MongoDB](https://www.mongodb.com/)
  Banco NoSQL para armazenar informações com alta performace que, no caso utilizei para notificação ao fornecedor no momento que o usuário faz o agendamento.

- [Redis](https://redis.io/)
  Banco Chave/Valor para armazenar os jobs das filas que, utilizei para controle de envio de emails.

Abaixo as bibliotecas que foram utilizadas para criação do projeto:

- [Express](https://expressjs.com)
  Framework do Node.js que nos auxilia na construção das nossas aplicações Web. Ele é um framework muito simples de ser utilizado, por isso vem sendo adotado pelos desenvolvedores de todos os níveis

- [Sequelize](https://sequelize.org/)
  Sequelize é um ORM baseado em promessas para Postgres, MySQL, MariaDB, SQLite e Microsoft SQL Server. Possui sólido suporte a transações, relações, carregamento rápido e preguiçoso, replicação de leitura e muito mais.

- [node-postgres](https://www.npmjs.com/package/pg)
  Cliente PostgreSQL Non-blocking para Node.js

- [Mongoose](mongoosejs.com)
  O Mongoose fornece uma solução direta e baseada em esquema para modelar os dados do aplicativo. Ele inclui conversão de tipo, validação, criação de consultas, ganchos de lógica de negócios e muito mais, prontos para uso.

- [Multer](https://github.com/expressjs/multer)
  Multer é um middleware node.js para lidar com dados de várias partes / formulário, usado principalmente para o upload de arquivos. Está escrito em cima do busboy para máxima eficiência.

- [date-fns](https://date-fns.org/)
  Fornece o conjunto de ferramentas mais abrangente, porém simples e consistente para manipular datas JavaScript em um navegador e no Node.js.

- [Nodemailer](https://nodemailer.com/about/)
  Biblioteca utilizada para controle de envio de emails.

- [Yup](https://github.com/jquense/yup)
  É um validador de esquema de objetos.

- [Youch](https://github.com/poppinss/youch)
  Relatórios de retorno de erros.

- [JWT](https://jwt.io/)
  O JSON Web Token (JWT) é um padrão aberto (RFC 7519) que define uma maneira compacta e independente de transmitir com segurança informações entre partes como um objeto JSON. Essas informações podem ser verificadas e confiáveis porque são assinadas digitalmente. Os JWTs podem ser assinados usando um segredo (com o algoritmo HMAC) ou um par de chaves pública / privada usando RSA ou ECDSA.

- [Sucrase](https://github.com/alangpierce/sucrase)
  Sucrase é uma alternativa ao Babel que permite construções de desenvolvimento super-rápidas. Em vez de compilar uma grande variedade de recursos de JS para poder trabalhar no Internet Explorer, o Sucrase assume que você está desenvolvendo com um navegador recente ou uma versão recente do Node.js.Por isso, concentra-se na compilação de extensões de linguagem não padrão: JSX, TypeScript e Flow. Devido a esse escopo menor, o Sucrase pode se dar bem com uma arquitetura muito mais eficiente, mas menos extensível e sustentável

- [Nodemon](https://nodemon.io/)
  O Nodemon é um utilitário que monitora qualquer alteração na sua fonte e reinicia automaticamente o servidor. Perfeito para o desenvolvimento

Ferramenta de análise de código estático:

- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

Style Guide utilizada:

- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
