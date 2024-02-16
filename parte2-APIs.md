# CONHECENDO APIs

## O que é uma API?
APIs são mecanismos que permitem que dois componentes de software se comuniquem usando um conjunto de definições e protocolos. 
- Por exemplo, o sistema de software do instituto meteorológico contém dados meteorológicos diários. A aplicação para a previsão do tempo em seu telefone “fala” com esse sistema por meio de APIs e mostra atualizações meteorológicas diárias no telefone.

## O que significa API?
API significa Application Programming Interface (Interface de Programação de Aplicação). No contexto de APIs, a palavra Aplicação refere-se a qualquer software com uma função distinta. A interface pode ser pensada como um contrato de serviço entre duas aplicações. Esse contrato define como as duas se comunicam usando solicitações e respostas. A documentação de suas respectivas APIs contém informações sobre como os desenvolvedores devem estruturar essas solicitações e respostas.

## Como as APIs funcionam?
A arquitetura da API geralmente é explicada em termos de cliente e servidor. A aplicação que envia a solicitação é chamada de cliente e a aplicação que envia a resposta é chamada de servidor. Então, no exemplo do clima, o banco de dados meteorológico do instituto é o servidor e o aplicativo móvel é o cliente. Existem quatro maneiras diferentes pelas quais as APIs podem funcionar, dependendo de quando e por que elas foram criadas.

- APIs SOAP (Simple Object Access Protocol ou Protocolo de Acesso a Objetos Simples): cliente e servidor trocam mensagens usando XML. Esta é uma API menos flexível que era mais popular no passado.

- APIs RPC ( Procedure Calls ou Chamadas de Procedimento Remoto): cliente conclui uma função (ou um procedimento) no servidor e o servidor envia a saída de volta ao cliente.

- APIs WebSocket: é outro desenvolvimento de API da Web moderno que usa objetos JSON para transmitir dados. Uma API WebSocket oferece suporte à comunicação bidirecional entre aplicativos cliente e o servidor. O servidor pode enviar mensagens de retorno de chamada a clientes conectados, tornando-o mais eficiente que a API REST.

- APIs REST: mais populares e flexíveis encontradas na Web atualmente. O cliente envia solicitações ao servidor como dados. O servidor usa essa entrada do cliente para iniciar funções internas e retorna os dados de saída ao cliente. Vejamos as APIs REST em mais detalhes abaixo.

# USANDO APIs

## Como criar uma API?

- Planejar a API: as especificações da API, como OpenAPI, fornecem o esquema para o design da sua API. É melhor pensar em diferentes casos de uso com antecedência e garantir que a API esteja de acordo com os padrões atuais de desenvolvimento de API.
- Criar a API: os designers de APIs prototipam APIs usando código boilerplate. Depois que o protótipo é testado, os desenvolvedores podem personalizá-lo de acordo com as especificações internas.
- Testar a API: teste de API é o mesmo que o teste de software e deve ser feito para evitar bugs e defeitos. As ferramentas de teste de API podem ser usadas para testar a resistência da API contra ataques cibernéticos.
- Documentar a API: embora as APIs sejam autoexplicativas, a documentação da API funciona como um guia para melhorar a usabilidade. APIs bem documentadas que oferecem uma série de funções e casos de uso tendem a ser mais populares em uma arquitetura orientada a serviços.
- Comercializar a API: assim como a Amazon é um marketplace online para varejo, existem marketplaces de API para desenvolvedores comprarem e venderem outras APIs. Catalogar sua API pode permitir que você ganhe dinheiro com ela.

## O que é teste de API?
As estratégias de teste de API são semelhantes a outras metodologias de teste de software. O principal foco é validar as respostas do servidor. O teste de API inclui:

- Fazer várias solicitações a endpoints de API para testes de performance.
- Escrever testes de unidade para verificar a lógica de negócios e a correção funcional.
- Testar a segurança simulando ataques ao sistema. 

## Como escrever a documentação da API?
Escrever uma documentação de API abrangente faz parte do processo de gerenciamento de API. A documentação da API pode ser gerada automaticamente usando ferramentas ou escrita manualmente. Algumas práticas recomendadas incluem:

- Escrever explicações em inglês simples e fácil de ler. Documentos gerados por ferramentas podem se tornar prolixos e exigir edição.
- Usar exemplos de código para explicar a funcionalidade.
- Fazer a manutenção da documentação para que seja precisa e atualizada.
- Visar o estilo de escrita para iniciantes
- Abranger todos os problemas que a API pode solucionar para os usuários.

