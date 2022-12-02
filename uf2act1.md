## ACTIVITATS

###### ACTIVITAT 1:

Calculem CC:


##### Complexitat ciclomàtica = nombre de branques – nombre de nodes + 2

###### Per saber quantes proves hem de fer.

**1**

![image](https://user-images.githubusercontent.com/113586105/204755853-198767a8-174a-418b-a46e-b877ae8cc2e0.png)


###### N. BRANQUES: 16

###### N. NODES: 14

###### 16 - 14 + 2 = 4


**2**

![image](https://user-images.githubusercontent.com/113586105/205242455-7d7be27a-d094-4700-8c86-637f161f0e7a.png)


###### N. BRANQUES: 16

###### N. NODES: 14

###### 16 - 14 + 2 = 4

**3**

![image](https://user-images.githubusercontent.com/113586105/205242595-c92f54fa-27a8-4e3f-a668-4f08dd652933.png)

###### N. BRANQUES: 8

###### N. NODES: 6

###### 8 - 6 + 2 = 4


---------------------------------------------------------------------------------------------------------------------------------------------------------

###### ACTIVITAT 2:

![Captura de pantalla de 2022-11-30 10-38-49](https://user-images.githubusercontent.com/113586105/204760936-bd939b71-62a9-4dae-a05f-78b040d91ac6.png)

![Captura de pantalla de 2022-11-30 10-38-03](https://user-images.githubusercontent.com/113586105/204760841-bdf02a42-6929-42cc-961f-f2b51c0d4729.png)

CC = 2 + 1 = 3

1 --> A=354 B=10 C=9

2 --> A=354 B=9 C=10

3 --> A=400 B=10 C=10

---------------------------------------------------------------------------------------------------------------------------------------------------------

###### ACTIVITAT 3:

![Captura de pantalla de 2022-11-30 10-07-48](https://user-images.githubusercontent.com/113586105/204754044-e49aee8b-3056-4209-a62a-6ce55e05b2ea.png)

CC = 

N.BRANQUES = 15

N. NODES= 13

15 - 13 + 2 = 4

Proves camins:

1 --> Temperatura < 0 = Roba d'esquiar

Temperatura -5º = roba d'esquiar

2 --> Temperatura > 0, Temperatura < 10 = Roba de muntanya

Temperatura 5º = roba de muntanya

3 --> Temperatura > 0, Temperatura > 10, Temperatura < 20 = Roba d'hivern

Temperatura 15º = roba d'hivern

4 --> Temperatura > 0, Temperatura > 10, Temperatura > 20, Temperatura < 30 = Roba d'estiu

Temperatura 27º = roba d'estiu 


---------------------------------------------------------------------------------------------------------------------------------------------------------

###### ACTIVITAT 4:

![Captura de pantalla de 2022-11-30 10-51-56](https://user-images.githubusercontent.com/113586105/204764257-f823d2a6-2502-43ae-8cea-1e77fb3772a9.png)

CC =

N.BRANQUES = 6

N. NODES= 6

6 - 6 + 2 = 2

Proves camins:

1 --> Llums = false, Return llums

2 -->  Llums = false, Hora <= 8 || Hora >= 20, Llums = true


---------------------------------------------------------------------------------------------------------------------------------------------------------

###### ACTIVITAT 5:

**Caixa negra**

En el camp de les proves de programari, hi ha alguns mètodes que es fan servir amb l'objectiu de trobar defectes i avaluar la qualitat del producte. Dos daquests mètodes són caixa blanca i caixa negra, white-box testing and black-box testing.

###### Caixa blanca

És el qual mira el codi i l'estructura del producte que es provarà i utilitza aquest coneixement per a la realització de les proves.

Per a l'execució d'aquest mètode cal que el tester o la persona que hagi de fer servir el mètode tinguin amplis coneixements de la tecnologia i l'arquitectura usada per desenvolupar el programa.

![image](https://user-images.githubusercontent.com/113586105/205248218-30408a23-46dc-48e3-94b4-f15deb9b63a3.png)

###### Caixa negra

És el mètode en què l'element és estudiat des del punt de vista de les entrades que rep i les sortides o respostes que produeix, sense tenir-ne en compte el funcionament intern. Aquestes proves són realitzades des de la interfície gràfica.

![image](https://user-images.githubusercontent.com/113586105/205248366-91591a16-821e-48f5-a625-007740bae67e.png)

Per exemple:

**Caixa negra** testing seria el qual una persona faria abans de comprar un cotxe, encendre els llums, encendre el motor entre altres proves (Sense necessitat de saber com funciona el cotxe per dins)

i 

Realitzar proves de tipus **caixa blanca** seria la tècnica que fa servir un mecànic quan portes el teu cotxe al mecànic i ha de buscar una avaria.
