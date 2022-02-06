# 1. <center>MARKDOWN</center>

**Markdown** é uma linguagem de marcação como a *HTML*. Elas são linguagens para desenvolvimento. **Git** e **Github** são compatíveis com a linguagem Markdown. 

O arquivo ***README.md*** dos repositórios no Github, são feitos com a linguagem Markdown.
 
> ***.md*** → é a extensão para os arquivos em Markdown.


<div id="hierarquia-titulos">

## 1.1. Hierárquia de títulos

- \# Título nível 1
- \## Título nível 2
- \### Título nível 3
- \#### Título nível 4
- \##### Título nível 5
- \###### Título nível 6 

▼ Pode-se também fazer o título e subtítulo assim:
~~~
2. Título principal 
===

2.1. Subtítulo 
---
~~~


## 2.2. Linha horizontal

- 3 traços \---
- 3 asteriscos \***
- 3 underlines ___


## 2.3. Parágrafos

Você pode criar um novo parágrafo deixando uma linha em branco entre as linhas de texto.


## 2.4. Quebra de linha

Pode-se usar **2 espaços no final da linha** ou a tag \<br> - quebra de linha do HTML no arquivo em Markdown. As tags HTML são aceitas em Markdown.


## 2.5. Formatação básica

**♦ Negrito:** São 2 asteriscos ou 2 underlines ou Ctrl B. `**negrito** ou __negrito__ ` **negrito**

**_♦ Itálico:_** é 1 asterisco ou 1 underline ou Ctrl I. `*itálico* ou _itálico` *itálico*

**♦ Texto excluído:** são 2 tils. `~~riscado~~` ~~texto excluído~~

**♦ Negrito-itálico:** são 2 asteriscos e 1 underline. `**_negrito-itálico_**` **_negrito-itálico_**

**♦ Todo o texto em negrito itálico:** são 3 asteriscos. `***Tudo em negrito e itálico*** ou ___tudo em negrito e itálico___` ***Tudo em negrito e itálico de forma mais simples.***

___
▬ Texto  sublinhado?  
▬ Texto marcado com cor? 
___


## 2.6. Mostrar os símbolos no texto

Para mostrar exatamente o símbolo basta usar uma barra invertida \ antes do símbolo para eliminar o seu efeito de formatação. `\#` assim pode-se usar o símbolo \# ou qualquer outro dentro do texto. 


## 2.7. Citação

O sinal de **>** no início da linha indica a citação. 

> Você pode citar automaticamente o texto em um comentário ***destacando o texto e digitando R***.

**♦ Citação aninhada:** Para criar um bloco aninhado de citações, utilize 2 ou mais sinais de maior que **>>** antes do parágrafo.

~~~
> Resultado da citação acima
>> citação nível 2
>>> citação nível 3
>>> citação nível 3
>>>> citação nível 4
~~~
> Resultado da citação acima
>> citação nível 2
>>> citação nível 3
>>> citação nível 3
>>>> citação nível 4


## 2.8. Trecho de código

▼ **Código inline →** colocar entre crases \` \` O código delimitado ou Ctrl E. Isso faz o texto ficar com uma fonte monoespaçada e com fundo acinzentado para dar destaque. Exemplo: `window.document.querySelector()` é escrito em linguagem JavaScript.

▼ **Código em linhas →** colocar o código entre 3 crases ``` ou 3 tils ~~~ consecutivos sem espaço entre eles.

~~~ python
    num = int(input('Digite um número: ')) 
    if num % 2 == 0: 
        print(f'O valor {num} é PAR') 
    else: 
        print(f'O valor {num} é ÍMPAR') 
    print('Fim do Programa') 
~~~

▼ **Código de linhas simples →** Colocar 4 espaços para antes do texto. 

    Exemplo para textos.

    ♦ Essa forma não é indicada para colocar trechos de linguagens de programação.


## 2.9. Links

Símbolo **\[link](URL)** → onde a descrição fica entre colchetes e o endereço do link entre parênteses.

Exemplo: [Pesquisa Google](https://www.google.com/)

♦ **Link relativo** → \[link](docs/CONTRIBUTING.md) – pode usar os operandos ./ e ../ para acessar as pastas.

♦ **Link direto** → envolva o endereço da web entre chaves <> ou colocar a URL completa. https://www.google.com/


## 2.10. Âncoras

Fazer âncoras no texto, ou seja, links dentro do texto.

**\[Hieráquia de títulos](#hierarquia-titulos)** → leva a página até o conteúdo referenciado por uma div: **\<div id="hierarquia-titulos">**

♦ Exemplo: [Hieráquia de títulos](#hierarquia-titulos)

▲ Com esse exemplo é possível criar sumários e íncices de tópicos no texto.


## 2.11. Imagens

Símbolo **\!\[img](URL)** → abre colchetes vazio e a URL da imagem entre parênteses. 

![CursoemVideo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png)

♦ **Imagem com título** → colocar uma descrição da imagem quando passar o mouse sobre ela. Tem a mesma função da tag \<title> do Html. Para isso, coloque após a url da imagem, a descrição entre aspas duplas: \!\[ ](URL "descrição").

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png "Logo do Markdown")

♦ **Imagem com link** → faz a imagem ir para um link. **\[![ ](URL img)](link)**.

[![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png)](https://commons.wikimedia.org/wiki/File:Markdown-mark.svg)


___

## 2.12. Emojis

São representados entre símbolos de **:emoji:**

:eyes:  :muscle:  :clap:  :+1:

👀      💪       👏      👍

► Emoji-Cheat-Sheet  
► https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

___

<div class="footer">
    <center>&copy; 2022 Karine s m Rodrigues</center>
</div>