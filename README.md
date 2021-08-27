## Aplicação simples com crud de tarefas e usuário

- Java 11
- Maven
- Spring Boot
- H2 bd
- Lombok
- ModelMapper
- Swagger

## Especificações:

- Controle de profile (dev)
- Crud para Usuarios
- Crud para Tarefas
- Controle de tarefas

## Packages:

## Config
	- MapperConfig = mapeamento de objetos,determinando automaticamente como um modelo de objeto mapeia para outro.
	- UpDataToBase = add valores na base com profile dev
	- SwaggerConfig = documentação (/mytasks/swagger-ui.html)
## Controller
	- Request = Objeto de entrada de dados 
	- Response = Objeto de saida de dados
	- Controllers = Recursos expostos da aplicação (crud)
## Exception
	- Exception = Tratamento de excessão 
## Model
	- Models = modelos de entidade (banco de dados)
## Repository
	- Repositories = comunicação com banco de dados
## Services
	- Services = regras de negocio da aplicação
