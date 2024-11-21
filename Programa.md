Algoritmo CalculoPuntaje
	           // Programa para calcular el puntaje de un juego.
	Definir fichasRojas, fichasAzules, fichasAmarillas, puntaje Como Entero
	Definir continuar Como Caracter
	continuar <- 's'
	
	Escribir "Programa para calcular el puntaje de un juego."
	
	Mientras continuar = 's' O continuar = 'S' Hacer
		Escribir "Ingresa la cantidad de fichas rojas (primeros lugares): "
		Leer fichasRojas
		Escribir "Ingresa la cantidad de fichas azules (segundos lugares): "
		Leer fichasAzules
		Escribir "Ingresa la cantidad de fichas amarillas (últimos lugares): "
		Leer fichasAmarillas
		
		puntaje <- (fichasRojas ^ 3) + (2 * fichasAzules) - (fichasAmarillas ^ 2)
		
		Escribir "El puntaje obtenido es: ", puntaje
		
		Escribir "¿Deseas calcular nuevamente? (s/n): "
		Leer continuar
	FinMientras
	
	Escribir "Programa terminado. ¡Hasta luego!"
FinAlgoritmo
