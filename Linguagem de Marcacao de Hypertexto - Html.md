Elementos obrigatórios

<!doctype html> O Doctype é uma instrução obrigatória e permite que seja informado ao navegador ou dispositivo o tipo de documento a ser carregado, permitindo assim a correta renderização da página.
<html> Tal elemento é a raiz do documento. Logo, e lembrando que o código HTML é composto por uma estrutura hierárquica de tags, podemos dizer que a <html> é a raiz da árvore do documento.
    <head>
    Cabeçalho do documento. Fazendo analogia ao corpo humano, devemos vê-la como a cabeça, uma vez que contém as tags que serão usadas para manter todo o documento funcionando e em ordem.
                     Tags que fazem parte do cabeçalho:
    <title> = É o título do documento, sendo visualizada na barra de título do navegador.
    <meta> = Engloba uma série de informações – comumente chamadas de metainformações – como a descrição da página, palavras-chave etc.
    <script> = É responsável pela inclusão e/ou definição de scripts relacionados ao documento.
    <link> = É responsável pela inclusão de folhas de estilo (externas) relacionadas ao documento. Também possibilita a inclusão de favicons (pequenos ícones que aparecem na barra de endereços do navegador).
    <style> = Assim como a anterior, é responsável pelo vínculo de folhas de estilo ao documento − quando elas são declaradas diretamente no documento.-->
    </head>  
    <body>
        <img src=”imagem.jpg” alt=”minha imagem” />
    <!--Esta é responsável pela estruturação do documento, sobretudo de seu conteúdo e também apresentação – embora seja fortemente recomendado que a apresentação do documento, como será visto no módulo específico, seja feita por meio de folhas de estilo (CSS).
    Quando navegamos em um website, todo o conteúdo que vemos – os textos, imagens e demais elementos – está contido na tag <body>.-->
    </body>
</html>
<!--Estrutura básica de uma página Web-->

O que são Tags?

Como visto nos exemplos do módulo anterior, 
tags são palavras, escritas entre os caracteres de menor “<” e maior “>” e que servem 
para informar ao navegador a estrutura e o significado do conteúdo inserido em uma página Web.-->

Tipos e composição das tags

    As tags podem ser divididas em tipos, de acordo com as suas funções: Estruturais, textuais e semânticas. Outra característica importante é que elas também podem ter atributos.

    ID = Utilizado para definir um identificador, que deve ser único, para uma tag em um documento.
    CLASS = Usado para definir uma classe à qual uma ou mais tags pertencem. Com base nesses dois tipos de identificação, é possível, por exemplo, fazer referência a um ou mais atributos para inserirmos estilização visual nas páginas, através de Folhas de Estilo ou eventos e interação, através de Javascript.

    Tipos de tags: textuais e semânticas

Até aqui, conhecemos algumas tags associadas à estrutura, dita obrigatória, de uma página. Também vimos que, na maioria dos casos, as páginas Web possuem uma mesma estrutura em termos de conteúdo. A seguir, conheceremos os tipos de tag textuais e semânticos.

Tags textuais

São responsáveis por organizar o conteúdo da página, ou seja, textos, mídias e links, por exemplo. Algumas das principais tags textuais, inclusive vistas anteriormente, são: <p>, <h1> ... <h6>, <img> e <a>. Essas tags e suas funções serão descritas a seguir.

Tags semânticas

A partir da HTML5 foram inseridas tags com a função semântica de organizar a estrutura de conteúdo de uma página.
