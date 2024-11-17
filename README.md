def intentar_nuevamente():
    while True:
        respuesta = input("¿Lo quieres intentar de nuevo? (si/no): ")
        if respuesta.lower() == "si":
            print("¡lo sabia que aun me amas ❤️😍!")
            break
        elif respuesta.lower() == "no":
            print("piensalo bien😢😢😢")
            
        else:
            print("Ingrese si o no.")

intentar_nuevamente()
