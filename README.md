<html>
<head>
</head>

<body>
<script>
//calcular los precios acutualizados segun la antiguedad y el sueldo del sujeto
let sueldo,anti,resultado;

sueldo= parseInt(prompt('ingrese su sueldo', ' '));
anti= parseInt(prompt('ingrese la antiguedad que tiene', ' '));

if (sueldo<500 && anti>=10)
{
resultado= sueldo+ sueldo *0.2;
}

if (sueldo<500 && anti<10)
{
resultado= sueldo+ sueldo *0.05;
}

if (sueldo>=500)
{
resultado= sueldo;
}

document.write(' el sueldo actualizado es de '+ resultado);

</script>
</body>
</html>
