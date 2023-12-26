# TRABAJO FINAL.

## ENLACES.

[VERCEL] ()
[GITHUB] ()

## INSTALACION

```shell
npm install

```

## EJECUCION

```shell
npm run dev
```

## DOCUMENTACION E INSTRUCCIONES.

En esta aplicación sencilla con REACT decidí centrarme en el funcionamiento de un carrito de compras y 
traté de aplicar conceptos básicos y fundamentales tanto de HTML, CSS, JAVASCRIPT y REACT.
La interfaz de usuario muestra una lista de productos que son traidas por una URL que estan disponibles
para la compra.
Al recorrer con el mouse sobre la interfaz y pasar sobre un producto se produce un efecto realizado con 
CSS como para darle mas interactividad a la aplicación.
De forma sencilla cada producto cuenta con su respectiva imágen, su nombre y modelo , su precio y su
botón para que el usuario pueda añadir al carrito de compras los productos que desee.
En la parte superior derecha es donde se muestra el carrito de compras con un iconito de bolsa de compra
y un número que representa la cantidad de productos que el usuario tiene.
Antes que se haya seleccionado algún boton de añadir al carrito, el número de cantidad de productos del
carrito está en 0 y si hacemos click sobre éste aparece un mensaje que muestra que el carrito está vacio.
A medida que uno vaya seleccionando el botón de añadir al carrito, el número de productos del carrito
se va incrementando y si le damos click al iconito se muestran los productos que vayamos seleccionando
con su descripción, precio, cantidad y el precio total. 
Si queremos seleccionar de un producto mas  cantidades podemos
darle otra vez click a añadir al carrito como también podemos dentro del carrito de compras editar
las cantidad de un producto con los botones de + o - que se encuentran al lado de la cantidad del 
producto permitiendo así a los usuarios ajustar la cantidad de productos en el carrito. Si se presiona
el botón de menos sobre un producto la cantidad no baja de cero y su total queda en 0. Además si queremos eliminar el producto del carrito de compras, podemos seleccionar el
iconito de cruz que al posicionarnos cambia su color a rojo. 
Además de poder eliminar los productos por separado del carrito tenemos la opción de vaciar al carrito
junto al botón de confirmar la compra.
Al presionar el botón de confirmar compra se produce una simulación de compra realizada con una alerta realizada
con sweet alert de React y el carrito se vacia.
