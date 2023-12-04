# API REST e RESTful

A arquitetura **REST** (Transferência de Estado Representacional) orienta a criação de APIs **RESTful**, que são interfaces de programação de aplicações para serviços web flexíveis. Essas APIs seguem um conjunto de regras que aderem às restrições do estilo arquitetônico REST. Ao utilizar métodos HTTP, as APIs REST operam em recursos identificados por URIs (Uniform Resource Identifiers), permitindo uma interação eficiente e desacoplada de tecnologias específicas. Essa abordagem proporciona uma metodologia simples e escalável para integrar sistemas distribuídos, tornando-se amplamente adotada na construção de serviços web.

## Diferenças entre REST e RESTFul

**REST** é um conjunto de princípios para sistemas de comunicação, enquanto **RESTful** refere-se à implementação desses princípios. Um serviço RESTful adere à arquitetura REST, usando URIs, verbos HTTP, e mantendo a ausência de estado. No contexto de REST, são princípios para o funcionamento ideal de serviços web, abrangendo comunicação, URIs, métodos HTTP (GET, POST, PUT, DELETE), e representação de dados (JSON ou XML). **RESTful** aplica esses princípios em uma API ou sistema específico, indicando aderência rigorosa durante o desenvolvimento.

## Verbos HTTP

Os **verbos HTTP**, incluindo GET, POST, PUT, DELETE, entre outros, desempenham um papel fundamental na indicação das ações a serem executadas em recursos específicos. Esses métodos são essenciais para as interações entre clientes e servidores na web, pois sinalizam claramente as operações a serem realizadas em um recurso identificado por um URI. Por exemplo, o `GET` é empregado para recuperar informações de um recurso específico, enquanto o `POST` é utilizado para enviar dados ao servidor, criando assim um novo recurso. O `PUT`, por sua vez, tem a finalidade de atualizar um recurso já existente no servidor, e o `DELETE` é responsável por remover um recurso específico do servidor. Esses métodos estabelecem a base para a comunicação eficiente entre sistemas distribuídos na web, permitindo a execução de diversas operações em recursos identificados de maneira única por URIs.

## Códigos de Status HTTP

Os **códigos de status HTTP** são retornados pelo servidor em resposta a uma requisição, comunicando o resultado da operação. Exemplos incluem o código `200 (OK)`, indicando uma requisição bem-sucedida; o `404 (Not Found)`, sinalizando que o recurso solicitado não foi encontrado; e o `500 (Internal Server Error)`, denotando um problema interno no servidor. Esses códigos são agrupados em categorias, abrangendo informativos, sucesso, redirecionamento, erro do cliente e erro do servidor. Cada código fornece uma indicação rápida sobre o estado da requisição, como sucesso, falha do cliente ou erro interno do servidor.

---

Thiago Pininga Tavares - 01525716