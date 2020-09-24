<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> 
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

### Questão 2.8  

A) Quais as possíveis combinações para esse tanque de água:  

Vazão de entrada: $$6 ft$$, $$7 ft$$ e $$8 ft$$  
Vazão de saída: $$6 ft$$, $$7 ft$$ e $$8 ft$$  

As possíveis combinações são dadas por um arranjo entre todas as variáveis:    

> Para $$6 ft$$    
+ $[6 entra, 5 sai]$    
+ $$[6 entra, 6 sai]$$    
+ $$[6 entra, 7 sai]$$    
> Para $$7 ft$$
+ $$[7 entra, 5 sai]$$  
+ $$[7 entra, 6 sai]$$  
+ $$[7 entra, 7 sai]$$  
> Para $$8 ft$$  
+ $$[8 entra, 5 sai]$$  
+ $$[8 entra, 6 sai]$$  
+ $$[8 entra, 7 sai]$$   

Total de possibilidade $$Quantidade_{entrada}.Quantidade_{saida} = 3.3 = 9$$  

B) Quais os possíveis valores de nível de água partido da premissa que no início do dia são registrados $$7 ft$$ de nível d'água. Para isso dever ser consirada a seguinte proposição: $$ NFD = NID + E -S$$.

| Nível início dia (NID)   |      Entrada (E)      |  Saída (S) |  Nível final dia (NFD) |  Probabilidade  |
|:------------------------:|:---------------------:|:----------:|:----------------------:|:---------------:|
| 7                        |  6                    | 5          | 8                      | 1/9             |
| 7                        |  6                    | 6          | 7                      | 1/9             |
| 7                        |  6                    | 7          | 6                      | 1/9             |
