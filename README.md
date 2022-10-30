# API_testing


### Para correr el server en el puerto 8080:
#### `nodemon ./src/server.js`
    
### Para correr el server en modo testing (puerto 8008):
#### `npm run server`



### Testing de controllers usando **jest** y generacion de requests usando **axios** 

```console
test
└── controllers
    ├── other.test.js
    └── product.test.js
```

## Comandos para testing: 
    /!\ el servidor debe estar corriendo usando `npm run server`

Resultados por consola:
#### `npm run test`

Guarda los resultados en **_testresults_** generando un archivo txt:
#### `npm run testReport`


