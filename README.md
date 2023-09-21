# trabajo-de-pogra
#Rodrigo Galindo Callen
#Trabajo supervisado Introducción a la programación
#21/09/2023

while True:
    # Solicitar al usuario un número
    numero = int(input("Ingrese un número para generar la tabla de multiplicar: "))

    # Mostrar la tabla de multiplicar
    print(f"Tabla de multiplicar del {numero}:")
    for i in range(1, 11):
        resultado = numero * i
        print(f"{numero} X {i} = {resultado}")

    # Preguntar si desea generar la tabla de otro número
    respuesta = input("¿Desea generar la tabla de otro número? (Sí/No): ").lower()
    if respuesta != "si":
        break
