# Resumo 
## Info
 **Aluno**: Júlio César Balsan Costa Barros
 
 **Livro**: Progressive Web Apps
## Objetivo
  - Resumir o 1° capítulo do livro
## Meu Resumo
O capítulo 1 do livro Progressive Web Apps(PWA) introduz o conceito de Progressive Web Apps, ou Aplicações Web Progressivas. Nesse contexto, a palavra progressiva significa que a aplicação procura atender o maior número de pessoas possível sob todos os aspectos. Isso significa que a aplicação deverá estar disponível para todos, com smartphones ou microcomputadores, browsers atualizados ou obsoletos, e mesmo sem conexão à internet; ou seja, o objetivo de uma PWA é criar uma experiência cujos usuários terão acesso contínuo sem restrição tecnológica. 
	 A primeira parte do capítulo lida com os vários requisitos que uma PWA deve obedecer. Há uma ferramenta chamada Lighthouse, organizada pelo Google, que pode avaliar e gerar um relatório sobre uma aplicação com base em vários critérios relevantes à uma aplicação PWA. Os critérios avaliados pelo Lighthouse são os seguintes. 
	Uma PWA deve registrar um Service Worker, que é uma especificação W3C que permite executar Javascript no nível do navegador. Essa é uma das ferramentas que que torna possível a implementação de recursos offline. 
	Uma PWA deve obter resposta com status 200 mesmo estando offline. Basicamente, isto significa que uma solicitação ao browser deve retornar o código 200 (sucesso), mesmo não estando conectado à internet. Para isso, são usados Local Storage (dados), Application
Cache	(arquivos), IndexedDB (dados), e o próprio Service Worker.
Uma PWA deve exibir conteúdo quando o Javascript estiver desabilitado. Isso pode significar que a aplicação deve ter uma resposta para quando o Javascript estiver desabilitado, mesmo que seja apenas uma tela informando que não é possível utilizar a aplicação. 
Uma PWA deve utilizar HTTPS, e todo o conteúdo HTTP deve ser redirecionado para HTTPS.
Uma PWA deve carregar rapidamente no 3G. Basicamente, a aplicação deve carregar rapidamente. O Lighthouse avalia se a aplicação carrega em menos de 10 segundos, mas o ideal é que ela demore menos de 3 segundos. 
Uma PWA deve questionar ao usuário se este deseja instalar a aplicação. 
Uma PWA deve ser configurado com uma Splash Screen personalizada, ou seja, uma tela com a logo da aplicação que é exibida enquanto o software é carregado. 
Uma PWA deve colorir a barra de endereço do navegador com as cores do site. Puramente cosmético, mas tecnicamente um critério do Lighthouse. 
Uma PWA deve implementar a metatag viewport, que melhora a visualização em dispositivos móveis. 
Uma PWA deve redimensionar o conteúdo da página para ser compatível com diferentes viewports, seja por layouts estáticos (organizados especificamente para dispositivos) ou layouts responsivos. 
As transições entre páginas de uma PWA não devem ser sensíveis a velocidade de conexão. Uma das maneiras de realizar isso é utilizando uma SPA, Single Page Application.
Finalmente, cada página de uma PWA deve ter um URL, e ele deve ser “bookmarkable”; ou seja, pode ser acessado por uma URL única. A URL também teve ter um nome amigável

A segunda parte do capítulo descreve aspectos da aplicação. Esses aspectos não são, estritamente, critérios avaliados pelo Lightouse, mas ainda assim são essenciais. São características de performance, acessibilidade, usabilidade e boas práticas. 
 
