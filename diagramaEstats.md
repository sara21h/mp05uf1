## diagrama d'estats

*****activitat 3***** 

- Diagrama d'estat del controlador de l'aparell d'aire acondicionat.

![image](https://github.com/sara21h/mp05uf1/assets/113586105/4838675d-27b1-4724-abe9-717471454177)

El que fa es:

Primer està a l'estat "parat", després s'engega apretant al botó d'engegar, passem a l'estat "engegat", on tenim la variable de "graus" que és igual a la temperatura ambient, després tenim 3 opcions:

- incrementar la variable "graus", passarà a l'estat acalentant, que el que farà serà sumar a graus x, que després d'incrementar-lo, tornarà a l'estat engegat.
- decrementar la variable "graus", passarà a l'estat refrescant, que el que farà serà restar a graus x, que després de decrementar torna a l'estat d'engegat.
- apagar amb el botó d'apagar, i passem a l'estat parat.

Li hem afegit això:

![image](https://github.com/sara21h/mp05uf1/assets/113586105/806d5cbf-286b-4e0e-aeca-a05915d76886)

- passem a calentar si la temperatura ambient és menor que la de l'aparell (graus). Si és menor vol dir que farà més fred així que el que fem és incrementar els graus.
- passem a refrescar si la temperatura ambient és major que la de l'aparell (graus), ja que això vol dir que faria més calor i el que volem és que refresqui.
- desde els 2 casos, tornarem a l'estat d'engegat quan la t.ambient i la de graus siguin iguals. 
