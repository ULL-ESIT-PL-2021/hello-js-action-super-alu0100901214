# hello-js-action-super

## Introducción

La práctica consiste en crear nuestra propia acción con una prueba sencilla que nos imprime un "Hello World!" o un "Hello (y un nombre que le pasemos)"

## Archivo metadata

Lo primero que crearemos sera un archivo .yml que ejecuta la acción, en este describimos los input y los output:

### Input

El input de nuestra acción sera el nombre de la persona a la que queremos saludar:

```
inputs:
  who-to-greet:  # id of input
    description: 'Who to greet'
    required: true
    default: 'World'
```

Dentro de este apartado tenemos:
* El id del imput 'who-to-greet'
* Una descripción
* En required le indicamos se es necesario el parámetro
* Y en caso de que no se proporcione una entrada tenemos como por defecto 'World'


