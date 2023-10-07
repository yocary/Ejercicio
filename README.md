## Configuración IDE recomendada

-  [ Código VS ] ( https://code.visualstudio.com/ ) + [ Volar ] ( https://marketplace.visualstudio.com/items?itemName=Vue.volar ) (y deshabilitar Vetur) + [ Complemento TypeScript Vue (Volar) ] ( https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin ) .
# Levantado a nivel de desarrollo
` npm ejecutar dev`

    - ejes: 1.5.1
    - vista: 3.3.4
    - nodo > 16
    - viento de cola

# acoplador

Construcción de la imagen de Docker, nombre de la imagen: dockerize-vuejs-app
` docker build -t dockerize-vuejs-app. `

Para correr la imagen
` docker run -it -p 8080:8080 --rm --name dockerize-vuejs-app-1 dockerize-vuejs-app ` 

- ejecución de ventana acoplable: ejecuta un nuevo contenedor
    - -it : abrir una sesión interactiva
    - -p : indica que puerto será expuesto del contenedor hacia la maquina local
    - --rm : borrar el contenedor después de que lo detengamos (para ahorrar espacio)
    - --name : nombre que se le dará al contenedor
    - imagen: imagen (dockerize-vuejs-app) que se va a construir en el contenedor (dockerize-vuejs-app-1)
-docker run: ejecuta un nuevo contenedor
    - -it: abrir una sesión interactiva
    - -p: exponer los puertos del contenedor
