# Análisis de Peticiones HTTP — Unidad 1
## Descripción
Repositorio de análisis de peticiones HTTP/HTTPS realizado con
Chrome DevTools y Postman como parte del laboratorio 2 de
Programación Web — Séptimo Semestre.
## Herramientas utilizadas
- Google Chrome + DevTools (panel Network)
- Postman (petición POST con tests)
## Análisis realizados
| # | Tipo | URL | Código |
|---|------|-----|--------|
| 1 [GET HTML](capturas/checkpoint1.png) | 200 OK |
| 2 [GET JSON](capturas/checkpoint2.png)  | /posts/1 | 200 OK |
| 3 [GET JSON](capturas/checkpoint3.png) | /posts/999 | 404 Not Found |
| 3 [GET JSON](capturas/checkpoint3.1.png) | /posts/999 | 404 Not Found |
| 4 [POST JSON](capturas/checkpoint4.png) | /posts | 201 Created |
## Conclusiones
se comprendió el ciclo completo de una petición 
HTTP, identificando cómo los headers, métodos y códigos de estado definen la 
comunicación entre cliente y servidor. Se evidenció la diferencia entre consumir 
una página HTML (GET 200), consultar una API REST (GET 200/404) y crear un 
recurso nuevo (POST 201), cada uno con sus propias características de respuesta. 
El uso de herramientas como Chrome DevTools y Postman resultan útiles para verificar cómo funcionan realmente.