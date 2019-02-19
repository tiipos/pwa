# Resumo
## Info

  **Aluno**: Flávio Henrique Silva Maria  
  **Livro**: Progressive Web App
  
## Objetivo

- Resumi o capítulo 1 do livro.

## Meu resumo

### O que são aplicações progressivas? 

Aplicações Progessivas ou PWAs (Progressive Web Apps) consistem em aplicações que atendem o maior numero de usuarios possiveis, em outras
palavras, uma aplicação universal e sem restriçoes tecnologicas (de plataformas, de browsers, de disponibilidade de internet etc).

### Requisitos de uma aplicação progressiva

Os requisitos tratados inicialmente no capitulo se referem em sua maioria aos analisados pelo	Lighthouse, que	é	uma	ferramenta	que	
permite	qualificar	aplicações	web	em	relação	aos	requisitos	de melhoria	progressiva. Existem outros requisitos alem dos citados no livro, que tambem dizem respeito a questões como usabilidade, boas praticas e acessibilidade.

### - Service Worker
A aplicação deve funcionar sem internet e de preferencia com recursos do Service Worker, uma especificação pela qual é possivel
implementar	 recursos	 offline	 e	 organizar	 o	 cache	 dos	 arquivos estáticos	da	página	web. 

### - Resposta com status 200

Paginas web que trabalham sob o protocolo HTTP trabalham com varios status de retorno às solicitações dos browsers, e um deles é o 
retorno do codigo 200, que significa sucesso na solicitação, este, em uma aplicação progessiva deve funcionar até mesmo offline.

### - Aplicação deve funcionar mesmo com JavaScipt desabilitado 

Uma aplicação progressiva deve estar preparada para a falta, por qualquer que seja o motivo, do JavaScript, ou seja, deve ser funciional, mesmo sem esse recurso habilitado.

### - Uso do HTTPS
Em aplicações progressivas o uso do protocolo HTTPS é obrigatório, pois apesar de não haver trafego de dados entre o front-end e o back-end, no primeiro acesso é possivel que haja um man-in-the-middle que coloque em risco dados da aplicação.

### - Redirecionamento para o HTTPS
Há varias alternativas para cumprir este requisito, mas a aplicação deve ter esta garantia de que todo o conteudo será acessado por este protocolo.

### - Carregar rapidamente em 3G
A aplicação deve rodar em velocidade inferior a 10 segundos de resposta mesmo usando dados moveis.

### - Vontade do usuario
O usuario, sobretudo usuarios mobile, devem ser sempre os unicos responsaveis pelo veredido de instalações de aplicações.

### - Splash screen
A aplicação deve exibir	uma	página	intermediária	enquanto	a	aplicação	é	carregada

### - Barra	 de	 endereço	 do	 navegador	colorida
Deve-se	 colorir	 a	 barra	 de	 endereço	 com	 cor semelhante	à	do	site.

### - Metatag viewport
Podemos	melhorar	a	visualização	da página	 nos	 dispositivos	 mobile através da	tag		<meta>		de	nome		viewport aliada a designs responsivos e recursos adequados.

### - Redirecionamento correto

Layout Estatico para cada viweport: Alta qualidade, porem baixa manutenibilidade. Se feito de maneira correta, como descobrir com eficacia o dispositivo	utilizado	pelo	usuário, funciona!
Layout	Responsivo: 	Se auto-organizam	 de	 acordo	 com	 o	 tamanho	 da	 viewport!

### - Cross-browser
A aplicação deve suportar múltiplos navegadores.

### - Transições de paginas independetes de conexão
Aconselha-se neste requisito a criação de 	Single-Page	Application (SPA), ou seja, aplicações de UMA unica pagina que se molda para outras paginas com transições fluentes sem necessidade de dowload em toda transição e consequente demora. 

### - URL unica para cada pagina
As URLs da aplicação devem ser objetivas, claras, com nome amigaveis e unicas para cada pagina da aplicação.

### Criando Backlog (lista de requisitos) 

### Scrum 
Uma	 metodologia	 de	 gerenciamento	 e planejamento de	 projetos organizados	 em	 ciclos	 fixos	 (Sprints)	 com	 um	 objetivo claro	 para	 toda	 equipe participante. No gerenciamento Scrum é comum o uso dos termos (e das metodologias) histórias e épicos.

### História
Um requisito.

### Épicos
Conjunto de requisitos.







