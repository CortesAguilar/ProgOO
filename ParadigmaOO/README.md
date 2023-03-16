# El paradigma orientado a objetos

## ¿Qué es un paradigma en programación?

[Se denominan paradigmas de programación a las formas de clasificar los lenguajes de programación en función de sus características. Los idiomas se pueden clasificar en múltiples paradigmas.
Algunos paradigmas se ocupan principalmente de las implicancias para el modelo de ejecución del lenguaje, como permitir efectos secundarios o si la secuencia de operaciones está definida por el modelo de ejecución. Otros paradigmas se refieren principalmente a la forma en que se organiza el código, como agrupar un código en unidades junto con el estado que modifica el código. Sin embargo, otros se preocupan principalmente por el estilo de la sintaxis y la gramática](https://es.wikipedia.org/wiki/Paradigma_de_programaci%C3%B3n)

## ¿Cual fue el primer lenguaje de programación? 

![image](https://user-images.githubusercontent.com/126859766/225513854-de746f3e-b28d-4a61-97bd-ca9fd5972d02.png)

[Simula es un lenguaje de programación orientada a objetos (POO) de 1962. Fue el primero de este tipo que incluyó el concepto de clase. Varios años después de su desarrollo, casi todos los lenguajes modernos comenzaron a utilizar sus principios de orientación a objetos. Así fue como se popularizaron términos como clases, objetos, instancias, herencia, polimorfismo, etc.
Simula 67 fue lanzado oficialmente por sus autores Ole Johan Dahl y Kristen Nygaard en mayo de 1967, en la Conferencia de Trabajo en Lenguajes de Simulación IFIO TC 2, en Lysebu cerca de Oslo](https://es.wikipedia.org/wiki/Simula)

## Abstracción

La abstracción es un concepto clave en programación orientada a objetos. Se dice que programar es abstraer; el proceso de abstracción es aquel que de un fenómeno o una estructura compleja y multifactorial se extraen las entradas-y-salidas y propiedades más importantes para poder representarla con código.
Por ejemplo, un partido de futbol puede ser un infierno probabilístico o una caja negra de goles y jugadores dependiendo del nivel de abstracció utilizado.

## Encapsulamiento

El encapsulamiento es otro concepto parte de la ~**GODHEAD**~ de la orientación a objetos. Consiste en la protección de los datos de un objeto con respecto al exterior. Los datos se protegen para no poder ser modificados directamente, sino por medio de métodos mensajeros. 

*Ejemplo de encapsulamiento con automóviles:*

![image](https://user-images.githubusercontent.com/126859766/225514846-e6a1eff0-be5c-4ee1-8822-a156c82758b3.png)



 *Sin encapsulamiento. La mismísima Gehena*![image](https://user-images.githubusercontent.com/126859766/225514985-cd46de64-4c3a-47bc-b7ec-2ae74f52761c.png)

## Herencia.

La herencia es otro concepto clave de la POO. En términos prácticos significa que podemos tomar abstracciones generales y crear basadas en ellas abstracciones más específicas. 

Por ejemplo, puedo crear una clase Persona que tenga todo lo que pueda tener una persona:

* Nombre
* Edad
* Peso
* Comer()

![image](https://user-images.githubusercontent.com/126859766/225515773-8afbdfb4-98f7-47f8-9afc-afbf67cde339.png)



Y con base en esta clase puedo crear una clase hija llamada Programador. Los objetos de tipo programador tendran todo lo que persona, además de sus particularidades.

* Lenguajes de programación
* Programar()

![image](https://user-images.githubusercontent.com/126859766/225515819-67763481-1d6c-4103-b9f0-0b406372940f.png)


Toda esta dinámica de clases madres e hijas ayuda a organizar todo de una manera elegante y estructurada.


# UML: Diagrama de clases

El Lenguaje de Modelado Unificado es un lenguaje de modelado visual utilizado en programación para especificar, construir y documentar sistemas de software. 
Este lenguaje se usa en mucha variedad de sistemas, desde aplicaciones de escritorio hasta sistemas empresariales complejos. En particular, el Diagrama de Clases de UML es una herramienta comúnmente utilizada para visualizar la estructura de clases y objetos en un sistema, así como las relaciones entre ellos.

En años recientes, UML sigue siendo una herramienta ampliamente utilizada para el modelado de software, aunque ha habido una tendencia hacia enfoques más ágiles y centrados en el usuario, como el Diseño Centrado en el Usuario y el Desarrollo Dirigido por el Comportamiento.

Existen diversas herramientas de software disponibles para el modelado en UML, tanto de código abierto como comerciales. Algunas de las herramientas más populares incluyen Visual Paradigm, Enterprise Architect, StarUML, Lucidchart, ArgoUML y MagicDraw. 
En lo personal, ignoro si estas herramientas son utilizadas en empresas locales en la actualidad. 

## Máquina expendedora de sodas 

Sea el sistema "M" una máquina expendora de Sodas perteneciente al Texas Institute of Technology and Science
A cambio de la mejor moneda de los Estados Unidos (usd) proporcionará saludables refrescos para saciar la sed de los bienaventurados alumnos. Esto lo hará mediante un innovador sistema de reconocimiento auditivo y tarjetas de débito del banco de la preferencia de los educandos.
El diagrama de clases *no* queda como ejercicio para el lector.

![Captura de pantalla 2023-03-15 223229](https://user-images.githubusercontent.com/126859766/225523994-99df230e-951b-4999-a6d4-affe55bcc7be.png)
