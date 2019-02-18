# Resumo   
## Info   
**Aluno**:Mateus Vitor Cavalcanti Rodrigues   

**Livro**:Progressive Web App   

## Objetivo
- Resumir o 1° cap. do livro
## Meu Resumo
# PWA: 
- A palavra vem da ideia de Progressive Enhancement ou melhoria progressiva que da a ideia de condicionar uma aplicação a atender o maximo de pessoas que for possivel, sob qualquer apescto. Não é um estudo direcionado aos dispositivos, navegadores, verses das linguagens HTML, CSS ou JS. Desenvolver com melhoria progressiva deve estar disponivel para todos e quaisquer usuarios, inclusive com conexão a internet ou não. O Texto afirma que o uso sem internet pode parecer loucura, mas, a ideia de construir progressivamente traz novos desafios ao desenvolvimento.   
# Requisitos de uma aplicação progressiva:   
- Mesmo estando offline, deve-se receber o retorno do código 200 que significa sucesso na solicitação. 
- Deve mostrar o conteúdo até mesmo quand oo javascript tiver desabilitado
- Usar o protocolo HTTPS é obrigatório pois não pode ter seus dados transmitidos em claro. Isso se da para evitar um "man-in-the-middle'" provendo arquivos falsos para capturar seus dados e enviá-los para um servidor na nuvem.
- Todo conteúdo HTTP deve ser redirecionado para HTTPS. O navegador do usuário acessa o servidor web pelo protocolo HTTP, que trabalha sob a porta 80. Ou	seja, todos os arquivos disponibilizados na porta 80 do servidor serão providos via	HTTP. O acesso a um servidor sem criptografia é o caso mais comum que ocorre quando um usuário digita o endereço sem explicitar o protocolo. Há outras formas mais incomuns como por exemplo configurar o servidor web para esmpre redirecionar as solicitações recebidas na porta 80 para a porta 443.
- Deve carregar rapidamente no 3G. Meta "three seconds and go".
- O usuário deve ser questionado se deseja instalar a aplicação
- Deve ser configurada com uma splash screen personalizada. A	ideia	é	simplesmente exibir uma	página intermediária	enquanto a	aplicação	é	carregada.
- Implementar	a	metatag	viewport. Viewport é a área visível do usuário em página da web. Quanto menor a tela do dispositivo, menor será a viewport.
- Página deve ser responsiva
- Deve haver compatibilidade com todos ou quase todos os navegadores (cross-browser).
- A transição das paginas não devem ser lentas independentemente da velocidade da internet. 
- Cada página deve ter uma URL, que é uma característica chamada bookmarkable, ou seja, é uma pagina que pode ser adicionada aos favoritos do navegador.
# Criando backlog
- A aplicação terá como principal objetivo organizar e agendar gentilezas do usuário. A aplicação deve eventualmente gerar uma gentileza aleatória que ficará pendente até o usuário realizá-la ou descartá-la. Essa é uma descrição bem abrangente. Não é necessario perder tempo com isso. Os componentes criados pelo react são altamente reaprovetáveis, o que torna o trabalho de desenvolvimento de telas demasiadamente repetitivo. o objetivo é fazer compreender a tecnologia necessaria para construir aplicações progressivas com o auxílio do framework React.
- Na primeira vez que um usuário acessar a aplicação, todos os arquivos estáticos serão baixados do servidor HTTPS para o dispositivo.
- Após salvar os dados do usuário, a aplicação criará automaticamente a primeira gentileza agendada. Diariamente a aplicação criará gentilezas agendadas. O que seria uma gentileza? se trata de um registro no tempo de uma ação realizada com alguem. O sistema terá sete tipo de gentilezas e haverá imagens representando cada uma delas.
- A lista de gentilezas exibirá gentilezas agendadas ou realizadas em ordem de cronologica. 
