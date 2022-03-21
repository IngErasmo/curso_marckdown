<!-- HEADDINGS -->
# Ejemplo de titulo h1
## Ejemplo de titilo h2
### Ejemplo de titulo h3
#### Ejemplo de titulo h4
##### Ejemplo de titulo h5
###### Ejemplo de titulo h6

___
## Ejemplo de formatos del texto
<!-- texto en cursiva -->
This is an *italic* text

This is an **strong** text

<!-- strikethrough -->
Esto es un ~~texto tachado~~

---
## Uso de listas
### Lista desordenada
* apple
    * red apple
    * Yellow apple
        * big Yellow apple
        * small yellow apple
            
* orange
* peach

### Lista ordenada
1. apple
    1. red apple
    2. Yellow apple
        1. big Yellow apple
        2. small yellow apple
2. orange
3. peach

___
## Enlaces de internet
<!-- Enlace sencillo -->
[faztweb.com](http://www.faztweb.com)
<!-- enlace cambiando la previsualizacion de la url por texto personalizado -->
[faztweb.com](http://www.faztweb.com "Custom title" )
___
<!-- citar textos  -->
> esta es una cita 


___
## Ejemplo de codigos
### linea de codigo simple
<!-- Linea de codigo sensilla -->
`console.log('hello world')`

### Linea de codigo multiple, indicando el lenguaje
<!-- Multiples lineas de codigo con el lenguaje -->
<!-- La tilde (`) se saca con 96 -->
```python
for col in encode:
    dummy = pd.get_dummies(df[col], prefix=col)
    df = pd.concat([df,dummy], axis=1)
    del df[col]
```

```htnl
    <h1> Texto h1 de html<h1>
```
___
## Uso de tablas
<!-- tablas -->
<!-- el pipe (|) se saca con 124  -->
| nombre    |cantidad   |precio|
|-----------|:---------:|-----:|
|teclado    |15         |$600  |
|mouse      |10         |$200  |
|monitor    |3          |$1000 |
|laptop     |2          |$50000|

___
## Uso de Imagenes
### imagen de internet
![VSCode logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png "vscode logo desde internet")

### imagen en el equipo
![vscode logo2](vscode_logo.png "vscode logo local")


<!-- REGLAS PROPIAS DE GITHUB MARCKDOWN -->
* [x] Task 1
* [x] Task 2
* [] Task 3
* [] Task 4
* [x] Task 5
