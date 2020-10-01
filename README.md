# se ocupa poner el float para convertir el string introducido
base = float(raw_input('Ingrese base:  '))
exponente = float(raw_input('Ingrese exponente:  '))
potencia=1;

while(exponente>0): 
         potencia = potencia*base;
         exponente=exponente-1;


print 'Potencia :',potencia
