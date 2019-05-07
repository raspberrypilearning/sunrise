## 소개

이 프로젝트에서 일출 애니메이션을 만들기 위해 CSS를 사용하는 방법을 배울 것 입니다.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### 교육자들을 위한 추가 정보

이 프로젝트를 인쇄하려면 [프린트용 문서](https://projects.raspberrypi.org/ko-KR/projects/sunrise/print)를 사용하십시오.

--- collapse ---
---
title: 교육자들을 위한 메모
---

## 들어가며:

이 프로젝트에서 학생들은 CSS를 활용하여 간단한 장면을 애니메이션화 하는 방법을 익히게 됩니다. 학생들은 CSS 의 @keyframes 규칙을 사용하여 이미지와 div의 다양한 속성을 애니메이션화할 것 입니다.

## 온라인 자료

이 자료에서는 [Trinket](https://trinket.io/)을 사용하여 HTML & CSS 를 온라인으로 편집할 것을 권장합니다. 이 프로젝트에 포함된 Trinket 은 다음과 같습니다:

+ ['일출' 시작](https://trinket.io/html/web-sunrise)

학생들은 새로운 Trinket을 사용할 수 있으며 [(jumpto.cc/html-black)](http://jumpto.cc/html-blank) 이를 통해 자신만의 HTML 과 CSS 코드를 사용하는 방법을 배울 수 있습니다. 또한, 템플릿이 제공된 Trinket을 사용할 수 있습니다. [(jumpto.cc/html-template)](http://jumpto.cc/html-template)

프로젝트의 샘플 정답이 다음 Trinket 에 있습니다.

+ ['일출' 끝](https://trinket.io/html/abcc0284a3)

## 오프라인 자료

여러분의 선호에 따라 프로젝트를 [오프라인에서 완성](../offline.html)할 수 있습니다. 'Download Project Materials' 라는 링크를 클릭하여 이 프로젝트의 자료를 확인해볼 수 있습니다. 이 링크에는 학생들이 프로젝트를 오프라인으로 완료하는 데 필요한 자료가 포함된 'Project Resource' 폴더가 있습니다. 학생들이 자료의 사본에 접근할 수 있는지 확인하십시오. 이 섹션에는 아래와 같은 파일들이 포함되어 있습니다.

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

이 프로젝트의 완성된 버전은 'Volunteer Resources' 섹션에서 찾을 수 있습니다. 다음 파일이 있습니다:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## 학습 목표

+ CSS에서 애니메이션과 스타일링 
    + 애니메이션의 단계 정의를 위한 `@keyframes` 규칙 소개.
    + 웹 페이지의 요소 크기, 모양, 위치 및 색상을 정의하기 위한 속성 사용 강화

이 프로젝트는 [라즈베리파이 디지털 메이킹 커리큘럼](http://rpf.io/curriculum) 중 아래의 과정에 있는 요소들을 다룹니다.

+ [2D와 3D 디자인](https://www.raspberrypi.org/curriculum/design/creator)

## 도전과제

+ "대각선 애니메이션" - `@keyframe` 특성을 왼쪽에서 사용할 수 있도록 애니메이션 편집
+ "하늘을 개선하라" - keyframes 추가하고 배경을 설정하라.
+ "더 많은 애니메이션" - 다양한 CSS속성을 이용하여 더 많은 이미지나 요소를 애니메이션으로 구현 

## 자주 물어보는 질문

+ 이 프로젝트에서는 브라우저간 애니메이션이 호환되도록 하기 위해 자바스크립트 `prefixfree.js` 라이브러리를 사용합니다. 만약, 이 라이브러리를 사용하지 않는다면, 옛날 브라우저를 사용하는 학생들은 아래와 같이 어떤 브라우저에 대한 애니메이션을 선언해야 합니다.

    animation: sky 10s infinite;            // 최신 브라우저
    -webkit-animation: sky 10s infinite;    // 웹킷 브라우저(크롬, 사파리 등)
    -moz-animation: sky 10s infinite;       // 모질라 브라우저
    -o-animation: sky 10s infinite;         // 오페라 브라우저
    -ms-animation: sky 10s infinite;        // 마이크로소프트 브라우저 
    

--- /collapse ---

--- collapse ---
---
title: 프로젝트 자료
---

## 프로젝트 리소스

+ [프로젝트의 모든 리소스가 들어있는 .zip 파일](resources/sunrise-project-resources.zip)
+ [썬라이즈 프로젝트 자료가 포함된 온라인 Trinket](http://jumpto.cc/web-sunrise)
+ [온라인 Trinket 템플릿](http://jumpto.cc/trinket-template)
+ [빈 Trinket](http://jumpto.cc/trinket-blank)
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

## 교육자를 위한 자료

+ [완료된 프로젝트 리소스가 담긴 .zip 파일](resources/sunrise-volunteer-resources.zip)
+ [완성된 온라인 Trinket 프로젝트](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

--- /collapse ---