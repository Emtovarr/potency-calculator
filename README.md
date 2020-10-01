# potency-calculator
Trabajo unal punto 4 
"""
 Calcular la potencia de un numero en Python usando el ciclo While, sin usar el Pow

"""
def potencia(numero, exponente):
     contador = 1
     elevado = 1
     
     while contador <= exponente:
    elevado = elevado * numero
    contador = contador + 1

 return elevado

"""

Probar
"""
print(potencia(2, 3))
