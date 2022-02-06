<div id="topo">
 
# ☺ MARKDOWN ✍ 

**Markdown** é uma linguagem simples de marcação originalmente criada por John Gruber e Aaron Swartz que converte texto em HTML válido.  
Markdown é frequentemente usado para formatar arquivos *README.md*, para escrever mensagens em fóruns de discussão online e para criar rich text usando um editor de texto simples.

A rede social para desenvolvedores: **Github** é compatível com a linguagem Markdown. 

Os arquivos *README.md* dos repositórios no Github, são feitos com a linguagem Markdown.

`.md` → é a extensão para os arquivos em Markdown.

Outra linguagem de marcação é a *HTML*.  
Essas linguagens são para desenvolvimento. Não são linguagens de programação. 

___

<div id="topicos">
 
## ▼ Tópicos do conteúdo 
 
📌 Comandos básicos                 | 📌 Links               | 📌 Designer            | 📌 Comandos de blocos      | 📌 Menções |
---                                  | ---                    | ---                    | ---                         | ---         |
🔹 [Hierárquia de títulos](#titulos) | 🔹 [Âncoras](#ancoras) | 🔹 [Imagens](#img)     | 🔹 [Citação](#citar)        | 🔹         |
🔹 [Linha horizontal](#hr)           | 🔹 [Links](#links)     | 🔹 [Emojis](#emojis)   | 🔹 [Inserir códigos](#code) | 🔹         |
🔹 [Parágrafos](#p)                  | 🔹                     | 🔹                     | 🔹                          | 🔹         |
🔹 [Quebra de linha](#br)            | 🔹                     | 🔹                     | 🔹                          | 🔹         |
🔹 [Formatação básica](#formatar)    | 🔹                     | 🔹                     | 🔹                          | 🔹         |
🔹 [Inserir símbolos](#simbolos)     | 🔹                     | 🔹                     | 🔹                          | 🔹         | 
 
___
 
<div id="titulos">

## ░ Hierárquia de títulos 

- \# Título nível 1
- \## Título nível 2
- \### Título nível 3
- \#### Título nível 4
- \##### Título nível 5
- \###### Título nível 6 

☞ Pode-se também fazer o título e subtítulo assim:
~~~
Título principal 
===

Subtítulo 
---
~~~

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape) 
___

<div id="hr">
 
## ░ Linha horizontal

- 3 traços \---
- 3 asteriscos \***
- 3 underlines ___

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="p">
 
## ░ Parágrafos

Você pode criar um novo parágrafo **deixando uma linha em branco** entre as linhas de texto.

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___

<div id="br">

## ░ Quebra de linha

Pode-se usar **2 espaços no final da linha** ou a tag \<br> - quebra de linha do HTML no arquivo em Markdown.  
☞ As tags HTML são aceitas em Markdown.

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="formatar">
 
## ░ Formatação básica

**▬ Negrito:** São 2 asteriscos ou 2 underlines ou Ctrl B. `**negrito** ou __negrito__`  **texto em negrito**

**_▬ Itálico:_** é 1 asterisco ou 1 underline ou Ctrl I. `*itálico* ou _itálico_`  *texto em itálico*

**▬ Texto excluído:** são 2 tils. `~~riscado~~` ~~texto excluído~~

**▬ Negrito-itálico:** são 2 asteriscos e 1 underline. `**_negrito-itálico_**` *__texto em negrito-itálico__* 

**▬ Todo o texto em negrito-itálico:** são 3 asteriscos ou 3 underlines. `***Tudo em negrito e itálico*** ou ___tudo em negrito e itálico___` ***Tudo em negrito e itálico de forma mais simples.***

‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ 
 
Isso é possível em Markdown?  
🟡 Texto  sublinhado  
🟡 Texto marcado com cor  
‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="simbolos">
 
## ░ Inserir símbolos no texto

Para mostrar exatamente o símbolo basta usar uma barra invertida `\` antes do símbolo. Isso faz parar o efeito de formatação.
 
Exemplo: `\#` mostrará o símbolo \# sem o efeito de título. 
 
\# Título sem a formatação padrão.

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="citar">
 
## ░ Citação
 
O sinal de `>` no início da linha indica uma citação. 

> Você pode citar automaticamente o texto em um *comentário* ***destacando o texto e digitando R***.

### ⚪ Citação aninhada

Para criar um bloco aninhado de citações, utilize **2 ou mais sinais de maior que** `>>` antes do parágrafo.
 
~~~
> Resultado da citação aninhada
>
>> citação nível 2
>> 
>>> citação nível 3
>>> 
>>>> citação nível 4
>>>>
~~~
> Resultado da citação aninhada
>
>> citação nível 2
>> 
>>> citação nível 3
>>> 
>>>> citação nível 4
>>>>
<br>
 
[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="code">

## ░ Inserir códigos de linguagens

▬ **Código inline →** colocar entre crases \` \` O código delimitado ou **Ctrl E**. Isso faz o texto ficar com uma fonte monoespaçada e com fundo acinzentado para dar destaque. Exemplo: `window.document.querySelector()` é escrito em linguagem JavaScript.

### ⚪ Código de bloco
 
Basta colocar o código entre 3 crases ``` ou 3 tils ~~~ consecutivos sem espaço entre eles.  
Exemplo logo abaixo.

\~\~\~ python  
 num = int(input('Digite um número: '))  
 if num % 2 == 0:  
     print(f'O valor {num} é PAR')  
 else:  
     print(f'O valor {num} é ÍMPAR')  
 print('Fim do Programa')  
\~\~\~ 
 
~~~ python
    num = int(input('Digite um número: ')) 
    if num % 2 == 0: 
        print(f'O valor {num} é PAR') 
    else: 
        print(f'O valor {num} é ÍMPAR') 
    print('Fim do Programa') 
~~~

### ⚪ Código de bloco simples
 
Basta colocar **4 espaços** antes do texto para abrir o espaço reservado. 

    Exemplo para textos.

    ☞ Essa forma não é indicada para colocar trechos de linguagens de programação.

### ⚪ Mostrar símbolos da formatação no bloco
 
Para exibir acentos graves triplos ou til triplos em um bloco de código, envolva-os dentro de acentos graves quádruplos.

~~~~
```
        Esse é um bloco de código para colocar linguagens de programação entre outros.  
    Seus símbolos de formatação estão vizíveis graças a acentos graves quaádruplos. 
```
~~~~
 
[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___
 
<div id="links">
 
## ░ Links 

O símbolo `[descrição](URL "title")` → onde a descrição fica entre colchetes e o endereço do link entre parênteses. O title tem a mesma função da tag \<title> no HTML, ele mostra uma mensagem ao passar o mouse sobre o link.
 
Para colocar o símbolo de forma prárica pressione **Ctrl K** no teclado.

Exemplo: [Pesquisa Google](https://www.google.com/ "Esse link abre a página na mesma ABA de seu navegador!")

### ⚪ Link relativo 
 
É o link interno do site. Exemplo: `[link](docs/markdown.md)` → pode usar os **operandos ./ e ../** para acessar as pastas.

### ⚪ Link direto
 
É o endereço da web entre **chaves <>** ou a URL completa colada na página. Exemplo: <https://www.google.com/>

 ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗
 
   É possível colocar um link em Markdown:  
🟡 Que abra em outra aba do navegador?  
‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗ ‗  ‗ ‗ ‗ ‗ 

 
[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___ 

<div id="ancoras">
 
## ░ Âncoras

Fazer âncoras no texto, ou seja, links dentro do texto.

`[Tópicos](#topicos)` → leva a página até o conteúdo referenciado por uma div `<div id="topicos">` 

☞ Exemplo: [Voltar para Tópicos](#topicos)

⚓ Com esse exemplo é possível criar sumários e índices de tópicos no texto.
 
[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___ 
 
<div id="img">
 
## ░ Imagens
 
O símbolo `![]()` ☛ `![alt](URL "title")` → onde o texto alternativo fica entre colchetes, o link da imagem entre parêntesis e a descrição da imagem entre aspas duplas - ao passar o mouse sobre ela vai mostrar um texto. Tem a mesma função da tag <title> do HTML.

![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png "Logo do Markdown")
 
✅ A função do texto alternativo é primordial, pois caso a imagem não carregar na página - aparecerá o ícone de link quebrado + o texto alternativo. Exemplo: ![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.pn)

### ⚪ Imagem como link
 
A imagem como link faz ir para um endereço de página diferente do endereço da imagem colocado.  
Para isso, basta colocar o símbolo da imagem `![alt](URL "title")` entre colchetes `[![alt](URL "title")]` e depois o endereço que será referenciado entre parêntesis `(link)` ↔ `[![alt](URL "title")](link)`.

[![Wiki Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png)](https://commons.wikimedia.org/wiki/File:Markdown-mark.svg "Wiki Markdown")

[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___ 
  
<div id="emojis">

## Emojis

 🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨🟨
 
São representações de ícones, pequenos símbolos inseridos por `: :` → `:eyes:` = 👀
 
✔️ Forma prática de inserir um emoji é digitar `:` depois as primeiras letras do emoji (em inglês) que abrirá uma guia com emojis.
 
🙃 Exemplos de emojis  
 
 Código                     | emoji
 :---                       | :---:
 `:warning:`                | ⚠️
 `:heavy_check_mark:`       | ✔️
 `:alien: `                 | 👽
 `:memo:`                   | 📝
 `:pushpin:`                | 📌
 `:sunny:`                  | ☀️
 `:sweat_drops:`            | 💦
 `:vertical_traffic_light:` | 🚦
 `:interrobang:`            | ⁉️
 `:white_circle:`           | ⚪
 `:octocat:`                | :octocat:
 
‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗
- `alt 1` = ☺   
- `alt 3` = ♥
- `alt 4` = ♦
- `alt 11` = ♂
- `alt 12` = ♀
- `alt 18` = ↕
- `alt 19` = ‼
- `alt 29` = ↔
- `alt 176` = ░
- `alt 177` = ▒
- `alt 178` = ▓
- `alt 219` = █  
 
‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗‗
  
☠ Outros exemplos de emojis:
 
☚ ☛  ☜  ☝  ☞  ☟  ✌   ✍  ☁  ☄ ☀ ♨ ❄  ✟ ☎ ✂ ☢ ⌛  ✏ ✎ 
 
✔️ [Lista completa de emojis](https://github.com/ikatyang/emoji-cheat-sheet)🔗

<br>
 
[Introdução](#topo) - [Tópicos](#topicos) - [Rodapé](#rodape)
___ 
 

 ___

<div id="rodape">
 
[Introdução](#topo) - [Tópicos](#topicos) 
  
<div class="footer">
    &copy; 2022 Karine s m Rodrigues
</div>
