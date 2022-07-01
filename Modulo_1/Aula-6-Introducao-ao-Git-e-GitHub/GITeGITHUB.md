### Introdução ao Git e ao GitHub



Git e GitHub não são a mesma coisa, são duas tecnologias diferentes,complementares porem diferentes.  

**Git** é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

O SHA1 é um algoritmo de encriptação, falando a grosso modo ele vai pegar o seu algoritmo, seja uma foto, imagem ou uma frase e vai embaralhar ele de uma forma muito especifica. A saída dessa encriptação gera um conjunto de caracteres de 40 dígitos que é único e serve como identificação. É uma forma curta de representar um arquivo.

Git é um Sistema distribuído Seguro. O terminal do git é o Git Bash (no Windows)

O Git possui 3 objetos internos, são eles o Blob,Trees e Commits

Primeiro objeto Blob: Os arquivos ficam guardados dentro do “Blob”. O git vai guardar os arquivos fazendo um “sha” deles, contendo metadados nesses objetos que é o Blob.

Segundo Objeto são as Tree (arvores), ela é uma crescente, armazena e apontam para blob e tree, e ela guarda o nome do arquivo. 

As tree apontam para outras tree ou para os blob. 

Tree retém informações dos arquivos, apontam para blob ou tree.

 Terceiro Objeto é o Commit – ele é o objeto que vai juntar tudo, que vai dar sentido para as alterações que o usuário faz. 

 

**GitHub **é um repositório online onde armazenamos o nosso código. 

Ele disponibiliza repositórios Git, ou seja, é uma forma de trabalhar com o Git, mas de forma centralizada. Podemos desenvolver a aplicação,localmente, e quando quisermos, podemos subi-la para um repositório online e centralizar o conteúdo. 