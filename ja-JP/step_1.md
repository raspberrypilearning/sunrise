## はじめに

In this project, you'll learn how to use CSS to create an animated sunrise.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### クラブリーダーのための追加情報

このプロジェクトを印刷する必要がある場合は、 [印刷用バージョン](https://projects.raspberrypi.org/en/projects/sunrise/print)を使用してください。

## \--- collapse \---

## title：クラブリーダー・ノート

## はじめに

In this project, children will to learn how to animate a simple scene using CSS. They will use the CSS @keyframes rule to animate various properties of images and divs.

## オンライン・リソース

We recommend using [trinket](https://trinket.io/) to write HTML & CSS online. This project contains the following trinkets:

+ ['Sunrise' starting point](https://trinket.io/html/web-sunrise)

Children can also make use of this blank trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) to write their own HTML & CSS, or alternatively they can use this template trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

また、チャレンジ(課題)に対しての回答例を含むtrinketもあります(以下参照)。

+ ['Sunrise' Finished](https://trinket.io/html/abcc0284a3)

## オフライン・リソース

このプロジェクトは[オフライン](../offline.html)で完成することが可能です。 You can access the project resources by clicking the 'Download Project Materials' link for this project. This link contains a 'Project Resources' folder, which includes resources that children will need to complete this project offline. 、必ず子供達各自が必要資料を全て持っているようにしてください。 This folder includes the following files:

+ template/index.html
+ template/prefix.js
+ template/style.css
+ sunrise/index.html
+ sunrise/style.css
+ sunrise/prefixfree.js
+ sunrise/boat.png
+ sunrise/cloud.png
+ sunrise/helicopter.png
+ sunrise/rainbow.png
+ sunrise/sun.png

なお、プロジェクト課題の完成版をボランティア・リソースのセクションに含まれています。

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## 学習目標

+ Styling and animation with CSS: 
    + Introducing `@keyframes` rule for defining steps in an animation.
    + Reinforcing the use of properties to define the size, shape, position and colour of elements on a webpage.

このプロジェクトでは [Raspberry Pi デジタル・メイキング・カリキュラム](http://rpf.io/curriculum)（英語）の柱の一つである、プログラミングの以下の要素を学びます。

+ [Design basic 2D and 3D assets](https://www.raspberrypi.org/curriculum/design/creator).

## チャレンジ

+ "Diagonal animation" - editing animation `@keyframe` properties to use left:;
+ "Improve the sky" - add more keyframes and setting background:.
+ "More animation" - animate more images or elements using a variety of CSS properties. 

## よくある質問

+ This project makes use of the javascript `prefixfree.js` library, to allow animation compatibility between browsers. If this library isn't used, then children using older browsers will instead need to declare an animation for their browser, for example:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title：プロジェクト資料

## プロジェクト資料

+ [全プロジェクト・リソースの入った.zipファイル](resources/sunrise-project-resources.zip)
+ [Online Trinket containing all 'Sunrise' project resources](http://jumpto.cc/web-sunrise)
+ [Online Trinket template](http://jumpto.cc/trinket-template)
+ [Online blank Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](resources/template-index.html)
+ [template/style.css](resources/template-style.css)
+ [intro/index.html](resources/intro-index.html)
+ [intro/style.css](resources/intro-style.css)
+ [sunrise/index.html](resources/sunrise-index.html)
+ [sunrise/style.css](resources/sunrise-style.css)
+ [sunrise/prefixfree.js](resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](resources/sunrise-sun.png)
+ [sunrise/rainbow.png](resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](resources/sunrise-cloud.png)
+ [sunrise/boat.png](resources/sunrise-boat.png)
+ [sunrise/helicopter.png](resources/sunrise-helicopter.png)

## クラブ・リーダー向けリソース

+ [全プロジェクトの完成版リソースの入った.zipファイル](resources/sunrise-volunteer-resources.zip)
+ [完成版プロジェクトのオンラインtrinket](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /collapse \---