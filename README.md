# ResumoApiRest



# Api REST e RESTFul

A API REST, também chamada de API RESTFul, é uma intefarce de programção de aplicações que está atrelado a arquitetura REST, permintindo que a interação com os serviços web RESTFul. REST é a singa para "Representational State Transfer", sendo no português: tansferência de estado representacional. REST é um conjunto de diretrizes que visa fornecer uma estrutura para a comunicação entre sistemas distribuídos. Essa arquitetura foi criada pelo cientista da computação Roy Fielding. Algo prático das API REST é que elas podem ser desenvolvidas usando praticamente qualquer linguagem de programação, oferecendo suporte a uma variedade de formatos de dados. Porém eles devem alinhar a seis princípios de design de REST logo abaixo, conhecidos como restrições de arquitetura:

- **Interface uniforme:** As solicitações da API para o mesmo recurso devem ser iguais, independente da origem da solicitação. A API de REST deve garantir que a mesma parte dos dados dados pertença a apenas um identificador de recurso uniforme, contendo todas as informações que o cliente precisa.

- **Desacoplamento do cliente-servidor:** Os aplicativos cliente e servidor devem ser independentes um do outro. A única informação que o aplicativo cliente deve receber é o URI do recurso solicitado. Assim, um aplicativo do servidor não deve modificar o aplicativo cliente, exceto exceto no caso de tranferência de dados solicitados via HTTP.
  
- **Sem estado definido:** Cada solicitação precisa incluir todas as informações necessárias para processá-lo. As API de REST não solicitam nenhuma sessão do lado do servidor. As aplicações do servidor não tem permissão para armazenar os dados solicitados pelo cliente.

- **Capacidade de armazenamento em cache:** Os recursos precisam ser armazenados em cache pelo cliente ou servidorr, assim quando for possível. Além disso, as respostas do servidor precisam conter informações das permissões de cache do recurso fornecido. Isso melhora o desempenho do cliente e a escalabilidade do servidor.

- **Arquitetura de sistema em camadas:** As chamadas e respostas passam por diferentes camadas. Assim, pode haver uma série de intermediários diferentes no meio da comunicação enre o cliente e o servidor, impedindo uma comunicação direta. As APIs de REST precisam ser projetadas para que nem o cliente e nem o servidor possam dizer a comunicação é realizada com o aplicativo final ou um intermediário.

- **Código sob demanda (opcional):** As APIs de REST geralmente enviam recursos estáticos, porém, pode acontecer que as respostas possam conter código executável (como applets Java). Nestes casos, o código deve ser executado somente sob demanda.

  
## Diferenças entre REST e RESTFul

APIs REST e RESTful são abordagens para projetar e desenvolver interfaces de programação web que seguindo os princípios da arquitetural REST.
APIs REST são baseadas em quatro conceitos principais:

- Utilização dos métodos HTTP, como GET, POST, PUT e DELETE, para realizar operações em recursos.
- Uso de URLs para identificar recursos específicos.
- Transferência de dados entre cliente e servidor em um formato padrão, como JSON ou XML.
- Manutenção do estado da aplicação no cliente, em vez de armazená-lo no servidor.

Já as APIs RESTful, são APIs que implementam os princípios REST. Seguindo as características das APIs REST e são consideradas uma implementação mais completa e rigorosa do modelo REST. Porém para ser considerado uma API RESTFul ela deve conter critérios adicionais da API REST, sendo ele:

- Interface uniforme: a API deve fornecer uma interface consistente e padronizada para o acesso e manipulação de recursos.
- Clientes sem estado: cada solicitação enviada pelo cliente para o servidor deve conter todas as informações necessárias, sem depender de nenhum contexto armazenado no servidor.
- Operações baseadas em recursos: as ações realizadas pela API devem ser orientadas a recursos identificados por URLs únicas.

Portanto, a diferença entre as APIs REST e APIs RESTFul, está no nível da implementação dos princípios REST. Enquanto as APIs REST implementam conceitos básicos da arquitetura REST, as APIs RESTFull implementam conceitos mais complexos da REST, sendo mais completas e restritas.


## HTTP verbs

O protocolo HTTP contém um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um algum recurso. Eles também são comumente referenciados como HTTP Verbs. Entre os métodos estão:

- GET

  O método GET solicita a representação de um recurso específico, retornando apenas dados.

- HEAD

  O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.

- POST

  O método POST é utilizado para submeter uma entidade a um recurso específico, causando uma mudança no estado do recurso ou efeitos colaterais no servidor.

- PUT

  O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

- DELETE

  O método DELETE remove um recurso específico.

- CONNECT

  O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.

- OPTIONS

  O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.

- TRACE

  O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.

- PATCH
  
  O método PATCH é utilizado para aplicar modificações parciais em um recurso.


## HTTP Status Code

Seu texto...

---

Autor do resumo: Nome Sobrenome - Matrícula
