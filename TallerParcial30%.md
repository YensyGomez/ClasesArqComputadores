# TALLER ( PRIMER PARCIAL)
### ARQUITECTURA DE COMPUTADORES
#### 2018
###### Jornada Especial.
1.¿Que es una arquitectura de computador?
2.Nombre las generaciones de los computadores y sus caracteristicas relevantes.
3.Segun Flynn ¿ Cual es la clasificación de las arquitecturas según las instrucciones?
4.Nombre clases de aplicaciones de computo.
5.Muestre la clasificacion de la jerarquia de un equipo de computo.
6.¿Que es un compilador?
7.¿ Defina que es una instrucción?
8.¿Cuales son los principios básicos de diseño de hardware de una arquitectura de computo, defina cada uno?
9.¿Que es SPARC V8?
10.¿Cuales son las categorias de intrucciones de la arquitectura SPARC V8?
11.¿Que tipos de registros se encuentran en SPARC V8?
12.¿ Cual es el número min y max que se puede implementar en la arquitectura SPARV8.
13. ¿ Cuales son las instrucciones de memoria de SPARC V8? de un ejemplo de cada uno.
14.Represente los siguientes números en complemento a 2.
```
	a.5
	b.12890
	c.56900
	d.11
	e.140
```
15.Explique las instrucciones aritmetico lógicas y su sintaxis en lenguaje ensamblador.
16.Explique cada uno de los campos de los 3 formatos de la arquitectura SPARC V8.
17.¿Que diferencia hay entre el campo op, op2 y op3?
18.¿Que es PSR ?, explique cada uno de sus campos.
19.¿ Que es ICC y CWP?
20.¿Que es una instruccion sintetica, de dos ejemplos?
21.¿Que significa el campo a para una instrucción BRANCH?.
22.¿Para que la instrucción CALL utiliza el registro %O7?.
23. convertir el programa en lenguaje de máquina a lenguaje ensamblador y luego a lenguaje de alto nivel el siguiente programa:
```
10100000000100000010000000000101
10100010000100000011111111111010
10010000000001000100000000010000
```
24.Solucione el siguientes programas en lenguaje ensamblador, lenguaje de máquina y hexadecimal, ademas coloque su dirección de memoria.
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

27. Implemente la función **Pot** en lenguaje de alto nivel,lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que realice la potencia de dos números enteros sin signo realizando llamados a la función desarrollada en el punto 9.
28. Implemente una función **Fact** en lenguaje de alto nivel, lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que calcule el factorial de un número entero sin signo.

