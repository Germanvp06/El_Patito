# El_Patito

Repetir
		
		Escribir "Ingrese la cantidad de datos:"
		Leer n
		Repetir
			
			Si n<=0 Entonces
				Escribir "El número debe ser positivo y distinto de cero."
				Escribir "Introduzca un número válido."
			Fin Si
			
		Hasta Que n>0
		
		acum<-0
		
		Para i<-1 Hasta n Hacer
			Escribir "Ingrese el dato ",i,":"
			Repetir
				Leer dato
				Si dato<0 Entonces
					Escribir "El dato debe ser positivo."
					Escribir "Ingrese el dato ",i,":"
				Fin Si
			Hasta Que dato>=0
			
			acum<-acum+dato
		Fin Para
		
		prom<-acum/n
		
		Escribir "El promedio es: ",prom
		
		Escribir "¿Quieres continuar?"
		Leer Respuesta;
		Si Respuesta = "Si" Entonces
			Escribir "Continuamos"
		FinSi
	Hasta que Respuesta = "No"