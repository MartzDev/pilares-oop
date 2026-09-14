# Sistema de Alquiler de Vehículos

**Objetivo:** Desarrollar una aplicación de consola en Java que aplique los 4 pilares de la Programación Orientada a Objetos (Encapsulamiento, Herencia, Polimorfismo y Abstracción) basándose en el diagrama de clases adjunto en la carpeta `diagrams`.

## Requerimientos Funcionales
1. **Registrar diferentes tipos de vehículos** (Autos y Motos).
2. Todo vehículo debe tener `marca`, `modelo` y una `tarifaBase` por día, los cuales no pueden ser modificados directamente desde fuera de su clase.
3. El sistema debe poder **calcular el costo de alquiler** de cualquier vehículo para una cantidad determinada de días.
   - Para un **Auto**, el costo incluye un recargo adicional de **$10 por día** en concepto de seguro.
   - Para una **Moto**, el costo tiene un recargo fijo único de **$5** por alquiler de casco, independiente de la cantidad de días.
4. En la clase `Main`, crear una lista de vehículos y agregar al menos un Auto y una Moto. Recorrer la lista, calcular el costo de alquiler para **5 días** para cada uno y mostrar los detalles por consola.

## Tiempos y Entrega
- **Tiempo estimado de desarrollo:** 1 Día (Es un proyecto corto y enfocado puramente en diseño de POO).
- **Entregables:** Código Java funcionando bajo un paquete y diagrama de clases analizado.

