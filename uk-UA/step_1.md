## Вступ

У цьому проекті ви дізнаєтеся, як використовувати CSS для створення мультиплікаційного сходу сонця.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Додаткова інформація для керівників гуртка

Якщо вам потрібно роздрукувати цей проект, будь ласка, скористайтеся [версією для друку](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Нотатки керівника гуртка

## Вступ:

У цьому проекті діти зможуть навчитися створювати просту сцену за допомогою CSS Вони використовуватимуть правило CSS @keyframes, щоб анімувати різні властивості зображень та divs.

## Онлайн Ресурси

Ми рекомендуємо використовувати [trinket](https://trinket.io/) щоб написати HTML & CSS онлайн. Цей проект містить наступні trinkets:

+ [Оберіть пункт відправлення](http://jumpto.cc/web-sunrise)

Діти також можуть скористатися цим пустим бланком [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) щоб написати свій власний HTML & CSS, або вони можуть по черзі використовувати цей шаблон [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Також, існує trinket, що міститься у зразку вирішення завдання:

+ ["Схід сонця" завершено](https://trinket.io/html/abcc0284a3)

## Офлайн Ресурси

Цей проект може бути [завершений офлайн](../offline.html), якщо потрібно. Ви можете отримати доступ до ресурсів проекту, натиснувши посилання " Матеріали Проекту" для цього проекту. Це посилання містить розділ "Ресурси Проекту", який включає в себе ресурси, якщо дітям доведеться завершувати цей проект в режимі офлайн. Переконайтеся, що кожна дитина має доступ до копії цих ресурсів. Ця версія містить наступні файли:

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

Також, ви можете знайти завершену версію завдання цього проекту в секції "Волонтерські Ресурси", яка містить:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Цілі навчання

+ Стиль та анімація з CSS: 
    + Представляємо правило @keyframes для визначення кроків у анімації.
    + Посилення використання властивостей для визначення розміру, форми, положення та кольору елементів на веб-сторінці.

Цей проект охоплює елементи з наступних напрямків навчального плану [ Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Розробка основних 2D та 3D активів](https://www.raspberrypi.org/curriculum/design/creator).

## Завдання

+ "Діагональна анімація" - редагування анімації @ властивості кеш-пам'яті для використання ліворуч :;
+ "Покращувати небо" - додати інші ключові кадри та налаштування фону :.
+ "Більше анімації" - анімують більше зображень або елементів, що використовують різні властивості CSS. 

## Найбільш поширенні питання

+ Цей проект використовує бібліотеку javascript prefixfree.js, щоб дозволити анімаційну сумісність між браузерами. Якщо ця бібліотека не використовується, то діти, що використовують старі браузери, замість цього повинні оголосити анімацію для свого браузера, наприклад:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\---collapse\---

## \--- collapse \---

## title: Матеріали проекту

## Проектні ресурси

+ [.zip файли, що містять всі проектні ресурси](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Online Trinket містить всі проектні ресурси 'Сходу сонця'](http://jumpto.cc/web-sunrise)
+ [Шаблон Online Trinket](http://jumpto.cc/trinket-template)
+ [Пустий Online Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
+ [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
+ [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
+ [sunrise/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
+ [sunrise/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
+ [sunrise/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
+ [sunrise/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
+ [sunrise/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
+ [sunrise/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Ресурси керівника гуртка

+ [.zip файли, що містять всі проектні ресурси](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Завершений Trinket проект онлайн](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\---collapse\---