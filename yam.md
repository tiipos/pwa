# Resumo

## Info

**Aluno:** Yam Gomes da Cunha

**Livro:** Progressive Web Apps

## Objetivo

- Resumo do primeiro capítulo do livro

## Meu resumo

O primeiro capítulo fala sobre as PWA (Progressive Web Apps), que são aplicações projetadas para qualquer usuário, independentemente da plataforma onde ele está utilizando, seja ela mobile ou computador, atualizada ou não e em todos os browsers. Há alguns requisitos que uma aplicação progressiva deve atender, e para verificá-los é sugerida a ferramenta Lighthouse, que gera relatórios baseados nas características. Alguns destes requisitos são:
- A aplicação deve funcionar mesmo sem conexão à internet, utilizando para tal Service Workers, Local Storage, Application Cache ou IndexedDB para dar resposta de status 200 às requisições realizadas;
- Exibir conteúdo mesmo com JavaScript desabilitado;
- Usar TLS e redirecionar todo o tráfego para HTTPS, para ter uma melhor segurança;
- Deve carregar rapidamente, mesmo em conexões lentas, como 3G. O Lighthouse define como bom o tempo de 10 segundos, mas o livro recomenda até 3 segundos;
- Caso instalável, a aplicação deve perguntar se o usuário deseja instalá-la;
- Utilizar `meta viewport`, `@media queries` e outras ferramentas para adaptar a aplicação à tela de qualquer dispositivo que a esteja acessando.
- Manter a transição entre telas ser a mesma, independentemente da velocidade de conexão, fazendo a aplicação uma SPA (Single Page Application);
- Fazer páginas *bookmarkable*.

A segunda parte do capítulo mostra um exemplo de criação de backlogs da aplicação, que deve utilizar de modelos conceituais e protótipos de telas de baixa fidelidade, focando apenas na funcionalidade. A aplicação é o *Be happy with me*, uma "agenda de gentilezas", e o texto mostra o processo de pensamento para a definição das responsabilidades de cada tela e também um protótipo da tela de registro.
