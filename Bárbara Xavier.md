#APLICAÇÕES PROGRESSIVAS#

PWA: Progressive Web Apps, ou Aplicações Web Progressivas;
O sentido de progressiva está associado a melhoria progressiva, isto é, proporcionar a aplicação ao maior número de pessoas possíveis. Ademais, esse fornecimento deve pautar a não restrição devido à tecnologia, ou seja, deverá ser compatível com todos aparelhos (smartphones, computadores etc) e softwares (browsers) com ou sem internet. 
Requisitos
Lighthouse: ferramenta/extensão da Google que permite a geração de um relatório completo acerca das características de uma aplicação (performance, acessibilidade e progressividade);
É possível, desse modo, ter ciência dos pontos a resolver na aplicação web e assim aperfeiçoá-la.
	Service Worker (especificação do W3C): execução continua de parte de um código JavaScript a fim de implementar recursos offline e organizar os caches dos arquivos estáticos.
	Resposta com status 200 mesmo offline: significa sucesso na solicitação, pode ser obtida mesmo offiline a partir do Local Storage, Application Cache e IndexedDB respectivamente dados, arquivos e dados, em outras palavras, ao guardar os dados localmente.
	Fornecer um “plano b” caso o JavaScript esteja desabilitado ou não seja suportado (a fim de evitar falhas de sistema, inconsistência de dados ou insegurança da aplicação).
	HTTPS: protocolo HTTP + TLS (Transport Layer Security)
a.	Atualização única dos dados (primeiro acesso) por segurança. Eles serão armazenados localmente, como supracitado.
b.	Redirecionamento da porta 80 para 443 (mais segura) obrigatoriamente pelo servidor. O usuário pode tentar acessar pela 80, mas será redirecionado para 443 – através do servidor Nginx.
 Velocidade: a aplicação deve carregar em até 10s no 3G (3s já é considerado lento).
