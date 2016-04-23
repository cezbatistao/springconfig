# springconfig 

Projeto criado para explicar e explorar como funciona o spring-cloud-config utilizado para externalizar suas configurações,
as configurações ficam em um servidor git, normalmente github, e pode-se alterar as variaveis em **runtime** que elas são atualizadas pelas
aplicações.

* Veja primeiro [spring-config-server](https://github.com/cezbatistao/springconfig/tree/master/spring-config-server) app que lê as variáveis;
* Então [spring-config-client](https://github.com/cezbatistao/springconfig/tree/master/spring-config-client) app que disponibiliza as variárias de acordo com o ambiente(profile).