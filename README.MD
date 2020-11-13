# Version de curso
Version actual v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
------------

Underline 2
============
# Formatos de Emphasis:
- letra *italica* Forma 1.
- letra _italica_ Forma 2.
- formato __bold o strong__ Forma1.
- formato **bold o strong** Forma2.
- formato ~~tachado~~.(altGr + 4) Forma1.Se usa para algo deprecated
- Aqui podemos usar ~~__*italica*__~~ los tres formatos al mismo tiempo.

# Listas:
1. item1 ordenado (ol)
2. item2 ordenado (ol)
3. item3 ordenado (ol)

- item desordenado (ul)
- item desordenado (ul)
- item desordenado (ul)

# Links
- <a href="http://www.google.com">Link html</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)
- [Link a Cabeceras](#Cabeceras)

# Imagenes
![Logo github](https://i.pinimg.com/474x/e6/f8/db/e6f8db60f6b1962fde9a88545fad8062.jpg)

# Code Snippets
- (https://highlightjs.org/)
- Se hace con las comillas invertidas x3 al inicio y al final
- Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

- Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | Documento1 |
| Alberto | Valencia | Documento23 |


# Citas
Esto es un texto referente a una cita que pondremos debajo, para poder escribir debajo hay que dejar una line en blanco para que no se junte con la cita
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior
>Esto es otra cita.

# Lineas divisorias
Esto es un texto que sera dividido por guiones.

---
Esto es otro texto dividido dividido por asteriscos

***

Esto es otro texto dividido dividido por asteriscos

---


# Saltos de linea
Esto es el parrafo 1.

Esto es el parrafo 2.

Esto es el parrafo 3.

Para hacer saltos de linea tenemos que meter doble enter para que lo reconozca.
