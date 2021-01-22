## إنشاء كائن الشمس

لنبدأ باضافة صورة للشمس ووضعها في مكانها باستخدام بعض ال CSS.

+ افتح مشروع trinket هذا: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    الآن يجب أن يبدو الملف الخاص بك مثل هذا:
    
    ![لقطة الشاشة](images/sunrise-starter.png)

+ بداخل `body` في ملف ال`index.html` ستجد عناصر ال`div` الخاصة بالسماء والبحر.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ هناك صورة للشمس موجودة مسبقاً في مشروعك.
    
    اضف الصورة داخل `div` السماء واضف لها id لتتمكن من تشكيلها:
    
    ![لقطة الشاشة](images/sunrise-sun-image.png)

+ يا الهي, الصورة هائلة. اذهب الى `style.css` وقم بأضافة الCSS لظبط ارتفاع الصورة:
    
    ![لقطة الشاشة](images/sunrise-sun-height.png)
    
    لاحظ أن العرض يحدّث تلقائياً لابقاء تناسب الحجم كما هو.

+ وأخيراً, لنضف بعض الكود البرمجي لوضع الشمس في مكانها:
    
    ![لقطة الشاشة](images/sunrise-sun-position.png)