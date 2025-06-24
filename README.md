Projeto: Sistema de Cadastro de Tarefas
Uma aplicação web simples (mas feita com muito café e vontade de aprender) para cadastro de tarefas, com backend em Node.js, integração com MySQL e uma interface web responsiva feita na unha com HTML e CSS.

Funcionalidades
Cadastro de novas tarefas

Listagem de todas as tarefas salvas

Atualização de status das tarefas (exemplo: pendente, concluída)

Integração completa com banco de dados MySQL

Frontend básico, mas funcional e responsivo

Tecnologias e Ferramentas Utilizadas
Node.js

Express.js

Sequelize ORM

MySQL

HTML5 e CSS3

Preview da Interface


Como Rodar o Projeto (sem dor de cabeça)
Pré-requisitos
Node.js instalado na sua máquina

MySQL Server rodando localmente

Passo a passo
bash
Copiar
Editar
# Clone o repositório
git clone https://github.com/seuusuario/seurepositorio.git

# Acesse o diretório
cd seurepositorio

# Instale as dependências
npm install

# Configure o banco de dados
# (Crie o banco no MySQL e ajuste as credenciais no arquivo de configuração do Sequelize)

# Inicie o servidor
node backend/server.js
O servidor deve rodar na porta padrão (exemplo: http://localhost:3000).

O que eu Aprendi com esse Projeto
Esse projeto foi mais que um simples CRUD. Foi meu laboratório pessoal pra testar na prática como migrar um backend que antes usava SQLite para um ambiente mais robusto com MySQL.

Trabalhar com Sequelize foi um baita aprendizado. Desde a criação de models até entender como funcionam as migrations e a conexão com o banco.

Além disso, coloquei a mão na massa pra melhorar a organização das rotas, separar melhor as camadas do backend e dar um pouco mais de atenção à estrutura de pastas.

A interface ainda é simples, mas o foco aqui foi backend mesmo. Prometo que na próxima versão eu capricho mais no frontend.

Próximos Passos (se der tempo e inspiração)
Criar autenticação de usuários

Melhorar o layout do frontend

Adicionar filtros por status ou data

Fazer o deploy em um ambiente online

Quem sabe até colocar um React ou Vue futuramente

Sobre o Autor
Meu nome é Isaque. Sou um desenvolvedor em constante evolução, apaixonado por tecnologia e por aprender coisas novas.

Esse projeto é mais uma etapa da minha caminhada pra dominar melhor Node.js, bancos relacionais e desenvolvimento web em geral.

Se quiser trocar ideia, dar feedback ou até sugerir melhorias no projeto, fique à vontade para me procurar no LinkedIn ou Instagram:

LinkedIn: https://linkedin.com/in/Isaque Cost

Instagram: https://instagram.com/isaque.tomberlin

Licença
Este projeto está disponível sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE.
