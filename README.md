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
### Peso en otro planeta
9.8 m/s² es la gravedad de la Tierra
3.7 m/s² es la gravedad de Marte
24.8 m/s² es la gravedad de Jupiter
Mi peso 77kg
pesoMarte = (miPeso * gravedadMarte)/gravedadTierra

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu peso en un lugar donde pesas menos</title>
</head>
<body>
    <h1>Tú peso en otro Planeta</h1>
    <p>En la Tierra pesas distinto que en Marte o Jupiter</p>

    <script type="text/javascript">
        var gravedadTierra = 9.8;
        var gravedadMarte = 3.7;
        var gravedadJupiter = 24.8;
        var peso = 77;

        var pesoFinal;

        pesoFinal = peso * gravedadMarte / gravedadTierra;
        pesoFinal = parseInt(pesoFinal);
         document.write("Peso en otro planeta es: " + pesoFinal);
    </script>
</body>
</html>
```