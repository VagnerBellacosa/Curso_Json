# O que é JSON

## Veja neste artigo sobre JSON onde começaremos pelo básico sobre e avançaremos para exemplos mais complexos nos próximos artigos.

[Artigos](https://www.devmedia.com.br/artigos/)[Java](https://www.devmedia.com.br/artigos/java)O que é JSON

### Afinal, o que é JSON?

JSON é basicamente um formato de nível de troca de informações/dados entre sistemas. Mas **JSON significa JavaScript Object Notation** , ou seja, só posso usar com JavaScript correto? Na verdade não e alguns ainda caem nesta armadilha.

O JSON além de ser um formato leve para troca de dados também é muito simples de ler. Mas quando dizemos que algo é simples, é interessante compará-lo com algo mais complexo para entendermos tal simplicidade não é? Neste caso podemos comparar o JSON com o [formato XML](https://www.devmedia.com.br/xml-tutorial/24936) .

![Afinal, o que é JSON?](https://www.devmedia.com.br/arquivos/Artigos/23166/oque-json.webp)

Veja esse [tutorial completo sobre JSON](https://www.devmedia.com.br/json-tutorial/25275)

#### Vamos visualizar essa diferença?

```
<note>
<to>Tove</to>
<from>Jani</from>
<heading>Reminder</heading>
<body>Don't forget me this weekend!</body>
</note>
```

**Código 1** . Exemplo XML

```
{
   "id":1,
   "nome":"Alexandre Gama",
   "endereco":"R. Qualquer"
}
```

**Código 2** . Exemplo JSON

Bom, é notável a diferença. Visualmente o segundo trecho (em JSON) é mais fácil de ler. Mas só existe essa diferença entre os dois? Na verdade não. Podemos listar algumas outras vantagens:

### Vantagens do JSON:

- Leitura mais simples
- Analisador(parsing) mais fácil
- JSON suporta objetos! Sim, ele é tipado!
- Velocidade maior na execução e transporte de dados
- Arquivo com tamanho reduzido
- Quem utiliza? Google, Facebook, Yahoo!, Twitter...

Estas são algumas das vantagens do JSON. Agora vamos ao que interessa: Código! Vamos fazer um exemplo extremamente simples na primeira parte e avançaremos neste próximo artigo, inclusive **falando sobre JSON** em páginas Web.

#### Qual biblioteca usar?

Existem diversas bibliotecas para trabalharmos com JSON e [Java](https://www.devmedia.com.br/java/) . Usaremos no nosso estudo o json.jar que você pode baixar tranquilamente neste link.

O nosso caso de estudo será simples: Teremos uma classe Carro que será a nossa classe [POJO](https://pt.wikipedia.org/wiki/Plain_Old_Java_Objects) e a classe EstudoJSON que terá o nosso famoso método main .

```
package br.com.json;

public class Carro {
    private Long id;
    private String modelo;
    private String placa;

    public Long getId() {
        return id;
    }
    public void setId(Long id) {
        this.id = id;
    }
    public String getModelo() {
        return modelo;
    }
    public void setModelo(String modelo) {
        this.modelo = modelo;
    }
    public String getPlaca() {
        return placa;
    }
    public void setPlaca(String placa) {
        this.placa = placa;
    }

        //Aqui fizemos o Override do método toString() para visualizar
        //a impressão com o System.out.println()
    @Override
    public String toString() {
        return "[id=" + id + ", modelo=" + modelo + ", placa=" + placa + "]";
    }

}
```

**Código 3.** Classe Carro

Esta é uma classe simples, onde temos os atributos Id, Modelo e Placa. Agora teremos uma aula EstudoJSON .

```
package br.com.json;

import org.json.JSONArray;
import org.json.JSONException;
import org.json.JSONObject;

public class EstudoJSON {
    public static void main(String[] args) throws JSONException {
        adicaoSimplesDeDados();
    }
}
```

**Código 4.** Classe EstudoJSON

Repare que criamos o método adicaoSimplesDeDados() que contém o código de exemplo:

```
private static void adicaoSimplesDeDados() throws JSONException {
    //Criação do objeto carro e atribuição dos valores
    Carro carro = new Carro();
    carro.setId(1l);
    carro.setModelo("Celta");
    carro.setPlaca("AAA1234");

    //Criação do objeto carroJson
    JSONObject carroJson = new JSONObject();
    //Inserção dos valores do carro no objeto JSON
    carroJson.put("id", carro.getId());
    carroJson.put("Modelo", carro.getModelo());
    carroJson.put("Placa", carro.getPlaca());

    //Impressão do objeto JSON
    System.out.println(carroJson);
}
```

**Código 4** . Método adicaoSimplesDeDados()

Se executarmos este código, veremos o que foi impresso no console ou o seguinte:

```
{"id":1,"Modelo":"Celta","Placa":"AAA1234"}
```

**Código 5** . Resultado do console

Você desenvolvedor mais atento vai reparar que existe um objeto impresso: Um Long ! Isso mesmo! Como vimos, o JSON consegue armazenar objetos! Podemos inclusive armazenar um objeto do tipo Carro mesmo:

Modificamos nosso método main :

```
public class EstudoJSON {
    public static void main(String[] args) throws JSONException {
        adicaoSimplesDeDados();

        adicaoDeUmObjeto();
    }
}
```

**Código 6.** Método principal

E adicionamos o método adicaoDeUmObjeto() :

```
private static void adicaoDeUmObjeto() throws JSONException {
    Carro carro = new Carro();
    carro.setId(1l);
    carro.setModelo("Celta");
    carro.setPlaca("AAA1234");

    JSONObject carroJson = new JSONObject();
    //Adição do objeto carro
    carroJson.put("Carro", carro);

    System.out.println(carroJson);
}
```

**Código 7** . Método adicaoDeUmObjeto()

Neste caso foi impresso no console o seguinte:

```
{"Carro":"[id=1, modelo=Celta, placa=AAA1234]"}
```

**Código 8** . Resultado do console

Simples não? Como o JSON funciona com coleção de pares nome/valor, podemos imprimir um valor específico simplesmente solicitando o nome que desejamos.

```
System.out.println(carroJson.get("Modelo"));
```

**Código 9** . Impressão de um valor específico

Veja que neste caso queremos somente o modelo do carro, bastando fazer a chamada get("nome que desejamos") !

### Integração do JSON com APIs Web

Atualmente, grande parte dos projetos web utilizam APIs para comunicação do front-end com o back-end, o JSON é o formato mais utilizado para esse tipo de implementação.

O JSON é muito utilizado em APIs para envio e coleta de dados entre o cliente e o servidor. Por exemplo, aplicação numa web onde o envio de transferências ao servidor e terá como coleta um JSON.

#### Benefícios de usar JSON em APIs

- Leve e Simples
- Eficiência
- Fácil de Ler e Escrever
- Multiplataforma
- Desempenho

#### Ferramentas úteis

- Carteiro
- Insônia
- Arrogância

### JSON e Inteligência Artificial: Integração e Aplicações

O JSON se torna uma ferramenta necessária para o desenvolvimento de sistemas de IA devido à sua simplicidade e eficiência na troca de dados. Conheça mais da relação entre JSON e IA:

- Comunicação entre o front-end e o back-end
- Formato de Dados para treinamento de modelos de IA
- Integração com APIs de IA, serviços de computação em nuvem utilizam JSON para enviar e receber dados.
- Armazenamento de configurações de modelos de IA.
- Visualização de resultados de modelos de IA, como específicas, análises de dados e relatórios, podem ser formatados em JSON.

#### Ferramentas e Bibliotecas Úteis

- TensorFlow
- Keras
- Pandas
- APIs de Serviços Cognitivos

A simplicidade e a flexibilidade do JSON tornam-se uma opção ideal para integrar e implementar sistemas de IA.

### Conclusão

É isso pessoal! Vimos as **vantagens do JSON** e vimos como é simples começar a trabalhar com ele. Nos próximos artigos veremos exemplos mais complexos e veremos algo mais real onde faremos chamadas à API do Facebook!

#### Confira outros conteúdos: