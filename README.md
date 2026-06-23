# 📘 Caderno Temático: Guia de Estudos para Programação Backend Java, Frameworks e IA
## 1. Contexto e Objetivos

**Contexto:**

O mercado de desenvolvimento Backend com Java é um dos mais consolidados e exigentes do mundo corporativo. Com a evolução constante do ecossistema, não basta apenas conhecer a sintaxe da linguagem. O desenvolvedor moderno precisa dominar frameworks de mercado (especialmente o Spring Boot), entender arquiteturas distribuídas (Microsserviços) e, mais recentemente, saber utilizar a Inteligência Artificial (IA) como ferramenta de pair programming, documentação e aceleração de produtividade. Este caderno temático centraliza os conhecimentos essenciais para navegar nesse cenário competitivo.

**Objetivos de Estudo:**

- Mapear a Trilha de Aprendizado: Definir uma rota clara desde os fundamentos do Java (POO) até tecnologias avançadas como Spring Cloud.

- Preparação para o Mercado: Levantar os conceitos arquiteturais e padrões de projetos mais cobrados em entrevistas técnicas.

- Integração com IA: Explorar como ferramentas generativas (como o NotebookLM) podem ser utilizadas para revisar conceitos complexos e simular sabatinas técnicas.

- Curadoria de Materiais: Centralizar fontes confiáveis e gratuitas para consulta contínua.

## 2. Curadoria de Fontes (Textos e PDFs para o NotebookLM)
As fontes abaixo são abertas, gratuitas e consideradas referências na comunidade. Elas devem ser adicionadas como base de conhecimento no seu NotebookLM:

**1. Documentação Oficial da Oracle (The Java™ Tutorials)**

- Guia definitivo sobre os fundamentos da linguagem, sintaxe e bibliotecas padrão.

