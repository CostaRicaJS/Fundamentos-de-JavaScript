# Alcance y Contexto [Scope]
Es la jerarquía sobre como accesar las variables, objetos y funciones.

```javascript
const avenida = 'AVE51325';   /* Variable Global */

function miAlcance() {
  const direccion = 'SF91';   /* direccion solo existe dentro de la función */
  console.log(avenida);     // AVE51325
  console.log(direccion);   // SF91
}

miAlcance();

console.log(avenida);       // AVE51325
console.log(direccion);     // direccion is not defined
```