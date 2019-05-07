## はじめに

このプロジェクトでは、CSSを使った日の出のアニメーションのつくり方を学びます。

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### 指導者のための追加情報

このプロジェクトを印刷する必要がある場合は、 [印刷用バージョン](https://projects.raspberrypi.org/en/projects/sunrise/print)を使用してください。

## \--- collapse \---

## title：指導者の方へ

## はじめに

このプロジェクトで、子供たちはCSSを使った簡単なシーンのアニメーションのつくり方を学びます。 imageタグとdivタグのプロパティを、CSSの@keyframesルールに沿って変更し、アニメーションをつくります。

## オンライン・リソース

オンライン上でHTMLとCSSを書くために、 [trinket](https://trinket.io/) を使うことをおすすめします。 以下のtrinketが利用できます。

+ ['Sunrise' starting point](https://trinket.io/html/web-sunrise)

また、子供たちが１からHTMLとCSSを記述できるように、何も書かれていない状態のtrinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank)を使うことができます。それに加え、trinketのテンプレート [(jumpto.cc/html-template)](http://jumpto.cc/html-template)も利用できます。

また、チャレンジ(課題)に対しての回答例を含むtrinketもあります(以下参照)。

+ [''日の出プロジェクト'完成版](https://trinket.io/html/abcc0284a3)

## オフライン・リソース

このプロジェクトは[オフライン](../offline.html)で完成することも可能です。 You can access the project resources by clicking the 'Download Project Materials' link for this project. This link contains a 'Project Resources' folder, which includes resources that children will need to complete this project offline. 子供たち一人ひとりが資料のコピーにアクセスできるようにしておいて下さい。 This folder includes the following files:

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

なお、プロジェクトの課題の完成版がボランティア・リソースのセクションに含まれています。

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

このプロジェクトでは [Raspberry Pi デジタル・メイキング・カリキュラム](http://rpf.io/curriculum)（英語）の柱の一つである、プログラミングの以下の要素を含みます。

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

+ [全プロジェクトの資料が入った.zipファイル](resources/sunrise-project-resources.zip)
+ [全プロジェクトの資料](http://jumpto.cc/web-sunrise)
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

## 指導者用資料

+ [全プロジェクトの完成版の資料が入った.zipファイル](resources/sunrise-volunteer-resources.zip)
+ [完成版Trinketプロジェクト(オンライン)](https://trinket.io/html/abcc0284a3)
+ [完成版のHTMLファイル](resources/sunrise-finished-index.html)
+ [完成版のCSSファイル](resources/sunrise-finished-style.css)
+ [完成版のJavaScriptソース](resources/sunrise-finished-prefixfree.js)
+ [完成版プロジェクトで使う太陽の画像](resources/sunrise-finished-sun.png)
+ [完成版プロジェクトで使うボートの画像](resources/sunrise-finished-boat.png)
+ [完成版プロジェクトで使う虹の画像](resources/sunrise-finished-rainbow.png)

\--- /collapse \---