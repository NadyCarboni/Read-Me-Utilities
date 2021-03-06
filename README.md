
<img src ="https://media1.giphy.com/media/mjQG3C8g8Uzc9Cv09F/giphy.gif?cid=ecf05e475a1dncy3l27nfaagug0ioemtsvcw913fznlftm6j&rid=giphy.gif&ct=s" width = "100px" height = "auto"> 


# Read-Me: Utilities <img src ="https://media1.giphy.com/media/e8dLRPN6d6V4iJIOUn/giphy.gif?cid=ecf05e47masc7atthyt1mq5r2f3jih5w2wfw13t0u0r28x10&rid=giphy.gif&ct=s" width = "40px" height = "auto"> 
Esse repositório tem a finalidade de colocar utilidades para se reutilizar em README's de futuros repositórios :). Por algum motivo, a sintaxe do Markdown não me vinha de forma tão natural quanto o HTML, e na tentativa de mudar isso (ou pelo menos ter uma colinha fácil à mãos), resolvi criar esse repositório com as marcações, e algum atalhos com utilidades diversas :)
<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Tópicos
- [Headers](#Headers)
- [Links](#Links)
- [Imagens](#Imagens)
- [Edições de texto (Negrito, itálico e etc...)](#Edições-de-Texto)
- [Códigos](#Códigos)
- [Listas ordenadas](#Listas-ordenadas)
- [Listas não ordenadas](#Listas-não-ordenadas)
- [Checkbox](#Checkbox)
- [Quotes](#Quotes)
- [Tabelas](#Tabelas)
- [Centralizar texto](#Centralizar-texto)
- [Utilidades+](#Utilidades)
- [Créditos](#Créditos)

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Headers
Headers ou cabeçalhos são equivalentes as tags H1, H2, H3, H4, H5 e H6 do HTML.

Para utilizar os headers no Markdown você deve colocar "#"s na frente do seu texto. O nímero de **"#"s** deve ser **igual ao número do cabeçalho** que você deseja.

Código:
```
# Isso é um texto H1
## Isso é um texto H2
### Isso é um texto H3
#### Isso é um texto H4
##### Isso é um texto H5
###### Isso é um texto H6
```
**Isso resulta:**

![image](https://user-images.githubusercontent.com/69855489/124361710-dcf6ac00-dc06-11eb-88ac-f4b64c14c05d.png)

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Links
Links são referentes as tags `<a></a>` no HTML.

**Como funciona a sintaxe?**
```
[Aqui você "nomeia" o link](E Aqui você insere o endereço do link)
```
**Exemplo funcional:**

```
[Isso é um link](https://www.youtube.com/watch?v=Wgw6tJ8yz9M)
```
**Isso resulta:** 
[Isso é um link](https://www.youtube.com/watch?v=Wgw6tJ8yz9M)

### Como colocar um link que está dentro do próprio README:
Você deve colocar no endereço um "#" seguido pelo título do cabeçalho.

```
[Aqui você "nomeia" o link](#Aqui-você-coloca-o-título)
```
**Isso resulta:**

[Aqui você "nomeia" o link](#Aqui-você-coloca-o-título)

###### Aqui você coloca o título
E ao clicar nesse link você é redirecionado para o cabeçalho à cima :) 


<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Imagens
A imagens são similares aos links no Markdown
```
![Alt da imagem](Aqui o endereço)
```

**Exemplo Real**
```
![Plantinha](https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&ct=s)
```
**Isso resulta:**

![Plantinha](https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&ct=s)

### Porém eu prefiro utilizar a tag HTML, nesse caso:
```
<img src ="https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&c"> 
```

**O resultado é o mesmo:**

<img src ="https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&c"> 

### E você também pode redimensionar a imagem.
Adicionando as propriedades Height e Width na imagem:
```
<img src ="https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&c" 
height="100px" width="auto"> 
```
**Isso resulta:**

<img src ="https://media3.giphy.com/media/daa8oT5L8Ox3ffWVjr/giphy.gif?cid=ecf05e47bsgonexr02yo6k2b72un2v41dgenbuinl2k47078&rid=giphy.gif&c" 
height="150px" width="auto">  

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Edições de Texto

### Negrito: 

```
**(Coloque o texto entre dois asterísticos assim)**
```
Resultado:

**(Coloque o texto entre dois asterísticos assim)**

### Itálico:
```
*Coloque o texto entre asterísticos assim*
```
Resultado:

*Coloque o texto entre asterísticos assim*

### Tachado:

```
~~Coloque o texto entre "tios" assim~~
```
Resultado:

~~Coloque o texto entre "tios" assim~~

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Códigos

### Blocos de código:
Para colocar um bloco de códigos você dele usar três crases no começo, e mais três crases no fim. 

```
      ```
      ```
```

**Resultado:**
```

```

### Código embutido:
Para colocar código embutido você deve usar as crases assim:
```
  `Isso é um código embutido`
```
**Resultado:**
`Isso é um código embutido`

### Como "colorir" parte dos códigos:
``` 
```diff
- Texto vermelho
+ Texto verde
! Texto laranja
# Texto cinza
@@ Texto roxo@@ ``` 
``` 

**Isso resulta:**

```diff
- Texto vermelho
+ Texto verde
! Texto laranja
# Texto cinza
@@ Texto roxo@@
```

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Listas ordenadas
Referentes as `<ol></ol>` no HTML

```
1. Tópico 1
2. Tópico 2
```

**Resultado:**

1. Tópico 1
2. Tópico 2

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>


## Listas não ordenadas
Referentes as `<ul></ul>` no HTML

```
- Tópico 1
- Tópico 2
```

**Resultado:**

- Tópico 1
- Tópico 2

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Checkbox

Para usar as checkbox, você deve:

```
- [ ] Tópico 1
- [x] Tópico 2
- [x] Tópico 3
- [ ] Tópico 4
```
**Isso resulta:**
- [ ] Tópico 1
- [x] Tópico 2
- [x] Tópico 3
- [ ] Tópico 4
<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Quotes

```
> Isso é uma citação.
```
**Resultado:**
> Isso é uma citação

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Tabelas

```
Cabeçalho 1 | Cabeçalho 2
------------ | -------------
Conteúdo 1 | Conteúdo 2
Conteúdo 2 | Conteúdo 4
```
**Resultado**

Cabeçalho 1 | Cabeçalho 2
------------ | -------------
Conteúdo 1 | Conteúdo 2
Conteúdo 2 | Conteúdo 4

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Centralizar texto
Para centralizar o texto eu gosto de novamente usar uma tag HTML, nesse caso a p de parágrafo.

```
<p Align=center>
Isso é um texto centralizado
</p>
```
**Resultado:**
<p Align=center>
Isso é um texto centralizado
</p>

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>

## Utilidades

Link | Para
------------ | -------------
[Divisórias - tumblr](https://www.tumblr.com/search/divider)| Divisórias para organizar o texto e decoração
[Divisórias - Deviantart](https://www.deviantart.com/search?q=divider) | Divisórias para organizar o texto e decoração
[Gifs - Giphy ](https://giphy.com/stickers) | Decoração
[Mini Gifs - SweetMagic](https://www.asweetmagic.com.br/2017/06/mini-gifs-kawaii-variados.html) | Decoração
[Icones - icons8](https://icons8.com/icons) | Decoração e melhor usabilidade


<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>


## Créditos:
<img src ="https://media2.giphy.com/media/2gj0dN1E4f9xUP21Yx/giphy.gif?cid=ecf05e47oxlqgdbw4v6yg8ntwp24n8bzto7sx1zzr7maose0&rid=giphy.gif&ct=s" height="20px" width="auto"> [Como fazer um README.md BONITÃO](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8) 

<img src ="https://media2.giphy.com/media/2gj0dN1E4f9xUP21Yx/giphy.gif?cid=ecf05e47oxlqgdbw4v6yg8ntwp24n8bzto7sx1zzr7maose0&rid=giphy.gif&ct=s" height="20px" width="auto">    [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

<p Align=center>
<img src ="https://64.media.tumblr.com/39240cabb4a10556459808190bd79195/cb61da9def746b60-be/s1280x1920/0f2196b58ec8bf38f21292d5a9fb7913e9245f39.png" height="5px" width="100%"> </p>


### Até mais!

<img src ="https://media1.giphy.com/media/mjQG3C8g8Uzc9Cv09F/giphy.gif?cid=ecf05e475a1dncy3l27nfaagug0ioemtsvcw913fznlftm6j&rid=giphy.gif&ct=s" width = "100px" height = "auto"> 




