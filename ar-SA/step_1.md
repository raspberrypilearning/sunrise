## المقدمة

في هذا المشروع, سوف تتعلم كيفية التعامل مع CSS لأنشاء شروق شمس متحرك.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### معلومات إضافية لقادة النادي

إذا كنت بحاجة إلى طباعة هذا المشروع، فيُرجى استخدام [النسخة القابلة للطباعة](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: ملاحظات قادة النادي

## مقدمة:

في هذا المشروع سيتعلم الاطفال كيفية صنع مشهد متحرك بسيط بـأستخدام CSS. سوف يستخدمون قاعدة CSS @keyframes من اجل تحريك خصائص او اجزاء مختلفة من الصورة.

## الموارد المتوفرة على الإنترنت

نوصي باستخدام [trinket](https://trinket.io/) لكتابة ملفات HTML و & CSS على الإنترنت. هذا المشروع يحتوي على مجموعة الtrinket التالية:

+ [الخطوة الاولى ل"شروق الشمس"](http://jumpto.cc/web-sunrise)

يمكن أن يستخدم الأطفال أيضًا ملف trinket الفارغ هذا[(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) لكتابة ملفات HTML & CSS الخاصة بهم، أو يمكنهم استخدام قالب trinket هذا [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

كما يوجد مشروع trinket يحتوي على نماذج حل التحديات:

+ ["شروق الشمس" مكتمل](https://trinket.io/html/abcc0284a3)

## الموارد المتوفرة دون اتصال بالإنترنت

يمكن اكمال هذا المشروع [دون اتصال بالإنترنت](../offline.html) إذا كنت تفضل ذلك. تستطيع الوصول الى موارد المشروع بالنقر على رابط المشروع هذا 'Download Project Materials'. هذا الرابط يحتوي على ملف "موارد المشروع", الذي يحتوي بدوره على الموارد التي يحتاجها الاطفال لأكمال هذا المشروع بدون اتصال بلانترنت. تأكد من أن كل طفل لديه امكانية الوصول الى نسخة من هذه الموارد. هذا المجلد يحتوي على الملفات التالية:

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

يمكنك أيضًا الحصول على النسخة الكاملة لهذا المشروع في قسم "موارد المتطوعين"والذي يحتوي على:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## أهداف التعلم

+ التصميم والتحريك باستخدام CSS: 
    + التعريف بقاعدة `@keyframes` لتحديد الخطوات في الصور المتحركة.
    + تعزيز استخدام الخصائص لتحديد الحجم و الشكل و الموقع و لون العناصر على صفحة الموقع الالكتروني.

يتناول هذا المشروع عناصر من هذة المعايير من منهج الصناعة الرقمية الخاص بـ [Raspberry Pi](http://rpf.io/curriculum):

+ [ تصميم اصول بسيطة بالأبعاد الثنائية والثلاثية](https://www.raspberrypi.org/curriculum/design/creator).

## التحديات

+ "تحريك قطري" - تحرير خصائص `@keyframe` للصور المتحركة لاستخدام left:;
+ "تطوير السماء"- اضافة المزيد من الخصائص والمحتويات الى الخلفية:.
+ "المزيد من الصور المتحركة"- قم بصنع المزيد من الصور او العناصر المتحركة بأستخدام تشكيلة من خصائص الCSS. 

## الأسئلة الشائعة

+ هذا المشروع يقوم بالاستفادة من مكتبة javascript `prefixfree.js`, للسماح بتوافق تحريك الصور بين متصفحات الانترنت. اذا لم يتم استخدام هذه المكتبة, عندها الاطفال الذين يملكون متصفحات انترنت قديمة سيحتاجون الى تعريف الصور المتحركة الى متصفحاتهم, مثال:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: مواد المشروع

## موارد المشروع

+ [ملف.zip يحتوي على كل موارد المشروع](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [ Trinket عبر الانترنت يحتوي على جميع موارد مشروع "شروق الشمس"](http://jumpto.cc/web-sunrise)
+ [قالب Trinket عبر الإنترنت](http://jumpto.cc/trinket-template)
+ [Trinket فارغ عبر الإنترنت](http://jumpto.cc/trinket-blank)
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

## موارد قائد النادي

+ [ملف.zip يحتوي على جميع موارد المشروع المكتمل](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [مشروع Trinket المكتمل على الإنترنت](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---