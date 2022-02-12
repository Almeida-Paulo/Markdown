# Markdown Document

; OBS: veja no modo fonte (clicando em <> na parte superior)

## Introdução

Markdown é uma sintaxe de formatação de texto simples.

Os parágrafos são separados por linhas vazias.

##Estilos de tamanho texto

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
- __asteriscos duplos__

Essas sentenças resultam em tags riscadas 'del':

- ~~acentos til duplos~~

## Links e Imagens

Este é um [exemplo de link embutido](https://dio.me/sign-up?ref=NABGWG3Y4C "Site plataforma DIO") com texto indicando o conteúdo do link.
[Este link](https://dio.me/sign-up?ref=NABGWG3Y4C) não tem texto imbutido indicando o conteúdo, "dica de ferramenta".

URLs e endereços de e-mail podem ser transformados em links colocando-os entre chaves angulares:

- <https://daringfireball.net/projects/markdown/>  
- <https://github.com/>

[Este link](#markdown-document) é vinculado ao primeiro título deste documento por meio de um ID personalizado.

## Images

This is an example of an image:

![Image](https://avatars.githubusercontent.com/u/9919?s=200&v=4)

This is an example of an image with a link:

[![Image](https://www.google.com/favicon.ico)](https://www.google.com)

## Blockquotes

Markdown said:

> This is the first level of quoting.
>
> > This is a nested blockquote.
>
> Back to the first level.

## Lists

Unordered list using minus signs (-):

- Step 1
- Step 2
- Step 3
  - Step 3a
  - Step 3b
  - Step 3c

Unordered list using plus signs (+):

+ Step 1
+ Step 2
+ Step 3
  + Step 3a
  + Step 3b
  + Step 3c

Unordered list using asterisks (*):

* Step 1
* Step 2
* Step 3
  * Step 3a
  * Step 3b
  * Step 3c

Ordered list:

1. Step 1
1. Step 2
1. Step 3
    1. Step 3a
    1. Step 3b
    1. Step 3c

Nested (unordered within ordered) list:

1. Step 1
1. Step 2
1. Step 3
    - Step 3a
    - Step 3b
    - Step 3c

Definition list:

Term #1
: This is the definition of term #1.

Term #2
: This is the definition of term #2.

## Code Blocks

Inline `code` can be delimited with characters.

This code block is fenced with three backticks and has its language specified:

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```

This code block is fenced with three tildes and has its language specified:

~~~ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
~~~

This code block is created by indenting the code, but no language can be specified:

    var foo = 1;

## Tables

| Fruit  | Color  |
|--------|--------|
| Apples | Red    |
| Grapes | Purple |
| Lemons | Yellow |

## Horizontal Rules

Horizontal rules are formed by placing three or more hyphens, asterisks, or underscores on a line by themselves.

---

***

___

## HTML Tags

<strong>HTML tags</strong> can optionally be used in <em>Markdown</em>.

## Special Characters

Unescaped:
\ ` * _ { } [ ] ( ) # + - . !

Backslash-Escaped:
\\ \` \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!