
## Objetivo
Resumir o 1º capítulo do livro Progressive Web Apps
## Meu resumo 
### O conceito
Progressive Web Apps são aplicações cujo objetivo é atender todas as especificidades da experiência usuário-software. 
Essa finalidade perpassa pela não restrição tecnológica, seja de acesso à Internet, navegadores, resoluções de tela ou hardware.
### Os requisitos 
##### a) Deve registrar um Service Worker
Service	Worker	é	uma	especificação	W3C	que	permite	executar um	 trecho	 de	 código	 JavaScript	 continuamente	 no	 nível	 do navegador. Ele é uma das formas pelas quais	é possível implementar	 recursos	 offline	 e	 organizar	 o	 cache	 dos	 arquivos estáticos	da	página	web

##### b) Resposta com status 200 mesmo estando offline
Uma	página	web	funciona	 sobre	 o	protocolo	HTTP,	 que,	por sua	 vez,	 trabalha	 com	 vários	 status	 de	 retorno	 às	 solicitações	 dos browsers.	O	retorno	de	código	200	significa	sucesso	na	solicitação. Uma	aplicação	progressiva	deve	simular	tal	status	mesmo	estando offline.	Isso é possivel guardando localmente os dados.

##### c) Deve exibir conteúdo quando o JavaScript estiver desabilitado
 Uma	 PWA	 deve	 ter	 uma resposta	programada	para	casos	em	que	o	JavaScript	é	desabilitado ou	não	suportado,	mesmo	que	esta	seja uma	 tela	informando	que não	 é	 possível	 usar	 a	 aplicação.	 Este	 requisito	 é	 bem	 simples	 de resolver,	mas	quase	sempre	ignorado	pelos	desenvolvedores.

##### d) Usar	HTTPS
Uma	 aplicação	 progressiva	 não	 pode	 ter	 seus	 dados transmitidos	 em	 claro.	 O	 protocolo	 HTTPS	 é	 obrigatório.	 No nosso	caso,	não	haverá	transmissão	de	dados	entre	o	front-end	e	o back-end.	 A	 única	 responsabilidade	 do	 back-end	 será	 prover arquivos estáticos	 que	 serão	 armazenados	 localmente	 no navegador.	Após	isso,	não	haverá	acesso	remoto.

##### e) Usar	HTTPS Todo	 conteúdo	 HTTP	 deve	 ser	 redirecionado	 para HTTPS
Por	 padrão,	 o	 navegador	 do	 usuário
(mobile	ou	desktop)	acessa	o	 servidor	web	pelo	protocolo	HTTP,
que	 trabalha	 sob	 a	 porta	 80.	 Ou	 seja,	 todos	 os	 arquivos
disponibilizados	na	porta	80	do	servidor	serão	providos	via	HTTP.
O	acesso	a	um	servidor	sem	criptografia	é	o	caso	mais	comum,	que
ocorre	quando	um	usuário	apenas	digita	o	endereço	sem	explicitar
o	protocolo

##### f) Deve	carregar	rapidamente	no	3G
Significa	basicamente	que	a	aplicação
deve	 estar	 disponível	 para	 interação	 do	 usuário	 em	 um	 tempo
inferior	 a	 10	 segundos.	Trabalhar na meta "three	seconds	and	go"

##### g) O	 usuário	 deve	 ser	 questionado	 se	 deseja	 instalar	 a aplicação
As	 atuais	 especificações	 da	 W3C	 favorecem	 muito	 tal
possibilidade,	principalmente	quando	se	 trata	de	usuários	mobile.
Para	 isso	 funcionar,	 além	 das	 configurações	 de
instalação	 por	 dispositivo,	 teremos	 de	 organizar	 ícones	 em
tamanhos	específicos	para	cada	caso.	

##### h) Deve	 ser	 configurada	 com	 uma	 splash	 screen personalizada
O	 termo	 splash	 screen	 (tela	 de	 abertura)	 tem	 origem	 nos aplicativos	desktop,	em	que	uma	pequena	tela	de	inicialização	com o	logotipo	é	exibida	enquanto	o	software	é	carregado.	

##### i) Colorir	 a	 barra	 de	 endereço	 do	 navegador	 com	 ascores	do	site
Basicamente,	 deve-se	 colorir	 a	 barra	 de	 endereço	 com	 cor semelhante	à	do	site.	Resolveremos	isso	com	uma	estilização	básica da	página,	no	futuro. 

##### j) Implementar	a	metatag	viewport
A	tag		<meta>		de	nome		viewport		melhora	a	visualização	da página	 nos	 dispositivos	 mobile.	 Viewport	 é	 a	 área	 visível	 do usuário	 em	 página	 da	 web.	 Quanto	 menor	 a	 tela	 do	 dispositivo, menor	será	a	viewport. 

##### k) Redimensionar	o	conteúdo	da	página	corretamente
As	boas	práticas	apontam	para	a	construção	de	páginas	que	se auto-organizam	 de	 acordo	 com	 o	 tamanho	 da	 viewport, escondendo	 elementos	inapropriados,	 substituindo	 componentes, e	 ajustando	 o	 tamanho	 de	 imagens	 e	fontes.	 Isso	 tudo	 é	 possível com	a	disposição	correta	das	tags	HTML,	uma	boa	organização	das classes	CSS	e	do	uso	de	@media	queries.

##### l) O	site	deve	ser	cross-browser
Para	 atender	 o	maior	 número	 de	 usuários	 possíveis,	devemos nos	 esforçar	 para	 tornar	 nosso	 código	 compatível	 com	 vários navegadores.

##### m) As	transições	entre	páginas	não	devem	ser	sensíveis	à velocidade	de	conexão
A	transição	entre	as	páginas	deve	ser	transparente aos	usuários,	sem	o		reload		ou		redirect		completo	da	página. Como	 isso	 também	 implica	 em	 não	 baixar	 todos	 os	 arquivos novamente,	 teremos	maior	 perspectiva	 de	 performance	 em	 nossa aplicação.

##### n) Cada	página	deve	ter	uma	URL
Em	aplicações	não-SPA,	cujas	 transições	de	páginas	são	feitas inteiramente,	esse	fator	vem	praticamente	de	graça	–	é	necessário apenas	definir	boas	URLs.	Em	uma	SPA,	todavia,	como	o	usuário fará	a	 transição	entre	as	views	(páginas)	sem	recarregar,	há	maior complexidade	em	resolver	este	requisito.

