# Curso_WebService

Primeiros passos no mundo dos WebServices

## O que é Web service?

Primeiro, a teoria. Um Web service é um conjunto de métodos acedidos e invocados por outros programas utilizando tecnologias Web.

- o que é, como funciona, para que serve?

Segundo, a tradução. Um Web service é utilizado para transferir dados através de protocolos de comunicação para diferentes plataformas, independentemente das linguagens de programação utilizadas nessas plataformas.

 Os Web services funcionam com qualquer sistema operativo, plataforma de hardware ou linguagem de programação de suporte Web. Estes transmitem apenas informação, ou seja, não são aplicações Web que suportam páginas que podem ser acedidas por utilizadores através de navegadores Web.

Os Web services permitem reutilizar sistemas já existentes numa organização e acrescentar-lhes novas funcionalidades sem que seja necessário criar um sistema a partir do zero. Assim, é possível melhorar os sistemas já existentes, integrando mais informação e novas funcionalidades de forma simples e rápida.

### Web service: Como funciona?
 
Tendo em conta as operações disponíveis no Web service, a aplicação solicita uma dessas operações. O Web service efetua o processamento e envia os dados para a aplicação que requereu a operação.

A aplicação recebe os dados e faz a sua interpretação, convertendo-os para a sua linguagem própria.

### Se são linguagens diferentes, como conseguem comunicar?

É necessário uma linguagem intermédia que garanta a comunicação entre a linguagem do Web service e o sistema que faz o pedido ao Web service. Para tal, existem protocolos de comunicação como o **SOAP (Simple Object Access Protocol)** e o **REST (Representational State Transfer)**.

O protocolo *SOAP* utiliza **XML** para enviar mensagens e, geralmente, serve-se do protocolo **HTTP** para transportar os dados. Associado ao protocolo *SOAP* está o documento **WSDL (Web Service Definition Language)** que descreve a localização do Web service e as operações que dispõe. Além disso, fornece a informação necessária para que a comunicação entre sistemas seja possível.

O *REST* é um protocolo de comunicação mais recente que surgiu com o objetivo de simplificar o acesso aos Web services. Este baseia-se no protocolo HTTP e permite utilizar vários formatos para representação de dados, como **JSON** (um dos mais utilizados), *XML*, *RSS*, entre outros.

Assim, uma das grandes vantagens do REST é a sua flexibilidade, já que não limita os formatos de representação de dados. O protocolo REST é também utilizado quando a performance é importante, uma vez que é um protocolo ágil e com a capacidade de transmitir dados diretamente via protocolo HTTP.

### Quais os benefícios dos Web services?
 
A utilização de Web services traz vários benefícios tanto a nível tecnológico, como a nível do negócio. Seguem-se os mais relevantes:

– Integração de informação e sistemas: uma vez que o funcionamento do Web service necessita apenas de tecnologia XML/JSON e protocolos HTTP, a comunicação entre sistemas e aplicações é bastante simplificada. Com um Web service é possível trocar informação entre dois sistemas, sem necessidade de recolher informação detalhada sobre o funcionamento de cada sistema. Os Web services permitem ligar qualquer tipo de sistema, independentemente das plataformas (Windows, Linux, entre outras) e linguagens de programação (Java, Perl, Python, etc.) utilizadas.

– Reutilização de código: um Web service pode ser utilizado por várias plataformas com diferentes objetivos de negócio. O código do Web service é feito uma vez e pode ser utilizado vezes sem conta por diferentes aplicações.

– Redução do tempo de desenvolvimento: é mais rápido desenvolver com Web services, porque os sistemas não são totalmente construídos a partir do zero e facilmente são incluídas novas funcionalidades. O tempo de implementação de sistemas com a utilização de Web services é mais reduzido, sendo uma boa opção no desenvolvimento de software à medida.

– Maior segurança: o Web service evita que se comunique diretamente com a base de dados. Assim, a segurança do sistema que fornece os dados está salvaguardada.

– Redução de custos: Com a utilização de Web services não é necessário criar aplicações à medida para a integração de dados, algo que pode ser bastante caro. Os web services tiram partido de protocolos e da infraestrutura Web já existente na organização, requerendo por isso pouco investimento.

### Web service: uma solução prática

Numa organização coexistem várias aplicações que organizam e trocam dados, muitas vezes, de formas distintas. Assim, nem sempre garantem a comunicação entre sistemas. Por outro lado, é cada vez mais comum a necessidade de trocar dados entre diferentes sistemas, seja dentro de uma organização ou entre organizações.

Uma solução prática e de baixo custo para solucionar a incompatibilidade de sistemas e garantir a sua comunicação são os Web services. Estes permitem ligar diferentes aplicações que integram um sistema, ultrapassando barreiras como o tipo de plataforma ou linguagens de programação utilizadas.

