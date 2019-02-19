# APLICAÇÕES PROGRESSIVAS

PWA: Progressive Web Apps, ou Aplicações Web Progressivas;  

O sentido de progressiva está associado a melhoria progressiva, isto é, proporcionar a aplicação ao maior número de pessoas possíveis. Ademais, esse fornecimento deve pautar a não restrição devido à tecnologia, ou seja, deverá ser compatível com todos aparelhos (smartphones, computadores etc) e softwares (browsers) com ou sem internet. 

## Requisitos
**Lighthouse:** ferramenta/extensão da Google que permite a geração de um relatório completo acerca das características de uma aplicação (performance, acessibilidade e progressividade);
É possível, desse modo, ter ciência dos pontos a resolver na aplicação web e assim aperfeiçoá-la.

**Service Worker (especificação do W3C):** execução continua de parte de um código JavaScript a fim de implementar recursos offline e organizar os caches dos arquivos estáticos.

**Resposta com status 200 mesmo offline:** significa sucesso na solicitação, pode ser obtida mesmo offiline a partir do Local Storage, Application Cache e IndexedDB respectivamente dados, arquivos e dados, em outras palavras, ao guardar os dados localmente.

**Fornecer um “plano b” caso o JavaScript esteja desabilitado ou não seja suportado** (a fim de evitar falhas de sistema, inconsistência de dados ou insegurança da aplicação).

**HTTPS:** protocolo HTTP + TLS (Transport Layer Security)

 - Atualização única dos dados (primeiro acesso) por segurança. Eles serão armazenados localmente, como supracitado.
 - Redirecionamento da porta 80 para 443 (mais segura) obrigatoriamente pelo servidor. O usuário pode tentar acessar pela 80, mas será redirecionado para 443através do servidor Nginx.  

**Velocidade:** a aplicação deve carregar em até 10s no 3G (3s já é considerado lento).

**Instalar aplicação:** e adequar (configurações de instalação, ícones).

**Splash Screen personalizada:** Página intermediária enquanto a aplicação é recarregada.

**Barra de navegação com cor de acordo com as cores do site**

**Utilizar a tag "<meta>":** aprimora a visualização das páginas nos dispositivos mobile. 

**Responsividade:** auto-organização das páginas com base no tamanho da tela.

**Adaptável a qualquer navegador**, independentemente da versão.

**As transições entre páginas devem ser eficientes:** o carregamento dos arquivos não deve comprometer a velocidade da experiência do usuário; sem reload ou redirect completo da página.

**Cada página deve ter uma URL:** bookmarkable; com nome amigável;

## Demais itens de avaliação

*Conceitos*
**História:** requisito.
**Épícos:** grupo de requisitos.
**Scrum:** framework de gerenciamento de projetos segmentado em períodos fixos, os *sprints*, com objetivo claro para todos os participantes. O detentor do projeto insere a lista de requisitos *(backlog)* e os inclui na sprint, habitualmente separada por histórias e épicos. 

**Histórias da PWA:** requsitos supracitados. 

**Aplicação: Be Happy With Me** tem por propósito "organizar e agendar gentilezas do usuário", por exemplo, abraços e apertos de mão. 

- Ele pode registrar gentilezas e ganhar experiência compatível
- A aplicação gera uma gentileza aleatória que terá o status de pendente até que o usuário a faça ou descarte-a. 
- Todas as gentilezas serão exibidas na página inicial do app

*Resumo do casos de uso*
- Novo usuário
- Nova gentileza
- Listar gentilezas
- Perfil do usuário

Os códigos React são reaproveitáveis, logo, é possível construir outras aplicações a partir dos mesmos códigos.

**Novo usuário**
- Arquivos estáticos serão baixados do servidor HTTPS (Nginx) para o dispositivo. Dados serão salvos no cache do navegador (permitindo posteriormente que as demais páginas possam ser acessadas). Caso a aplicação não encontre os dados do usuário, ele poderá se cadastrar.

//A tela será considerada um épico, os componentes formarão a *suíte* de componentes para toda a aplicação.

**O código completo está em: https://github.com/lgapontes/behappywith.me**

**Nova gentileza**
"Após salvar os dados do usuário, a aplicação criará automaticamente a primeira gentileza *agendada*." O usuário tem 24h para realizá-la ou descartá-la.

Toda gentileza tem um *destinatário*, o receptor. Há 6 tipos de destinatários:
- Pais
- Filhos
- Parceiros
- Pets
- Amigos
- Outros

A gentileza é o registro de ação realizada com alguém. Existem 7 tipos de gentileza:
- Zap
- Bom-dia
- Ligação
- Aperto de mãos
- Abraço
- Doce
- Presente 

**Listar gentilezas**
Exibe as gentilezas agendadas ou realizadas ordenadas por data mais recente. As realizadas estarão resolvidas e as agendadas possuirão um botão de "confirmação" ou "descarte". 

**Perfil do usuário**
Exibe o nome, avatar, total de gentilezas, atrasos, gentilezas descartadas e a média de gentilezas diárias.

*Nos capítulos posteriores se avançará na resolução do backlog, com fundamentação para escolha e uso dos frameworks necessários.*
