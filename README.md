# dev_app_my_tasks

Aplicação simples com crud de tarefas e usuário
Java 11
Maven
Spring Boot
H2
Lombok
ModelMapper
Swagger 
===============================================================
Especificações:
Controle de profile(dev)
Crud para Usuarios
Crud para Tarefas
===============================================================
Packages:

config
	- MapperConfig = mapeamento de objetos,determinando automaticamente como um modelo de objeto mapeia para outro.
	- UpDataToBase = add valores na base com profile dev
	- SwaggerConfig = documentação (/mytasks/swagger-ui.html)
controller
	- Request = Objeto de entrada de dados 
	- Response = Objeto de saida de dados
	- Controllers = Recursos expostos da aplicação (crud)
exception
	- Exception = Tratamento de excessão 
model
	- Models = modelos de entidade (banco de dados)
repository
	- Repositories = comunicação com banco de dados
services
	- Services = regras de negocio da aplicação


