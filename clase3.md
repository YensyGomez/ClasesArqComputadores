# Principios de diseño de arquitectura
## Segundo principio de diseño de hardware: Entre más pequeños más rápido.
### Operandos de memoria.

Cuando el procesador necesita utilizar la información que se encuentra en una estructura compleja de datos se hace necesesario el llamado a memoria. Para realizar este tipo de accesos necesitamos utilizar instrucciones conocidas como instrucciones de tranferencias de datos.

En nuestra arquitectura **SPARC V8** tenemos las instrucciones **ld** (LOAD) y **st** (STORE), cada una tiene la capacidad de manejar datos de **32 bits**.

la manera en como se usa las instrucciones de memoria de la arquitectura **SPARC V8** es de la siguiente manera:

- ld[**address**],regrd
- st regrd, [**adress**]

La arquitectura de **SPARC V8** maneja un direccionamiento por **byte**, de esta manera cada posición de memoria almacena **32 bits** o **4 bytes**.


### EJEMPLO.

- A = B + C[9]
Lo primero que debemos hacer es asignarle los registros a las variables, en este caso a **A, B, C**.
Una vez le halla asigando los registros:**A = %l0**,  **B = %l1**, **C = %l2**. Debo usar una intrucción de tranferencia que me carge el dato que esta contenido en C[9]; para ello usa la instrucción **LOAD**.
- ld[%l2+(9*4)],%l3
- add %l1,%l3,%l0
