# Projeto-App-de-Tarefas
Abaixo seguem os repositórios do front-end e do back-end:
- [Front-end](https://github.com/Augusto-Ildefonso/Front-End-Projeto-App-Tarefas)
- [Back-end](https://github.com/Augusto-Ildefonso/Back-End-Projeto-Tarefas)

Além disso, nesse repositório se encontra a documentação do projeto, tanto em PDF quanto em DOCX.
## Geral
### Descrição do projeto
O projeto consiste em um aplicativo mobile, tanto iOS quanto Android, de gerenciamento de tarefas. Nesse app, o usuário poderá adicionar tarefas com diversas propriedades, como nome, data de entrega, horário, descrição e status. Além disso, ele poderá editá-las e excluí-las, ou então, adicionar uma tarefa rápida que terá apenas nome.

O aplicativo divide as tarefas de acordo com o status dela, para facilitar tanto a visualização, quanto a organização do usuário. Desse modo, existem as seguintes divisões: atrasadas, não iniciadas, em andamento e concluídas. Esses status são atribuídos pelo usuário, exceto pelo status de atrasado, que é calculado pelo app de acordo com a data de entrega.

Além dessas funcionalidades, o usuário também terá uma conta. Com ela, ele terá acesso à todas as suas tarefas, em qualquer aparelho que conecte. O usuário também terá liberdade de alterar seus dados pessoais, sair da conta e deletá-la.

### Tecnologias utilizadas
O app é dividido entre front-end, back-end e banco de dados. Cada uma dessas partes utilizou uma tecnologia diferente para a sua implementação. Ademais, a sua prototipação foi feita com o Figma, que permite um desenvolvimento de protótipos tanto de baixo nível quanto de alto nível.
  
O front-end foi implementado com React-Native, um framework baseado em Javascript, utilizado para desenvolver aplicativos nativos para iOS, Android, entre outros. Por essa característica de servir para várias plataformas, que ele se tornou um bom candidato para desenvolver o projeto.

O back-end foi implementado com NodeJS, que é uma ferramenta que permite simular um servidor, interpretando código Javascript. As bibliotecas utilizadas foram: express, esm, cors, bcrypt, jsonwebtoken, mongoose. Além disso, o servidor foi implementado como uma Rest API, seguindo os princípios básicos desse modelo.

O banco de dados foi implementado com MongoDB, um software de banco de dados não relacional, NoSQL, orientado a documentos, ao invés de tabelas e linhas. Ele foi escolhido por causa da sua fácil implementação com o NodeJS através da biblioteca mongoose.

Por último, foi utilizado o Expo, uma plataforma para fazer apps nativos para diversos sistemas com React e Javascript, para simulação do aplicativo. Ele foi usado através da sua biblioteca para o NodeJS.
## Prototipação
Como foi dito anteriormente, a prototipação do projeto foi feita no Figma. Nela criamos tanto um protótipo de baixo nível para poder organizar as ideias quanto um de alto nível que foi base para o front-end. Veja abaixo o projeto
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/hXpHsgBAjNOz7ublMsMPq1/Projeto-App-de-Gerenciamento-de-Tarefas?node-id=0-1&embed-host=share" allowfullscreen></iframe>
