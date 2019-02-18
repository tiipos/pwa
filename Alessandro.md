# Resumo
## Info
**Aluno** : Alessandro da Silva Medeiros

**Livro** : Progressive Web app
## Objetivo
- resumir o 1° Capitulo do livro
## Meu resumo
Aplicações progressivas surgiram com a ideia de abranger a maior parte de usuarios possíveis, além disso, como o nome sugere ela estará sempre em melhoria. Um dos aspctos que mais chama a atenção nessa parte inicial é dizer que o usuairo terá acesso mesmo sem internet. Em seguida apresenta o conceito de mobile-first que consiste em desenvolver softwares focados aos dispositivos mobile, obviamente, sem ignorar os usuários de microcomputadores.

### Requisitos 
O tópico seguinte trata dos requisitos que devem ser atendidos por uma aplicação progressiva e cita a ferramenta Lighthouse, a qual gera um relatório das caracteristicas do programa.  Esta extensão é mantida pela google. A seguir os requisitos citados:

**Registrar um Service Worker** – Service Workeri se trata de uma especificação da W3C(World Wide Web Consortium) que permite implemantar ercursos offline em páginas web.

**Resposta com status 200 mesmo estando offline** – O status 200 se trata de um retorno de sucesso em sua solicitação, portanto o site deve retornar essa mensagem mesmo quando offline.

**Deve exibir conteúdo quando Javascript estiver desabilitado** - Se um Javascript é desabilitado, seja propositalmente ou não, isso gera conflitos e erros extremamente prejudiciais. Por issso a aplicação deve ter uma resposta pronta para esse tipo de situação.

**Usar HTTPS** – O protocolo é totalmente necessário pois mesmo que o contato entre front e back - end aconteça apenas uma vez ainda há risco de haver corrupção dos arquivos.
	
**Redirecionar HTTP para HTTPS** – Por oferecer mais segurança o HTTPS é a escolha lógica. 

**Carregamento rápido em 3G** – Nesse tópico é estipulado que o carregamento da página deve ser de no maximo 3 segundos.

**O usuário deve ser questionado  se dejeja instalar a aplicação** – Novamente seguindo as recomendações da W3C, o usuário sempre deve ser indagado sobre o download de um arquivo, principalmente em mobiles.
