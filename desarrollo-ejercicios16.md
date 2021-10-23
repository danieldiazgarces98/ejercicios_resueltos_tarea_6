# Tarea #6

## PARTICIPANTE
1. Daniel Diaz Garces .........................

## Ejercicio #16

```javascript
var nombre = prompt("ingrese un nombre");
var nombreotra = prompt("ingrese otro nombre");
var len1 = nombre.length
var len2 = nombreotra.length
var ultima1 = nombre.slice(len1-1,len1);
var ultima2 = nombreotra.slice(len2-1,len2);
if (nombre.charAt() == nombreotra.charAt()  ) {
window.alert("los nombres coinciden en la primera letra");
}
else if (ultima1 == ultima2) {
window.alert("coinciden en la ultima letra");
}
else {
window.alert("los nombres  NO coinciden ni en la primera letra ni en la ultima");
}
```