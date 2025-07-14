# Net_practice

Para este proyecto, es importante tener en cuenta de parte teórica varios puntos:
- Que es una direccion IP?
- Como es el formato IPV4?
- Cual es el ID de la red y cual es el ID del host?
- Clases de IP.
- Diferencia de una IP pública y una privada.
- Que es un mascara de red?
- Que es un mascara de subred?
- Tener muy en cuenta lo de los rangos(Básicamente te dice cuantos hosts puedes tener conectados en una subred de tu propia red).
- Saber que siempre reservamos dos host: DEFAULT y BROADCAST.
- No es necesario, pero estaría bien que supieras que es el broadcast.
- Que es la puerta de enlace predeterminada (Gateway).
- Que son las rutas estáticas?
- Que es NAT?
- MASKS o CIDR.
- Por que dividir una red?
- Que son las interfaces?
- Aprender conversion de numeros decimales a binarios y de binarios a decimales.

Este último punto yo lo aprendí pero no lo aplique, yo lo hice de otra manera y aqui te dejaré las formulas que yo usé:

32 es el numero de bytes permitidos en una parte de las partes del ip.
N es el numero que te dan tipo /26, /18...

| 32 - N = R | 2^R = Total de hosts |
|------------|----------------------|

Ya con el Total de host tienes el rango con el que puedes trabajar, ahora si quieres saber como es la mascara correcta así:

H = Total de hosts.

| xxx.xxx.xxx.(256 - H) |
|-----------------------|

