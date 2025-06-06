# O que é e pra que serve JSON?

## Neste artigo:

[O que é o JSON e para que serve?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-0)[Qual é a principal finalidade do JSON em programação?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-1)[Como é a estrutura de um JSON?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-2)[Onde o JSON é mais utilizado?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-3)[Como fazer um arquivo em JSON?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-4)[Qual a diferença entre HTML e JSON?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-5)[Qual a diferença entre JSON e XML?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-6)[Qual a diferença entre JS e JSON?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-7)[Quais as vantagens do JSON em relação a outras linguagens?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-8)[Quais são os principais desafios ao trabalhar com JSON?](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-9)[Simplifique sua gestão de documentos fiscais com a Focus NFe](https://focusnfe.com.br/blog/o-que-e-e-pra-que-serve-json/#sumario-10)

## O que é o JSON e para que serve?

JSON ou JavaScript Object Notation é uma formatação usada para a estruturação de dados em formato de texto que permite a troca de informações de forma prática e otimizada. E apesar de ser um tipo de notação de objetos JavaScript, só passou a fazer parte desta linguagem após a versão 5 do ECMAScript.

O modelo *.json* é um dos formatos utilizados para estruturar informações trafegadas em transferências de dados entre aplicações realizadas por [APIs (Application Programming Interface)](https://focusnfe.com.br/blog/o-que-e-uma-api/). 

Além disso, é utilizado para a realização de requisições AJAX em sites em que são feitas diferentes interações com o banco de dados para realizar operações como consulta, inclusão e exclusão de registros, como o MySql.

Outra forma de utilização de arquivos .json é para o gerenciamento de projetos em diferentes linguagens de programação. O Node.js, por exemplo, utiliza um arquivo chamado package.json em seus projetos para armazenar as dependências utilizadas na aplicação.

## Qual é a principal finalidade do JSON em programação?

Sua principal finalidade é a troca de dados entre sistemas e a representação de dados estruturados de forma leve e simples. Tornando a comunicação entre aplicações mais fácil, especialmente em contextos web e mobile.

Também é muito utilizado na programação de código API por acelerar a troca de dados e resultados de serviços web. Reduzindo a incompatibilidade de impedância entre objetos no código do aplicativo e suas representações seriadas. 

## Como é a estrutura de um JSON?

Os dados contidos em um arquivo no formato JSON devem ser estruturados através de uma coleção de pares, com nome e valor, ou ser uma lista ordenada de valores. Desse modo, seus elementos devem conter:

**Chave**: é o identificador do conteúdo e, por isso, deve ser uma string delimitada por aspas;

**Valor**: é o conteúdo correspondente e pode conter os tipos de dados string, array, object, number, boolean ou null.

### String

Uma string é uma sequência de zero ou mais caracteres Unicode, cercada por aspas duplas. Por exemplo:

```
"cidade": "Rio de Janeiro"
```

Neste caso, "Rio de Janeiro" é uma string por ser um conjunto de caracteres colocados entre aspas duplas.

### Number

Em JSON, um número (Number) pode ser do tipo inteiro ou fracionado e não utiliza aspas, desde que indique um valor numérico válido, como:

```
"age": 40
```

### Boolean

Os valores booleanos podem ser *true* (verdadeiro) ou *false* (falso) e não são colocados entre aspas: 

```
"solteiro": false
```


Neste exemplo, false é um valor booleano, indicando uma condição falsa sem o uso de aspas.

### Null

Em JSON, null é usado para representar a ausência de valor ou informação para determinado assunto, e não é colocado entre aspas:

```
"telefone": null
```

### Object

Um objeto é uma coleção de pares chave/valor, onde as chaves e os valores são separados por dois pontos e cada par é separado por vírgulas. Os objetos são cercados por **chaves { }**, como:

```
"carro": {"marca": "Toyota", "modelo": "Corolla"}
```

Aqui, "carro" é a chave, enquanto o valor é um objeto que contém as propriedades "marca" e "modelo".

### Array

Um array é uma coleção ordenada de valores, cercada por **colchetes [ ]** e com valores separados por vírgulas. 

Vejamos um exemplo com um array chamado "cidades", contendo três objetos que representam diferentes cidades e seus respectivos países:

```
"cidades": [

  {"nome": "São Paulo", "país": "Brasil"},

  {"nome": "Lisboa", "país": "Portugal"},

  {"nome": "Tóquio", "país": "Japão"}

]
```



### Exemplos de códigos JSON

Veja a seguir exemplos práticos de aplicação do JSON:

#### 1. Gerar um objeto JSON a partir de dados gerados pelo usuário

Imagine que um usuário preencha um formulário com seu nome e email em um site. Esses dados podem ser transformados em um objeto JSON para processamento ou armazenamento temporário.

```
{

  "nome": "João Silva",

  "email": "joao.silva@email.com"

}
```


Esse JSON pode ser enviado para o servidor para ser processado, armazenado ou utilizado para outras ações.

#### 2. Transferir dados entre sistemas

Para verificar um endereço, o JSON contendo o endereço do cliente é enviado para uma API de validação de endereços que vai retornar se o endereço é válido ou não.

```
{

  "endereco": {

    "rua": "Av. Paulista",

    "numero": "1000",

    "cidade": "São Paulo",

    "estado": "SP",

    "cep": "01310-100"

  }

}
```

#### 3. Configurar dados de aplicações

Configurações de uma aplicação, como credenciais de banco de dados e caminhos de arquivos de log, podem ser armazenadas em um arquivo JSON, tornando o acesso mais fácil e organizado.

```
{

  "banco_de_dados": {

    "host": "localhost",

    "usuario": "admin",

    "senha": "123456",

    "nome_banco": "meu_banco"

  },

  "configuracao_log": {

    "caminho_arquivo": "/var/logs/meu_app.log"

  }

}
```

A aplicação lê este arquivo JSON para obter os dados necessários para se conectar ao banco de dados e ao arquivo de log.

#### 4. Simplificar modelos de dados complexos

Um modelo de dados complexos, como um cadastro completo de um usuário com múltiplos endereços e contatos, pode ser simplificado em um arquivo JSON, permitindo uma estrutura mais clara e organizada.

```
{

  "usuario": {

    "id": 123,

    "nome": "Maria Oliveira",

    "enderecos": [

      {

        "tipo": "residencial",

        "rua": "Rua das Flores",

        "numero": "45",

        "cidade": "Rio de Janeiro",

        "estado": "RJ",

        "cep": "20000-000"

      },

      {

        "tipo": "comercial",

        "rua": "Av. Central",

        "numero": "1500",

        "cidade": "Rio de Janeiro",

        "estado": "RJ",

        "cep": "20000-010"

      }

    ],

    "contatos": [

      {

        "tipo": "telefone",

        "numero": "(21) 98765-4321"

      },

      {

        "tipo": "email",

        "email": "maria.oliveira@email.com"

      }

    ]

  }

}
```

Este exemplo de modelo complexo foi transformado em um formato de fácil leitura e manipulação com JSON.

## Onde o JSON é mais utilizado?

É muito utilizado na comunicação entre servidores clientes em [APIs RESTful](https://focusnfe.com.br/blog/o-que-e-api-rest/), armazenamento de dados, configurações de aplicações, troca de dados entre sistemas e desenvolvimento de aplicações web.

Além disso, serializa e transmite dados estruturados, tornando seu uso comum em aplicativos móveis onde é preciso requisitar dados em um servidor e utilizá-los rapidamente na aplicação.

Também, como já mencionado, o JSON é muito utilizado em requisições AJAX para aplicações web e para resolver o problema de domínio cruzado. 

## Como fazer um arquivo em JSON?

Para criar um arquivo em JSON, é preciso compreender como sua estrutura funciona e como os dados são estruturados. Em seguida, através de um editor de texto, você pode criar a estrutura desejada e salvar o arquivo em extensão .json. 

Confira mais detalhes destes passos abaixo:

### 1. Entenda a estrutura

Em primeiro lugar, é importante entender como funciona a estrutura do JSON, uma vez que essa formatação organiza os dados em pares chave-valor onde as chaves são strings e os valores podem ser strings, number, arrays, object, boolean ou null.

### 2. Escolha um editor de texto

Para criar o arquivo JSON, você precisará de um editor de texto. Existem várias opções disponíveis, como Notepad (Windows), TextEdit (Mac), ou editores de código como Visual Studio Code e Sublime Text.

### 3. Crie a estrutura

Abra o editor de texto escolhido e escreva a estrutura JSON. Certifique-se de seguir a sintaxe correta e incluir chaves e colchetes conforme necessário. 

### 4. Salve o arquivo

Após criar a estrutura JSON, você precisa salvar o arquivo:

Vá até o menu do editor, clique em “Arquivo” e depois em “Salvar como”. 

Depois, escolha o local onde deseja armazená-lo, dê um nome ao arquivo (por exemplo, livros.json) e certifique-se de que a extensão seja .json. 

Clique em Salvar para concluir o processo.

## Qual a diferença entre HTML e JSON?

O HTML (HyperText Markup Language) é uma linguagem de marcação baseada em tags usada para estruturar e apresentar conteúdos na web. 

Enquanto o JSON é um formato de troca de dados feito de estruturas de pares chave/valor que tem o objetivo de transmitir dados entre um servidor e um cliente (geralmente em aplicações web).

## Qual a diferença entre JSON e XML?

Ambos são representações de dados utilizados na comunicação de dados entre sistemas e aplicações. Entretanto, o JSON é independente de qualquer linguagem de programação, além de ser uma saída de API muito comum em diversas aplicações. 

Já o XML é uma linguagem de marcação que disponibiliza regras para definir qualquer dado, usando tags para diferenciar atributos de dados e dados reais. 

Entre as principais diferenças temos:

### Notação

A diferença inicial dos dois modelos é a maneira de realizar a notação dos dados. Como já dito, o JSON usa uma notação simples, enquanto o XML uma estrutura de tags personalizadas para representar os objetos. Além disso, elas devem conter o par, ou seja, a tag de abertura e a de fechamento.

Outra característica da notação XML, é que o seu conteúdo não precisa ser delimitado com aspas, como acontece com os textos no formato JSON. Nele, o que indica o início e o fim das informações são as tags de abertura e fechamento.

### Tipos de dados

O formato XML suporta diferentes tipos de dados, como imagens e gráficos, o que não é possível transmitir no formato JSON, uma vez que ele apenas oferece suporte a números e textos. Em contrapartida, o XML não oferece suporte a arrays.

### Codificação

A codificação representa as formas de conversão para o formato binário suportadas pelo modelo. O JSON utiliza o formato UTF-8, enquanto o XML oferece essa e outras opções. 

**Importante** frisar que o UTF-8 é o formato mais utilizado em sites na internet.

### Facilidade de leitura e comentários

Os arquivos em formato JSON são fáceis de entender, já que a estrutura e notação são bem simples. Já o XML é mais estruturado e com a interpretação mais complexa. 

Outra diferença é com relação aos comentários no arquivo, que são permitidos apenas no modelo XML.

### Quando usar JSON e quando devo usar XML?

Isso vai depender de cada projeto, é preciso analisar as requisições e exigências do aplicativo ou sistema para verificar qual opção vai produzir o melhor resultado.

Por exemplo, se o foco é desenvolver algo mais leve e rápido (especialmente na web), JSON é a escolha ideal, já que sua integração com JavaScript facilita o trabalho dos desenvolvedores. Além da sua legibilidade ser superior e permitir uma manipulação de dados mais simples e intuitiva.

Por outro lado, em sistemas que utilizam SOAP, o XML é que se destaca porque sua utilização é uma exigência. Sendo a melhor opção quando há uma maior complexidade de dados, necessidade de padronização na validação e transformações frequentes. Além disso, quando a categorização e identificação de dados são fundamentais, os metadados proporcionados pelo XML se tornam essenciais.

## Qual a diferença entre JS e JSON?

O [JavaScript (JS)](https://focusnfe.com.br/blog/o-estado-da-arte-javascript/) é uma linguagem de programação interpretada usada para tornar as páginas web mais interativas, suportando variáveis, funções, objetos, arrays, condicionais, entre outros. Enquanto o JSON é um formato que facilita a leitura, escrita e a comunicação de dados estruturados, sem executar lógica ou funções. 

Assim, enquanto o JS cria a lógica das aplicações e manipula os dados no lado do cliente, o JSON faz a troca dos dados entre o cliente e o servidor. 

## Quais as vantagens do JSON em relação a outras linguagens?

O JSON se destaca como o formato padrão para troca de informações entre sistemas web, especialmente em APIs. Sua simplicidade e legibilidade facilitam a comunicação entre aplicativos móveis e web, permitindo que ambos acessem os mesmos dados de forma eficiente. 

Além disso, a estrutura do JSON é fácil de entender e manipular, o que o torna acessível para desenvolvedores de diversas linguagens.

Outra vantagem significativa é seu uso como uma “linguagem de configuração”. Ele é amplamente utilizado para armazenar parâmetros e opções que configuram ou personalizam programas e aplicativos, seja em ambientes desktop, mobile ou servidores. 

Algumas das vantagens do JavaScript Object Notation:

Leitura mais simples;

Analisador (parsing) mais fácil;

Suporta objetos;

Velocidade maior na execução e transporte de dados;

Arquivo com tamanho reduzido.

Essa flexibilidade, aliada ao suporte universal em praticamente todas as linguagens de programação modernas, torna o JSON uma escolha popular no desenvolvimento de software.

## Quais são os principais desafios ao trabalhar com JSON?

Os principais desafios incluem manipular dados aninhados de forma eficiente, garantir a segurança dos dados e a compatibilidade entre diferentes sistemas e linguagens de programação. Além disso, é preciso ter capacidade de gerenciar e lidar com grande quantidade de dados. 

## Simplifique sua gestão de documentos fiscais com a Focus NFe

Somos um ecossistema de soluções para a emissão e gestão de documentos fiscais. Nossas APIs utilizam o formato JSON, o que facilita a integração e a gestão fiscal, permitindo que empresas de todos os tamanhos e setores economizem tempo e orientem seus esforços no que realmente importa.

Sua empresa tem desenvolvedores e um sistema interno, e deseja otimizar a emissão de notas fiscais? Conheça nosso conjunto de APIs e tenha acesso a uma solução ágil e eficiente!

Converse já com a nossa equipe: [Solicite Contato Aqui!](https://focusnfe.com.br/contato?utm_campaign=textoctablog)

![Egon](https://focusnfe.com.br/assets/img/blog/authors/egon.webp)

## [Egon](https://focusnfe.com.br/blog/autor/egon)

CTO e cofundador do Focus NFe, desenvolvedor, professor de yoga e praticante de meditação. Enquanto não está programando, procura a resposta para a vida, para o universo e para tudo mais.