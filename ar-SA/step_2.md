## إنشاء كائن الشمس

لنبدأ بإضافة صورة للشمس وتحديد موضع لها باستخدام بعض تعليمات CSS البرمجية.



+ افتح مشروع trinket هذا: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>. 

    سيكون المشروع بالشكل التالي:

	![screenshot](images/sunrise-starter.png)

+ إذا نظرتَ داخل العنصر `body` في الملف `index.html`، فستجد عنصرَي `div` للسماء والبحر.

    ```
    <div id="sky">
    </div>
    
    <div id="sea">
    </div>
    ```

+ تتوفر صورة للشمس في مشروعك بالفعل. 

    أضف الصورة داخل عنصر `div` الخاص بالشمس مع تحديد معرف للصورة حتى يمكنك تحديد نمط لها:

    ![screenshot](images/sunrise-sun-image.png)

+ حجم الصورة كبير جدًا. انتقل إلى الملف `style.css` وأضف تعليمات CSS البرمجية لتعيين قيمة الارتفاع للشمس:

    ![screenshot](images/sunrise-sun-height.png)

    لاحظ أن قيمة العرض تُحدَّث تلقائيًا للحفاظ على النسب. 

+ وأخيرًا، لنضِف بعض التعليمات البرمجية لتحديد موضع الشمس:

    ![screenshot](images/sunrise-sun-position.png)




