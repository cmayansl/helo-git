# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline

Underline 1 equivale a la cabecera 2
-----------
Underline 2 equivale a la cabecera 1
===========

# Formatos de enfasis    
- formato *itálica* primero forma
- formato  _itálica_ segunda forma
- formato **bold o strong** primero forma
- formato  __bold o strong__ segunda forma
- formato ~~tachado~~, formato nornmal

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- [Esto es un limk](http://www.google.es)

# Imagenes
![Logo github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets - highlight.js 

Código JSON
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
Código en Javascript
``` Javascript
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
| Pedro  | Perez    | 33444     |
| Javier | Sanchez  | 34566     |

# Citas
Estos es un  texto referente a una cita que hay debajo.
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita

