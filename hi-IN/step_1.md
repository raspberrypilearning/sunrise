## भूमिका

इस परियोजना में, आप एनिमेटेड सूर्योदय बनाने के लिए CSS का उपयोग करना सीखेंगे।

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### क्लब लीडरों के लिए अतिरिक्त जानकारी

यदि आप इस परियोजना को प्रिंट करना चाहते हैं, तो कृपया [प्रिंटर अनुकूल संस्करण](https://projects.raspberrypi.org/en/projects/sunrise/print) का उपयोग करें।

## \--- collapse \---

## title: क्लब नेता नोट्स

## भूमिका:

इस परियोजना में, बच्चे CSS का उपयोग करके एक सरल दृश्य को एनिमेट करना सीखेंगे। वे चित्र और div के विभिन्न गुणों को चेतन करने के लिए CSS @keyframes नियम का उपयोग करेंगे।

## ऑनलाइन संसाधन

HTML और CSS को ऑनलाइन लिखने के लिए हम trinket का उपयोग करने की अनुशंसा करते हैं। इस परियोजना में निम्नलिखित trinkets शामिल हैं:

+ ['सूर्योदय' शुरुआती बिंदु](http://jumpto.cc/web-sunrise)

बच्चे स्वयं का HTML और CSS लिखने के लिए इस [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) खाली trinket का भी उपयोग कर सकते हैं, या वैकल्पिक तौर पर वे इस नमूना trinket का उपयोग कर सकते हैं [(jumpto.cc/html-template)](http://jumpto.cc/html-template)।

ऐसा trinket भी होता है, जिसमें चुनौतियों के लिए हल का नमूना शामिल होता है:

+ ['सनराइज' खत्म](https://trinket.io/html/abcc0284a3)

## ऑफ़लाइन संसाधन

This project can be [completed offline](https://rpf.io/html-offline) if preferred. आप इस परियोजना के लिए 'परियोजना सामग्री डाउनलोड करें' लिंक पर क्लिक करके परियोजना संसाधनों तक पहुँच सकते हैं। इस लिंक में एक 'परियोजना संसाधन' फ़ोल्डर है, जिसमें वे संसाधन शामिल हैं जिन्हें बच्चों को ऑफ़लाइन इस परियोजना को पूरा करने की आवश्यकता होगी। सुनिश्चित करें कि प्रत्येक बच्चे को इन संसाधनों की प्रतिलिपि तक पहुँच प्राप्त होती है। इस फ़ोल्डर में निम्न फाइलें शामिल हैं:

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

आप इस परियोजना की चुनौतियों का पूर्ण संस्करण ‘Volunteer Resources’ भाग में भी देख सकते हैं, जिसमें ये शामिल हैं:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## सीखने के उद्देश्य

+ CSS के साथ स्टाइलिंग और एनीमेशन: 
    + एक एनीमेशन में rule परिभाषित करने के लिए `@keyframes` नियम का परिचय।
    + वेब पृष्ठ पर तत्वों के आकार, माप, स्थिति और रंग को परिभाषित करने के लिए गुणों के उपयोग को फिर से लागू करना।

इस परियोजना में [Raspberry Pi डिजिटल निर्माण पाठ्यक्रम](http://rpf.io/curriculum) के निम्नलिखित पहलुओं के तत्व सम्मिलित हैं:

+ [बुनियादी 2D और 3D संपत्ति डिजाइन करें](https://www.raspberrypi.org/curriculum/design/creator)।

## चुनौतियाँ

+ "विकर्ण एनीमेशन" - संपादन एनीमेशन `@keyframe` के लिए बाएं का उपयोग करें;
+ "आकाश में सुधार" - अधिक कीफ्रेम और सेटिंग बैकग्राउंड जोड़ें:।
+ "और एनिमेशन" - CSS गुणों की एक किस्म का उपयोग करके अधिक छवियों या तत्वों को यूज़ करें। 

## अक्सर पूछे जाने वाले प्रश्न

+ यह परियोजना JavaScript `prefixfree.js` लाइब्रेरी का उपयोग करती है, जिससे ब्राउज़रों के बीच एनीमेशन संगतता की अनुमति मिलती है। यदि इस लाइब्रेरी का उपयोग नहीं किया जाता है, तो पुराने ब्राउज़र का उपयोग करने वाले बच्चों को इसके बजाय अपने ब्राउज़र के लिए एक एनीमेशन घोषित करने की जरुरत होगी, उदाहरण के लिए:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: परियोजना सामग्री

## परियोजना संसाधन

+ [सभी परियोजना संसाधनों वाली.zip फ़ाइल](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [ऑनलाइन Trinket जिसमें सभी 'Sunrise' परियोजना संसाधन हैं](http://jumpto.cc/web-sunrise)
+ [ऑनलाइन Trinket टेम्प्लेट](http://jumpto.cc/trinket-template)
+ [ऑनलाइन खाली Trinket](http://jumpto.cc/trinket-blank)
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

## क्लब लीडर ले लिए संसाधन

+ [सभी परियोजना संसाधनों वाली.zip फ़ाइल](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [ऑनलाइन पूर्ण Trinket परियोजना](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---