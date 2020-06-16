## Animando o nascer do sol

Para animar o seu nascer do sol, você precisa definir como o sol se move e quanto tempo leva para subir.

Para fazer isso, você define uma lista de **key frames**. Cada key frame define as propriedades CSS de um elemento em um determinado ponto em uma animação.

+ Primeiro, você precisa usar `@keyframes` para criar uma nova animação chamada sunrise.
    
    Adicione este código CSS ao final do seu arquivo `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Este código indica o posicionamento do sol no início (`0%`) e a posição final (`100%`) da animação.
    
    Porque o sol está dentro do céu `div`, as posições `top` e `left` que você informa estão dentro do céu, com `top: 100%` sendo o fundo do céu, e não a parte inferior da página da web.

+ Agora que você criou uma animação `sunrise`, você pode ver o seu sol em execução!
    
    Adicione o código destacado do CSS no seu sol:
    
    ![screenshot](images/sunrise-sunrise.png)
    
    Isso irá dizer para o sol ficar 10 segundos animando o amanhecer.

+ Para executar a animação novamente no Trinket, basta clicar **Autorun**.