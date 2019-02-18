# Resumo
## inf
**aluno:** Danielle Costa de Lima
**livro:** Progressive Web App
## Objetivo 
- Resumir o 1º capitulo do livro 
## Meu resumo 
PWA são aplicações progressivas, ou seja, de melhoria progressiva e que buscam atender o maior número de pessoas possível. Trata-se de uma criação voltada para a experiência do usuário, dos quais terão acesso a plataforma sem restrições tecnológicas. Tais aplicações são avaliadas de acordo com o cumprimento de alguns requisitos que serão listados logo abaixo.
#### Requisitos 
##### 1. Deve registrar um Service Worker 
O servisse worker é uma especificação da W3C que permite executar um trecho de código JavaScript continuamente no nível do navegador. Nas PWA o servisse worker atua no conjunto de elementos que atuarão no funcionamento offline da aplicação.  

##### 2. Resposta com status 200 mesmo estando offline
O status 200 consiste em um dos códigos de retorno do protocolo HTTP e denota o sucesso na solicitação. Esse requisito atua de maneira a garantir com que esse sucesso ocorra mesmo estando offline. 

##### 3. Deve exibir conteúdo quando o JavaScript estiver desabilitado 
Essa funcionalidade consiste basicamente que uma PWA deve ter uma resposta programada no caso de o JavaScript estar desativado ou não seja suportado.

##### 4. Usar HTTPS
Uma aplicação progressiva não pode ter seus dados transmitidos em claro, ou seja, o protocolo HTTPS irá atuar na segurança dos dados que serão armazenados no download de dados inicial da aplicação. 

##### 5. Todo conteúdo HTTP deve ser redirecionado para HTTPS 
O protocolo HTTP trabalha sobre a porta 80 e, por não ser criptografado, deixa margem para interferência dos dados da aplicação. Sendo assim, recomenda-se o direcionamento para o protocolo HTTPS que trabalha sobre o protocolo TLS (Transporte Layer Security). O direcionamento pode ocorrer por meio do próprio endereço de navegação, de modo a utilizar o protocolo HTTPS ao invés do HTTP, ou por configuração no servidor web, redirecionando sempre o link da porta 80 para a 443. 

##### 6. Deve carregar rapidamente no 3G 
Uma aplicação deve estar disponível para o usuário em um tempo inferior a 10 segundos. 

##### 7. O usuário deve ser questionado se desejar instalar a aplicação 
Como o próprio título já bem descreve, consiste em questionar o usuário sobre a instalação da aplicação. As atuais especificações da W3C já favorecem bastante tal possibilidade principalmente quando se trata se usuários mobiles.  

##### 8. Deve ser configurada com uma splash screen personalizada
Essa funcionalidade consiste em uma tela de carregamento enquanto o usuário espera a disponibilização da aplicação.

##### 9. Colorir a barra de endereço do navegador com as cores do site 
Trata-se, basicamente, de colorir a barra de navegação do site com as cores deste. 

##### 10. Implementar a metatag viewport
A tag meta melhora a visualização das páginas nos dispositivos mobile, determinando a área visível do usuário. 

##### 11. Redimensionar o conteúdo da página corretamente 
Consiste na construção de layouts responsivos.

##### 12. O site deve ser cross-browser 
Uma PWA deve ter suporte a maior quantidade possível de navegadores, apresentando alguma resposta programa ao usuário em caso de falta de suporte em algum browser. 

##### 13. As transições entre páginas não devem ser sensíveis à velocidade de conexão 
Os elementos do HTML são organizados através do DOM (Modelo de Objeto de documento). Portanto, ao carregar uma página o navegador segue a lógica de organização do DOM. Nessa perspectiva, esse requisito atenta-se para o tempo de transição no carregamento desses elementos. Dessa forma, é sugerido que ao invés da criação de várias páginas, a aplicação contenha apenas uma, de modo a alterar sua a visibilidade de seus componentes mediante as ações do usuário.

##### 14. Cada página deve ter uma URL 
Essa característica se atribui tecnicamente ao termo bookmarkable, que seria uma página que pode ser acessada por uma URL única. 

#### Criando nosso backlog 
Backlog seria uma espécie de lista de requisitos, no qual faz parte da organização de uma aplicação. Sendo assim, será iniciada uma aplicação utilizando os conceitos já apresentados. Os tópicos a seguir assumem um caráter fundamentalmente de um fichamento, pois descreverão os passos demonstrados nos tópicos.
##### 1. Histórias da PWA 
Nesse tópico há simplesmente uma transcrição dos requisitos PWA em um quadro, de maneira a se dimensionar o que será necessário para o projeto cumprir. 
Uma história pode ser considerada como um requisito. 

##### 2. Visão geral da aplicação 
Esse tópico foi direcionado para a descrição do projeto a ser construído (behappywith.me), que consiste basicamente numa aplicação de cadastro de gentilezas. 

##### 3. Novo usuário
Nesse tópico temos a descrição do protótipo da tela de novo usuário, demonstrando o momento inicial de download dos dados da aplicação. Os componentes aqui criados poderão ser usados durante o desenvolvimento do resto a aplicação.

##### 4. Demais funcionalidades 
Esse tópico aborda a demais funcionalidades do projeto, do qual tem as funcionalidades iniciais reaproveitadas. A aplicação conta com seis tipos de destinatários de uma gentileza, do qual pode ser agendada, ou já nascer concluída. 
As gentilezas podem ainda ser classificadas em cinco tipos: zap, bom-dia, ligação, aperto de mãos, abraço, doce e presente.
Neste tópico também é apresentada a funcionalidade de listar gentilezas. 


