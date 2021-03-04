# forumApi

Esse Sistema consiste de uma API do Fórum de Dúvidas da Alura, desenvolvido durante um dos Cursos de Spring Boot da Alura (www.alura.com.br).

Desenvolvido utilizando Spring Boot, o projeto foi concebido utilizando as melhores práticas em arquitetura de API java, sendo dividido nas seguintes camadas:

- Controller:  Classes de Endpoints, onde são recebidas as requisições dos usuários.
- DTO: Classes que montam o conteúdo e o formato das informações que serão trafegadas entre o Cliente e o Servidor, trazendo os seguintes benefícios.
   1) Recebimento e envio somente da informação necessária.
   2) Evitando o contato direto à camada de acesso ao Banco de Dados e seu contexto de persistência.
   3) Enviando respostas ao cliente em um formato padronizado e amigável.
- Repository: Camada de Acesso aos dados, padrão Repository do Spring Boot.
- Modelo: Classes de Entidades do Banco de Dados


