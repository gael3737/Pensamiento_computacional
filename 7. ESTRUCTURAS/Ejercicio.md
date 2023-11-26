1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
  
  ......Algoritmo sin_titulo
	Definir num1, num2 Como Entero
	Escribir "Ingresa el primer número"
	Leer num1
	Escribir "Ingresa el segundo número"
	Leer num2
	Si num1 > num2 Entonces
		Escribir "El primer número es mayor que el segundo"
	Sino
		Si num2 > num1 Entonces
			Escribir "El segundo número es mayor que el primero"
		Sino
			Escribir "Ambos números son iguales"
		FinSi
FinSi
FinAlgoritmo......

        
2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

    ....Algoritmo sin_titulo
	Definir cal1, cal2, cal3, cal4, promedio Como Real
	Escribir "Ingresa la calificación del primer periodo"
	Leer cal1
	Escribir "Ingresa la calificación del segundo periodo"
	Leer cal2
	Escribir "Ingresa la calificación del tercer periodo"
	Leer cal3
	Escribir "Ingresa la calificación del cuarto periodo"
	Leer cal4
	promedio = (cal1 + cal2 + cal3 + cal4) / 4
	Si promedio > 6 Entonces
		Escribir "¡Felicidades! Tu promedio es mayor a 6"
	Sino
		Escribir "Lo siento, has reprobado"
FinSi
FinAlgoritmo.....


3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

   ..... Algoritmo sin_titulo
	Definir num Como Entero
	Escribir "Ingresa un número"
	Leer num
	Si num mod 2 = 0 Entonces
		Escribir "El número es par"
	Sino
		Escribir "El número es impar"
	FinSi
FinAlgoritmo.....

Algoritmo para calcular el imc
Algoritmo detarea

Declaramos las siguientes variables.

               definir peso,estatura,imc como real

               definir masa como carácter

Con la función escribir pedimos que se ingres el peso en kilogramos.

               Escribir «Ingresa tu peso en kilogramos»

Este dato lo asignamos en a variable peso.

               Leer peso

Con la función escribir pedimos que se ingrese la estatura en metros.

               Escribir «Ingresa tu estatura en metros»

Este dato lo asignamos en la variable estatura.

               Leer estatura

Para calcular el índice de masa corporal, simplemente dividimos el peso entre la estatura elevado al cuadrado.

               imc = peso / (estatura * estatura)

Después evaluamos si el índice de masa corporal es menor a 18.5.

               Si imc < 18.5 Entonces

Si la condición se cumple, entonces quiere decir que la persona tiene bajo peso.

                              masa = «bajo peso»

               SiNo

Si la condición no se cumple, entonces evaluamos si el índice de masa corporal es menor o igual a 24.9.

                              Si imc <= 24.9 Entonces

Si la condición se cumple, entonces quiere decir que la persona tiene peso normal.

                                             masa = «peso normal»

                              SiNo

Si la condición anterior no se cumple, entonces evaluamos si el índice de masa corporal es menor o iguala a29.9.

                                            Si imc <= 29.9 Entonces

Entonces quiere decir que la persona tiene sobrepeso.

                                                            masa = «sobrepeso»

                                            SiNo

Cuando ninguna de las condiciones anteriores se cumpla, entonces quiere decir que la persona tiene obesidad.

                                                           masa = «Obesidad»

                                            FinSi

                              FinSi

               FinSi

Finalmente mostramos en pantalla un mensaje donde indicamos el índice de masa corporal.               Escribir «Tu índice de masa es: «,imc,» tienes «,masa

FinAlgoritmo
