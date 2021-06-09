# Programing

### Fundamentos
Primera linea de código.

```javascript

alert("Mi nombre es Freddy");

var nombre = "Freddy";

alert("Mi nombre es " + nombre);

nombre = "Juana la alpaca";

nombre = prompt("Cual es tu nombre?");

```

### Qué es HTML .html ?
Archivo sobre el que nosotros trabajamos, es el lenguaje en el que se define la información, el contenido del documento. (Estruturar la informacion).
Lenguaje de Marcado de hipertexto

### Qué es CSS .css ?
En el tenemos nuestro diseño. (Diseño),
Lenguaje de estilos en cascada


### Qué es Javascript .js ?
Lenguaje en el que se hace interactivo en el que programamos.(Interactividad)

### Javascript != Java
No son los mismo, java es un lenguaje de programación para servidores, pensado tambien para aplicaciones de escritorio, popular en bancos, tambien se crean aplicaciones para android.

### Primeros pasos en el navegador con alert

```javascript

alert('Hola mamá estoy programando');

var x = 1;
var y = 2;
var z = x + y ;

alert("El valor de z es: " + z);

```

### Html, Css y Javascript de verdad
Se integro los tres en un archivo.
```html
<html>
    <head>
        <title>Mi Primer Archivo Html</title>
        <style>
            body{
                background-color: darkcyan;
                color: white;
                font-family: Arial, Helvetica, sans-serif;
            }

            strong{
                background-color: thistle;
            }
        </style>
    </head>
    <body>
        <p>Hola <strong>Mamá ya casi</strong> Aprendo</p>
        <p>Este es otro parrafo</p>
        <script type="text/javascript">
            var x = 1;
            var y = 2;
            var z = x + y
            document.write("mensaje especial");
            document.write("El valor de z es: " + z);
        </script>
    </body>

</html>
```
