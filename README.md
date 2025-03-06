#EJEMPLO PRÁCTO


# DEFINIMOS UNA LISTA PARA LAS NOTAS
notas = [1, 2, 4, 1, 5, 1.5, 2.5, 3, 1, 1.5, 1.2, 3]

# CREAMOS UNA VARIABLE PARA ALMACENAR LA SUMA DE NOTAS
sumatoria = 0

# USAMOS UN BUCLE FOR PARA ITERAR SOBRE LA LISTA Y SUMAR LOS ELEMENTOS
for n in notas:
    sumatoria += n

# CALCULAMOS EL PROMEDIO DE LAS NOTAS 
cantidadelementos = len(notas)
promedio = sumatoria / cantidadelementos

# FINALMENTE IMPRIMIMOS EL PROMEDIO
print(f"El promedio de las notas obtenidas por los estudiantes en el parcial es: {promedio}")


#EL RESULTADO SERÍA


El promedio de las notas obtenidas por los estudiantes en el parcial es: 2.225
