# fdff
import math

def calcula_distancia_do_projetil(v,y0,teta):
    p1= (v**2)/(2*9.8) * (math.sinh(2*teta))
    p2= (1+ 1+(2*9.8*y0/v**2*(math.sinh(teta**2))**1/2)
    return p1*p2


def celsius_para_fahrenheit(c,f):
    temp= (9*c)/(5*f-160)
    return temp
