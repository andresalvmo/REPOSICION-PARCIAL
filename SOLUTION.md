
**PARTE DE DISEÑO

![image](https://user-images.githubusercontent.com/80064766/116014099-2a4c1100-a5f9-11eb-9a46-dc38e719c8bf.png)

![image](https://user-images.githubusercontent.com/80064766/116014824-c4fa1f00-a5fc-11eb-8b41-cf3c9bb260dc.png)


**PARTE DE EXTENDIENDO

![dependencia](https://user-images.githubusercontent.com/80064766/116013810-ae9d9480-a5f7-11eb-959f-e2255aa8f4d1.JPG)

* PARTE CONCEPTUAL

1. ¿Cuales son las acciones los tres momentos importantes de las excepciones? 

Son lanzamiento, propagación y captura

¿Cual es el objetivo de cada una?

- Lanzamiento: comunicar al usuario que existe una excepción
- Propagación: se quiere controlar
- Captura: se controla la excepción

¿Como se implementa en java cada acción?

- Lanzamiento: Se lanza con: throw new exception
- Propagación public void cualquiercosa() throws exception
- Captura: 

try{

//cualquiercosa

}catch(Exceptionerror){

}

2. ¿ Que es sobre-escritura de metodos? 

Es cuando un metodo tiene el mismo nombre y tipo de otro en diferente clase

¿Por que aplicarla? 

Nos permite redefinir un metodo que se heredo para que funcione de acuerdo a nuestras necesidades y no al metodo de la superclase ya definido

¿Como impedir que se sobre-escriba un metodo?

Con la palabra final

