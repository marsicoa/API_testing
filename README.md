# API_testing

## Testeamos nuestra API

    Para correr el server en el puerto 8080 -> nodemon ./src/server.js
    Para correr el server en modo testing -> npm run server (corre el server en modo testing en el puerto 8008)

Testing de controllers mediante **Jest**
Generacion de requests mediante **axios** 

```console
test
└── controllers
    ├── other.test.js
    └── product.test.js
```

Comandos para testing: _(el servidor debe estar corriendo usando **npm run server**)_

### `npm run test`

Resultados por consola


### `npm run testReport`

Guarda los resultados en **_testresults_** generando un archivo txt