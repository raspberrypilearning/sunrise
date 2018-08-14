## Repetição da animação

Vamos fazer a animação ficar repetindo para sempre.

+ Se você quiser que o sol se levante e depois ele volte a dormir, basta adicionar mais quadros-chave(keyframes) na sua animação:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    Isso significa que a animação começará e terminará com o sol no espaço do céu e fica no topo de 33% até 66% da animação.

+ Agora você só precisa adicionar a palavra `infinite` à animação `#sun` para ficar repetindo para sempre:
    
    ![captura de tela](images/sunrise-infinite.png)

+ Testando sua animação. O sol continua subindo e se pondo?