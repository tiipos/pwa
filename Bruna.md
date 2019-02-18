#Resumo
##Info
**Aluno**[Bruna]
**Livro**:Progressive Web App
##Objetivo
  -Resumir o 1° capítulo do livro


##Meu resumo

*PWA -> Um acrônimo para Aplicações Web Progressiva
     -> Desenvolver	com	melhoria progressiva	 é	 um	 paradigma	 em	 que	 a	 aplicação	 deverá	 estar disponível	 para	 todos,	 
        sejam	 usuários	 de	 microcomputadores	 ou smartphones,	 com	 browsers	 atualizados	 ou	 obsoletos, 
        com conexão	à	internet	ou	não.
     -> Uma	 aplicação	 progressiva	 deve estar	disponível	até	mesmo	quando	o	usuário	estiver	offline.   


*1.1 REQUISITOS DE UMA APLICAÇÃO PROGRESSIVA*   
-> Uma ferramenta	chamada	Lighthouse	que	é	capaz	de	gerar	um	relatório completo	 das	 características	 de	 uma	 aplicação.

*Deve registrar um Service Worker -> Aplicvação W3C que perimite executar um trecho de código JavaScript.
                                  -> É possível implementar recursos offline.
                                  -> Um dos itens do relatório Lighthouse.
                                  

*Resposta	com	status	200	mesmo	estando	offline -> Uma	página	web	funciona	 sobre	 o	protocolo	HTTP,	 que,	por sua	 vez,	 
                                                   trabalha	 com	 vários	 status	 de	 retorno	 às	 solicitações	 dos browsers.
                                                -> O	retorno	de	código	200	significa	sucesso	na	solicitação.
                                                -> Isso	 pode	 ser	 realizado	 via	Local	 Storage	 (dados),	Application
                                                   Cache	(arquivos),	IndexedDB	(dados),	e	o	próprio	Service	Worker. Esse último
                                                   ajuda 
                                                
 *Deve	 exibir	 conteúdo	 quando	 o	 JavaScript	 estiver desabilitado -> Basicamente, quando o JavaScript for desabilitado deverá
                                                                           haver uma informação avisando o mesmo.
                                                                           
 *Usar HTTPS -> Uma	 aplicação	 progressiva	 não	 pode	 ter	 seus	 dados transmitidos	 em	 claro.
             -> O	 protocolo	 HTTPS	 é	 obrigatório.	
             -> No nosso	caso,	não	haverá	transmissão	de	dados	entre	o	front-end	e	o back-end.
             -> A	 única	 responsabilidade	 do	 back-end	 será	 prover arquivos	 estáticos	 que	 serão	 
             armazenados	 localmente	 no navegador.
             
*Todo	 conteúdo	 HTTP	 deve	 ser	 redirecionado	 para HTTPS -> Por	 padrão,	 o	 navegador	 do	 usuário
                                                                 (mobile	ou	desktop)	acessa	o	 servidor	web	pelo	protocolo	HTTP,
                                                                 que	 trabalha	 sob	 a	 porta	 80.	 
                                                              -> Ou	 seja,	 todos	 os	 arquivos disponibilizados	na	porta	80	do  
                                                                 servidor	serão	providos	via	HTTP.
                                                              -> Outra	 possibilidade	 é	 acessar	 o	 servidor	 web	 pelo   
                                                                 protocolo HTTPS,	 que	 nada	 mais	 é	 do	 que	 o	 próprio	 HTTP	 
                                                                 sobre	 o protocolo	 TLS	 (Transport	 Layer	 Security).	 Este	 é	 
                                                                 fornecido	 na porta	 443	 e	 basicamente	 estabelece	 um	 canal	                                                                    de	 comunicação criptografado	entre	o	navegador	e	o	servidor	web.	
                                                              -> Outra	 opção	 é	 configurar	 o	 servidor	 web	 para	 sempre
                                                                 redirecionar	as	solicitações	recebidas	na	porta	80	para	a	porta                                                                    443,	neste	 caso,	 obrigando	 o navegador	 a	 estabelecer um	 canal
                                                                 de comunicação	 seguro	através	 do	 protocolo	 HTTPS. 
                                                              -> Vamos	 publicar	 nossa	 aplicação	 progressiva	 por	 meio	 de	 um
                                                                 servidor	 web	 chamado	 Nginx	 (cuja	 pronúncia	 é	 enginex).	
                                                                 Ele possui	 vários	 recursos, inclusive	 o	 de	 redirecionar	 as	 
                                                                 mensagens HTTP	da	porta	80	para	a	443, decorando-as	com	Transport	
                                                                 Layer Security	(TLS).                                                          
                                                                 	  
                                                                 	

