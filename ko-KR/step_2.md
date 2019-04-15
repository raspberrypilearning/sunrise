## 해 만들기

해 이미지를 삽입하고, CSS로 배치해 보도록 하겠습니다.

+ 다음 Trinket 파일을 열어주세요. <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    프로젝트는 아래와 같이 보일 것입니다:
    
    ![스크린샷](images/sunrise-starter.png)

+ `index.html`의 `body`에서 sky, sea에 대한 `div` 요소를 발견할 것입니다.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ 해 이미지는 이미 프로젝트에 추가되어 있습니다.
    
    다음과 같이 스타일을 설정할 수 있도록 id를 포함하여 해의 ` div `에 이미지를 추가하십시오.
    
    ![스크린샷](images/sunrise-sun-image.png)

+ 헉, 이미지가 너무 크네요. `style.css` 파일에서 CSS를 추가하여 이미지 높이를 설정해 봅시다.
    
    ![스크린샷](images/sunrise-sun-height.png)
    
    너비는 비율을 동일하게 유지하기 위해 자동으로 업데이트됩니다.

+ 마지막으로, 해의 위치를 지정하는 코드를 추가해 봅시다.
    
    ![스크린샷](images/sunrise-sun-position.png)