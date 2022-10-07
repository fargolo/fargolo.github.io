# Fluxo de postagens  

1 . Se for nova categoria:  
1.1 Criar diretório para categoria (e.g."/esportes/")  
1.2 Criar post dentro do diretório (e.g."esportes/nome-do-post.md")  
1.3 Criar indíce para categoria na pasta raiz (e.g."/indice-esportes.md") com +++ estrutura de title, hascode, rss, rss_title, tags +++ e depois linkar posts da seguinte forma:  
1.3.1 [Nome que será linkado](/esportes/nome-do-post)  
1.3.2 Alterar \_layout/sidebar.html incluindo novo \<nav class> alterando "ispage", "href" e texto de referência (e.g. olhar exemplos no próprio arquivo sidebar.html  