*Deve carregar rapidamente no 3G -> A	aplicação deve	 estar	 disponível	 para	 interação	 do	 usuário	 em	 um	 tempo inferior	 a	 10	 segundos.

*O usuário deve ser	questionado se deseja	instalar a aplicação -> As atuais configurações do W3C favorecem essa possibilidade, principal
                                                                  para usuário mobile
                                                               -> "Veremos	 que,	 para	 isso	 funcionar,	 além	 das	 configurações de
                                                                  instalação	 por	 dispositivo,	 teremos	 de	 organizar	 ícones	 em
                                                                  tamanhos específicos	para	cada	caso."
 
 *Deve	 ser	 configurada	 com	 uma	 splash	 screen personalizada -> O	 termo	 splash	 screen	 (tela	 de	 abertura) tem	 origem	                                                                          nos aplicativos	desktop.
                                                                      -> Uma	pequena	tela	de	inicialização	com o	logotipo	é	exibida	                                                                          enquanto	o	software	é	carregado.
                                                                      -> Exibir	uma	página	intermediária	enquanto	a	aplicação	é
                                                                         carregada.
                                                                         
 *Colorir	 a	 barra	 de	 endereço	 do	 navegador	 com	 as cores	do	site -> Deve-se	 colorir	 a	 barra	 de	 endereço	 com	 cor
semelhante	à	do	site.                  
                                                                      
 * Implementar	a	metatag	viewport -> A	tag		<meta>		de	nome		viewport		melhora	a	visualização	da página	 nos	 dispositivos	                                         mobile.
                                   -> Quanto	 menor	 a	 tela	 do	 dispositivo, menor	será	a	viewport.
                                   
*Redimensionar	o	conteúdo	da	página	corretamente -> Duas formas de construir uma aplicação viewport: layouts estáticos(organizados
                                                        especificamente	para	os	dispositivos),	ou	layouts	responsivos.
                                                     -> layouts estáticos: oferece	 resultados	 de	 alta qualidade, mas	 possui	 baixa	                                                      manutenibilidade. Vai depener do aparelho que o usuário estiver usando. 
                                                     -> O protocolo HTTP possui um cabeçalho com a informação do User-Agent; por	meio	                                                         dessa	 propriedade,	 podemos	 descobrir	 se	 o	usuário está	 utilizando	 um	                                                       celular,	 um	 tablet	 ou	 um	 computador.
                                                     -> @media	queries	é	um	trecho	do	CSS	que	permite	alterar	o estilo	 de	 acordo	                                                         com	 o	 tamanho	 da	 viewport.
                                                     -> layouts	responsivos deixa o cite mais organizado.
                                                     
*O	site	deve	ser	cross-browser -> Para	 atender	 o	maior	 número	 de	 usuários	 possíveis,	devemos
                                     nos	 esforçar	 para	 tornar	 nosso	 código	 compatível	 com	 vários
                                     navegadores.	Por	sorte	nossa,	a	maioria	dos	frameworks	CSS	atuais
                                     já	 resolvem	esse	problema.	Entretanto,	 se	utilizarmos	um	 recurso                  
                                     restrito	 para	 os	 browsers	 mais	 modernos,	 podemos	 criar	 uma               
                                     página	do	 tipo	“Desculpe-nos,	mas	 seu	browser	não	é	compatível com	nosso	 site!”.
                                     
