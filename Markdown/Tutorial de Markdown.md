# Tutorial de Markdown

#### Um guia desenvolvido para o Bootcamp Santander Full-Stack 2022.

<a name="ancora"></a>

### Menu de navegação:

- [Títulos](#titulos)
- [Estilos](#estilos)
- [Citações](#citacoes)
- [Adicionando blocos de Códigos](#codigos)
- [Tabelas](#tabelas)
- [Emojis](#emojis)
- [Links](#links)

Fala Dev, tudo bem? :stuck_out_tongue_winking_eye:

Este é um resuminho de como utilizar a sintaxe **Markdown** para estilizarmos nossos textos aqui no Github.

<a id="titulos"></a>

### Títulos

Caso você ja esteja familiarizado com **HTML**, a titulação em **Markdown** funciona assim:

```
# Título <h1>
## Título <h2>
### Título <h3>
#### Título <h4>
##### Título <h5>
###### Título <h6>
```



<a id="estilos"></a>

### Estilos

Deixar seu texto em **negrito**  ou *itálico* , ~~ou riscar seus erros cruéis~~ : 

```
**negrito** 
*itálico*
~~riscado~~
<u>sublinhado</u>
```

> **OBS:** Os textos <u>sublinhados</u> eram feitos anteriormente com``__underline__`` mas aparentemente não tem funcionado, então...vamos para o HTML mesmo ! :pensive: 



<a id="citacoes"></a>

### Citações

>  With great power comes great responsibility
>
>  **Ben,TIO**

Legal e muito inspirador, para fazer essa **Quote** é bem simples, você começa sua citação com um sinal de  `>`. Dá uma olhada como fica:

```
>  With great power comes great responsibility
**Ben,TIO**
```



<a id="codigos"></a>

### Adicionando Códigos

- **Uma linha de código**: adicione um acento grave `ˋ` no início e no final do código.
- **Um bloco de código**: Comece e termine o seu código com `ˋˋˋ` ou três tils `~~~`. 

Assim:

~~~
A *tag* que corresponde á um titulo de página em HTML é `<title>`.
~~~

A *tag* que corresponde á um titulo de página em HTML é `<title>`.

Da até para determinar qual a linguagem de programação você esta usando, colocando depois dos `~~~` o nome da linguagem. Olha só:

~~~~
~~~javascript
public class OlaMundo {
    public static void main(String[] args) {
        System.out.println("Ola, Mundo!");
    }
}
~~~
~~~Html
<h4>Escrevendo um código maneiro em HTML
~~~

~~~~

Resultado:

~~~javascript
public class OlaMundo {
    public static void main(String[] args) {
        System.out.println("Ola, Mundo!");
    }
}
<h4>Escrevendo um código maneiro em HTML
~~~



<a id="Tabelas"></a>

### Tabelas

Adicione os títulos das colunas e use `|` para delimitar cada uma delas. Depois, utilize o sinal de menos `-` na segunda linha para indicar que os títulos estão em cima das colunas. Olha como é facil:

~~~
Nome      | Idade  | Salário
--------- | ------ | -------
May       | 45     | 1000,00
Ned       | 20     | 1500,00
Peter     | 20     | 1800,00
Mary Jane | 19     | 2500,00
~~~

O resultado fica assim:

| Nome      | Idade | Salário |
| :-------- | ----- | ------- |
| May       | 45    | 1000,00 |
| Ned       | 20    | 1500,00 |
| Peter     | 20    | 1800,00 |
| Mary Jane | 19    | 2500,00 |



<a id="emojis"></a>

### Emojis

A  forma principal de comunicação, claro, os emojis :rofl:!

Existem muitos, **muitos** deles para serem uzados , e são gerados pelo  [GitHub Emoji API](https://api.github.com/emojis) e pela  [Unicode Full Emoji List](https://unicode.org/emoji/charts/full-emoji-list.html).

Quer ver todos eles? [Clica nesse link](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#writing) e veja esse README completo com todos os emojis! 

Seja feliz! :smiley:



<a id="links"></a>

### Links

Para Adicionar links diretos  ou links âncoras é só seguir esses passos:

* **Links  Diretos:**

Entre chaves `< >` , desse jeito: `<https://seulinkaqui.com>`

Resultado: <https://seulinkaqui.com>

* **Link âncora:**

Entre os caracteres `[]`, adicione o texto clicavel , e entre os parênteses ``()``, o endereço de destino, desse jeito: `[Seu texto aqui](https://seulinkaqui.com)`.

Resultado: [Seu texto aqui](https://seulinkaqui.com)