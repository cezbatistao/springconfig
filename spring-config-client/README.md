# spring-config-client

O segundo projeto conecta na máquina server [spring-config-server](https://github.com/cezbatistao/springconfig/tree/master/spring-config-server) que então lê as variáveis de acordo com
ambiente(profile) informado.

Para rodar: 
`
mvn spring-boot:run [-Dspring.profiles.active=development]
`

o parametro entre colchetes é opcional, por padrão é utilizado: __default__