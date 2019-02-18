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


*REQUISITOS DE UMA APLICAÇÃO PROGRESSIVA*   
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
                                                              -> Ou	 seja,	 todos	 os	 arquivos disponibilizados	na	porta	80	do	servidor	
                                                                 serão	providos	via	HTTP.
                                                              -> Outra	 possibilidade	 é	 acessar	 o	 servidor	 web	 pelo	 protocolo
                                                                 HTTPS,	 que	 nada	 mais	 é	 do	 que	 o	 próprio	 HTTP	 sobre	 o
                                                                 protocolo	 TLS	 (Transport	 Layer	 Security).	 Este	 é	 fornecido	 na
                                                                 porta	 443	 e	 basicamente	 estabelece	 um	 canal	 de	 comunicação
                                                                 criptografado	entre	o	navegador	e	o	servidor	web.	
                                                              -> Outra	 opção	 é	 configurar	 o	 servidor	 web	 para	 sempre
                                                                 redirecionar	as	solicitações	recebidas	na	porta	80	para	a	porta	443,
                                                                 neste	 caso,	 obrigando	 o	 navegador	 a	 estabelecer	 um	 canal	 de
                                                                 comunicação	 seguro	 através	 do	 protocolo	 HTTPS. 
                                                              -> Vamos	 publicar	 nossa	 aplicação	 progressiva	 por	 meio	 de	 um
                                                                 servidor	 web	 chamado	 Nginx	 (cuja	 pronúncia	 é	 enginex).	 Ele
                                                                 possui	 vários	 recursos,	 inclusive	 o	 de	 redirecionar	 as	 mensagens
                                                                 HTTP	da	porta	80	para	a	443,	decorando-as	com	Transport	Layer Security	(TLS). 

*Deve carregar rapidamente no 3G -> A	aplicação deve	 estar	 disponível	 para	 interação	 do	 usuário	 em	 um	 tempo inferior	 a	 10	 segundos.

  
