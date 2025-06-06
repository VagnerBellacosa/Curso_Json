# Afinal, o que é JSON e para que ele serve? Descubra agora!

O formato JSON é utilizado para estruturar dados em formato de texto e permitir a troca de dados entre aplicações de forma simples, leve e rápida. Por isso é tão importante saber como é estruturado e as principais diferenças com o modelo XML.

![Ivan de Souza](https://secure.gravatar.com/avatar/eb1e3960268016620722afe889c85c81?s=300&d=mm&r=g)

[Ivan de Souza](https://rockcontent.com/br/blog/author/ivan/)



22 set, 20 | Leitura: 8min

[✓ Conteúdo criado por humano](https://www.writeraccess.com/br/trial/?utm_source=referral&utm_medium=top-of-blog-posts-human-author&utm_campaign=writeraccess-br)

Atualizado em: 13/10/2023

![img](https://rockcontent.com/br/wp-content/uploads/sites/2/2023/10/Web-Development-vs-SEO-1-1024x538.png)

Precisando de conteúdo para sua empresa? Nós podemos ajudar!

[Fale com um consultor](https://rockcontent.com/br/fale-conosco/fale-consultor)

[![img](https://rockcontent.com/br/wp-content/uploads/sites/2/2025/02/190225_BANNER_CERTIFICACAO.png)](https://pingback.com/certificacao/home?utm_medium=rock-convert&utm_source=rock&utm_campaign=blog)

JSON, que significa JavaScript Object Notation, **é uma formatação utilizada para estruturar dados em formato de texto e transmiti-los de um sistema para outro,** como em aplicações cliente-servidor ou em aplicativos móveis. Uma maneira de utilização é por meio de requisições AJAX, em que a aplicação recupera os dados armazenados no servidor de [hospedagem](https://rockcontent.com/br/blog/hospedagem/) sem a necessidade de recarregar a página.

A especificação JSON surgiu por volta do ano 2000, mas só passou a fazer parte da linguagem JavaScript após o lançamento da versão 5 do ECMAScript. Atualmente, esse formato é suportado por diversos tipos de linguagem de programação, além de ser uma alternativa mais leve que o modelo XML.

Para explicar esse conceito e a importância desse formato, fizemos este post, em que vamos mostrar:



- O que é .json?
- Para que serve o modelo JSON?
- Quais as principais características desse formato?
- Quais as diferenças entre .json e .xml?
- Por que o .json tem sido cada vez mais utilizado?
- Onde posso utilizar .json?
- Quais os benefícios do formato JSON?
- Quais são as grandes empresas que utilizam o formato JSON?



Faça o download deste post inserindo seu e-mail abaixo

 Não se preocupe, não fazemos spam.

Vamos lá? Boa leitura!



## O que é .json?

Na prática, **.json é um arquivo que contém uma série de dados estruturados em formato texto e é utilizado para transferir informações entre sistemas**. É importante dizer que, apesar de sua origem ser por meio da linguagem JavaScript, JSON não é uma linguagem de programação.

Em vez disso, é uma notação para a transferência de dados que segue um padrão específico. Por isso, pode ser amplamente utilizada em diferentes linguagens de programação e sistemas.

Os dados contidos em um arquivo no formato JSON devem ser estruturados por meio de uma coleção de pares com nome e valor ou ser uma lista ordenada de valores. Seus elementos devem conter:

- **chave**: corresponde ao identificador do conteúdo. Por isso, deve ser uma string delimitada por aspas;
- **valor**: representa o conteúdo correspondente e pode conter os seguintes tipos de dados: string, array, object, number, boolean ou null.



## Para que serve o modelo JSON?

A transferência de dados entre aplicações é feita por meio de [API](https://rockcontent.com/br/blog/rest-api/) — Application Programming Interface — que, entre outros formatos, utiliza a notação JSON para estruturar as informações trafegadas.

**O formato JSON também é utilizado para a realização de requisições AJAX** em [sites](https://rockcontent.com/br/blog/site/), em que são feitas diferentes interações com o [banco de dados](https://rockcontent.com/br/blog/banco-de-dados/), como o [MySql](https://rockcontent.com/br/blog/mysql/), para realizar operações como consulta, inclusão e exclusão de registros.

Outra forma de utilização de arquivos .json é para o gerenciamento de projetos em diferentes linguagens de programação. O [Node.js](https://rockcontent.com/br/blog/node-js/), por exemplo, utiliza um arquivo chamado package.json em seus projetos para armazenar as dependências utilizadas na aplicação.



## Quais as principais características desse formato?

Os arquivos no formato .json contêm algumas características específicas que tornam essa especificação mais atraente para a utilização em aplicações que consomem dados de outros sistemas. Confira as principais, a seguir.

### Linguagem independente

A simplicidade com que os dados são estruturados no formato JSON **permite que ele seja utilizado em qualquer tipo de linguagem de programação**. Além disso, ele pode ser manipulado em diferentes plataformas, como Windows, macOS, Linux, e em vários tipos de sistemas, como em aplicações web e aplicativos móveis.

### Formatação do arquivo

Além da terminação .json em todos os arquivos que utilizam esse formato, os dados armazenados devem seguir uma notação específica, ou seja, precisam ser organizados com os seguintes elementos básicos:

- **chaves** { } para delimitar os objetos e obrigatórias para iniciar e encerrar o conteúdo;
- **colchetes** [ ] para indicar um array;
- **dois pontos** : para separar a chave e seu valor correspondente;
- **vírgula** , para indicar a separação entre os elementos.

Veja, a seguir, alguns exemplos de como os dados devem ser relacionados em um arquivo .json.

#### String

```
{ "estado": "São Paulo"}
```

#### Array

```
{
    "estados": ["São Paulo", "Minas Gerais", "Rio de Janeiro"]
}
```

#### Objeto 

```
{ "estado": {
       "estado": "São Paulo",
       "sigla": "SP"
  }
}
```

#### Lista de objetos

Confira como fazer a notação para indicar uma lista de objetos:

```
{   "estados":[
    {"estado": "São Paulo", "sigla": "SP"},
    {"estado": "Minas Gerais", "sigla": "MG"},
    {"estado": "Rio de Janeiro", "sigla": "RJ"}
    ]
}
```



## Quais as diferenças entre .json e .xml?

Outro **formato utilizado para a troca de dados entre aplicações é o XML** — eXtensible Markup Language. Apesar de também ser um arquivo de texto, existem algumas diferenças entre os dois modelos. Confira as principais.

### Notação

A primeira diferença entre os dois modelos é a forma de fazer a notação dos dados. Conforme mencionamos, o JSON utiliza uma notação simples, enquanto **o XML utiliza uma estrutura de tags personalizadas para representar os objetos**. Além disso, elas devem conter o par, ou seja, a tag de abertura e a de fechamento.

[![img](https://rockcontent.com/br/wp-content/uploads/sites/2/2025/02/190225_BANNER_DIAGNOSTICO.png)](https://pingback.com/diagnostico-gratuito?utm_medium=rock-convert&utm_source=rock&utm_campaign=blog)

Outra característica da notação XML é que o seu conteúdo não precisa ser delimitado com aspas, como acontece com os textos no formato JSON. Nele, o que indica o início e o fim das informações são as tags de abertura e fechamento. Confira o exemplo, a seguir.

```
<?xml version="1.0" encoding="UTF-8" ?>
<estados>
    <estado>
        <nomeEstado>São Paulo</nomeEstado>
        <sigla>SP</sigla>
    </estado>
    <estado>
        <nomeEstado>Minas Gerais</nomeEstado>
        <sigla>MG</sigla>
    </estado>
    <estado>
        <nomeEstado>Rio de Janeiro</nomeEstado>
        <sigla>RJ</sigla>
    </estado>
</estados>
```

### Tipos de dados

O formato XML suporta diferentes tipos de dados, entre eles: imagens e gráficos, o que não é possível transmitir no formato JSON, pois ele só oferece suporte a números e textos. Em contrapartida, o XML não oferece suporte a arrays.

### Codificação

A codificação representa as formas de conversão para o formato binário suportadas pelo modelo. O JSON utiliza o formato UTF-8, enquanto o XML oferece essa e outras opções. É importante dizer que o UTF-8 é o formato mais utilizado em sites na internet, como o [WordPress](https://rockcontent.com/br/blog/wordpress/) e muitos outros.

### Facilidade de leitura e comentários

Os arquivos JSON são fáceis de entender, pois sua estrutura e notação são bem simples. Já o XML é mais estruturado e, portanto, com a interpretação mais complexa. Outra diferença é com relação aos comentários no arquivo, que são permitidos apenas no modelo XML.

[![[PTBR\] [MQL] Conheça Ion](https://rockcontent.com/br/wp-content/uploads/sites/2/2023/03/PPC-arts-Display-728-%C3%97-90-px-1.gif)](https://materiais.rockcontent.com/br/ion?utm_medium=rock-convert&utm_source=blog&utm_campaign=rock-convert)



## Por que o .json tem sido cada vez mais utilizado?

**A simplicidade do formato JSON é uma das principais razões pelas quais ele é bastante utilizado**. Isso porque as requisições AJAX, que permitem a atualização da página sem a necessidade de recarregá-la completamente, precisam ser executadas com muita rapidez para que essas atualizações sejam transparentes para o usuário.

Por ser leve e compacto, o formato JSON atende a essa necessidade. Portanto, os dados podem ser trafegados de forma rápida e interpretados com facilidade pela aplicação.

Vale dizer que o formato XML também pode ser utilizado em requisições AJAX. Entretanto, é um arquivo maior, por conter mais informações em razão do grande número de tags de abertura e fechamento, o que torna a sua transferência e processamento mais lentos que o modelo JSON.

Outra razão importante para utilizar esse formato é para resolver o problema de domínio cruzado, que é a impossibilidade de executar requisições AJAX em domínios que não estejam hospedados no mesmo servidor. Existe um recurso chamado JSONP que elimina essa situação com facilidade e permitir a recuperação de informações com essa característica.



## Onde posso utilizar .json?

O arquivo .json pode ser utilizado em diferentes finalidades. Uma delas é para serializar e transmitir dados estruturados. Ele também é indicado para a utilização em aplicativos móveis, em que é preciso requisitar dados em um servidor e utilizá-los rapidamente na aplicação.

Conforme mencionamos, o JSON é muito utilizado em requisições AJAX para aplicações web e para resolver o problema de domínio cruzado. Além disso, **ele também é utilizado como arquivo de configuração** para armazenar dados que são verificados em tempo de utilização da aplicação.



## Quais os benefícios do formato JSON?

Existem diversas vantagens em optar pela utilização do formato JSON para diversos tipos de aplicações. Confira as principais delas.

### Leitura mais simples

O formato JSON é fácil de utilizar, pois sua notação permite, inclusive, o entendimento visual da organização dos dados. Isso significa que se alguém abrir um arquivo .json, provavelmente, conseguirá compreender as suas informações. A mesma facilidade é com relação ao processamento desse arquivo, especialmente, por ser em formato texto.

### Mais agilidade na execução e transporte de dados

Armazenar os dados em formato texto, aliás, permite que o arquivo .json ocupe pouco espaço em memória. Essa característica oferece ótima performance, pois como ele é pequeno, ocupa poucos bytes, o que oferece mais [agilidade para a transferência e carregamento](https://rockcontent.com/br/blog/velocidade-do-site/) durante o processamento.

### Arquivos mais leves

A forma com que os dados são estruturados no modelo JSON é extremamente compacta. Isso permite armazenar muitas informações com menos delimitadores que o modelo XML. Conforme mencionamos, os arquivos gerados são leves e mais rápidos para transmitir e fazer o processamento pela aplicação.

### Parsing mais fácil

Como os dados armazenados em um arquivo JSON são em formato de texto, **é preciso realizar a interpretação de seu conteúdo para que ele seja consumido pela aplicação**. Isso pode ser feito facilmente por diferentes tipos de linguagens, como JavaScript, [jQuery](https://rockcontent.com/br/blog/jquery/) e muitas outras.

- [Front-End e SEO: o que desenvolvedores front-end precisam saber sobre SEO](https://rockcontent.com/br/blog/frontend-e-seo/)
- [O que é Java? Conheça as particularidades dessa linguagem de programação](https://rockcontent.com/br/blog/o-que-e-java/)
- [O que é PHP e por que você precisa conhecer essa linguagem de programação web](https://rockcontent.com/br/blog/o-que-e-php/)



## Quais são as grandes empresas que utilizam o formato JSON?

O formato JSON é amplamente utilizado em aplicações web, especialmente, pelas suas características de leveza e velocidade. Existem diversas grandes empresas que utilizam esse formato em suas páginas e sistemas, entre elas: **Google, Yahoo, Facebook, Twitter** e muitas outras.

**JSON é uma notação que permite estruturar dados em formato texto para serem utilizados em diferentes tipos de sistemas**. Trata-se de um formato simples e leve, que oferece uma série de benefícios, como maior velocidade no tráfego em rede e mais agilidade no processamento. Por isso, é amplamente utilizado em aplicações web, aplicativos móveis e como arquivo de configuração.

Gostou do nosso conteúdo sobre a utilização de arquivos JSON? Então, confira este post sobre [o que é linguagem de programação e confira os principais tipos](https://rockcontent.com/br/blog/linguagem-de-programacao/)!