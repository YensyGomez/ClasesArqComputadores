Capitulo 4---> Manual arquictectura sparc v8.

# Registros
El procesador SPARC V8 incluye varios ripos de registros: los de proposito general o registros de datos y resgistro de control y estado. 
- IU(unidad de tipo entero)
- FPU(Unidad de punto flotante)
- CP 
## Registro de estados.
Permiten modificar el comportamiento en un momento determinado.

### Registros de propósito general.
- r(register file soporta entre 40-520 registros)
- f(FPU:Floating Point Unit)
- Co-Procesador


![Registros  en SPARC V8](./images/registros.png "Definición de registros de la arquitectura SPARC V8")


### Registro de control y estado.
- **PSR**(Processor State Register)

![Processor State Register](./images/psr.png "Register")

- **impl**: Implementación
- **version**: Vérsión
- **ICC** : Esta dividido en 4 bits: **n**: Negativo cuando una operación da un número negativo, **Z**: se coloca en 1, cuando el resultado de la operación da cero, **v**: Over Flow se activa cuando el resultado de una operación da más de 32 bits y el bit **c**: Carry, se activa cuando se tiene acarreo.

![Integer condicional code](./images/icc.png "Integer conditional code")

- **reserved**: son un conjunto de bit no definidos dentro de la especificación de la arquitectura para que el diseñador los use de manera libre.
- **EC**(Enable co-processor): Indica si el procesador tiene unidad de co-procesamiento(FPGA,Targeta gráfica, etc)
- **EF**: Es un bit que me indica si la arquitectura tiene unidad de punto flotante.

