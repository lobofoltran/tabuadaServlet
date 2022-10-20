# TabuadaServlet

Tabuada com Java para Web.

Recebe por parâmetro GET (numero) na rota /tabuada um número que é validado. Também pode ser um Array de números, separados por ponto e vírgula (;).

Exemplo: /tabuada?numero=10;20;30

O servidor irá responder a tabuada do número 10, 20 e 30. Não responde caso receba letras para evitar erros. 
Se o servidor não encontrar parâmetros, responde a tabuada de 1 a 10.

![image](https://user-images.githubusercontent.com/89169668/196841543-c0ae61c5-aab1-4b18-b593-87fb0f356348.png)
