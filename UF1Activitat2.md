# LLENGUATGE INTERPRETAT # 

## RUBY      

**INTERPRETAT**

No es tradueix tot de cop i s’executa directament el codi màquina sinó que l’intèrpret (un altre programa) s’encarrega d’anar executant indirectament el codi instrucció per instrucció.

###### EXEMPLE:


![image](https://user-images.githubusercontent.com/113586105/195207864-1b0d23a3-e841-4401-a400-47e9f5e7900f.png)

Descarguem el ruby.

![image](https://user-images.githubusercontent.com/113586105/195207967-b1536e2d-9031-4435-9e2d-18ff12a64670.png)

Aquí hem mirat la versió.

![image](https://user-images.githubusercontent.com/113586105/195208045-40b66cf9-e960-4f41-a724-1c4953b109f2.png)

Amb el nano hem creat un hello world.

![image](https://user-images.githubusercontent.com/113586105/195208089-d198d150-546d-4a29-a2bf-c36dd1ff39d4.png)


El nom de l’executable és .rb (hello_world.rb).
Ruby és l’executable.

![image](https://user-images.githubusercontent.com/113586105/195208247-3c88f7d9-0704-4478-8317-b48afa95b141.png)



Aquí hem posat un exemple, el “irb” serveix per a fer operacions.

![image](https://user-images.githubusercontent.com/113586105/195208287-7c6b3b42-60d1-4e10-b560-db27fabc25e8.png)



Aquí ja tenim el codi bé i ens dona un número aleatori de entre l’1 i el 6.
### Avantatges:

- És independent de la màquina i del sistema operatiu, ja que no conté instruccions pròpies d'un processador sinó que conté trucades a funcions que l'intèrpret haurà de reconèixer. 

- A més, un llenguatge interpretat permet modificar en temps d'execució el codi que s'està executant així com afegir-hi nou

### Desavantatges:

- Velocitat. És l'aspecte més notable.

- Portabilitat. Ja que gairebé tots els llenguatges compilats, existeixen per a totes les plataformes, no així les màquines virtuals o frameworks, encara que en el cas de Java, s'ha fet un excel·lent treball pel que fa a això.

### IDE PER A DESARROLLADORES DE RUBY
-  **Aptana Studio**: suporta les últimes tecnologies per a navegadors amb HTML5, CSS3L JavaScript, Ruby, etc.
- **Net Beans**: estaba pensat per desenvolupar en Java pero és comaptible amb JavaFX, PHP, JavaScriopt, Ruby, etc.
- **RubyMine**: té tot el que un desenvolupador de Rubt necessita en un entorn de desnvolupament.


Webs visitades:

https://openwebinars.net/blog/que-es-ruby/ 
https://www.rubyguides.com/2015/03/ruby-random/
https://apuntes.de/ruby/la-linea-de-comandos/#gsc.tab=0
https://www.ecured.cu/Lenguaje_interpretado#Ventajas
https://programacion.net/articulo/los_5_mejores_ides_para_ruby_on_rails_1077

# LLENGUATGE COMPILAT

## C

El compilador no és més que un traductor entre el llenguatge d’alt nivell i el codi màquina, entre el que entenen les persones i el que entén la CPU.

### Avantatges
- **Multiplataforma:** el llenguatge C pot ser executat en qualsevol tipus de programari o maquinari.
- **Ús de llenguatge eficient:** Utilitza llenguatge compilat i s’acobla de manera efectiva amb el llenguatge assemblador, així com també és el que millor aprofita la CPU de la màquina.
- **Alt nivell d’exercici:** el primer que has de saber sobre el llenguatge C és que es molt eficient per fer trucades directes al sistema operatiu.
- **Té ús eficient** de la memòria i compta am **funcions i variables estàtiques**
### Desavantatges
- **Llenguatge incomplet:** no té prou operadors per fer més abstracta la traducció del sistema. No té un llenguatge visual, per lo que impedeix que es pugui deduir intuïtivament.
- **Manca de funcions:** no té alliberament de memòria automàtica, lo que significa que ho hauràs de fer manualment. No tè suport per a la programaciò orientada a objectes.
- **No permet checking a temps d’execució:** el llenguatge C mostra el error després d’haver compilats estos, en lloc de fer-ho en temps d’execució.

### IDE PER A DESARROLLADORES DE C

- **Virtual Studio:** 
	- Compatible amb: Windows, macOS i Linux.
	- Finalització de codi usant IntelliSense.
	- Integració Git incorporada.
	- Fácil desenvolupament d’Azure.
	- Suport integrat de depurador i VCS.
- **Xcode:**
	- Compatible amb macOS.
	- Depurador gràfic.
	- Anàlisi de codi estàtic.
	- Documentació completa.
	- Integració contínua.
- **Eclipse:**
	- Comunitat rica i de codi obert.
	- Compatible amb: Windows, macOS i Linux.
	- Creació de projectes més senzilla.
	- Admet anàlisi de codi estàtic.
	- Fàcil depuració.




![image](https://user-images.githubusercontent.com/113586105/195208392-6e85234b-d1cb-42ee-94f5-c9c9e8f51e50.png)



Aquí hem instal·lat el gcc per a poder fer servir coses del c.
El “gcc -o ___” és el comando per a passar de codi font a codi executable.
El nom de l’executable és .c.

![image](https://user-images.githubusercontent.com/113586105/195208460-675d9370-a063-4534-922b-1bbce916815f.png)


Hem creat amb el gedit un fitxer i hem ficat aquest codi per a que ens digue un número aleatori de l’1 al 6:

![image](https://user-images.githubusercontent.com/113586105/195208519-8b3ae997-c239-463a-961c-071718fa4bcd.png)


Passem de codi font a codi executable.


![image](https://user-images.githubusercontent.com/113586105/195208854-1e46ee27-3d66-4c97-917c-190c1c5e6b31.png)

![image](https://user-images.githubusercontent.com/113586105/195208940-43955fde-82a0-40d3-b1f5-2a272ce30239.png)


Això és el resultat

![image](https://user-images.githubusercontent.com/113586105/195208962-6137c2ba-7c79-4170-8e52-0752c289a81e.png)


##### BIBLIOGRAFIA
https://vitux.com/how-to-write-and-run-a-c-program-in-linux/
https://itsfoss.com/run-c-program-linux/
https://linuxhint.com/rand-function-in-c-language/ (exemples de ranomcommand
https://www.geeksforgeeks.org/generating-random-number-range-c/














Aquí hem instal·lat el python3.

Amb el touch creem un fitxer.
EL “chmod +x” és per a passar de codi font a codi executable.


Aquest és el codi.


El resultat.
Python3 és per a mostrar el resultat.

A bytecode:


el nom de l’executable és .py.
el comando és python -m (he posat 3 perquè m’he descarregat el 3)

(no puc obrir-ho però és el bytecode).

### AVANTATGES
- Es arriben a executar en qualsevol plataforma.
- No ocupen gairebé espai a la memòria.
- L’entorn de la feina és el que s’arriba a encarregar de que el maquinari executa les instruccions que se’ls doni.
- Les variables de dades utilitzades arriben a ser dinàmiques pel que no es restringeixen a un tipus en específic.
- Aquest llenguatges són molt utilitzats en el desenvolupament web i de l’electrònica.

### DESAVANTATGES
- L’execució d’aquests llenguatges és més lenta a diferència del llenguatges compilats.
- Són difícils de depurar.
- Es necessita d’un programari que serveix per interpretar les instruccions del processador.
- No tots el programes es troben disponibles en totes les plataformes..




###### IDES
PyCharm.
KDevelop.
SlickEdit.



### WEBGRAFIA
https://www.clubdetecnologia.net/blog/2014/lenguajes-alternativos-de-la-java-virtual-machine/
https://askubuntu.com/questions/244378/running-python-file-in-terminal
https://linuxhint.com/run-python-scripts-linux/
https://opensource.com/article/18/4/introduction-python-bytecode 
https://programacion.net/articulo/los_5_mejores_ides_para_ruby_on_rails_1077 
https://www.crehana.com/blog/transformacion-digital/ventajas-desventajas-lenguaje/ 
https://es.acervolima.com/10-mejores-ide-para-desarrolladores-de-c-o-c-en-2021/ 














