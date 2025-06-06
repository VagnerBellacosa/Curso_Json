# O que é JSON?

Jeffrey Erickson | Estrategista de Conteúdo | 4 de abril de 2024

![img](https://www.oracle.com/a/ocom/img/rc24-bsa-what-is-json.jpg)

**Neste artigo**

- [O que é JSON (JavaScript Object Notation)?](https://www.oracle.com/sg/database/what-is-json/#what)
- [JSON explicado](https://www.oracle.com/sg/database/what-is-json/#explained)
- [Por que o JSON é usado?](https://www.oracle.com/sg/database/what-is-json/#why)
- [JSON vs. HTML vs. XML](https://www.oracle.com/sg/database/what-is-json/#vs)
- [Tipos de dados JSON](https://www.oracle.com/sg/database/what-is-json/#data-types)
- [Os 5 principais casos de uso para JSON](https://www.oracle.com/sg/database/what-is-json/#use-cases)
- [O que é um banco de dados de documentos JSON?](https://www.oracle.com/sg/database/what-is-json/#document-db)
- [Comece a usar o Oracle Autonomous JSON Database gratuitamente](https://www.oracle.com/sg/database/what-is-json/#get-started)
- [Perguntas frequentes sobre JSON](https://www.oracle.com/sg/database/what-is-json/#faqs)

No desenvolvimento de aplicativos web e mobile, um formato de dados versátil reina supremo: a Notação de Objetos JavaScript, mais conhecida como JSON. JSON é um formato leve para intercâmbio de dados que fornece uma maneira padronizada e eficiente para diferentes sistemas trocarem dados. Graças à sua simplicidade, flexibilidade e compatibilidade com linguagens de programação populares, JSON se tornou uma tecnologia fundamental para a construção de aplicativos web e conta com o apoio ávido da comunidade de desenvolvedores.

Aqui está o que você precisa saber sobre JSON.

## O que é JSON (JavaScript Object Notation)?

JSON (JavaScript Object Notation) é um formato baseado em texto para armazenar e trocar dados de forma legível por humanos e analisável por máquinas. Como resultado, JSON é relativamente fácil de aprender e solucionar problemas. Embora JSON tenha suas raízes em JavaScript, ele se tornou um formato de dados muito eficiente que simplifica a troca de dados entre diversas plataformas e linguagens de programação. Se você trabalha com desenvolvimento web, análise de dados ou engenharia de software, JSON é um formato de dados importante para entender.

**Principais conclusões**

- JSON é um formato de dados popular frequentemente usado por desenvolvedores web para transferir dados entre um servidor e um aplicativo web.
- Como o JSON é baseado em texto, ele é facilmente lido por humanos e compreendido por computadores.
- A natureza independente de linguagem do JSON o torna um formato ideal para troca de dados entre diferentes linguagens de programação e plataformas.
- Muitos bancos de dados surgiram para armazenar e trocar dados em JSON.

## JSON explicado

JSON é um formato de dados comumente usado por desenvolvedores web para transferir dados entre um servidor e uma aplicação web. Desenvolvedores geralmente preferem JSON porque ele simplifica a troca de dados entre diferentes tecnologias. Por exemplo, quando um usuário interage com uma aplicação web para fazer uma compra, a aplicação envia a entrada do usuário para o servidor em formato JSON. O servidor processa os dados e envia uma resposta, também em formato JSON, que é então renderizada pela aplicação web. Isso permite uma troca de dados fluida entre o cliente e o servidor, facilitando experiências web rápidas, dinâmicas e interativas.

## Por que o JSON é usado?

A natureza independente de linguagem do JSON o torna um formato ideal para a troca de dados entre diferentes linguagens de programação e plataformas. Por exemplo, um aplicativo escrito em Java pode facilmente enviar dados JSON para um aplicativo Python. Ou um aplicativo móvel escrito em JavaScript pode usar JSON para se comunicar com um servidor back-end escrito em PHP. Por quê? Porque ambos os sistemas podem analisar e gerar JSON.

Além do desenvolvimento web, o JSON é frequentemente usado em um aplicativo ou sistema de TI para armazenar e gerenciar definições de configuração. Por exemplo, arquivos de configuração escritos em JSON podem conter informações essenciais, como detalhes de conexão com o banco de dados, chaves de API ou preferências do usuário. Ao armazenar dados de configuração em arquivos JSON simples, fáceis de ler e analisar, os desenvolvedores podem modificar as configurações do aplicativo sem a necessidade de alterações no código.

### Por que JSON é popular entre desenvolvedores?

JSON é popular entre desenvolvedores por ser um formato flexível para troca de dados com amplo suporte em linguagens de programação e sistemas de software modernos. É baseado em texto, leve e possui um formato de dados fácil de analisar, o que significa que não requer código adicional para entender e interpretar os dados fornecidos.

JSON ganhou força na programação de APIs e em serviços web porque proporciona troca de dados e resultados de serviços web mais rápidos. O fácil acesso a bancos de dados de documentos NoSQL de código aberto, como MongoDB e outros, que armazenam dados em formato JSON e não exigem processamento adicional durante a troca de dados, também é importante. [Bancos de dados relacionais](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/) populares agora podem lidar com JSON como formato nativo, permitindo que ainda mais aplicações aproveitem os benefícios do JSON.

## JSON vs. HTML vs. XML

Existem diversos formatos para armazenar e transmitir dados na web. Três opções populares são JSON, XML e HTML. JSON e XML são formatos usados para armazenar e transmitir dados, e cada um possui diferentes vantagens. HTML é uma linguagem usada para criar a estrutura de uma página web e é frequentemente usada em conjunto com esses formatos de armazenamento de dados.

### Principais diferenças

- **JSON** (JavaScript Object Notation) é comumente usado para armazenamento e transferência de dados. JSON é uma escolha popular para aplicativos que se beneficiam de um formato de dados simples e fácil de usar.
- **XML** (Extensible Markup Language) é uma linguagem de marcação de propósito geral semelhante ao JSON que permite estruturas de dados mais complexas.
- **HTML** (Hypertext Markup Language) é usado para criar a estrutura e o conteúdo de páginas da web. Você frequentemente o verá usado com outras linguagens, como CSS (Cascading Style Sheets) e JavaScript, para unificar o estilo de um site e adicionar interatividade às suas páginas.

## Tipos de dados JSON

No contexto de desenvolvimento, tipos de dados são os diferentes tipos de valores que podem ser armazenados e manipulados em uma linguagem de programação. Cada tipo de dado possui seu próprio conjunto de atributos e comportamentos. JSON suporta diversos tipos de dados, incluindo os seguintes:

1. **Objetos.** Um tipo de dado de objeto JSON é um conjunto de pares de nomes ou valores inseridos entre {} (chaves). As chaves devem ser strings, separadas por vírgula e devem ser únicas.
2. **Matrizes.** Um tipo de dado de matriz é uma coleção ordenada de valores. Em JSON, os valores de matriz devem ser do tipo string, número, objeto, matriz, booleano ou nulo.
3. **Strings.** Em JSON, strings são colocadas entre aspas duplas, podem conter qualquer caractere Unicode e são comumente usadas para armazenar e transmitir dados baseados em texto, como nomes, endereços ou descrições.
4. **Booleano.** Valores booleanos são designados como verdadeiro ou falso. Valores booleanos não são colocados entre aspas e são tratados como valores de string.
5. **Nulo.** Nulo representa um valor que foi deixado em branco intencionalmente. Quando nenhum valor é atribuído a uma chave, ela pode ser tratada como nula.
6. **Número.** Números são usados para armazenar valores numéricos para diversos fins, como cálculos, comparações ou análise de dados. JSON suporta números positivos e negativos, bem como pontos decimais. Um número JSON segue o formato de ponto flutuante de precisão dupla do JavaScript.

### Exemplo JSON

O JSON funciona representando dados de forma hierárquica, usando pares chave-valor para armazenar informações. Os dados JSON são colocados entre chaves ({}), com cada par chave-valor separado por uma vírgula (,). Por exemplo, o JSON a seguir representa as informações de contato de uma pessoa:

```
``` { "name": "Jane Smith", "age": 35, "city": "San Francisco", "phone": "014158889275", "email": "janesmith@sample.com" } ```
```

Neste exemplo, "nome", "idade", "cidade", "telefone" e "e-mail" são as chaves, e "Jane Smith", "35", "São Francisco", "014158889275" e "janesmith@sample.com" são os valores correspondentes.

## Os 5 principais casos de uso para JSON

JSON é popular e amplamente utilizado por desenvolvedores, incluindo aqueles que trabalham com pilhas como MERN, que abrange MongoDB, Express, React e Node.js, e MEAN, que substitui o React no Angular.

1. **Transferência de dados entre sistemas.** JSON é ideal para transferir dados entre diferentes sistemas e linguagens de programação. Por exemplo, digamos que um banco de dados de um site tenha o endereço de correspondência de um cliente, mas ele precisa ser verificado por meio de uma API para garantir sua validade. Uma empresa pode enviar os dados do endereço no formato JSON em que já estão armazenados diretamente para a API do serviço de validação de endereços.
2. **Geração de um objeto JSON a partir de dados gerados pelo usuário.** JSON é ideal para armazenar dados temporários. Por exemplo, dados temporários podem ser gerados pelo usuário, como um formulário enviado em um site. JSON também pode ser usado como dados de serialização.
3. **Configurando dados para aplicativos.** Ao desenvolver aplicativos, cada um precisa das credenciais para se conectar a um banco de dados, bem como do caminho do arquivo de log. As credenciais e o caminho do arquivo de log podem ser especificados em um arquivo JSON para serem facilmente lidos e utilizados por todos os sistemas envolvidos.
4. **Simplificando modelos de dados complexos.** O JSON simplifica documentos complexos até os componentes identificados como significativos e converte o processo de extração de dados em um arquivo JSON previsível e legível.
5. **Arquivos de configuração e armazenamento de dados.** JSON permite fácil manipulação e recuperação de dados. Especificamente, ele suporta estruturas aninhadas, o que facilita o armazenamento de dados complexos e hierárquicos. JSON também suporta arrays, tornando-o adequado para armazenar múltiplas instâncias de dados semelhantes.

## O que é um banco de dados de documentos JSON?

A popularidade do JSON entre os desenvolvedores gerou uma série de bancos de dados altamente capazes e dedicados ao formato de dados, incluindo bancos de dados [SQL](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/) e [NoSQL](https://www.oracle.com/sg/database/nosql/what-is-nosql/) .

Bancos de dados NoSQL armazenam dados diretamente no formato JSON sem a necessidade de processamento adicional. Bancos de dados NoSQL populares, como MongoDB, Redis e Couchbase, também suportam aninhamento, referências a objetos e arrays, o que facilita a manutenção de um banco de dados JSON. Nos últimos anos, esses bancos de dados NoSQL evoluíram para oferecer vantagens como esquemas flexíveis e melhor escalabilidade e desempenho. Com suporte para estruturas de dados flexíveis e dinâmicas, esses bancos de dados se destacam no armazenamento de dados semiestruturados, como documentos de texto, imagens ou feeds de mídia social.

Bancos de dados SQL amplamente utilizados, como [o Oracle Database](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/) , agora oferecem JSON como tipo de dado, permitindo que desenvolvedores trabalhem com JSON sem precisar adicionar um banco de dados JSON especializado aos seus projetos. Isso oferece às equipes de desenvolvimento os benefícios já conhecidos do SQL, bem como a capacidade de trabalhar com outros tipos de dados em um [único banco de dados](https://blogs.oracle.com/database/post/what-is-a-converged-database) , incluindo dados gráficos, espaciais, REST, blockchain e relacionais.

## Comece a usar o Oracle Autonomous JSON Database gratuitamente

Quem busca usar JSON para gerenciar seus dados pode considerar [o Oracle Autonomous JSON Database](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/) , um serviço completo de banco de dados de documentos baseado em nuvem que simplifica o desenvolvimento de aplicativos centrados em JSON. O Oracle Autonomous JSON Database também oferece uma ampla gama de recursos sofisticados de banco de dados, incluindo APIs de documentos no estilo NoSQL via Oracle SODA e Oracle Database API para MongoDB, escalonamento sem servidor, transações ACID de alto desempenho e segurança abrangente, com preços acessíveis por uso.

A Oracle também oferece um serviço de banco de dados fácil de usar que automatiza o gerenciamento de bancos de dados, incluindo recursos para provisionamento, configuração, ajuste, dimensionamento, aplicação de patches, criptografia e reparo de bancos de dados. Você pode começar a usar o Oracle Autonomous JSON Database gratuitamente e aproveitar muitos [recursos úteis que não estão disponíveis no MongoDB Atlas](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/oracle-json-vs-mongodb-atlas/) .

JSON tornou-se um formato de dados simples, versátil e onipresente em diversos domínios, incluindo desenvolvimento web, troca de dados, gerenciamento de configuração e transmissão de dados. Sua ampla adoção e suporte entre as linguagens de programação mais populares consolidaram a posição do JSON como um pilar fundamental da comunicação e do intercâmbio de dados modernos.

![img](https://www.oracle.com/a/ocom/img/rc58-autonomous-json-database.png)

O Oracle Autonomous JSON Database é um serviço de nuvem de banco de dados de documentos que simplifica o desenvolvimento de aplicativos centrados em JSON.

[Experimente o Oracle Autonomous Database gratuitamente](https://www.oracle.com/sg/autonomous-database/autonomous-json-database/get-started/?source=:ow:o:p:po:::RC_WWMK230209P00003:BSA_WhatIsJson_sg&intcmp=:ow:o:p:po:::RC_WWMK230209P00003:BSA_WhatIsJson_sg)

## Perguntas frequentes sobre JSON

**JSON é um arquivo ou código?**

JSON não é um arquivo nem um código. Em vez disso, é um formato simples usado para armazenar e transportar dados. É um formato de texto simples, que permite fácil troca de dados entre diferentes linguagens de programação. JSON é frequentemente usado para enviar dados entre aplicativos web e servidores.

**JSON é uma linguagem de programação?**

JSON não é uma linguagem de programação. É, na verdade, um formato leve de intercâmbio de dados. Embora derivado do JavaScript, o JSON em si não suporta funções como uma linguagem de programação de verdade. JSON é usado simplesmente para armazenar e transmitir dados entre um servidor e uma aplicação web ou entre sistemas diferentes.

**JSON é melhor que XML?**

Embora JSON e XML sejam usados por desenvolvedores para armazenar e transferir dados entre sistemas, eles geralmente são utilizados em circunstâncias diferentes. XML (Extensible Markup Language) é uma linguagem de marcação de uso geral que permite a criação de estruturas de dados complexas e hierárquicas, enquanto a natureza leve e compacta do JSON o torna uma escolha melhor para a transmissão de dados em redes, especialmente em aplicações onde a largura de banda é limitada ou a velocidade de transmissão de dados é crítica.