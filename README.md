Inicio del pseudocódigo

// Definición de la función para obtener detalles del personaje
función obtenerDetallesPersonaje(nombre_personaje):
    // Simulamos una llamada a la API con datos ficticios
    si nombre_personaje es "Itadori Yuji":
        retornar {
            nombre: "Itadori Yuji",
            estado: "vivo",
            edad: 16,
            estatura: "175 cm",
            tipo: "hechicero"
        }
    sino si nombre_personaje es "Sukuna":
        retornar {
            nombre: "Sukuna",
            estado: "muerto",
            edad: "Desconocida",
            estatura: "Varía",
            tipo: "maldición"
        }
    sino:
        retornar "Personaje no encontrado"

// Uso de la función para obtener detalles de personajes específicos
detalles_1 = obtenerDetallesPersonaje("Itadori Yuji")
imprimir detalles_1

detalles_2 = obtenerDetallesPersonaje("Sukuna")
imprimir detalles_2

Fin del pseudocódigo
