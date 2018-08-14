## Animando o céu

A animação não é apenas um movimento. Vamos animar o céu para ficar escuro durante à noite.

+ Adicione uma animação chamada `sky` ao seu CSS:
    
        @keyframes sky {
            0%
            100%
        }
        
    
    Note que desta vez você está animando a cor do céu, e não a posição.

+ Adicione o código ao seu céu, para que ele use sua nova animação:
    
        animation: sky 10s;
        
    
    ![screenshot](images/sunrise-sky.png)

+ Clique **Autorun** para testar sua animação.