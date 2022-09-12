# newblog

1) instalar o pacote Franklin.jl

```
pkg> add Franklin
```
2) rodar localmente:

```
julia> using Franklin
julia> serve()
```

# guia de estilo do post

novas entradas devem ser adicionadas no arquivo *index.md* formatados dessa forma

```
<!-- note que nessa caso " Título do Post" (respeitar o espaçamento) vai servir para referenciar o post em indice.md --> 
## Título do Post
#### Subtítulo do Post
~~~
<!-- adicionar esse caso seja necessário referenciar post original -->
<div style="text-align: right"><a href="https://linkparapostoriginal"><i>publicado originalmente em [DATA DO POST ORIGINAL]<i></a></div>
<br>
<!-- data do post: -->
<div style="text-align: right">><i>[DATA DO POST]<i></div>
<br>
~~~

Lorem ipsum dolor sit amet, [REFERÊNCIA](https://linkdareferencia). Aenean nisi sem, commodo ut sapien sit amet...

<--! inserir imagem (a imagem deve ser armazenada em /assets) -->
~~~
<div class="row">
  <div class="container">
    <center><img class="center" src="/assets/imagem.jpeg">
    <figcaption>Caption da Imagem (Foto: <a href="https://urldafonte.com">Didssph @Unsplash</a>)</figcaption></center>     
  </div>
</div>
<br>
~~~

## Tópico 1

Vestibulum tincidunt, magna sed sodales placerat, tellus elit aliquet diam, a fringilla neque mi sit amet nulla...

### Tópico 2

Proin eleifend ut dui eget efficitur. Praesent ultrices, elit sed sagittis gravida, risus est eleifend diam...

```

e no arquivo *indice.md*, inserir link para novo post:

```
- [Título do Post](/## Título do Post)
```



