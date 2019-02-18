# resumo
## inf
**aluno** [nome]
**livro**: Progressive Web App
## Objetivo 
- resumir o 1º capitulo do livro 
## Meu resumo 

mark down (.md)
# h1
## h2 
### h3 


As aplicações PWA consistem em aplicações de melhoria progressiva, de modo a atender o maior número de pessoas possível. Tratam da experiencia do usuário com em uma aplicação; não está ligada a versões de linguagem, mas sobre a forma com que uma página torna-se disponivel para o usuário. 
Uma aplicação PWA tem como um de seus fundamentos estar disponivel para todos, seja qual for o navegador, dispositivo, ou até condições de acesso a internet. 
Posto isso, uma aplicaçõ PWA conta com alguns requisitos dos quais alguns serão listados abaixo:

1. Service worker
Consiste, basicamente, em uma especificação da WC3 que permite executar um trecho de código javascript continuamente no nível do navegador. 

2. Resposta com status 200 mesmo estando offline
Esse requisito consiste na resposta da página ao protocolo HTTP mesmo estando offline. 

3. Deve exibir um  conteúdo com javascript desabilitado
Essa funcionalidade consiste na execução de códigos javascript mesmo que essa linguagem esteja desabilitada ou não suportado.

4. Usar HTTPS: 
Essa funcionalidade é obrigatória, pois busca garantir a segurança no download de dados da aplicação. 

5. Todo conteúdo HTTP deve ser redirecionada para HTTPS
Essa funcionalidade se justifica pela citada anteriormente. Consiste basicamente em fazer com que um link direcionado inicialmente para a porta 80 seja direcionado 443. 

6. Deve carregar rapidamente no 3G 
Considerando que a aplicação deve ter bom funcionamento em vários aspectos,  de maneira que o tempo de carregamento deve ser inferior a 3 segundos. 

7. O usuário deve ser questionado da aplicação que quer instalar 

8. Deve ser configurada com	uma	splash screen personalizada

9. Colorir a barra de endereço do navegador 

10. Implementar a metatag viewport

11. Redimensionar o conteúdo da página corretamente 

12. O site deve ser cross-browser

13. Cada página deve ter uma URL 


7. As transições entre páginas devem ser sensíveis 
Essa funcionalidade atua no carregamento dos elementos HTML, dos quais são organizados através do DOM (Modelo de Objeto de Documento). Em curso normal, toda vez que uma página é carregada os elementos dos DOM são carregados novamente. Sendo assim, como uma aplicação PWA precisa funcionar em caso de excassez de internet, a aplicação deve se estruturar para que tal carregamento não precise acontecer. Posto isso, a maneira com que o livro aborda tal temática é mudando a apropriedade do CSS denominada display, no qual muda a visibilidade de elementos, de maneira que tal evento pode ser realizado a partir do clique de um botão, por exemplo. 


