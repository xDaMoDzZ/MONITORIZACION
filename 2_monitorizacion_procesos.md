# Monitorización de Procesos

La monitorización de procesos es esencial para identificar aplicaciones que consumen muchos recursos y que podrían afectar el rendimiento del servidor.

## Comando `ps`

El comando `ps` se utiliza para obtener una instantánea de los procesos en ejecución en el sistema. A continuación, se describen algunas de las opciones más comunes:

- **ps**: Muestra los procesos actuales del usuario.
- **ps a**: Muestra los procesos de todos los usuarios.
- **ps aux**: Muestra todos los procesos, incluidos los de otros usuarios.
- **ps -C <nombre>**: Muestra procesos con el nombre especificado.

### Ejemplo de uso y salida
    ps aux
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/psAux.png)

## Conclusión
El comando muestra una lista completa de todos los procesos del sistema, incluyendo detalles como el usuario, PID, uso de CPU, memoria y el tiempo de ejecución.



## Comando `top`

El comando `top` proporciona una visualización dinámica y en tiempo real del uso de recursos del sistema. Algunas opciones útiles incluyen:

- top T: Ordena los procesos por tiempo de ejecución.
- top M: Ordena los procesos por uso de memoria.
- top P: Ordena los procesos por uso de CPU.

### Ejemplo de uso y salida
    top M
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/topM.png)

## Conclusión
El comando `top` ordenado por memoria muestra los procesos que más memoria están consumiendo en tiempo real.



## Comando `htop`
`htop` es una versión mejorada de top, con una interfaz más amigable y opciones interactivas, como la posibilidad de eliminar procesos directamente.

- htop -u <usuario>: Filtra los procesos por usuario.
- htop --tree: Muestra los procesos en una estructura de árbol.

### Ejemplo de uso y salida
    htop --tree
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/htopTree.png)

## Conclusión
`htop --tree` presenta los procesos organizados jerárquicamente, lo que facilita la visualización de las relaciones entre procesos padre e hijo.



## Comando `atop`
`atop` ofrece una monitorización avanzada que incluye estadísticas de procesos, CPU, memoria, disco y red.

### Ejemplo de uso y salida
    atop
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/psAux.png)

## Conclusión
`atop` proporciona una vista detallada del sistema, permitiendo ver el uso de los recursos con mayor granularidad, y también permite ver registros históricos.
