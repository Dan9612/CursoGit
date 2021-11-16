# Encabezados
# Titulo H1
## Titulo H2
### Titulo H3
#### Titulo H4
##### Titulo H5
###### Titulo H6

# Underlines

Underline 1
-----------
Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato unico.
- Aqui podemos usar formato *italico*, **bold** y ~~tachado~~.


# Listas
1. un item de lista ordenada
2. un item de lista ordenada
3. un item de lista ordenada

- un item de lista desordenada.
- un item de lista desordenada.
- un item de lista desordenada.

# Links

- <a href="https://www.google.com">Google Html</a>
- [Google Markdown](https://www.google.com)
- [Link Index](index.html)

# Imagenes

![Logo Github](https://saeplus.com/images/imgpsh_fullsize.png)

# Code Snippets

#### Codigo en JSON
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

#### Codigo en Javascript
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
| Daniel | Villarroel | 26419880 |
| Mariana | Calderón | 24313389 |

# Citas


Esto es un texto referente a una cita que colocaremos debajo:
> Esto es una cita.

Este texto no se relaciona con la cita anterior:
> Esta es otra cita.

# Lineas Divisoras

Este texto esta dividido por guiones.

---
Este texto esta dividido por asteriscos.

***

Este texto esta dividido por guiones bajos.

___
