# Digital Innovation One: Expert class
## Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot

Projeto da Live coding ministrada por Rodrigo Peleias (rpeleias) do desenvolvimento de um pequeno sistema para o gerenciamento de pessoas de uma empresa através de uma API REST criada com o Spring Boot.

* Setup inicial de projeto com o Spring Boot Initialzr
* Criação de modelo de dados para o mapeamento de entidades em bancos de dados
* Desenvolvimento de operações de gerenciamento de usuários (CRUD).
* Relação de cada uma das operações acima com o padrão arquitetural REST.
* Desenvolvimento de testes unitários para validação das funcionalidades
* Implantação do sistema na nuvem através do Heroku

## Pré-requisitos
* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.

## Executar projeto
```shell
mvn spring-boot:run 
```

### Visualização da execução do projeto
Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:
(Recomendo utilizar o Postman)
```
http://localhost:8080/api/v1/people
```

### Acesso ao banco de dados h2database utilizado no projeto
```
http://localhost:8080/h2-console/
```


## Referências sobre tópicos da Live Coding:

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial do Spring Initialzr, para setup do projeto](https://start.spring.io/)
* [Site oficial do Heroku](https://www.heroku.com/)
* [Site oficial do GIT](https://git-scm.com/)
* [Site oficial do GitHub](http://github.com/)
* [Documentação oficial do Lombok](https://projectlombok.org/)
* [Documentação oficial do Map Struct](https://mapstruct.org/)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)

[Neste link](https://drive.google.com/file/d/1crVPOVl6ok2HeYjh3fjQuGQn2lDZVHrn/view?usp=sharing), seguem os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto da nossa sessão.