*As	transições	entre	páginas	não	devem	ser	sensíveis	à velocidade	de	conexão -> DOM o  acrônimo	original em	 inglês	
                                                                                   é	 Document	 Object	 Model	 (Modelo	 de	 Objeto	                                                                                      de Documento) 
                                                                                -> DOM	é	uma	estrutura	de	dados	que organiza	 os	                                                                                         elementos HTML	 em	 uma	 árvore.
                                                                                -> Cada	 nó	 desta árvore, mantem	 informações	 sobre	                                                                                    sua	 posição	 na estrutura e 	atributos	e	métodos	                                                                                    para	usufruto	do	navegador
                                                                                -> Mas o DOM pode falhar e ser muito lento para carregar
                                                                                   algumas coisas para isso usa-se o Single-Page                                                                                            Application (SPA).
                                                                                -> SPA - Uma	aplicação	de	única	página não significa
	 	                                                                               literalmente	 que	 ela	deve	 ter	 uma	 única	                                                                                      página.	 Ela pode	 ter	 quantas páginas	                                                                                              precisarmos. A	 diferença	 está	 no	 que ocorre
	                                                                                 na	transição:	as	páginas	não	precisam	ser                                                                                            recarregadas.  
                                                                                -> A	transição	entre	as	páginas	deve	ser	transparente                                                                                    aos	usuários.
                                                                                
*Cada	página	deve	ter	uma	URL -> O	 termo	 técnico	para	essa	característica	é	bookmarkable (não existe tradução).
                                -> Boookmarkable	 é	 aquela que	 pode	 ser	 acessada	 por	 uma	 URL	 única.
                                -> Em	aplicações	não-SPA,	cujas	 transições	de	páginas	são	feitas inteiramente,	esse	fator vem	
	                                 praticamente	de	graça	–	é	necessário apenas	definir	boas	URLs.
                                -> Em	uma	SPA,	todavia,	como	o	usuário fará	a	 transição	entre	as	views	(páginas)	sem	recarregar,                                    há	maior complexidade	em	resolver	este	requisito. 
                                
*1.2 CRIANDO NOSSO BACKLOG*  
*História da PWA -> Service Worker; Status 200; JavaScript desabilitado, Usar HTTPS; Redirecionar HTTP para HTTPS; Carregamento em 3G;
                    Instalar Aplicação; Splash screen; Colorir barra de endereço; Metatag de initial-scale;Uso de @media(redimensionar);
                    Cross-Brower;Transições das páginas; URL bookmarkable
                    
*Visão	geral	da	aplicação -> Aplicativo de gentileza: você se cadastra, tem, uma gentileza para cumprir, você cumpre e despois de 
                               19h os desenvolvedores atualizam.

 
*Novo	usuário -> Criando um novo usuário
              -> Na	primeira	vez	que	um	usuário	acessar	a	aplicação,	 todos	os arquivos	estáticos	serão	baixados	do	servidor HTTPS
	               (Nginx)	para o	 dispositivo.
             -> Todos	 os	 dados	 do	 usuário	 e	 das	 gentilezas	 serão	 salvos localmente,	 no	 cache do	 navegador.
             -> Protótipo	de	baixa	fidelidade.
	 
    
 *Demais funcionalidades -> Após	 salvar	 os	 dados	 do	 usuário,	 a	 aplicação	 criará automaticamente	 a	 primeira	gentileza
                            agendada.
                         -> A	aplicação	criará	gentilezas	agendadas. 
                         -> O	sistema terá	 sete	 tipos	 de	 gentileza,	 e	 haverá	 uma	 imagem	 representativa para	cada	uma	                                 delas.
                         -> O	usuário	 poderá registrar	uma	gentileza	realizada.
                         -> A	 lista	 de	 gentilezas	 exibirá	 as	 gentilezas,	 agendadas	 ou realizadas,	ordenadas	da	mais	                                   recente	para	a	mais	antiga.
                         -> Gentilezas	 criadas	 pelo	 usuário	 já estarão	automaticamente	resolvidas. As	demais	vão	oferecer	                                 botões de	 confirmação	 ou	 descarte	 na	 lista	 de	 gentilezas.	
                         -> A	última	tela	trata	da	exibição	consolidada	do	perfil	do	usuário da	aplicação.Esta	 tela	 exibe	 o	                          nome,	 o	 avatar	 e	 a	 experiência	 do	 usuário.
                         -> Como	 resultado	consolidado,	 são	exibidos	o	 total	de	gentilezas,	o total	 de	 atrasos,	 o	 total	                             de	 gentilezas	 descartadas,	 e	 a	 média	 de gentilezas	por	dia.


*Conclusão ->A parte da conclusão serve mais para dizer, de forma extremamente resumida, o que o capítulo trata.
                                                                                

	    
                             
                              


  
