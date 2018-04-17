## भूमिका

इस प्रोजेक्ट में, आप एनिमेट किया हुआ सूर्योदय बनाने के लिए CSS का उपयोग करना सीखेंगे।

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### क्लब लीडर्स के लिए अतिरिक्त जानकारी

यदि आप इस प्रोजेक्ट को प्रिंट करना चाहते हैं, तो कृपया [प्रिंटर के लिए अनुकूल संस्करण](https://projects.raspberrypi.org/en/projects/sunrise/print) का उपयोग करें।


--- collapse ---
---
title: क्लब लीडर के नोट्स
---


## भूमिका:
इस प्रोजेक्ट में, बच्चे CSS की सहायता से एक साधारण सीन को एनिमेट करना सीखेंगे। वे चित्रों और divs के कई गुणों को एनिमेट करने के लिए CSS @keyframes नियम का उपयोग करेंगे।

## ऑनलाइन संसाधन

HTML और CSS को ऑनलाइन लिखने के लिए हम [trinket](https://trinket.io/) का उपयोग करने की अनुशंसा करते हैं। इस प्रोजेक्ट में निम्नलिखित Trinkets शामिल होते हैं:

+ ['सूर्योदय' का आरंभिक बिंदु](https://trinket.io/html/web-sunrise)

बच्चे स्वयं का HTML और CSS लिखने के लिए इस [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) खाली ट्रिंकेट का भी उपयोग कर सकते हैं, या वैकल्पिक तौर पर वे इस टैंपलेट ट्रिंकेट का उपयोग कर सकते हैं [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

एक ऐसा भी ट्रिंकेट होता है जिसमें चुनौतियों के लिए हल का नमूना शामिल होता है:

+ ['सूर्योदय' पूरा हो गया है](https://trinket.io/html/abcc0284a3)

## ऑफ़लाइन संसाधन
यदि इच्छा हो तो इस प्रोजेक्ट को [ऑफ़लाइन पूरा किया](../offline.html) जा सकता है। आप इस प्रोजेक्ट के लिए 'Download Project Materials' पर क्लिक करके प्रोजेक्ट के संसाधनों का उपयोग कर सकते हैं। इस लिंक में एक 'प्रोजेक्ट संसाधन' फोल्डर शामिल है, जिसमें वे संसाधन शामिल होते हैं जिनकी आवश्यकता बच्चों को प्रोजेक्ट को ऑफ़लाइन पूरा करने के लिए होगी। सुनिश्चित करें कि प्रत्येक बच्चे की इन स्रोतों तक पहुँच है। इस फोल्डर में निम्नलिखित फाइलें शामिल होती हैं:

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

आप 'स्वैच्छिक संसाधन' अनुभाग में इस प्रोजेक्ट की चुनौतियों का पूर्ण संस्करण भी खोज सकते हैं, जसमे यह शामिल है:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## अधिगम उद्देश्य
+ CSS के साथ स्टाइलिंग और एनिमेशन:
	+ एक एनिमेशन में चरण परिभाषित करने के लिए `@keyframes` नियम इस प्रकार है।
	+ वेबपेज पर एलिमेंट्स का आकार, आकृति, स्थिति और रंग को परिभाषित करने के लिए गुणों का उपयोग का समर्थन करना।

इस प्रोजेक्ट में [Raspberry Pi डिजिटल निर्माण पाठ्यचर्या](http://rpf.io/curriculum) के निम्नलिखित गुणों के तत्व शामिल होते हैं:

+ [Design basic 2D and 3D assets](https://www.raspberrypi.org/curriculum/design/creator).

## चुनौतियाँ
+ "तिरछी एनिमेशन" - left: का उपयोग करने के लिए `@keyframe` एनिमेशन के गुणों को एडिट करना;
+ "आकाश में सुधार करें" – और कीफ्रेम और सेटिंग बैकग्राउंड शामिल करें: ।
+ "और एनिमेशन" – भिन्न-भिन्न CSS गुणों द्वारा चित्रों या एलिमेंट्स को एनिमेट करें। 

## अक्सर पूछे जाने वाले प्रश्न

+ यह प्रोजेक्ट ब्राउज़रों के बीच एनिमेशन की अनुकूलता की सुविधा देने के लिए  javascript `prefixfree.js` लाइब्रेरी का उपयोग करता है। यदि इस लाइब्रेरी का उपयोग नहीं किया जाता है, तो पुराने ब्राउज़र का उपयोग करने वाले बच्चों को इसकी बजाए उनके ब्राउज़र के लिए एक एनिमेशन घोषित करनी होगी, उदाहरण के लिए:

```
animation: sky 10s infinite; 		  	//सभी नए ब्राउज़र्स के लिए
-webkit-animation: sky 10s infinite;  	// वेबकिट ब्राउज़र्स (क्रोम, सफारी...)
-moz-animation: sky 10s infinite;     	// मोज़िला ब्राउज़र्स के लिए
-o-animation: sky 10s infinite;       	// ओपेरा ब्राउज़र्स के लिए
-ms-animation: sky 10s infinite;		//माइक्रोसॉफ्ट ब्राउज़र्स के लिए 
```


--- /collapse ---


--- collapse ---
---
title: प्रोजेक्ट सामग्री
---
## प्रोजेक्ट संसाधन
* [प्रोजेक्ट के सभी संसाधनों युक्त .zip फाइल](resources/sunrise-project-resources.zip)
* ['सूर्योदय' प्रोजेक्ट के सभी संसाधनों युक्त ऑनलाइन ट्रिंकेट](http://jumpto.cc/web-sunrise)
* [ऑनलाइन ट्रिंकेट टैंपलेट](http://jumpto.cc/trinket-template)
* [ऑनलाइन खाली ट्रिंकेट](http://jumpto.cc/trinket-blank)
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

## क्लब लीडर संसाधन
* [पूरे किए प्रोजेक्ट के सभी संसाधनों युक्त .zip फाइल](resources/sunrise-volunteer-resources.zip)
* [ऑनलाइन पूरा किया गया ट्रिंकेट](https://trinket.io/html/abcc0284a3)
* [sunrise-finished/index.html](resources/sunrise-finished-index.html)
* [sunrise-finished/style.css](resources/sunrise-finished-style.css)
* [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
* [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
* [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
* [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

--- /collapse ---