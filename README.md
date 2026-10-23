Algoritmo Ejercicio1
	
		Definir cantidad, i, numero Como Entero
 Escribir "Cuantos números vas a introducir?"
		Leer cantidad
		i = 1
		Mientras i <= cantidad Hacer
 Escribir "Introduce un número:"
 Leer número
			Si numero > 10 Entonces
				Escribir "Es mayor que 10"
			Sino
				Si numero < 10 Entonces
					Escribir "Es menor que 10"
				Sino
					Escribir "Es igual a 10"
				FinSi



        
Algoritmo Ejercicio2
	
		Definir cantidad, i, numero, referencia Como Entero
		
 Escribir "Introduce el número de referencia:"
		Leer referencia
		
 Escribir "Cuantos números vas a comparar?"
		Leer cantidad
		
		i = 1
		Mientras i <= cantidad Hacer
 Escribir "Introduce un número:"
 Leer número
			
			Si numero > referencia Entonces
 Escribir "Es mayor que el número de referencia"
			Sino
				Si numero < referencia Entonces
 Escribir "Es menor que el número de referencia"
				Sino
 Escribir "Es igual al número de referencia"
				FinSi
			FinSi
			
			i = i + 1
		FinMientras
FinAlgoritmo

			FinSi
			i = i + 1
		FinMientras
FinAlgoritmo


Ejercicio Ergoritmo 3
	
 Definir número, contador Como Entero
		
 número = 1
		contador = 0
		
 Mientras número < 100 Hacer
			Si numero MOD 2 <> 0 Entonces
 Escribir número
				contador = contador + 1
			FinSi
			
 número = numero + 1
		FinMientras
		
 Escribir "Cantidad de números impresos: ", contador
FinAlgoritmo






Algoritmo Ejercicio4
	
		Definir limite, numero, suma, sumaMultiplos Como Entero
		
 Escribir "Introduce el límite:"
 Leer límite
		
 número = 0
 SUMA = 0
		sumaMultiplos = 0
		
		Mientras numero <= limite Hacer
			Si numero MOD 5 = 0 Entonces
 sumaMultiplos = sumaMultiplos + número
			Sino
 Escribir número
 SUMA = SUMA + Número
			FinSi
			
 número = numero + 1
		FinMientras
		
 Escribir "La suma de los números no multiplos de 5 es: ", suma
		Escribir "La suma de los multiplos de 5 es: ", sumaMultiplos
FinAlgoritmo
	





Algoritmo Ejercicio5
	
		Definir limite, numero, suma, contador Como Entero
		
 Escribir "Introduce el límite:"
 Leer límite
		
 número = 1
 SUMA = 0
		contador = 0
		
		Mientras numero <= limite Hacer
			Si numero MOD 2 = 0 Y numero MOD 3 = 0 Entonces
 Escribir número
 SUMA = SUMA + Número
				contador = contador + 1
			FinSi
			
 número = numero + 1
		FinMientras
		
		Escribir "La suma es: ", suma
		Escribir "La cantidad de multiplos es: ", contador
FinAlgoritmo




