# resumoApiREST
## Api REST e RESTFul
**- O que é API REST?** <br>
  API REST, também chamada de API RESTful, é uma interface de programação de aplicações (API ou API web) em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTful. REST é a sigla em inglês para "Representational State Transfer", que em português significa tansferência de estado representacional. <br><br>
**- O que são APIs?** <br>
  Uma API é um conjunto de definições e protocolos usado no desenvolvimento e na integração de aplicações. Às vezes, APIs são descritas como um contrato entre um provedor e um usuário de informações, estabelecendo o conteúdo exigido pelo consumidor (a chamada) e o conteúdo exigido pelo produtor (a resposta). Por exemplo, o design da API de um serviço meteorológico pode especificar que o usuário forneça um CEP e o produtor responda em duas partes, a primeira contendo a temperatura mais elevada e a segunda com a temperatura mais baixa. <br> Em outras palavras, ao interagir com um computador ou sistema para recuperar informações ou executar uma função, a API ajudará a comunicar o que você quer ao sistema para que ele entenda e realize o que foi solicitado. <br><br>
**- O que significa REST?** <br>
REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas. Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação. O formato JSON é a linguagem de programação mais usada porque, apesar de seu nome, é independente de qualquer outra linguagem e pode ser lido por máquinas e humanos.  <br><br>
**- Implementação RESTFul** <br>
De forma resumida é preciso: Identificar os recursos desejados, como usuários ou produtos. Projetar URIs únicas para cada recurso, usando os métodos HTTP apropriados (GET, POST, PUT, DELETE). Escolher um formato de representação, como JSON. Clarificar o estado e as transições dos recursos. Incluir links nas representações para facilitar a descoberta de funcionalidades (HATEOAS). Cuidar do tratamento de erros com códigos de status adequados. Adicionar autenticação e autorização para segurança. Documentar de forma clara, abordando recursos, URIs, métodos e exemplos. Realizar testes extensivos para garantir o funcionamento adequado. Projetar a API considerando a escalabilidade. Implementar monitoramento para identificação de problemas de desempenho. Ajustar essas diretrizes conforme necessário para sua linguagem e framework específicos.

## Diferenças entre REST e RESTFul
REST (Representational State Transfer) refere-se a um estilo arquitetural que estabelece princípios e restrições para o design de serviços web. Em contrapartida, o termo "RESTful" é usado para descrever serviços que seguem esses princípios. Basicamente, enquanto REST define os princípios, RESTful é a aplicação prática desses princípios em um serviço específico. Quando um serviço web utiliza corretamente métodos HTTP, mantém statelessness, utiliza URIs significativas e fornece representações de recursos, ele é considerado RESTful. Portanto, no dia a dia, os termos REST e RESTful são frequentemente usados de forma intercambiável para descrever serviços web que aderem aos princípios da arquitetura REST.

## HTTP verbs
- Os principais usado para interações entre clientes e servidores na web são: <br><br>
  **GET:** O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.
  **HEAD:** O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.<br>
  **POST:** O método POST é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.<br>
  **PUT:** O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.<br>
  **DELETE:** O método DELETE remove um recurso específico.<br>
  **CONNECT:** O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.<br>
  **OPTIONS:** O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.<br>
  **TRACE:** O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.<br>
  **PATCH:** O método PATCH é utilizado para aplicar modificações parciais em um recurso.

## HTTP Status Code
- Os códigos de status HTTP são retornados pelo servidor em resposta a uma solicitação feita pelo cliente. Esses códigos indicam o resultado da solicitação e fornecem informações sobre o status da operação. Esses códigos de status são essenciais para entender o resultado de uma solicitação HTTP e diagnosticar problemas durante a comunicação cliente-servidor. Eles são agrupados em 5 grupos: <br><br>

**1xx (Informational):**
  - 100 Continue
  - 101 Switching Protocols
  - 102 Processing

**2xx (Success):**
  - 200 OK
  - 201 Created
  - 202 Accepted
  - 204 No Content
  - 205 Reset Content
  - 206 Partial Content

**3xx (Redirection):**
  - 300 Multiple Choices
  - 301 Moved Permanently
  - 302 Found
  - 303 See Other
  - 304 Not Modified
  - 307 Temporary Redirect
  - 308 Permanent Redirect

**4xx (Client Error):**
  - 400 Bad Request
  - 401 Unauthorized
  - 402 Payment Required
  - 403 Forbidden
  - 404 Not Found
  - 405 Method Not Allowed
  - 406 Not Acceptable
  - 407 Proxy Authentication Required
  - 408 Request Timeout
  - 409 Conflict
  - 410 Gone
  - 411 Length Required
  - 412 Precondition Failed
  - 413 Payload Too Large
  - 414 URI Too Long
  - 415 Unsupported Media Type
  - 416 Range Not Satisfiable
  - 417 Expectation Failed
  - 418 I'm a teapot
  - 421 Misdirected Request
  - 422 Unprocessable Entity
  - 429 Too Many Requests
  - 431 Request Header Fields Too Large
  - 451 Unavailable For Legal Reasons

**5xx (Server Error):**
  - 500 Internal Server Error
  - 501 Not Implemented
  - 502 Bad Gateway
  - 503 Service Unavailable
  - 504 Gateway Timeout
  - 505 HTTP Version Not Supported
  - 511 Network Authentication Required

 ---

Autor do resumo: Maísa Souza dos Santos - 01508744
