## 해 만들기

해 이미지를 삽입하고, CSS로 포지션을 잡아 보도록 하겠습니다.

+ 다음 Trinket 파일을 열어주세요. <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    프로젝트는 아래와 같이 보일 것입니다:
    
    ![스크린샷](images/sunrise-starter.png)

+ `index.html`의 `body`에서 sky, sea에 대한 `div` 요소를 찾아 보세요.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ 해 이미지는 이미 프로젝트에 추가되어 있습니다.
    
    `div` 내에 이미지를 삽입하고, 아래와 같이 이미지에 대한 id를 지정하여 스타일링할 수 있도록 합니다.
    
    ![스크린샷](images/sunrise-sun-image.png)

+ 헉, 이미지가 너무 크네요. `style.css` 파일에서 이미지 높이를 수정해 봅시다.
    
    ![스크린샷](images/sunrise-sun-height.png)
    
    너비는 자동으로 업데이트되어 비율이 동일하게 유지됩니다.

+ 마지막으로, 해의 위치를 지정하는 코드를 추가해 봅시다.
    
    ![스크린샷](images/sunrise-sun-position.png)