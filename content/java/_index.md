+++
date = '2024-12-10T21:34:09+01:00'
draft = false
title = 'Sección Técnica: Java'
+++


###### En esta sección voy a explicar un par de conceptos sobre Java:


Java es el primer lenguaje de programación que aprendí y el que maás he utilizado, es un lenguaje orientado a objetos, lo que lo hace muy poderoso y estructurado.

###### Algunos ejemplos de código son los siguientes:

#### Estructura Básica:

Un programa en Java se compone de clases y métodos. El punto de entrada principal es el método main.

```
public class MiPrimeraClase {
    public static void main(String[] args) {
        System.out.println("¡Hola, mundo!");
    }
}
```
- ``` public class MiPrimeraClase ```:  Declara una clase llamada *MiPrimeraClase*.
- ```public static void main(String[] args) ```: El método principal donde inicia la ejecución.
- ``` System.out.println("¡Hola, mundo!"); ```:  Imprime texto en la consola.


#### Declaración de variables:

Java es fuertemente tipado, lo que significa que cada variable debe tener un tipo definido.

```
int numero = 10;          // Entero
double decimal = 5.5;     // Número con decimales
char letra = 'A';         // Carácter
boolean esVerdad = true;  // Booleano (verdadero/falso)
String texto = "Hola";    // Cadena de texto

```

#### Condicionales:

Las estructuras condicionales se utilizan para tomar decisiones.

```
int edad = 18;
if (edad >= 18) {
    System.out.println("Eres mayor de edad.");
} else {
    System.out.println("Eres menor de edad.");
}

```

#### Bucles:

Se utilizan para repetir bloques de código.

- **Bucle** ```for```:
```
for (int i = 0; i < 5; i++) {
    System.out.println("Iteración: " + i);
}

```

- **Bucle** ```while```:
```
int contador = 0;
while (contador < 5) {
    System.out.println("Contador: " + contador);
    contador++;
}


```

#### Clases y Objetos:

En Java, los programas se organizan en clases y se pueden crear objetos para utilizarlas.

```
public class Persona {
    String nombre;

    public Persona(String nombre) { // Constructor
        this.nombre = nombre;
    }

    public void saludar() {
        System.out.println("Hola, mi nombre es " + nombre);
    }

    public static void main(String[] args) {
        Persona p = new Persona("Carlos");
        p.saludar();
    }
}
```
**Resultado:**
```
Hola, mi nombre es Carlos

```