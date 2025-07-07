# Elocuencia

El primer paso en la historia para escapar de la programación telegráfica.

## ¿Qué es el lenguaje telegráfico?

Un lenguaje telegráfico es un lenguaje compuesto de expresiones [elípticas](https://es.wikipedia.org/wiki/Elipsis_(ling%C3%BC%C3%ADstica)), con [símbolos](https://es.wikipedia.org/wiki/Anexo:S%C3%ADmbolos_matem%C3%A1ticos), con [abreviaciones](https://es.wikipedia.org/wiki/Abreviatura), sin [conexiones discursivas](https://es.wikipedia.org/wiki/Conector_(ling%C3%BC%C3%ADstica)), sin [contexto](https://es.wikipedia.org/wiki/Contexto_ling%C3%BC%C3%ADstico), entre otras cosas, que contribuyen a que estas expresiones sean malinterpretadas y, en la mayoría de los casos, indescifrables.

Por ejemplo, observemos la siguiente expresión:

```
Vamos a salir a pasear en familia
```

En un lenguaje telegráfico podría ser:

```
vms psr en fam
```

## Imprimir

```js
_.imprimimos({
    _: "Hola hispanidad"
})
```

```js
_.imprimimos({
    _: [
        "Hola",
        "hispanidad"
    ]
})
```

```js
_.imprimimos({
    _: "Hola hispanidad",
    dejando_un: "rastro"
})
```

## el tipo de ...

```js
// texto
_.el_tipo({
    de: "Hola hispanidad"
})
```

```js
// número
_.el_tipo({
    de: 10
})
```

```js
// lista
_.el_tipo({
        de: [
        "México",
        "España",
        "Argentina"
    ]
})
```

```js
// verdadero
_.el_tipo({
    de: "Hola hispanidad",
    es: "texto"
})
```

```js
// verdadero
_.el_tipo({
    de: 10,
    es: "número"
})
```

```js
// verdadero
_.el_tipo({
    de: [
        "México",
        "España",
        "Argentina"
    ],
    es: "lista"
})
```

```js
// falso
_.el_tipo({
    de: "Hola hispanidad",
    no_es: "texto"
})
```

```js
// falso
_.el_tipo({
    de: 10,
    no_es: "número"
})
```

```js
// falso
_.el_tipo({
    de: [
        "México",
        "España",
        "Argentina"
    ],
    no_es: "lista"
})
```

## el índice de ...

```js
// México, España, Argentina
_.el_índice({
    de: {
        "México" : "es-MX",
        "España": "es-ES",
        "Argentina": "es-AR"
    }
})
```

```js
// 0, 1, 2
_.el_índice({
    de: [
        "México",
        "España",
        "Argentina"
    ]
})
```

## el número de ...

```js
// 3
_.el_número({
    de_países: [
        "México",
        "España",
        "Argentina"
    ]
})
```

```js
// 2
_.el_número({
    de_colores: [
        "rojo",
        "azul"
    ]
})
```

## existe o no existe el ...

También en plural, «existen» o «no existen».

```js
// verdadero
_.existe({
    el: "texto"
})
```

```js
// verdadero
_.no_existe({
    porque_es: nulo
})
```
