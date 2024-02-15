# Projeto: Dungeon Talk API

## Descrição:
O projeto consiste na criação de uma API para um sistema de chat voltado para grupos de jogadores de Dungeons & Dragons (D&D). Essa API permitirá a comunicação entre os integrantes do grupo por meio de mensagens de texto, além de fornecer recursos para armazenamento de informações sobre campanhas, jogadas de dados, habilidades adquiridas durante as sessões e outros detalhes relevantes para o jogo.

## Tecnologias Utilizadas:
- Java: Linguagem de programação principal para o desenvolvimento da API.
- Spring Boot: Framework que facilita a criação de aplicativos Java baseados em Spring, fornecendo configuração pré-definida para facilitar o desenvolvimento.
- Banco de Dados ( PostgreSQL): Para armazenar informações sobre os usuários, campanhas, habilidades, etc.

## Funcionalidades Planejadas:
- Autenticação de Usuários: Permitir que os jogadores façam login e autentiquem-se no sistema.
- Criação e Gerenciamento de Grupos: Capacidade de criar grupos de jogadores para cada campanha de D&D.
- Chat em Tempo Real: Possibilitar a comunicação entre os membros do grupo por meio de mensagens de texto em tempo real.
- Armazenamento de Informações da Campanha: Permitir o registro de detalhes sobre a campanha atual, como nome, descrição, NPCs, localizações, entre outros.
- Registro de Jogadas de Dados: Registrar as jogadas de dados realizadas durante as sessões de jogo.
- Gerenciamento de Personagens e Habilidades: Permitir que os jogadores cadastrem e atualizem as informações de seus personagens, bem como habilidades adquiridas durante o jogo.
- Notificações: Possibilidade de enviar notificações aos jogadores sobre eventos importantes no jogo ou atualizações relevantes no sistema.

## Estrutura do Projeto:
- Controllers: Controle das requisições HTTP, definindo os endpoints da API.
- Services: Lógica de negócios da aplicação, processando as requisições vindas dos controllers.
- Repositories: Interação com o banco de dados para persistência e recuperação de dados.
- Models: Representação das entidades do sistema, como Usuário, Grupo, Mensagem, Campanha, Personagem, etc.
- Configuração: Configurações específicas do Spring Boot, como segurança, conexão com o banco de dados, etc.

## Considerações Finais:
Este projeto visa facilitar a comunicação e organização das sessões de jogo de Dungeons & Dragons, oferecendo uma plataforma centralizada para os jogadores gerenciarem suas campanhas, personagens e interações. A utilização das tecnologias Java e Spring Boot garantirá uma base sólida e robusta para o desenvolvimento da API.
