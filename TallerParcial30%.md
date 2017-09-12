# TALLER ( PRIMER PARCIAL)
### ARQUITECTURA DE COMPUTADORES
#### 2017
###### Porcentaje 30%


1. Describa la Taxonomía de Flynn.
2. Diga cuales son los 4 principios de diseño.
3. Explique los tres formatos que se usan en la arquitectura SPARC V8, y que instrucciones usan los formatos correspondientes a la arquitectura **SPARC V8** 
4. Explique cómo inicializar un valor grande, que ocupe más de 13 bits, en la arquitectura **SPARC V8**.
5. Como puedo reescribir la instrucción **(OR y SUBcc)** cuando inicializo y  comparó 2 registros.

6. Implementa en lenguaje ensamblador y lenguaje de máquina el siguiente programa.
7. ¿Qué instrucciones utilizan el delay slot antes de saltar ?
8. ¿Qué significa el bit **a**, en el formato 2 de las instrucciones **BRANCH**?
9. ¿Por que la instrucción **CALL** utilizar el registro %o7 ---> registro 15.
10. Convierta el siguiente código a lenguaje ensamblador, máquina **SPARC V8** y hexadecimal.
a.
 ```c
 int main(){
 int a = 8;
 int b = -16800;
 int c = 33; 
 if((a+b)<=b*32){
 	c=a+(b*2);
	}
else{
	return b;
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
		return c/8;
}
else{
	return b;
}
}
```
c.
 ```c
int main(){
	int a = -21180;
}
```

11. Convierta el siguiente código a lenguaje ensamblador, máquina **SPARC V8** y hexadecimal.
 ```c
int test(int a, int b, int c){
	int z;
	z = a - b + c*4;
	return z + 2;
}

int main(){
	int p = 4, y = 2, c = -128;
	int x = test(p,y,c);
	return x + 45;
}
 ```
12. Implemente una función **Mul** en lenguaje de alto nivel, lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que realice la multiplicación de dos enteros sin signo usando solo sumas.
13. Implemente la función **Pot** en lenguaje de alto nivel,lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que realice la potencia de dos números enteros sin signo realizando llamados a la función desarrollada en el punto 9.
14. Implemente una función **Fact** en lenguaje de alto nivel, lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que calcule el factorial de un número entero sin signo.
15. Implemente una función **Div** en lenguaje de alto nivel, lenguaje ensamblador **SPARC V8** y lenguaje de máquina SPARC V8 que calcule la division de un número entero sin signo.
