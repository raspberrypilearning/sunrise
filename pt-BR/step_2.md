## Criando o sol

Vamos começar adicionando uma imagem para o sol e posicionando-a com algum CSS.

+ Abrar o trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    O projeto deve ficar assim:
    
    ![screenshot](images/sunrise-starter.png)

+ Olhe dentro do `body` do seu arquivo `index.html` e você encontrará os elementos `div` para o céu e para o mar.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Uma imagem para o sol já está incluída no seu projeto.
    
    Adicione a imagem dentro do seu sol `div` incluindo uma identificação para que você possa usar um estilo:
    
    ![screenshot](images/sunrise-sun-image.png)

+ Uau, a imagem é enorme. Vá para `style.css` e adicione o CSS para definir a altura da imagem:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Observe que a largura é atualizada automaticamente para manter as proporções iguais.

+ Finalmente, vamos adicionar um código para posicionar o sol:
    
    ![screenshot](images/sunrise-sun-position.png)