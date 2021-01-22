## Вступ

У цьому проєкті ти дізнаєшся, як використовувати CSS для створення анімації сходу сонця.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Додаткова інформація для керівників гуртка

Якщо вам потрібно роздрукувати цей проєкт, скористайтеся [версією для друку](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Нотатки керівника гуртка

## Вступ:

У цьому проєкті діти зможуть навчитися створювати просту сцену за допомогою CSS. Вони використовуватимуть правило CSS @keyframes, щоб анімувати різні властивості зображень та елементів div.

## Онлайн Ресурси

Ми рекомендуємо використовувати [trinket](https://trinket.io/) щоб писати код HTML та CSS онлайн. Цей проєкт містить наступні ресурси trinket:

+ [Шаблон "Схід сонця"](http://jumpto.cc/web-sunrise)

Діти також можуть скористатися порожнім проєктом [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) щоб писати свій власний код HTML та CSS, або вони можуть використовувати шаблон [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Також, існує проєкт, що містить приклади вирішення завдань:

+ [Завершений "Схід сонця"](https://trinket.io/html/abcc0284a3)

## Офлайн Ресурси

This project can be [completed offline](https://rpf.io/html-offline) if preferred. Ви можете отримати доступ до ресурсів проєкту, натиснувши на посилання "Завантажити матеріали проєкту". Це посилання містить папку "Project Resources", яка включає в себе ресурси, необхідні дітям для реалізації цього проєкту в режимі офлайн. Переконайтеся, що кожна дитина має доступ до копії цих ресурсів. Ця папка містить наступні файли:

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

Також, ви можете знайти завершену версію цього проєкту в розділі "Ресурси керівника гуртка", яка містить:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Цілі навчання

+ Стиль та анімація в CSS: 
    + Знайомство з правилом @keyframes для визначення кроків анімації.
    + Закріплення навичок використання властивостей для визначення розміру, форми, положення та кольору елементів на вебсторінці.

Цей проєкт охоплює елементи з наступних напрямків [Електронного навчального плану Raspberry Pi](http://rpf.io/curriculum):

+ [Розробка простих ресурсів 2D та 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Завдання

+ "Діагональна анімація" — редагування властивостей анімації `@keyframe` з використанням left:;
+ "Вдосконалення неба" — додавання більшої кількості ключових кадрів та використання background:.
+ "Вдосконалення анімації" — анімація додаткових зображень або елементів із використанням різних властивостей CSS. 

## Найбільш поширенні питання

+ Цей проєкт використовує бібліотеку javascript `prefixfree.js`, для сумісності анімації між браузерами. Якщо цю бібліотеку не використовувати, то діти, що використовують старі браузери, замість цього повинні оголосити анімацію для свого браузера, наприклад:

    animation: sky 10s infinite;            // Для всіх нових браузерів
    -webkit-animation: sky 10s infinite;    // Для Webkit браузерів (Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // Для Mozilla браузерів
    -o-animation: sky 10s infinite;         // Для Opera браузерів
    -ms-animation: sky 10s infinite;        // Для Microsoft браузерів 
    

\---collapse\---

## \--- collapse \---

## title: Матеріали проєкту

## Ресурси проєкту

+ [.zip файл, що містить всі проєктні ресурси](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Онлайн проєкт Trinket, що містить всі проєктні ресурси "Сходу сонця"](http://jumpto.cc/web-sunrise)
+ [Онлайн шаблон проєкту Trinket](http://jumpto.cc/trinket-template)
+ [Порожній онлайн проєкт Trinket](http://jumpto.cc/trinket-blank)
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

+ [.zip файл, що містить всі завершені проєктні ресурси](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Завершений онлайн проєкт Trinket](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\---collapse\---