---
marp: true
author: Anvil
size: 4:3
theme: gaia
---
# Markdown ![Logo de Markdown height:50px](img/icon_md.png)

Es un lenguaje de marcado que permite añadir cierto formato al texto plano y se popularizo por su sencillez.<br>
![Creador de Md height:300px](img/john_gruber.jpg)

---
# Encabezados
Md ofrece una forma de jerarquizar nuestros encabezados mediante el uso de `#` que preceden al texto y dependiendo de la cantidad de estos el formato de la letra cambia.
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3

---
# Tablas
Con el uso de md podemos maquetar tablas separando los valores de cada columna con `|` y cada fila con un salto de renglón.
| Nombre | Edad | Correo |
| --- | --- | --- |
| Anvil | 39 | anvil@sap.com |
| Leo | 22 | leeeooo@gt.com |
| Paul | 17 | luap@eee.com |
| Mell | 25 | llem@et.com |

---
# Código.
Dentro de Md se trabaja con dos tipos de bloques que son
#### En linea
`let variable;`
#### En bloque
```js
function gcd(a,b){
    if(b==0) return a;
    return gcd(b,a%b);
}
```

---
# Listas
##### Listas ordenadas
1. Primavera
1. Verano
1. ...
##### Listas con viñetas
- Carro
- Casa
- ...

---
# Listas.
Podemos tener sublistas con ayuda de la indentación
- Compra de ingredientes
   - Jitomate
   - Cebolla
     - Cebolla morada
   - Chile
   - ...

---
# Imágenes
La estructura general para insertar imágenes es:
`![<Descripción breve de la imagen>](<path>)`
![Imagen remota width:400px](https://i.pinimg.com/originals/69/65/72/696572d4fb900aecce7cefb717fc5290.png)

---
# Texto
Podemos hacer que ciertas palabras estén en itálica y negritas asi como tachado.

**Texto en negritas**

*Texto en itálica*

~~Texto tachado~~

**_Combinación de dos_**

---
# Links
En Md tenemos un forma de introducir links. La estructura o sintaxis es:
`[<texto del enlace>](url)`
- [YouTube](https://www.youtube.com)
- [Spotify](https://open.spotify.com/)
- [Facebook](https://www.facebook.com)
- [Twitter](https://twitter.com)