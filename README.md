# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- Formato *itálica* de la primera forma.
- Formato _itálica_ de la segunda forma.
- Formato **bold o strong** de la primera forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, formato normal.
- Aqui podemos usar *formato itálico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://cdn.textstudio.com/output/graphic/preview/large/0/6/9/9/9960_a863ac94.webp)

# Code Snippets
Codigo en JSON
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
Codigo en Javascript
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

export $initHighlight;
```