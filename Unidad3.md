Ejercioio Unidad 3
Calcular edad de una persona a partir de su fecha

Datos entrada: 
Dia actual (Dia_A)
Dia cumpleaños (Dia_C)
Mes actual (Mes_A)
Mes cumpleaños (Mes_C)
Año actual (Año_A)
Año cumpleaños (Año_C)

Inicio
    Leer Dia actual (Dia_A)
    Leer Dia cumpleaños (Dia_C)
    Leer Mes actual (Mes_A)
    Leer Mes cumpleaños (Mes_C)
    Leer Año actual (Años_A)
    Leer Año cumpleaños (Cumpleaños_A)

    Definir cumpleaños y edad
    Cumpleaños=mes_a-mes_c+dia_a-dia_c
    edad=año_a-año_c
    mes=mes_a-mes_c
    Si el valor mes es menor a 0
        imprimir edad
    Si el valor mes es mayor a 0
        edad=edad-1
        imprimir edad
    Si el valor cumpleaños igual o menor 0
        edad=edad-1
        Imprimir "Feliz cumpleaños!" 
        Imprimir edad
    

    Fin
