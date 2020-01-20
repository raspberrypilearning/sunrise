## Introdução

Neste projeto irás aprender a utilizar CSS para criar uma animação do nascer do sol.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Informações adicionais para os líderes do clube

Se precisar imprimir este projeto, por favor, use a [versão para impressão](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Notas de líder de clube

## Introdução:

Neste projeto, os participantes vão aprender a como animar uma cena simples utilizando CSS. Vão utilizar a regra das @keyframes CSS para animar várias propriedades de imagens e divs.

## Recursos online

Recomendamos usar o [trinket](https://trinket.io/) para codificar HTML & CSS online. Este projeto contém os seguintes trinkets:

+ ["Nascer do Sol" ponto de partida](http://jumpto.cc/web-sunrise)

Os participante podem também utilizar este trinket em branco [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) para escrever o seu próprio HTML & CSS, ou alternativamente usar este modelo de trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Há também um trinket que contém uma amostra de solução para os desafios:

+ ["Nascer do Sol" terminado](https://trinket.io/html/abcc0284a3)

## Recursos offline

Este projeto pode ser [ concluído offline ](../offline.html), se preferires. Podes ter acesso aos recursos do projeto clicando no link 'Materiais de Projeto' deste projeto. Este link contém uma secção 'Recursos do projeto', que inclui recursos de que os participantes necessitam para concluir este projeto offline. Certifique-se de que cada participante tem acesso a uma cópia destes recursos. Esta pasta inclui os seguintes arquivos:

+ template/index.html
+ template/prefix.js
+ template/style.css
+ shares/index.html
+ shares/style.css
+ shares/prefixfree.js
+ shares/boat.png
+ shares/cloud.png
+ shares/helicopter.png
+ shares/rainbow.png
+ shares/sun.png

Também pode encontrar uma versão completa dos desafios deste projeto na secção 'Recursos para Voluntários', que contém:

+ recipe-finished/index.html
+ recipe-finished/style.css
+ recipe-finished/prefixfree.js
+ recipe-finished/boat.png
+ recipe-finished/sun.png
+ recipe-finished/rainbow.png

## Objetivos de Aprendizagem

+ Criar estilos e animar com CSS: 
    + Introduzir regras `@keyframes` para definir passos na animação.
    + Reforçar o uso de propriedades para definir o tamanho, forma, posição e cor de elementos numa página web.

Este projeto abrange elementos das seguintes vertentes do [ Curriculo Raspberry Pi Digital Making ](http://rpf.io/curriculum):

+ [ Criar conteúdos básicos em 2D e 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Desafios

+ "Animação diagonal" - restantes propriedades `@keyframe` de edição de animação;
+ "Melhorar o céu" - acrescentar mais keyframes e definir o pano de fundo;
+ "Mais animação" - animar mais imagens ou elementos utilizando diversas propriedades CSS. 

## Perguntas Frequentes

+ Este projeto faz uso da bilioteca javascript `prefixfree.js`, para permitir compatibilidade da animação entre browsers. Se esta biblioteca não for utilizada, os utilizadores que usem navegadores mais antigos terão necessidade de declarar uma animação para o seu navegador, por exemplo:

    -animation: sky 10s infinite;            //para todos os novos navegadores
    -webkit-animation: sky 10s infinite;    // Para navegadores Webkit (Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // Para navegadores Mozilla
    -o-animation: sky 10s infinite;         // Para navegadores Opera
    -ms-animation: sky 10s infinite;        // Para navegadores Microsoft 
    

\--- /collapse \---

## \--- collapse \---

## title: Materiais do projeto

## Recursos do projeto

+ [Arquivo.zip contendo todos os recursos do projeto](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Trinket on-line contendo todos os recursos do projeto 'Nascer do Sol!'](http://jumpto.cc/web-sunrise)
+ [Modelo on-line para Trinket](http://jumpto.cc/trinket-template)
+ [Trinket em branco on-line](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
+ [wanted/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
+ [wanted/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
+ [shares/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
+ [shares/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
+ [shares/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
+ [shares/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
+ [shares/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
+ [shares/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
+ [shares/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
+ [shares/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Recursos do líder de clube

+ [Arquivo.zip contendo todos os recursos do projeto concluído](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Projeto Trinket concluido on-line](https://trinket.io/html/abcc0284a3)
+ [recipe-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [recipe-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [recipe-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [recipe-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [recipe-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [recipe-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---