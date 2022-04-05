
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
FinAlgoritm
![image](https://user-images.githubusercontent.com/101481278/161847729-7e1cd87d-c07e-4891-81f1-ae7689b100aa.png)



7. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.
Algoritmo par_o_impar
	Escribir "ingresa un número"
	Leer num
	Si num % 2 == 0 Entonces
	escribir "el número ",num," es par"
	SiNo
	escribir "el número ",num, " es impar"
	Fin Si
	FinAlgoritmo
	![image](https://user-images.githubusercontent.com/101481278/161847827-5093e757-5222-4fc2-950e-3c804f5c5340.png)


9. Un programa que pida una letra y detecte si es una vocal.
10. 
11. Algoritmo detecta_si_es_vocal
	Escribir "ingresa una letra"
	Leer vocal
	Segun vocal Hacer
	"a"|"A":
	Escribir "la letra ",vocal," es una vocal"
	"e"|"E":
	Escribir "la letra ",vocal," es una vocal"
	"i"||"i":
	Escribir "la letra ",vocal," es una vocal"
	

	
	"o"||"O":
	Escribir "la letra ",vocal," es una vocal"
	"u"||"U":
	Escribir "la letra ",vocal," es una vocal"
	De Otro Modo:
	Escribir "la letra ",vocal," no es vocal"
	Fin Segun
	
	FinAlgoritmo
	![image](https://user-images.githubusercontent.com/101481278/161453267-bbb53a93-9cca-453c-b9d8-6fc49537a670.png)


11. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
lgoritmo orderar_numeros
	Escribir "ingresa un número"
	Leer num1
	Escribir "ingresa otro número"
	Leer num2
	Escribir "ingresa otro número"
	Leer num3
	Si num1<num2 && num1<num3 Entonces
	Si num2<num3 Entonces
	Escribir num1,num2,num3
	SiNo
	Escribir num1,num3,num2
	Fin Si
	SiNo
	Si num2<num1 && num2<num3 Entonces
	Si num1<num3 Entonces
	Escribir num2,num1,num3
	SiNo
	Escribir num2,num3,num2
	Fin Si
	SiNo
	Si num3<num1 Entonces
	Si num1<num2 Entonces
	Escribir num3,num1,num2
	SiNo
	Escribir num3,num2,num1
	Fin Si
	SiNo
	Escribir "hay algún número repetido"
	Fin Si
	Fin Si
	Fin Si
		FinAlgoritmo


13. 
14. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
15. Algoritmo nombre_impreso_un_numero_de_veces
	Escribir "ingresa tu nombre"
	Leer nombre
	Escribir "ingresa el número de veces que deseas imprimir tu nombre"
	Leer num
	Para i<-1 Hasta num Con Paso 1 Hacer
	Escribir nombre
	Fin Para
	FinAlgoritmo
	![image](https://user-images.githubusercontent.com/101481278/161453374-2eda7c02-3e44-4379-9eaa-e19f738866c0.png)

	
15. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
16. 
Algoritmo tablas_de_multiplicar
	Escribir "ingresa un numero"
	Leer num
	Mientras num > 0 Hacer
	resultado<-resultado + num
	Escribir "ingresa un numero"
	Leer num
	Fin Mientras
	Escribir "el resultado de la suma de los número positivos es ",resultado
	FinAlgoritmo
