# TravelingWeb v2.0 - Docker Compose

## Descripción

En este proyecto es una versión actualizada de mi proyecto de título en la cuál se incoporó tecnología basada en contenedores mediante el orquestador de Docker Compose. En la cuál para ello, se desplego de la siguiente forma mediante 3 contenedores Docker:

1- Contenedor frontend con React
2- Contenedor con backend mediante archivos PHP
3- Contenedor con base de datos MySQL

De esta forma, se despliega el ambiente completo mediante el comando #docker-compose up 
Este comando orquesta levantar toda el software mediante una arquitectura monolítica y que automáticamente cada capa se puede comunicar entre sí, es por ello, que esta aplicación busca la optimización de búsqueda de pasajes y vuelos con dos interfaces, la interfaz de usuario y la interfaz de administrador, la interfaz de usuario hace la búsqueda de pasajes y vuelos disponibles y por otro lado, el administrador se encarga mediante un CRUD hacer las actualizaciones de los vuelos disponibles.

Este proyecto si bien le falta mayor desarrollo, me ayudó a implementar las bases correspodientes de mis skills sobre una arquitectura basada en contenedores, dónde es perfectamente compatible con Kubernetes y se puede extender a mayores diagramas de arquitectura.

- Carlos Galindo
  