## Como usar uma API?
As etapas para implementar uma nova API incluem:

- Obter uma chave de API. Isso é feito criando uma conta verificada com o provedor de API.
- Configure um cliente de API HTTP. Essa ferramenta permite estruturar solicitações de API facilmente usando as chaves de API recebidas.
- Se você não tiver um cliente de API, tente estruturar a solicitação por conta própria em seu navegador consultando a documentação da API.
- Quando estiver familiarizado com a nova sintaxe da API, você poderá começar a usá-la em seu código.

## Onde posso encontrar novas APIs?
Novas APIs Web podem ser encontradas em marketplaces de APIs e diretórios de APIs. Os marketplaces de API são plataformas abertas nas quais qualquer pessoa pode catalogar uma API para venda. Os diretórios de APIs são repositórios controlados e regulamentados pelo proprietário do diretório. Designers de API experientes podem avaliar e testar uma nova API antes de adicioná-la ao diretório. Alguns sites de API populares incluem:

- RapidAPI: o maior mercado global de APIs com mais de 10.000 APIs públicas e 1 milhão de desenvolvedores ativos no local. O RapidAPI permite que os usuários testem APIs diretamente na plataforma antes de fazer a compra.
- Public APIs: a plataforma agrupa APIs remotas em 40 categorias de nicho, tornando mais fácil navegar e encontrar a API certa para atender às suas necessidades.
- APIForThat e APIList: ambos os sites têm listas de mais de 500 APIs Web, juntamente com informações detalhadas sobre como usá-las.

# CONHECENDO API REST

## O que são APIs REST?
REST significa Transferência Representacional de Estado. REST define um conjunto de funções como GET, PUT, DELETE e assim por diante, que os clientes podem usar para acessar os dados do servidor. Clientes e servidores trocam dados usando HTTP.

A principal característica da API REST é a ausência de estado. A ausência de estado significa que os servidores não salvam dados do cliente entre as solicitações. As solicitações do cliente ao servidor são semelhantes aos URLs que você digita no navegador para visitar um site. A resposta do servidor corresponde a dados simples, sem a renderização gráfica típica de uma página da Web.

## Quais são os benefícios das APIs REST?

- Integração: as APIs são usadas para integrar novas aplicações com sistemas de software existentes. Isso aumenta a velocidade de desenvolvimento porque cada funcionalidade não precisa ser escrita do zero. Você pode usar APIs para aproveitar o código existente.
- Inovação: setores inteiros podem mudar com a chegada de uma nova aplicação. As empresas precisam responder rapidamente e oferecer suporte à rápida implantação de serviços inovadores. Elas podem fazer isso fazendo alterações no nível da API sem precisar reescrever todo o código.
- Expansão: as APIs apresentam uma oportunidade única para as empresas atenderem às necessidades de seus clientes em diferentes plataformas. Por exemplo, a API de mapas permite a integração de informações de mapas por meio de sites, Android, iOS etc. Qualquer empresa pode fornecer acesso semelhante aos seus respectivos bancos de dados internos usando APIs gratuitas ou pagas.
- Facilidade de manutenção: a API atua como um gateway entre dois sistemas. Cada sistema é obrigado a fazer alterações internas para que a API não seja afetada. Dessa forma, qualquer alteração futura de código feita por uma parte não afetará a outra parte.

## Como proteger uma API REST?

- Tokens de autenticação: são usados para autorizar os usuários a fazer a chamada de API. Os tokens de autenticação verificam se os usuários são quem afirmam ser e se têm direitos de acesso para aquela chamada de API específica. Por exemplo, quando você faz login em seu servidor de e-mail, seu cliente de e-mail usa tokens de autenticação para acesso seguro.
- Chaves de API: as chaves de API verificam o programa ou a aplicação que faz a chamada de API. Elas identificam a aplicação e garantem que ela tenha os direitos de acesso necessários para fazer a chamada de API específica. As chaves de API não são tão seguras quanto os tokens, mas permitem o monitoramento da API para coletar dados sobre o uso. Você pode ter notado uma longa sequência de caracteres e números no URL do seu navegador ao visitar diferentes sites. Essa string é uma chave de API que o site usa para fazer chamadas de API internas.
