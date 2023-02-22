# Desafío 21

## Testeamos nuestra API

Se agregó testing de algunos controllers utilizando **Jest**, se generaron las Requests con **axios**.

```console
test
└── controllers
    ├── other.test.js
    └── product.test.js
```

Para correr los tests se puede ejecutar los siguientes comandos _(debe estár levantado el servidor)_

### `npm run test`

Se mostrarán por terminal los resultados.


### `npm run testReport`

Se mostrarán los resultados por terminal y además se guardarán en un archivo en la carpeta **_testresults_** , cada archivo está identificado con la fecha en que se corrió.
