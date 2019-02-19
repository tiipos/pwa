# Resumo
## Info

**Aluno**: João Pedro Silva de Queiroz<br>
**Livro**: Progressive Web App

## Objetivo
- Resumir o Capítulo do Livro

## Meu Resumo

As denominadas Aplicações Progressivas ou PWA (Progressive Web Apps) são um dos principais objetivos do desenvolvedor web atual afim de tornar sua aplicação ou site o mais acessível e dinâmico possível, atendendo às demandas de uma base de usuários cada vez mais impaciente e equipadas com diversos tipos de dispositivos, uns mais atuais que os outros, e diferentes velocidades de conexão, ou até mesmo uma conexão instável.

O principal objetivo de uma PWA é atender ao maior número de usuários possível, utilizando de requisitos de performance, acessibilidade e de progressão que são qualificados pela ferramenta de código aberto da Google, Lighthouse, que gera um relatório medindo o quão progressiva é uma aplicação, no entanto alguns desses requisitos requerem uma avaliação manual. 

Dentre esses requisitos estão:
### A Página deve	registrar	um	Service	Worker
Service	Worker	é	uma	especificação	W3C	que	permite	executar um trecho de	código JavaScript	continuamente	no nível do navegador.	O principal objetivo desse requisito é a funcionabilidade da página em um estado off-line.
  
### Deve	 exibir	 conteúdo	 quando	 o	 JavaScript	 estiver desabilitado
Uma PWA deve ter programada uma resposta programada para caso houver uma requisição de um navegador com o Javascript desabilitado ou não-suportado.

### Usar	HTTPS
Para garantir maior segurança na hora de troca de dados entre o servidor e o cliente, utilizar do protocolo HTTPS.

### Deve	carregar	rapidamente	no	3G 
Ao utilizar-se de dados móveis, a página deve carregar rapidamente para não irritar o usuário.

### Redimensionar	o	conteúdo	da	página	corretamente
Os componentes da página devem atender ao tamanho da tela do dispositivo do usuário, utilizando a	disposição correta	das	tags	HTML,	uma	boa	organização	das classes	CSS	e	do	uso	de	@media	queries. 

### O	site	deve	ser	cross-browser
Uma PWA deve ser compatível no maior número de navegadores possíveis, no caso de incompatibilidade, exibir uma página alertando ao usuário.

### As	transições entre	páginas	não	devem	ser	sensíveis	à velocidade	de	conexão
É aconselhado o uso de Single-Page Application, uma aplicação aonde todos os recursos estão disponíveis na mesma página.
