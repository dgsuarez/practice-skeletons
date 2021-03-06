# TypeScript

Este proyecto contiene una configuración básica de [TypeScript](https://www.typescriptlang.org/) con [Jest](https://jestjs.io/) como framework de testing. Como herramientas de apoyo, también está instalado [TSLint](https://palantir.github.io/tslint/) y un conjunto de paquetes de apoyo que notificarán sobre posibles [_code smells_](https://en.wikipedia.org/wiki/Code_smell).

## ¿Cómo...?

### Instalar dependencias

Utiliza `npm` para instalar las dependencias de este proyecto desde su propia raíz a través de una interfaz de línea de comandos:

```sh
npm i
```

### Ejecutar la suite de tests

Hay una serie de scripts de `npm` preparados para ejecutar la suite de tests:

```sh
npm run test        # ejecuta la suite completa
npm run test:watch  # ejecución continua de los tests con cambios relacionados
```

### Analizar el código

A través de `npm run lint` podrás obtener un informe del conjunto de _code smells_ identificados por TSLint.
