# calculadora_python

def calculadora():

	#CALCULADORA EN FUNCIONES
	
	print("Hola Bienvenido A Tu Calculadora")

	print("Que Deseas Hacer? = \n  + : s \n  - : r \n  * : m \n  / : d")
	operacion = raw_input()

	x = int(input("num: "))
	y = int(input("num: "))

	if operacion == "s":
		resultado = (x + y)
		print x,"+", y , "=",resultado

	elif operacion == "r":
		resultado = (x - y)
		print x,"-", y , "=",resultado

	elif operacion == "m":
		resultado = (x * y)
		print x,"*", y , "=",resultado

	elif operacion == "d":
		resultado = (x / y)
		print x,"/", y , "=",resultado
	
calculadora()
