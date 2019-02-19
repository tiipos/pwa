 # Progressive Web Apps
 
 ### PWA é um termo usado para denotar uma nova metodologia de desenvolvimento de software. Ao contrário dos tradicionais aplicativos, um Progressive Web App pode ser visto como uma evolução híbrida entre as páginas da web regulares (ou sites) e um aplicativo móvel.
 
 **Aluno: Rodrigo Cardoso**
 
 **Livro:  Progressive Web Apps**
 
 ## Alguns Requesitos
 
 **Deve	registrar	um	Service	Worker**
 
 Service	Worker	é	uma	função que	permite	executar um	 trecho	 de	 código	 JavaScript	 continuamente	 no navegador.	Por	 meio	 dele	 é	possível
implementar recursos	offline	e	organizar o	cache dos arquivos estáticos da	página	web.

**Resposta com status 200 mesmo estando offline**

O	retorno	de	código	200	significa	sucesso	na	solicitação. Uma	aplicação	progressiva	deve	
simular	tal	status	mesmo	estando offline. Isso acontece atraves de dados guardados de forma local

**Deve exibir conteúdo quando o JavaScript estiver desabilitado**

O programa deve ter outra alternativa caso o javascript fique desabilitado ou não seja suportado

**Usar	HTTPS**

O protocolo HTTPS é obrigatorio. Os arquivos são arquivados de forma local a partir do segundo carregamento 
para evitar download.

**Todo conteúdo HTTP	deve ser redirecionado para HTTPS**

É importante que haja a configuração do servidor para que ocorra o redirecionamento das solicitações recebidas na porta 80 (HTTP) para a porta 443 (HTTPS).

**Deve	carregar	rapidamente	no	3G**

A	aplicaçã deve	 estar	 disponível	 para	 interação	 do	 usuário	 em	 um	 tempo
inferior	 a	 10	 segundos.	Há	 estudos	 que indicam	que	uma	aplicação	que	demora	mais	do	que	3	segundos	já
é	 considerada	 lenta	 pelos	 usuários.

**Colorir	 a	 barra	 de	 endereço	 do	 navegador	 com	 as cores	do	site**

Apersar de ser um item de menor relevância, ele também faz parte dos requesitos. 
Basicamente,	 deve-se	 colorir	 a	 barra	 de	 endereço	 com	 cor
semelhante	à	do	site.	
