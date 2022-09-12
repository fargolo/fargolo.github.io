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

Lorem ipsum dolor sit amet, [REFERÊNCIA](https://linkdareferencia). Aenean nisi sem, commodo ut sapien sit amet, eleifend ullamcorper urna. Ut bibendum libero pellentesque nulla sodales, quis iaculis turpis dignissim. Ut malesuada ex ut ipsum lobortis, id cursus nulla euismod. Donec dapibus vel lacus id ultrices. Proin tempus laoreet sapien at ullamcorper. In ut vulputate arcu. Curabitur enim nisi, varius at ligula sit amet, accumsan fringilla turpis. Donec et ornare metus. Etiam et nulla non lorem mattis aliquam vel eu nunc. Etiam rutrum purus eget magna tincidunt dictum. Ut luctus dui sed nulla pellentesque, nec bibendum neque consectetur. Morbi nulla libero, vestibulum vel velit tristique, vehicula gravida mauris. Sed suscipit laoreet metus non accumsan. Proin in justo interdum, rutrum felis a, fringilla diam.

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

Vestibulum tincidunt, magna sed sodales placerat, tellus elit aliquet diam, a fringilla neque mi sit amet nulla. Vestibulum vestibulum nunc et purus aliquam tempus. Nulla in urna eros. Nullam suscipit laoreet suscipit. Praesent auctor consectetur lectus eget malesuada. Sed placerat in urna sit amet interdum. Donec quam lectus, placerat sit amet ex at, commodo auctor risus. Etiam vestibulum libero nunc, vulputate commodo nulla consequat sed. Phasellus placerat urna id molestie blandit. Etiam eu mollis augue. Vestibulum feugiat ante ut ligula imperdiet, at auctor augue molestie. Pellentesque mattis bibendum nulla, eget malesuada erat eleifend ac. Sed id orci et ante placerat lobortis vitae et tortor. Sed lobortis nisl quis massa convallis, varius consequat felis bibendum. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae;

### Tópico 2

Proin eleifend ut dui eget efficitur. Praesent ultrices, elit sed sagittis gravida, risus est eleifend diam, at porttitor nisi augue sit amet turpis. Curabitur ac condimentum arcu. Quisque dictum nulla est, eget pretium ipsum maximus pretium. Sed sit amet sem id ex suscipit ultrices. Ut et sagittis elit. Curabitur in pharetra enim. Fusce ut tincidunt nisi, sit amet mollis nisl. Sed a tortor aliquet purus scelerisque consequat. Morbi ultricies vitae lorem a tempus. Nam non sagittis dui, ac fringilla justo. In rhoncus odio nec eros dignissim suscipit.
```

e no arquivo *indice.md*, inserir link para novo post:

```
- [Título do Post](/## Título do Post)
```



