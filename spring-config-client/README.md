# spring-config-client

O segundo projeto conecta na máquina server [spring-config-server](https://github.com/cezbatistao/springconfig/tree/master/spring-config-server) que então lê as variáveis de acordo com
ambiente(profile) informado.

Para rodar: 
`
mvn spring-boot:run [-Dspring.profiles.active=development]
`

o parametro entre colchetes é opcional, por padrão é utilizado: __default__


Para verificar que está no ar, basta acessar a seguinte url: [http://localhost:8080/configclient/env](http://localhost:8080/configclient/env)

É exibido as variáveis de ambiente da aplicação, no configService é possível verificar as variáveis que estão configuradas para o ambiente(profile) informado ao subir está aplicação

Para mais detalhes verificar artigo: [Externalizando configurações com Spring Cloud Config](https://cezbatistao.wordpress.com/2016/05/18/externalizando-configuracoes-com-spring-cloud/)
