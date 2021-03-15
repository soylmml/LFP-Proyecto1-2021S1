# [LFP]Proyecto 1 - Archivos de Entrada

Universidad de San Carlos de Guatemala  
Facultad de Ingeniería  
Escuela de Ciencias y Sistemas  
Lenguajes Formales y de Programación  
Primer Semestre 2021

### [menu.lfp](menu.lfp)

```
restaurante='Restaurante LFP'
'Bebidas'  :
[bebida_1;'Bebida #1';11.;'Descripción Bebida 1'    ]
[ bebida_2;'Bebida #2';10.50;    'Descripción Bebida 2']

'Desayunos':
[d1;'Desayuno 1';45.00;'Descripción Desayuno 1']
[d2 ;'Desayuno 2';    40.   ;'Descripción Desayuno 2']
[d3;'Desayuno 3';35;'Descripción Desayuno 3']

'  Postres':
[   pos_001;'Postre 1'   ;25;'Descripción Postre 1']
```

### [orden.lfp](orden.lfp)

```
'Luis Morales', '12345676', 'Guatemala' , 8.5%
2,bebida_1  
2 ,bebida_2
2 ,d1
 2,d3
4,  pos_001
```

----
# Archivos de entrada 2
## Taco Bell

### [Menú](TacoBell/MenuTacoBell.lfp)
### [Orden 1](TacoBell/OrdenTacoBell.lfp)
### [Orden 2](TacoBell/Orden2Tacobell.lfp)

## Con errores

### [Menú](TacoBell/MenuErrores.lfp)

| No.   | Línes     | Columna   | Lexema    | Descricipción |
|:-:    |:-:        | :-:       |:-:        | :-:           |
|1|3|10|"|  Caracter desconocido |                
|2|6|1|@|  Caracter desconocido |                
|3|9|1|(|  Caracter desconocido |                
|4|11|16|>|  Caracter desconocido |                
|5|17|30|1.900.50|  Número inválido |                
|6|23|1|bb-1|  Identificador inválido |                


### [Orden 2](TacoBell/Orden2Errores.lfp)

| No.   | Línes     | Columna   | Lexema    | Descricipción |
|:-:    |:-:        | :-:       |:-:        | :-:           |
|1|2|3|crun-chy|  Identificador Inválido |                
|2|5|11|?|  Caracter desconocido |                         
