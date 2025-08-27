# Ejemplo de Listas HTML para Recetas
#### Paula Andrea Viviescas Jaimes

Este proyecto es una demostración simple de cómo utilizar listas ordenadas (`<ol>`) y desordenadas (`<ul>`) en HTML para estructurar contenido, en este caso, dos recetas de cocina: un pastel de chocolate y una ensalada de frutas.

## Características Demostradas

El archivo `index.html` muestra varios conceptos clave sobre las listas en HTML:

### Listas Ordenadas (`<ol>`)
- **Numeración por defecto:** Se usa para los pasos principales de las recetas.
- **Tipos de numeración:** Se utiliza el atributo `type` para cambiar el estilo de los marcadores:
    - `type="I"`: Números romanos en mayúsculas.
    - `type="a"`: Letras en minúsculas.
    - `type="A"`: Letras en mayúsculas.
    - `type="i"`: Números romanos en minúsculas.
- **Inicio de lista personalizado:** El atributo `start` se usa para que una lista comience en un número diferente a 1 (ej. `start="5"`).
- **Orden inverso:** El atributo `reversed` se emplea para mostrar una lista en orden descendente, como en una cuenta regresiva.

### Listas Desordenadas (`<ul>`)
- Se utilizan para listar ingredientes donde el orden no es crítico.
- Se estilizan con CSS para cambiar las viñetas a cuadrados (`list-style-type: square`).

### Anidación de Listas
- Se muestra cómo anidar listas dentro de otras para crear sub-pasos o sub-listas de ingredientes, creando una jerarquía clara.

### Estilización con CSS
- Se incluye una etiqueta `<style>` en el `<head>` para aplicar estilos básicos a las listas a través de clases (`.main-steps`, `.sub-steps`, `.ul-steps`). Esto demuestra cómo se puede personalizar la apariencia de las listas.

## ¿Cómo ver el proyecto?

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` en cualquier navegador web moderno (como Google Chrome, Firefox, o Microsoft Edge).

No se requiere ninguna instalación ni servidor.

## Estructura del Proyecto

El proyecto consta de:

```
.
└── index.html
└── README.md
```
