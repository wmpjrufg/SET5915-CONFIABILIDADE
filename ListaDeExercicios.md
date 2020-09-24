<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> 
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

### Questão 2.8  

A) Quais as possíveis combinações para esse tanque de água:  

Vazão de entrada: $$6 ft$$, $$7 ft$$ e $$8 ft$$  
Vazão de saída: $$6 ft$$, $$7 ft$$ e $$8 ft$$  

As possíveis combinações são dadas por um arranjo entre todas as variáveis:    

**Para nível $$6 ft$$**: $$[6, 5]$$, $$[6, 6]$$ e $$[6, 7]$$;    
**Para nível $$7 ft$$**: $$[7, 5]$$, $$[7, 6]$$ e $$[7, 7]$$;     
**Para nível $$8 ft$$**: $$[8, 5]$$, $$[8, 6]$$ e $$[8, 7]$$.      

Total de possibilidade $$Quantidade_{entrada}.Quantidade_{saída} = 3.3 = 9$$    

B) Quais os possíveis valores de nível de água partido da premissa que no início do dia são registrados $$7 ft$$ de nível d'água. Para isso dever ser consirada a seguinte proposição: $$ NFD = NID + E -S$$.

| Nível início dia (NID)   |      Entrada (E)      |  Saída (S) |  Nível final dia (NFD) |  Probabilidade  |
|:------------------------:|:---------------------:|:----------:|:----------------------:|:---------------:|
| 7                        |  6                    | 5          | 8                      | 1/9             |
| 7                        |  6                    | 6          | 7                      | 1/9             |
| 7                        |  6                    | 7          | 6                      | 1/9             |
