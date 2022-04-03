
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

Algoritmo multiplicar_por_9_un_numero
	Escribir "ingresa un número"
	Leer num
	resultado<-num * 9
	Escribir "el resultado de ",num," * 9 es: ",resultado
	FinAlgoritmo
	![image](https://user-images.githubusercontent.com/101481278/161452979-b98fd86e-b01b-4c8e-9ece-d137e861a2ef.png)

	
FinAlgoritmo

3. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 
Algoritmo suma_10_cantidades
	sum<-0
	c<-1
	Mientras c<=10 Hacer
	Leer va
	sum=sum+va
	c=c+1

	
	Fin Mientras
	Escribir sum
	FinAlgoritmo
Algoritmo suma_10_cantidades
	sum<-0
	c<-1
	Mientras c<=10 Hacer
	Leer va
	sum=sum+va
	c=c+1

	
	Fin Mientras
	Escribir sum
	FinAlgoritmo

![image](https://user-images.githubusercontent.com/101481278/161453048-69ab41f5-ae01-4327-a021-7c468d5789d0.png)

	

	

5. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo promedio_calificaciones
Escribir "ingresa la calificación del primer periodo"
Leer cal1
Escribir "ingresa la calificación del segundo periodo"
Leer cal2
Escribir "ingresa la calificación del tercer periodo"
Leer cal3
Escribir "ingresa la calificación del cuarto periodo"
Leer cal4
promedio<-(cal1+cal2+cal3+cal4)/4
Si promedio >= 6 Entonces
Escribir "felicidades has aprobado, tu promedio es de ",promedio
SiNo
Escribir "Lo siento has reprobado, tu promedio es de ", promedio
Fin Si
FinAlgoritmo
![image](https://user-images.githubusercontent.com/101481278/161453085-81215158-c361-4081-a3da-c8fbc1439001.png)

7. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.
8. 
9. Un programa que pida una letra y detecte si es una vocal.
10. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
11. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
12. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
