# Markdown Document

; OBS: veja no modo fonte (clicando em <> na parte superior)

## Introdução

Markdown é uma sintaxe de formatação de texto simples.

Os parágrafos são separados por linhas vazias.

## Estilos de tamanho texto

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## Estilos de caracteres

Essas sentenças resultam em tags de ênfase 'em':

- *asteriscos simples*
- _sublinhas simples_

Essas sentenças resultam em tags de importância, como em 'strong':

- **asteriscos duplos**
- __sublinhas duplas__

Essas sentenças resultam em tags riscadas 'del':

- ~~acentos til duplos~~

## Links e Imagens

Este é um [exemplo de link embutido](https://dio.me/sign-up?ref=NABGWG3Y4C "Site plataforma DIO") com texto indicando o conteúdo do link.
[Este link](https://dio.me/sign-up?ref=NABGWG3Y4C) não tem texto imbutido indicando o conteúdo, "dica de ferramenta".

URLs e endereços de e-mail podem ser transformados em links colocando-os entre chaves angulares:

- <https://daringfireball.net/projects/markdown/>  
- <support@microsoft.com>

[Este link](#markdown-document) é vinculado ao primeiro título deste documento por meio de um ID personalizado.

## Imagens

Este é um exemplo de uma imagem:

![Image](Images/bandeira-nacional-brasil.png)

Este é um exemplo de uma imagem com um link:

[![Image](https://github.com/favicon.ico)](https://github.com)

## Citações em bloco

Markdown diz:

> Este é o primeiro nível de citação.
>
> > Esta é uma citação de bloco ligada/aninhada.
>
> De volta ao primeiro nível.

## Listas

Lista não ordenada usando sinais de menos (-):

- Step 1
- Step 2
- Step 3
  - Step 3a
  - Step 3b
  - Step 3c

Lista não ordenada usando sinais de adição (+):

+ Step 1
+ Step 2
+ Step 3
  + Step 3a
  + Step 3b
  + Step 3c

Lista não ordenada usando asteriscos (*):

* Step 1
* Step 2
* Step 3
  * Step 3a
  * Step 3b
  * Step 3c

Lista ordenada:

1. Step 1
1. Step 2
1. Step 3
    1. Step 3a
    1. Step 3b
    1. Step 3c

Lista ligada/aninhada (não ordenada dentro de ordenada):

1. Step 1
1. Step 2
1. Step 3
    - Step 3a
    - Step 3b
    - Step 3c

Lista de definições:

Term #1
: This is the definition of term #1.

Term #2
: This is the definition of term #2.

## Blocos de código

O `código` embutido pode ser delimitado com caracteres.

Este bloco de código é cercado com três crases e tem sua linguagem especificada:

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```

Este bloco de código é cercado com três til e tem sua linguagem especificada:

~~~ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
~~~

Este bloco de código é criado pela indentação do código, mas nenhuma linguagem pode ser especificada:

    var foo = 1;

## Tabelas

| Fruit  | Color  |
|--------|--------|
| Apples | Red    |
| Grapes | Purple |
| Lemons | Yellow |

## Regras horizontais

As regras horizontais são formadas colocando três ou mais hífens, asteriscos ou sublinhados em uma linha.

---

***

___

## Tags HTML

<strong>tags HTML</strong> podem ser usadas opcionalmente em <em>Markdown</em>.

## Caracteres especiais

Unescaped:
\ ` * _ { } [ ] ( ) # + - . !

Backslash-Escaped:
\\ \` \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!
