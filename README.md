ALGORITMOS
==========

CLASS


// PROGRAMA FIBONACCI

>>> import sys
>>> def fibonacci():
    print "\n Seleccione la cantidad de numeros que quiere ver en la secuencia"
    n= int(sys.stdin.readline())
	  Serie(n)

>>> def Serie(n):
	  a,b = 0,1
	  for i in range (0,n):
		  print a
		  a,b, =b,a+b

>>> fibonacci()