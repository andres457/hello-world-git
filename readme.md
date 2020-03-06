# version del curso
version actual: v1.2.2

# cabeceras
# Cabecera H1
## cabecera H2
### cabecera H3
#### cabecera H4

# underline
underline1
----------
underline2
==========

# formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** primera forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~.
- podemos hacer *formato italico* pero tambien **bold** y ~~tacahdo~~

# listas
1. esto es un item de lista ordenada
2. esto es un item de lista ordenada
3. esto es un item de lista ordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada

# Links

- <a href="http://google.com ">link html</a>
- [Esto es un link en markdown](http.//www.google.com)
- [Esto es un link al index](index.html)

# iamgenes
![logo github](https://www.google.com/url?sa=i&url=https%3A%2F%2Flogosmarcas.com%2Fgithub-logo%2F&psig=AOvVaw1X9xIP5ECKWnPuS8XxgVm2&ust=1583436113382000&source=images&cd=vfe&ved=0CA0QjhxqFwoTCPiC48TFgegCFQAAAAAdAAAAABAJ))

 # code snippets
 codigo en json
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
codigo en javascript
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

 # tablas
 | Nombre | Apellido | Documento|
 |------- | -------- | -------- |
 | Maxi | Burgos | 3546481
 | thomas | tompson| 324561 | 

 # citas
 Esto es un texto referente a una cita que pondremos debajo:
>Esto es una cita

esto es otro texto
>otra cita

# lineas Divisoras
Esto es un texto q sera dividido por guion medio

---
otro tex dividido por asteriscos

***

este es otro por guiones bajos

___

# saltos de linea
Primer parrafo

segundo parrafo

tercerparrafo
- lista
>>>>>>> Stashed changes
