# Progressive Web Apps

### PWA é uma abreviação para *Progressive Web Apps*, cuja ideia se resume em elaborar uma aplicação que atenda ao maior número de pessoas e funcione sobre todos os aspectos possíveis, sem nenhum tipo de restrição tecnológica.

**Aluno: Luan Henrique Gomes da Silva**

**Livro: Progressive Web Apps**

## Requisitos de uma aplicação progressiva

1. **Deve registrar um Service Worker**

    Através do uso do Javascript, executar trechos de códigos ao nível do navegador, tornando possível a implementação de recursos offline e a organização do cache dos arquivos estáticos da página.

2. **Resposta com status 200 mesmo estando offline**

    Tornar possível a simulação de requisitos de status 200, que para o seu funcionamento precisa estar online, estando offline, guardando os dados localmente via *Local Storage*, *Application Cache*, *IndexedDB* e *Service Worker*.

3. **Exibir conteúdo quando o javascript estiver desabilitado**

    Deve ter uma saída programada em casos de que o javascript possa estar desabilitado ou não suportado. Por exemplo, em casos que haja uso de javascript para formatar dados mas por algum motivo esses dados não sejam formatados.

4. **Usar HTTPS**

    Protocolo HTTPS obrigatório. Não haverá tráfego de dados após o primeiro carregamento da página, os arquivos serão arquivados localmente para que a partir do segundo carregamento não haja download de arquivos.

5. **Todo conteúdo HTTP deve ser redirecionado para HTTPS**

    Como o protocolo HTTPS possui uma camada de segurança chamada *Transport Layer Security* (TLS), o seu uso é mais seguro que o protocolo HTTṔ, sendo assim, é importante que haja a configuração do servidor para que ocorra o redirecionamento das solicitações recebidas na porta 80 (HTTP) para a porta 443 (HTTPS).

6. **Deve carregar rapidamente no 3G**

    Há estudos que indicam que um aplicativo que demora mais que 3 segundos é considerando lento pelos usuários, então é importante que a aplicação seja rápida até mesmo em conexões mais lentas como o 3G.

7. **O usuário deve ser questionado se deseja instalar a aplicação**

    Organização quando se trata das configurações de instalação, como ícones em tamanhos específicos para cada caso.

8. **Deve ser configurada com uma splash screen personalizada**

    Também conhecida como "Tela de Abertura", tem origem nos aplicativos desktop, é a tela intermediária enquanto a aplicação é carregada.

9. **Colorir a barra de endereço do navegador com as cores do site**

    Colorir a barra de endereço com a cor semelhante à do site.

10. **Implementar a metatag viewport**

    Através da tag <meta> melhorar a vizualização da página, para que ela se adeque tanto a telas maiores (desktops) quanto menores (mobile).

11. **Redimensionar o conteúdo da página corretamente**

    Há duas maneiras de construir uma aplicação compatível com diferentes tamanhos de tela, utilizando layouts estáticos e layouts responsivos.
    Seguindo as boas práticas, o melhor a se fazer é utilizar layouts responsivos, isso facilita na manutenção da aplicação, já que se fosse o caso utilizar um layout estático, seria necessária a criação de dois sites para a mesma aplicação (um site para mobile e um para desktops).

12. **O site deve ser cross-broswer**

    Para que a aplicação funcione devidamente em todos os navegadores, é importante que utilizemos recursos que sejam compatíveis com todos eles, abrindo mão de recursos mais modernos. 

13. **As transições entre páginas não devem ser sensíveis à velocidade de conexão**

    Para que não haja sempre um total recarregamento da página durante a navegação do usuário, uma alternativa é o uso de *Single-Page Applications* (SPA), que recarregará apenas aquilo que for necessário, como por exemplo, de uma página para outra apenas ser recarragado o conteúdo, mantendo-se tudo aquilo que for estático e presente em todas as páginas.

14. **Cada página deve ter uma URL**

    Conhecido pelo termo técnico *bookmarkable*, uma página *bookmarkable* pode ser acessada por uma URL única e é definida com um nome amigável ao usuário final.
    Por exemplo, um blog faz uma postagem sobre as melhores bandas de todos os tempos, o resultado seria: 
    https://blogderockqualquer.com/blog/best-bands-of-all-time/
