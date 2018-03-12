# TALLER ( PRIMER PARCIAL)
### ARQUITECTURA DE COMPUTADORES
#### 2018
###### Jornada Especial.
1. ¿Que es una arquitectura de computadores?

2. Nombre las generaciones de los computadores y sus características más relevantes.

3. Segun Flynn ¿ Cuál es la clasificación de las arquitecturas?

4. Nombre las clases de aplicaciones de cómputo.

5. Muestre la clasificación de la jerarquía de un equipo de cómputo.

6. ¿Qué es un compilador?

7. ¿ Defina qué es una instrucción?

8. ¿Cuales son los principios básicos de diseño de hardware de una arquitectura de cómputo, escriba una definición de cada uno?

9. ¿Qué es SPARCV8?

10. ¿Cuáles son las categorías de instrucciones de la arquitectura SPARCV8?

11. ¿Que tipos de registros se encuentran en SPARC V8?

12. ¿ Cuál es el número mínimo y máximo de registros que se puede implementar en la arquitectura SPARCV8?

13. ¿ Cuáles son las instrucciones de acceso a memoria de SPARCV8? de un ejemplo de cada uno.

14. Represente los siguientes números en complemento a 2.
```
	a.5
	b.12890
	c.56900
	d.11
	e.140
```
15. Explique las instrucciones aritmético lógicas y su sintaxis en lenguaje ensamblador.

16. Explique cada uno de los campos de los 3 formatos de la arquitectura SPARC V8.

17. ¿Qué diferencia hay entre el campo **op, op2 y op3**?

18. ¿Qué es **PSR** ?, explique cada uno de sus campos.

19. ¿ Qué es **ICC** y **CWP**?

20. ¿Qué es una instrucción sintética, de dos ejemplos?

21. ¿Qué significa el campo **a** para una instrucción BRANCH?.

22. ¿Para qué la instrucción **CALL** utiliza el registro %O7?.

23. Convertir el siguiente programa en lenguaje de máquina a lenguaje ensamblador y luego a lenguaje de alto nivel:
```
10100000000100000010000000000101
10100010000100000011111111111010
10010000000001000100000000010000
```
24.Solucione el siguiente programas en lenguaje ensamblador, lenguaje de máquina y hexadecimal, además coloque su dirección de memoria.
```c
int main(){
	int i = 5; 
	int b = -4;
	int c[100];
	int d[20];
	c[5] = i + 2;
	d[4] = b + 3;
	return c[5] + d[4] -i
}
```

25. Convierta el siguiente código a lenguaje ensamblador, máquina **SPARC V8** y hexadecimal.
a.
 ```c
 int main(){
 int a = 8;
 int b = -14800;
 int c = 33; 
 if((a+b)<=b*16){
 	c=a+(b*2);
	}
else{
	return b-78;
}
	return a+c;
}
 ```

b.
 ```c
int main(){
	int a = 8;
	int b = -10;
	if(a!=b){
		return c/16;
	}
	else{
		return b*32;
	}
}
```
c.

 ```c
int main(){
	int a = -21180;
}
```

26. Convierta el siguiente código a lenguaje ensamblador, máquina **SPARC V8** y hexadecimal.
 ```c
int test(int x, int y, int w){
	int z;
	z = x - y + w*4;
	return z + 2;
}

int main(){
	int a = 4, b = 2, c = -15600;
	int x = test(a,b,c);
	return x + 45;
}
 ```

27. Implemente la función **Pot** en lenguaje de alto nivel,lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que realice la potencia de dos números enteros sin signo realizando llamados a la función multiplicacion hecha en clase.

28. Implemente una función **Fact** en lenguaje de alto nivel, lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que calcule el factorial de un número entero sin signo.

