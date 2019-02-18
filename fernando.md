# Resumo
## inf
**aluno** : Fernando Brüch
**Livro** : Progressive Web App
## Objetivo
- resumir o 1° capitulo do livro
## Meu resumo

A sigla PWA que vem de Progressive Web Apps no português Aplicação Web Progressivas.
O PWA se resume basicamente em uma experiência onde o usuário poderá acessar qualquer aplicação sem restrição tecnológica alguma. Como exemplos dessas restrições temos a diferença dos dispoditivo sendo utilizado ou a falta de internet. As aplicações progessivas devem ser confortáveis e sempre seguras para o usuário, não dando nenhuma preferência a usuários que acessam pelo computador ou pelo celular.

No livro é citada uma ferrmenta do google no qual avalia e qualifica as aplicações progressivas que é o Lighthouse, no entanto alguns requisitos importantes não constam na avaliação do Lighthouse. Os requisitos das PWAs são:

-Service Worker
Permite executar trechos javaScript no nível do navegador, o que permite o que foi falado no começo do resumo que é utilização de recursos offline

-Simular status de sucesso na solicitação (status 200) mesmo estando offline

-Exibir conteúdo mesmo com o javascript desativado ou não suportado, isso é muito importante visto a comunicaão com o back-end para que não ocorra bugs.

-Uso de https, mesmo que não seja obrigatório, como dito no começo do resumo, a segurança do usuário é algo essencial em PWA, toda precaução é importante

-Redirecionar o conteúdo do protocolo http para o https, o protocolo https estabelece uma comunicação criptografada, um dos jeitos de se fazer isso é configurar o servidor web para que redirecione as solicitações feitas na porta 80 (http) para a 443(https).

-Deve carregar rapidamente ao 3G, estudos dizem que o usuário poder perder o interesse após esperar apenas 3 segundos para a resposta de uma solicitação.

-O usurio deve ser questionado se deseja instalar a aplicação

-Deve ser configurada uma splash screen personalizada, ou seja, deve exibir o logotipo do app enquanto o software é inicializado, dessa forma o usuário sabe que existe um carregamento o que causa um conforto.

-Se deve implementar a metatag viewport, essa tag melhora a visualização da págino em dispositivos mobile.

-É importante redimensiorar o conteúdo das páginas de jeito correto independente do dispositivo utilizado, existem duas formas de fazer isso, a organização estática que tem alta qualidade porém manutenibilidade muito baixa já que teriam que ser feitas várias páginas para vários tamanhos de viewport. Também temos a organização responsiva, onde por meio de CSS e o uso de @media queries, a página se adequa 
de acordo com o tamanho do viewport.

-O site deve ser cross-browser, ou seja, deve ser compatível com qualquer navegador, sejam eles mais antigos ou modernos demais, como dito no começo do resumo, não deve haver restrição por tecnologias.

-Transições entre páginas não devem ser sensíveis à velocidade de conexão, a aplicação podem ter quantas páginas forem necessárias porém é pouco viável ter que baixar todas e renderizar o DOM em todas as transições, visto isso, a solução foi uma construção de uma Singe-Page Application (SPA) ou aplicação de única página. Com isso as transações entre páginas são fluentes e não é necessário refazer o download

-Cada página deve ter um URL, essas urls devem ser fáceis e amigaveis aos olhos do usuário para que faça sentido.
