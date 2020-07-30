## परिचय

या प्रकल्पात (project), आपण सजीव (Animated) सूर्योदय तयार करण्यासाठी CSS कसे वापरावे हे शिकाल.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### क्लब प्रमुखांसाठी अधिक माहिती

आपल्याला जर हा प्रकल्प प्रिंट करायचा असेल तर आपण [प्रिंटर अनुकूल आवृत्ती](https://projects.raspberrypi.org/en/projects/sunrise/print) चा वापर करू शकता.

## \--- collapse \---

## title: क्लब प्रमुखांसाठी टिपा

## परिचय:

या प्रकल्पात, मुलांना CSS वापरुन एक साधा देखावा कसे सजीव करावे हे शिकवले जाईल. ते प्रतिमा आणि डिव्हजचे विविध गुणधर्म सजीव करण्यासाठी CSS @keyframes नियम वापरेल.

## ऑनलाईन संसाधने

आम्ही HTML & CSS ऑनलाइन ल्ह्याला [trinket](https://trinket.io/) वापरण्याची शीफारस करतो. या प्रकल्पात पुढील trinkets आहेत:

+ ['सूर्योदय' प्रारंभ बिंदू](http://jumpto.cc/web-sunrise)

HTML& आणी CSS लिहीण्यासाठी मुले ह्या रिक्त trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) चा उपयोग करू शकतात किंवा ते ह्या टेम्प्लेट trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template) चाही उपयोग करू शकतात.

आव्हानांवर नमुना निराकरण करणारा एक trinket देखील आहे:

+ ['सूर्योदय' संपला](https://trinket.io/html/abcc0284a3)

## ऑफलाइन संसाधने

हा प्रकल्प पसंत असल्यास [ऑफलाइन पूर्ण केला जाऊ शकतो](../offline.html). आपण या प्रकल्पाची संसाधने 'Download Project Materials' link वर​ क्लिक करून मिळवू शकता. या लिंक मध्ये 'Project Resources' विभाग आहे, ज्यामध्ये मुलांना हा प्रकल्प ऑफलाइन पूर्ण करण्यासाठी आवश्यक असणारी संसाधने आहेत. प्रत्येक मुलास ह्या संसाधंनांच्या प्रतिवार प्रवेश असल्याचे सुनिश्चित करा. या विभागात खालील फायली समाविष्ट आहेत:

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

आपल्याला या प्रकल्पातील आव्हानांची पूर्ण आवृत्ती 'Volunteer Resources' विभागात सापडेल, ज्यात खालील बाबी आहेत:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## शिकण्याचे उद्दिष्टे

+ CSS सह स्टाईलिंग आणि अ‍ॅनिमेशन: 
    + सादर करीत आहोत `@keyframes` अ‍ॅनिमेशनमधील चरण परिभाषित करण्यासाठी नियम.
    + वेबपृष्ठावरील(webpage) घटकांचा आकार, स्थिती आणि रंग परिभाषित करण्यासाठी गुणधर्मांच्या वापरास मजबुती देणे.

या प्रकल्पात [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum) चे खालील घटक समाविष्ट आहेत:

+ [मूलभूत 2D आणि 3D ऍसेटस् डिझाइन करणे](https://www.raspberrypi.org/curriculum/design/creator).

## आव्हाने

+ "कर्णरेषा(Diagonal) अ‍ॅनिमेशन" -अ‍ॅनिमेशन संपादन `@keyframe` डावे वापरण्यासाठी गुणधर्म:;
+ "आकाश सुधारित करा" - अधिक कीफ्रेम्स आणि सेटिंग पार्श्वभूमी जोडा:.
+ "अधिक अ‍ॅनिमेशन" - विविध CSS गुणधर्मांचा वापर करून अधिक प्रतिमा किंवा घटक सजीव करा. 

## वारंवार विचारले जाणारे प्रश्न

+ हा प्रकल्प javascript `prefixfree.js` लायब्ररी तसेच ब्राउझर दरम्यान अ‍ॅनिमेशन सुसंगततेसाठी वापरतो. जर ही लायब्ररी वापरली नसेल तर त्याऐवजी जुने ब्राउझर वापरणार्‍या मुलांना त्यांच्या ब्राउझरसाठी अ‍ॅनिमेशन घोषित करण्याची आवश्यकता असेल, उदाहरणार्थ:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: प्रकल्प साहित्य

## प्रकल्प संसाधने

+ [सर्व प्रकल्पाची संसाधने असलेली .zip फाइल](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [ऑनलाईन Trinket ज्यामध्ये सर्व 'Sunrise' प्रकल्प संसाधने आहेत](http://jumpto.cc/web-sunrise)
+ [ऑनलाइन Trinket टेम्पलेट](http://jumpto.cc/trinket-template)
+ [ऑनलाइन रिक्त Trinket](http://jumpto.cc/trinket-blank)
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

## क्लब प्रमुख संसाधने

+ [सर्व पूर्ण प्रकल्पाची संसाधने असलेली .zip फाइल](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [ऑनलाईन पूर्ण Trinket प्रकल्प](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---