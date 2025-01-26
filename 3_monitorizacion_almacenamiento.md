# Monitorización del Almacenamiento

La monitorización del almacenamiento es crucial para garantizar que el sistema tenga suficiente espacio libre y para detectar posibles problemas de rendimiento relacionados con el disco.

## Comando `free`

El comando `free` muestra el uso de la memoria RAM y swap.

- **-h**: Muestra los valores en un formato legible (KB, MB, GB).
- **-t**: Muestra la memoria total (RAM + swap).
- **-s [segundos]**: Actualiza la salida cada cierto número de segundos.

### Ejemplo de uso y salida
    free -h
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/freeH.png)

## Conclusión
La salida muestra la memoria total, utilizada, libre y el uso del swap en un formato fácil de leer.



## Comando `df`
El comando `df` muestra información sobre el uso de los sistemas de archivos.

- -h: Muestra los valores en un formato legible.
- -T: Muestra el tipo de sistema de archivos.
- -x [tipo]: Excluye el tipo de sistema de archivos especificado.

### Ejemplo de uso y salida
    df -h
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/dfH.png)

## Conclusión
`df -h` proporciona una visión general del uso del disco en todos los sistemas de archivos montados.



## Comando `du`
El comando `du` calcula el espacio utilizado por archivos y directorios.

- -h: Muestra los valores en un formato legible.
- -s: Muestra solo el total del directorio.
- -d [nivel]: Muestra los subdirectorios hasta el nivel especificado.

### Ejemplo de uso y salida
    du -sh /home/user
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/du.png)

## Conclusión
La salida muestra el espacio total utilizado en el directorio /home/user.
