# Generador de Contraseñas Aleatorias
Este proyecto es un generador de contraseñas aleatorias en Python que también encripta 
las contraseñas utilizando la librería `werkzeug`. 
El objetivo es proporcionar contraseñas seguras y encriptadas para su uso en diversas aplicaciones.
## Características
- Genera contraseñas aleatorias de una longitud especificada.
- Utiliza una combinación de letras mayúsculas, minúsculas, números y símbolos.
- Encripta las contraseñas utilizando el algoritmo `scrypt` de `werkzeug`.
## Requisitos Previos
- Python 3.6 o superior
- Librería `werkzeug`

###  Ejemplo de Salida
```
1pZ7Gv]f&^Jm => scrypt:32768:8:1$D3jrW9DyaZkt2CHV$43bfed7e53bbcd1625d65421af96dbc19c52a99417b2500e8d97f756c845546a1fce333cd7867c2919ce69df7335414989ba761c1d8416c68a7daab5c5a8096d
C./=O&}7Fdl* => scrypt:32768:8:1$yrf6BAknvUyVmQFg$2388019fb6f17f907622a2331c01e0cbd144c83a29727a66dced88f142d3a48d1c8ddb08a43ffa1c3b7b52c02989debec4b5b8858f0e07f68e9c85d8fa477d08
...
```
siendo los primeros 12 caracteres la contrasena proporcionada,y luego del scrypt: la contrasena encriptada
## Contribuciones
Las contribuciones son bienvenidas. 
Si deseas contribuir, por favor haz un fork del repositorio, crea una rama con tus cambios y envía un pull request.
