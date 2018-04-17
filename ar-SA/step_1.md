## المقدمة

في هذا المشروع، ستتعلم كيفية استخدام CSS لإنشاء رسم متحرك لشروق الشمس.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### معلومات إضافية لقادة النادي

إذا كنت بحاجة إلى طباعة هذا المشروع، فيُرجى استخدام [نسخة سهلة الطباعة](https://projects.raspberrypi.org/en/projects/sunrise/print).


--- collapse ---
---
title: ملاحظات قادة النادي
---


## المقدمة:
في هذا المشروع، سيتعلَّم الأطفال كيفية تحريك مشهد بسيط باستخدام CSS. وسيستخدمون قاعدة keyframes@ في CSS لتحريك خصائص مختلفة للصور وعناصر divs.

## الموارد المتوفرة على الإنترنت

نوصي باستخدام [trinket](https://trinket.io/) لكتابة ملفات HTML وCSS على الإنترنت. يحتوي هذا المشروع على ملفات trinket التالية:

+ ['شروق الشمس' مشروع البدء](https://trinket.io/html/web-sunrise)

يمكن أن يستخدم الأطفال أيضًا ملف trinket الفارغ هذا [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) لكتابة ملفات HTML و CSS، أو يمكنهم استخدام قالب trinket هذا [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

كما يوجد مشروع trinket يحتوي على نموذج حل للتحديات:

+ [مشروع 'شروق الشمس' مُكتمل](https://trinket.io/html/abcc0284a3)

## الموارد المتوفرة دون اتصال بالإنترنت
بالنسبة إلى هذا المشروع، يمكن [إكماله دون اتصال بالإنترنت](offline.html/..) إذا كنت تفضل ذلك. ويمكنك الوصول إلى موارد المشروع من خلال النقر فوق الرابط "تنزيل مواد المشروع" الخاص بهذا المشروع. يحتوي هذا الرابط على مجلد "موارد المشروع"، الذي يتضمن الموارد التي يحتاج إليها الأطفال لإكمال هذا المشروع دون اتصال بالإنترنت. تأكد من أن كل طفل لديه حق الوصول إلى نسخة من هذه الموارد. يتضمن هذا المجلد الملفات التالية:

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

يمكنك أيضًا العثور على نسخة كاملة من تحديات هذا المشروع في قسم "موارد المتطوعين" الذي يحتوي على:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## أهداف التعلم
+ تحديد الأنماط وإنشاء الرسوم المتحركة باستخدام CSS:
	+ تناول القاعدة `keyframes@` لتحديد خطوات الرسم المتحرك.
	+ زيادة تعزيز استخدام الخصائص لتحديد حجم العناصر وشكلها وموضعها ولونها على صفحة الويب.

يتناول هذا المشروع عناصر من الصفوف التالية من [المناهج الرقمية الخاصة بـ Raspberry Pi](http://rpf.io/curriculum):

+ [الأصول الأساسية للتصميمات ثنائية الأبعاد وثلاثية الأبعاد](https://www.raspberrypi.org/curriculum/design/creator).

## التحديات:
+ "التحريك بشكل قطري" - تحرير خصائص الرسوم المتحركة `keyframe@` لاستخدام الخاصية :إلى اليسار؛
+ "تحسين ظهور السماء" - إضافة المزيد من الإطارات المفتاحية وتعيين الخلفية:.
+ "رسوم متحركة أخرى" - تحريك صور أو عناصر أخرى باستخدام مجموعة متنوعة من خصائص CSS. 

## الأسئلة الشائعة

يستخدم هذا المشروع مكتبة `prefixfree.js` للغة javascript لتوفير توافق الرسوم المتحركة بين المتصفحات. وإذا لم تكن هذه المكتبة مستخدمة، فإن الأطفال الذين يستخدمون متصفحات قديمة سيحتاجون إلى الإعلان عن رسم متحرك للمتصفحات التي يستخدمونها، على سبيل المثال:

```
animation: sky 10s infinite; 		  	//for all newer browsers
-webkit-animation: sky 10s infinite;  	// For Webkit browsers(Chrome, Safari...)
-moz-animation: sky 10s infinite;     	// For Mozilla browsers
-o-animation: sky 10s infinite;       	// For Opera browsers
-ms-animation: sky 10s infinite;		// For Microsoft browsers 
```


--- /collapse ---


--- collapse ---
---
title: مواد المشروع
---
## موارد المشروع
* [ملف .zip يحتوي على كل موارد المشروع](resources/sunrise-project-resources.zip)
* [Trinket عبر الإنترنت يحتوي على كل موارد مشروع 'شروق الشمس'](http://jumpto.cc/web-sunrise)
* [قالب Trinket عبر الإنترنت](http://jumpto.cc/trinket-template)
* [Trinket فارغ عبر الإنترنت](http://jumpto.cc/python-new)
* [template/index.html](resources/template-index.html)
* [template/style.css](resources/template-style.css)
* [intro/index.html](resources/intro-index.html)
* [intro/style.css](resources/intro-style.css)
* [sunrise/index.html](resources/sunrise-index.html)
* [sunrise/style.css](resources/sunrise-style.css)
* [sunrise/prefixfree.js](resources/sunrise-prefixfree.js)
* [sunrise/sun.png](resources/sunrise-sun.png)
* [sunrise/rainbow.png](resources/sunrise-rainbow.png)
* [sunrise/cloud.png](resources/sunrise-cloud.png)
* [sunrise/boat.png](resources/sunrise-boat.png)
* [sunrise/helicopter.png](resources/sunrise-helicopter.png)

## موارد قادة النادي
* [ملف .zip يحتوي على كل موارد المشاريع المكتملة](resources/sunrise-volunteer-resources.zip)
* [مشروع Trinket المكتمل على الإنترنت](https://trinket.io/html/abcc0284a3)
* [sunrise-finished/index.html](resources/sunrise-finished-index.html)
* [sunrise-finished/style.css](resources/sunrise-finished-style.css)
* [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
* [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
* [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
* [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

--- /collapse ---