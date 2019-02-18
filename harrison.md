
# Resumo
## Info
**Aluno** : Harrison Kelven Soares De Lima


**Livro** : Progressive Web App
## Objetivo
- Resumir o 1º capitulo do livro

## Meu Resumo

## Progressive Web App

PWA é um acrônimo para Progressive Web Apps, ou Aplicações Web Progressivas. No qual a palavra progressive tem como ideia de objetivo alcançar o maior número de pessoas, como por exemplo deixar acessível as plataformas tanto para dispositivos móveis como para microcomputadores. O PWA também pode ser conceituado como uma aplicação na qual o usuário não terá restrições tecnológicas. 
Umas das restrições é o uso da internet ou não nas aplicações, ou também como já foi dito, o fator acessibilidade tanto para microcomputadores quanto para dispositivos móveis. Porém, além da acessibilidade, vamos citar alguns requisitos que toda aplicação progressiva precisa ter, para que essa demonstração seja apresentada de maneira simples e fácil, podemos separar esses requisitos em duas partes, uma que trata de requisitos da parte de "Back-end" e outra da parte aparente da PWA que seria o "front-end". Vale lembrar que esta divisão não é extremamente correta se for levado em consideração todos os aspectos em si, porém para um entendimento geral a organização serve como um bom resumo e quebra-galho.

## Back-end

- O uso da ferramenta Lighthouse, que gera relatorios a respeito das caracteristicas presentes da PWA.
- Fazer o uso do Service Work, que se trata de uma ferramenta da W3C que permite implementar recursos offline por meio da organização e armazenamento de cache de arquivos, além de permitir um fator importante que pe o retorno do código 200 que significa sucesso nas solicitações de protocolo HTTP, essas solicitações são uma peça importante levando em conta que necessitamos fazer a simulações dessas solicitações por meio do Service Worker pra trabalharmos offline.
- Garantir que a PWA possua uma resposta programada caso o JavaScript seja desailitado de alguma forma, pois isso impedirá que ocorra problemas futuros como o desativamento do mesmo provindo de usuários mal intencionados.
- A aplicação deve estar disponível para interação do usuário em um tempo abaixo de 10 segundos, isso se não levarmos em conta alguns estudos que indica que quando a página demora mais que 3 segundos para carregar, já é considerada lenta pelos usuários.

## Front-end

- O usuário deverá se questionado se deseja instalar a aplicação.
- Quando a aplicação se encontrar funcionando, deverá haver um ícone na área de trabalho que dá acesso a página, fazendo com que o usuário a ultilize como um aplicativo nativo.
- Deverá possuir uma splash screen, termo que tem uma origem nos aplicativos de desktop, e que se resumem em uma imagem que na maioria das vezes possui a logotipo dos criadores da aplicação e mostrando ao usuário que o processo de carregamento está acontecendo.
- Um dos itens que o LightHouse verifica, é a cor da barra de endereço do navegador, se está de acordo com o restante das cores do site, esse item tem uma relevância.
- Implementar a tag Viewport que melhora a visualização da página em dispositivos mobile.
- Redimensionamento do conteúdo das páginas de maneira correta, isso se torna mais fácil se usar ferramentas que fazem esse redimensionamento através do tamanho da Viewport, como o CSS e o @media queries.
- A aplicação deve ser Cross-browser, ou seja, ser compatível com vários navegadores.
- As transições de páginas devem manter a velocidade indepente da conexão, uma maneira simples de fazer isso é com a utilização de SPA(Single-page application), onde as transições ocorrem de uma página para outra sem precisar refazer o donwload dos conteúdos dela, uma vez que acontece apenas uma ocultação e exibição de divs ou conteúdo que são baixados assim que o primeiro load na página é feito, e apenas é mostrado quando pedido a transição pelo usuário.
- O site deverá ter url separadas para cada página, assim fica mais fácil ser adicionada aos favoritos.

## Backlog

Além das características que toda PWA precisa ter para passar na varredura de testes do lighthouse, há também outras características de performance, boas práticas, acessibilidade e usuabilidade, porém podemos simplificar essa parte, dizendo que boa parte das coisas que são requisitadas nas PWAs são seguidas até o passo final, nas regras de negocio, e impulsionamento de resultados como no carregamento de páginas, download de arquivos, responsividade correta garantindo que o usuário não se perca e coisas parecidas que contribuem para uma boa experiência do usuário.

## Considerações finais do resumo

Bem, podemos explicar de forma resumida o primeiro capitulo do livro "Progressive Web App" demonstrando o assunto de maior predominância nessa parte de inicio do livro, quanto ao backlog, a explicação ficaria mais fácil ultilizando as imagens disponibilizadas no livro, então se não quisermos estender tanto o resumo dessa parte, uma pequena introdução ao tema se torna eficiente.




