# Evidencia06_Ocultamiento_de_datos


Integrantes 
Valentina Huenchuñir -
Maria Jose Powell - 
Fernanda Muñoz

Profesor
Dr. Samuel Sepulveda

Asignatura
Programación Orientada a Objetos


Fecha
04 de octubre de 2023

Evidencia del programa:


![Captura de pantalla 2023-10-04 171120](https://github.com/FernaMunoz/Evidencia06_Ocultamiento_de_datos/assets/142464144/4b4577db-50fd-4c4c-ad83-0ba04d37da57)



![Captura de pantalla 2023-10-04 171353](https://github.com/FernaMunoz/Evidencia06_Ocultamiento_de_datos/assets/142464144/debf7d53-edda-415a-8c1c-120a6c4c4c5b)


Compilación exitosa del programa:


![Captura de pantalla 2023-10-04 171529](https://github.com/FernaMunoz/Evidencia06_Ocultamiento_de_datos/assets/142464144/116b4df2-f012-48f2-bfae-65c72ef30dad)


![Captura de pantalla 2023-10-04 171633](https://github.com/FernaMunoz/Evidencia06_Ocultamiento_de_datos/assets/142464144/4ec08cb4-867f-49fc-9569-645c090a2110)



Preguntas:

1.¿Desde dónde es posible acceder a la variable time?
   
a. Cualquier otra clase

b. java.util package 

c. myUtilities package

d. La clase TodaysDate 

La clase TodaysDate y sus sub clases

Respuesta respecto a nuestro código: 
Entre las opciones presentadas, la opción d) y e) son más viables, si se accede la variable hora está definida en la propia clase TodaysDate. En este caso, es accesible dentro de la propia clase.
La opción e) igual es posible, si la variable hora tiene un modificador de acceso, siendo este privado y si las subclases de TodaysDate están en el mismo paquete o son subclases que pueden acceder a miembros protegidos o públicos de la clase TodayDate.

Respuesta respecto a código ppt: 
Según el código presentado en campus virtual,  la variable Time es de tipo “default”, por lo tanto es posible acceder a esta desde cualquier clase que se encuentre en el mismo paquete, por lo tanto las alternativa correcta es e), segun entendi se utiliza el package java.util por lo tanto también se puede acceder a la variable time en subclases del mismo paquete por lo que la alternativa b) igual es correcta


2. ¿Quiénes pueden acceder al atributo day?
Respuesta respecto a nuestro código:
El atributo day a estar en privado, la clase que contiene al atributo puede acceder. 
Por lo que ninguna otra clase, ni siquiera las subclases, pueden acceder directamente al atributo day. Esto se debe a que el modificador de acceso private, ya que restringe el acceso de la variable en la propia clase.

Respuesta respecto a código ppt: 
Según el código del ppt, el atributo day es público cualquiera puede acceder a este, ya sea dentro la misma clase, desde cualquier otra clase dentro del mismo package, desde cualquier subclase o clase de otro package


3. ¿Qué atributos de las clases tienen el método de acceso más restrictivo?
   
a.Day 

b.Month  

c.Time 

d.Year

Respuesta respecto a nuestro código: 
Las 4 alternativas tienen modificador de acceso privado, siendo que solo se puede acceder en la misma clase TodayDate, por lo que todas las alternativas tienen el mismo método de acceso restrictivo.

Respuesta respecto a código ppt: 

En orden de menos a más restrictivo

a.Day es el menos restrictivo ya que es de tipo public

b.Time es de tipo default 

c.Year ya que es de tipo protected

d.Month es el método con acceso más restrictivo ya que es de tipo private


4. ¿Desde dónde se puede acceder al atributo year?
   
Sólo dentro del package myUtilities. 

Sub clases de TodaysDate en cualquier package. 

La clase TodaysDate 

Sub clases de TodaysDate

Respuesta respecto a nuestro código: 
Si el atributo year está declarado como privado, entonces solo se puede acceder a él desde dentro de la propia clase TodaysDate. Debido a que ninguna otra clase fuera de TodaysDate puede acceder directamente al atributo year sí está declarado como privado, incluso si son subclases de TodaysDate. Para que las subclases puedan acceder a un atributo privado, generalmente se proporcionan métodos en la clase principal, para permitir un acceso controlado.

Respuesta respecto a código ppt: 
El atributo Year al ser protected puede ser en c),  b) y d).  


![Captura de pantalla 2023-10-04 172421](https://github.com/FernaMunoz/Evidencia06_Ocultamiento_de_datos/assets/142464144/39a3da31-dcdb-4f36-87b9-7754eaeb75de)


