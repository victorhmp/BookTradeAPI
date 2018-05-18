# RELATÓRIO

# INTEGRANTES

Nomes:  Kaique Komata           NUSP: 
        Ricardo Hideki Kojo     NUSP:
        Victor Hugo M. Pinto    NUSP: 
        Yurick Yussuke Honda    NUSP: 10258984

## PRIMEIRA FASE

### IDEIA

A ideia inicial é a uma plataforma onde os usuários possam oferecer livros que não queiram mais ou que achem bacana compartilhar com outras pessoas, recebendo outro livro de um usuário com o mesmo propósito. 

### REUNIÃO

Nessa primeira parte, antes de iniciar o desenvolvimento propriamente dito, foram feitas três reuniões. 
Na primeira reunião discutiu-se a proposta a ser oferecida pelo projeto, realizando um "brainstorm" para tornar a ideia cada vez mais inovadora e impactante para com o público a ser atingido. Assim, a partir do objetivo inicial, foi se levantando funcionalidades que podem ser implementadas posteriormente e melhorarão a experiência do usuário, como: integração do sistema de troca com os Correios, criação de sistema de pontuação relacionado a quantidade de trocas efetuadas, etc.
Na segunda reunião o foco foi as tecnologias que utilizaríamos para o desenvolvimento. Assim, após diversas discussões sobre as tecnologias que integraríamos ao Rails, concluiu-se haveria melhor desempenho na programação com o uso do Docker. Além disso, como o uso de ReactJS tornou-se popular, a decisão foi utilizá-lo para a programação do Cliente. Vale ressaltar que para melhor organização das tarefas e dos objetivos a serem cumpridos, os integrantes estão usando o Trello.
Na terceira reunião se fez a preparação para o início do desenvolvimento, realizando uma ordenação nas funcionalidades que seriam implementadas e a discussão sobre os modelos do banco de dados e os relacionamentos entre as tabelas. Tudo isso foi feito por meio de .

### DOCKER

### MODELOS E CONTROLADORES

Nessa primeira fase já foram criadas todas as tabelas do banco de dados na API do projeto e seus controladores. Os controladores de cada modelo criado tem seu CRUD implementado seguindo as restrições de autenticação de login do usuário, por meio das tokens.
As tabelas criadas foram: 
* Advertisements: anúncios de livros dos quais o usuário está disposto a realizar a troca;
* Offers: oferta de um usuário após visualizar um anúncio;
* Trades: os dados da troca entre os usuários;
* Users: o usuário e todo o processo de criação e dados de usuário;
* Wishlists: lista de desejos do usuário que busca um certo livro em específico, o ajudando quando livros de sua wishlists são ofertados;

### CLIENTE

Sabendo da dificuldade do processo de programação/desenvolvimento do Cliente, foi criada uma página inicial e um logo para a plataforma, com redirecionamento para páginas básicas de registro e login, porém sem integração com o CRUD dos controladores da API.