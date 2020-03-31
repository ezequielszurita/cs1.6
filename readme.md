Buenas Amigos, estoy teniendo problemas con un servicio de counter strike

1) Utilizo el repositorio https://github.com/JimTouz/counter-strike-docker de base
2) Este es el docker file https://github.com/JimTouz/counter-strike-docker/blob/master/Dockerfile
3) Creo un archivo docker-compose (adjunto file en repo)
4) El servicio inicia de manera correcta pero entro desde un cliente y no aparece disponible. (Adjunto LOG del contenedor activo)
5) Probe abriendo los puertos tanto en el contenedor como en el servidor, pero no funciona// cuando hago un nmap dice que los puertos  443, 26900, 27015 y 27020 no estan abiertos
6) probe cambiando la configuracion de red del contenedor con un macvlan, pero no funciona.


