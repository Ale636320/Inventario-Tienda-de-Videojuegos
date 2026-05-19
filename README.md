# Sistema de Gestión de Inventario para Tienda de Videojuegos

Este proyecto es una aplicación de escritorio desarrollada en Java para la asignatura de Programación Orientada a Objetos. Su objetivo es automatizar el control de existencias y ventas para pequeños comercios de videojuegos.

## Arquitectura y Organización del Código

El código está organizado siguiendo las buenas prácticas de la Programación Orientada a Objetos, aplicando conceptos de Herencia, Encapsulamiento y Polimorfismo.

* `src/main`: Contiene la clase `Main` que inicializa la aplicación.
* `src/clases`: Contiene la lógica del negocio.
    * `Usuario.java`: Gestiona la autenticación.
    * `Producto.java`: Clase padre que define los atributos básicos de la mercancía.
    * `Videojuego.java`: Clase hija de `Producto` que incorpora atributos específicos (Plataforma, Género).
    * `Inventario.java`: Administra la colección de productos y las alertas de stock.
    * `Venta.java`: Controla el carrito de compras y la facturación.
* `src/gui`: Contiene las interfaces gráficas creadas con Java Swing (Login, Panel Principal, Punto de Venta).

## Requisitos de Ejecución
* Java Development Kit (JDK) 8 o superior.
