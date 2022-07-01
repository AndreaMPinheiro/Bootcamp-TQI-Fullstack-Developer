## HTML5

Com o HTML definimos o significado e a estrutura do conteúdo da web e, além de texto, nossas páginas precisam de imagens, vídeos e vários outros formatos e para isso temos os elementos HTML.

Um elemento HTML é formado pela tag de abertura e seus atributos, o conteúdo e uma tag de fechamento. Mas também pode exirtir elementos que não tem tag de fechamento. 

Com esses elementos podemos agrupar tipos de conteúdo, alterar tamanho e forma de fontes e adicionar diferentes mídias a página da web que criamos.



- <html> a tag html é a raiz do documento, todos os elementos HTML devem estar dentro dela, também informar qual o idioma do documento utilizando o atributo "lang", para o português brasileiro usamos pt-BR.
- <head> a tag head contém elementos que serão lidos pelo navegador, como os metadados - um exemplo é o charset, que é a codificação de caracteres e a mais comum é a UTF-8, o JavaScript com a tag script, o CSS através das tags style e link.
- <body> a tag body é onde colocamos todo o conteúdo visível ao usuário: textos, imagens, vídeos.

### Semântica

Durante muitos anos o elemtno padrão no HTML era a "div", construíamos nosso conteúdo todo baseado nela, e assim nascia a sopa de divs.

A semântica nos permite descrever mais precisamente o nosso conteúdo, agora um bloco de texto não é apenas uma div, agora é um article e tem mais significado assim. Alguns elementos para ressignificar as divs:

- <section> Representa uma seção genérica de conteúdo quando não houver um elemento mais especifíco para isso.
- <header> É o cabeçalho da página ou de uma seção dapágina e normalmente contém logotipos, menus, campos de busca.
- <article> Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.
- <aside> É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografica do autor e publicidade.Normalmente são representadas como barras laterais.
- <footer> Esse elemetnos representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um footer são informações de autor e links relacionados. 
- <h1><h6> Eles não foram criados na versão 5 do HTML e nem são específicos para semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo <h1> o mais importante e <h6> o menos. Uma dica: use apenas um h1 por página, pois ele representa o objetivo da sua página. 



