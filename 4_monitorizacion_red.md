# Monitorización de la Red
La monitorización de la red es importante para verificar la conectividad, el tráfico y las conexiones activas.

## Comando `tcpdump`
`tcpdump` captura y analiza el tráfico de red.

- **-i <interfaz>**: Especifica la interfaz de red.
- **port <número>**: Filtra el tráfico por puerto.

### Ejemplo de uso y salida
    sudo tcpdump -i eth0
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/tcpdump.png)

## Conclusión
`tcpdump` muestra el tráfico en la interfaz de red `eth0`, lo que permite analizar las conexiones activas.



## Comando `tcptrack`
`tcptrack` muestra las conexiones TCP activas en tiempo real.

### Ejemplo de uso y salida
    sudo tcptrack -i eth0
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/tcptrack.png)

## Conclusión
`tcptrack` muestra las conexiones TCP activas, las direcciones IP de origen y destino, y la cantidad de datos transferidos.



## Comando `iptraf-ng`
`iptraf-ng` proporciona estadísticas detalladas sobre el tráfico de red en tiempo real.

### Ejemplo de uso y salida
    sudo iptraf-ng
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/iptraf-ng.png)

## Conclusión
`iptraf-ng permite monitorear el tráfico de red en tiempo real, mostrando detalles como conexiones activas y estadísticas de tráfico.



## Comando `netstat`
`netstat` muestra las conexiones de red, puertos abiertos y estadísticas de red.

- -a: Muestra todas las conexiones y puertos.
- -n: Muestra las direcciones y puertos en formato numérico.

### Ejemplo de uso y salida
    netstat -a
![](https://github.com/xDaMoDzZ/MONITORIZACION/blob/master/img/netstat.png)

## Conclusión
`netstat -a` muestra todas las conexiones activas y los puertos abiertos en el sistema.
