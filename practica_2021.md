# Práctica FaaS

## Enunciado

Crear una función en Azure Functions que responda a eventos **http**. Esta función se programará en Python y lo que hará es recoger un parámetro de entrada (mediante _Query String_) con el número de tareas a crear automáticamente.

Por ejemplo, si en el _query string_ indico el número 6, la respuesta de función podría ser algo como esto

```json
{
  "error": 0,
  "tasks": [
    {
      "name": "Tarea 0",
      "completed": false
    },
    {
      "name": "Tarea 1",
      "completed": true
    }
  ]
}
```

## Extras
1. Modificar nuestra aplicación para que tenga un botón que llame a esta función y así generar tareas _"dummy"_.
2. ¿Te animas a hacerlo en Java?
3. Inventa una función extra

## Entregables

1. Entregar en un fichero comprimido que contenga:
    * El código de la función.
    * Un documento Word que contenga:
        * la url de tu función y cómo realizar la llamada para poder probarla.
        * En caso de haber hecho la integración en la aplicación web, explicación de los cambios que has realizado y pantallazos del resultado final.

> **NOTA:** El documento Word tendrá que nombrarse de la siguiente manera NombreApellido1Apellido2.docx

## Evaluación

|||
|------|-------:|
| Crear función | 60% |
| Modificación de la web | +15% |
| Función en Java | +20% |
| Función extra| +5% |