- Link: [https://docs.oracle.com/javase/tutorial/](https://docs.oracle.com/javase/tutorial/)

**2. Apostila Aberta: Java e Orientação a Objetos (Caelum/Alura)**

- Um dos materiais em português mais tradicionais e completos para consolidar a base de Programação Orientada a Objetos.

- Link: [https://www.caelum.com.br/apostila-java-orientacao-objetos](https://www.caelum.com.br/apostila-java-orientacao-objetos)

**3. Refactoring.Guru: Padrões de Projeto (Design Patterns)**

- Catálogo ilustrado em português explicando os principais padrões de projeto de software, com exemplos de código em Java.

- Link: [https://refactoring.guru/pt-br/design-patterns/java](https://refactoring.guru/pt-br/design-patterns/java)

**4. Spring Boot Reference Documentation**

- A documentação oficial do framework mais utilizado no mercado Java para criação de APIs e Microsserviços.

- Link: [https://docs.spring.io/spring-boot/docs/current/reference/html/](https://docs.spring.io/spring-boot/docs/current/reference/html/)

**5. Guia de Arquitetura de Microsserviços (Microsoft Azure)**

- Material textual denso e excelente para entender as vantagens, desafios e padrões (como API Gateway e Service Discovery) de arquiteturas distribuídas.

- Link: [https://learn.microsoft.com/pt-br/azure/architecture/guide/architecture-styles/microservices](https://learn.microsoft.com/pt-br/azure/architecture/guide/architecture-styles/microservices)

## 3. Recomendações de Vídeos (Panorama de Mercado e Portfólio)
Vídeos de profissionais renomados para complementar o estudo com visão de carreira e prática de projetos:

**I. "Roadmap para se tornar um Desenvolvedor Java Backend" - Fernanda Kipper (KipperDev)**

- Aborda exatamente o que estudar e em qual ordem para ser contratado hoje.

**II. "Mercado de Trabalho para Programador Java" - Michelli Brito**

- Visão realista sobre salários, exigências das empresas e o domínio do Spring Boot.

**III. "Como construir um Portfólio Backend que chama a atenção" - Giuliana Bezerra**

- Dicas práticas de projetos que fogem do simples "CRUD" e impressionam recrutadores.

**IV. "Microsserviços na Prática com Spring Boot" - DevDojo (Maratona Spring)**

- Série essencial para entender a construção prática de serviços escaláveis.

**V. "Inteligência Artificial no dia a dia do Desenvolvedor" - Filipe Deschamps**

- Como utilizar IA generativa (Copilot, ChatGPT, Gemini) para acelerar a escrita de código sem perder os fundamentos.

## 4. Miniguia de Estudo (Resumos Estruturados)
**O que estudar para ser um desenvolvedor Java e por quê?**
- Fundamentos Sólidos (Java Core): Entender a fundo a JVM, Collections, Streams API e manipulação de exceções. O mercado não tolera falhas conceituais básicas.

- Spring Boot: É o padrão absoluto da indústria. Estude porque ele reduz o tempo de configuração e traz dezenas de ferramentas prontas (Spring Data JPA, Spring Security).

- Banco de Dados (Relacional e NoSQL): Toda aplicação precisa salvar dados. Domine SQL (PostgreSQL/MySQL) e entenda onde encaixar bancos não relacionais.

- Testes Automatizados: Escrever código que testa o seu código (JUnit, Mockito). É um diferencial gigantesco para vagas de nível Pleno.

- IA Generativa: Ferramentas para gerar boilerplate (códigos repetitivos), escrever documentação e explicar stack traces de erros complexos.

**Conceitos para dominar em Entrevistas**
- Princípios SOLID: A base de um código limpo e de fácil manutenção.

- Injeção de Dependências: Como o Spring gerencia o ciclo de vida dos objetos (Inversion of Control).

- REST e Maturidade de Richardson: Como projetar uma API seguindo os padrões HTTP corretos (verbos, status codes).

- Escalabilidade: A diferença entre escalar verticalmente (mais hardware) e horizontalmente (mais instâncias, Microsserviços).

**Tecnologias e Frameworks**
- Linguagem: Java 17 ou 21 (versões LTS).

- Framework Web: Spring Boot 3.x (Spring Web MVC, Spring Cloud).

- Ferramentas de Build: Maven ou Gradle.

- Infraestrutura Básica: Docker (para containerização) e Git (versionamento).

## 5. Glossário de Conceitos Chave
**Conceitos da Linguagem e POO:**

- Encapsulamento: Esconder os detalhes internos de funcionamento de uma classe, expondo apenas métodos públicos seguros (getters/setters).

- Polimorfismo: A capacidade de um objeto se comportar de múltiplas formas. Permite tratar diferentes tipos de objetos através de uma interface comum.

- Record: Introduzido nas versões recentes do Java, é uma classe especial utilizada puramente para transportar dados (DTOs) de forma imutável e com menos verbosidade.

- Stream API: Recurso funcional do Java para processar coleções de dados de forma declarativa (filtrar, mapear, somar) sem necessidade de loops complexos.

**Padrões de Projeto e Arquitetura:**

- Singleton: Padrão que garante que uma classe tenha apenas uma única instância durante toda a execução da aplicação (muito usado em configurações e conexões de banco).

- DTO (Data Transfer Object): Um objeto simples usado para carregar dados entre processos, evitando expor a entidade real do banco de dados diretamente para o usuário.

- API Gateway: O padrão arquitetural onde um único servidor atua como "porta de entrada" (recepcionista) para todos os microsserviços do seu sistema.

- Service Discovery: Ferramenta (como o Netflix Eureka) que atua como uma "lista telefônica" dinâmica, permitindo que microsserviços encontrem uns aos outros sem precisar saber o IP fixo de cada um.

## 6. Engenharia de Prompts (Reutilizáveis para o NotebookLM)
Documentação dos testes de extração de conhecimento da IA. Utilize esses prompts na sua base de documentos para revisar matérias antes de entrevistas.

**Prompt 1: Sabatina de POO**

`"Aja como um recrutador sênior de Java. Faça-me 3 perguntas de nível intermediário sobre Programação Orientada a Objetos com base nos documentos que eu anexei. Após eu responder, corrija minhas falhas e aponte trechos da documentação que eu deveria revisar."`

**Prompt 2: Tradução de Complexidade (Design Patterns)**

`"Estou com dificuldade para entender o padrão de projeto 'Factory Method'. Utilize uma analogia do mundo real (fora da programação) para me explicar esse conceito. Em seguida, mostre um pequeno exemplo prático em Java focado no ecossistema Spring Boot."`

**Prompt 3: Troubleshooting de Erros (Microsserviços)**

`"Estou criando uma arquitetura de microsserviços e recebi um erro '404 Not Found' ao tentar acessar meu serviço de produtos através do API Gateway. Com base nos guias de arquitetura anexados, liste as 3 causas mais prováveis para esse erro envolvendo o roteamento do Gateway e o registro no Service Discovery."`

**Prompt 4: Resumo Ativo de Frameworks**

`"Crie uma tabela comparativa com as vantagens e desvantagens de utilizar uma arquitetura Monolítica versus uma arquitetura de Microsserviços utilizando Spring Cloud. Inclua na tabela: complexidade de deploy, facilidade de testes, e escalabilidade de banco de dados."`
