## Criar o Sol

Vamos começar por acrescentar e posicionar uma imagem para o Sol com algum CSS.

+ Abre este trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    O projeto deverá ter este aspeto:
    
    ![captura de ecrã](images/sunrise-starter.png)

+ Espreita dentro do `corpo` do teu ficheiro `index.html` e irás encontrar os elementos `div` para o céu e o mar.
    
        <div id="sky"><div id="sky">
        </div></div>
        
        <div id="sea"><div id="sea">
        </div></div>
        

+ Este projeto tem já incluída uma imagem para o Sol.
    
    Acrescenta a imagem ao `div` do teu sol juntamente com um id para que o consigas estilizar:
    
    ![captura de ecrã](images/sunrise-sun-image.png)

+ Whoa, a imagem é gigantesca. Vai a `style.css` e acrescenta o CSS para definir a altura da imagem:
    
    ![captura de ecrã](images/sunrise-sun-height.png)
    
    Nota que a largura é atualizada automaticamente para manter as mesmas proporções.

+ Finalmente, vamos acrescentar algum código para posicionar o Sol:
    
    ![captura de ecrã](images/sunrise-sun-position.png)