# Metodología de la programación

## 1. Introducción a la metodología de la programación I
### El computador y los programas
+ Contenido: Explicación básica de qué es un computador y cómo funcionan los programas.
+ Ejemplo: Describir el proceso de ejecución de un programa simple.
+ Ejercicio: Investigar y presentar las partes principales de un computador.
### Que significa programar
+ Contenido: Definición de programación y su importancia.
+ Ejemplo: Crear un programa simple en Python que imprima “Hola, mundo”.
```python
print("Hola, mundo")
```
+ Ejercicio: Escribir un programa que salude al usuario por su nombre.
### Breve reseña histórica
+ Contenido: Historia de la programación desde los primeros lenguajes hasta Python.
+ Ejemplo: Mencionar hitos importantes como la creación de FORTRAN, C, y Python.
+ Ejercicio: Crear una línea de tiempo con los lenguajes de programación más importantes.
### Características comunes de los programas
+ Contenido: Elementos comunes en todos los programas (entrada, procesamiento, salida).
+ Ejemplo: Programa que suma dos números dados por el usuario.
```python
a = int(input("Introduce el primer número: "))
b = int(input("Introduce el segundo número: "))
print("La suma es:", a + b)
```
+ Ejercicio: Modificar el programa para que también reste, multiplique y divida los números.
### Estructura de un programa
+ Contenido: Partes de un programa (declaraciones, instrucciones, funciones).
+ Ejemplo: Programa con una función que calcula el área de un círculo.
```python
def area_circulo(radio):
    return 3.14159 * radio * radio

print("El área es:", area_circulo(5))
```
+ Ejercicio: Crear una función que calcule el perímetro de un círculo.
### Ciclo de instrucción
+ Contenido: Explicación del ciclo de instrucción de la CPU.
+ Ejemplo: Describir cómo la CPU ejecuta un programa paso a paso.
+ Ejercicio: Dibujar un diagrama del ciclo de instrucción.
## 2. Introducción a la metodología de la programación II
### El ordenador
+ Contenido: Explicación del ciclo de instrucción de la CPU.
+ Ejemplo: Describir cómo la CPU ejecuta un programa paso a paso.
+ Ejercicio: Dibujar un diagrama del ciclo de instrucción.
### El algoritmo (resolución de problemas)
+ Contenido: Definición de algoritmo y su importancia en la programación.
+ Ejemplo: Algoritmo para encontrar el mayor de tres números.
```python
def mayor_de_tres(a, b, c):
    if a > b and a > c:
        return a
    elif b > c:
        return b
    else:
        return c

print("El mayor es:", mayor_de_tres(5, 7, 3))
```
+ Ejercicio: Escribir un algoritmo para ordenar tres números.
### Los datos
+ Contenido: Tipos de datos y su uso en programación.
+ Ejemplo: Variables de tipo entero, flotante, cadena y booleano en Python.
```python
entero = 10
flotante = 10.5
cadena = "Hola"
booleano = True
```
+ Ejercicio: Crear un programa que use diferentes tipos de datos y los imprima.
### Hardware y software
+ Contenido: Diferencias entre hardware y software.
+ Ejemplo: Ejemplos de hardware (CPU, RAM) y software (sistemas operativos, aplicaciones).
+ Ejercicio: Clasificar una lista de elementos en hardware o software.
### Operadores y expresiones
+ Contenido: Tipos de operadores (aritméticos, relacionales, lógicos) y cómo se usan.
+ Ejemplo: Uso de operadores en Python.
```python
a = 10
b = 5
print(a + b)  # Suma
print(a > b)  # Mayor que
print(a and b)  # Operador lógico
```
+ Ejercicio: Escribir expresiones que usen diferentes operadores y evaluar su resultado.
### Técnicas de programación
+ Contenido: Diferentes enfoques y técnicas para resolver problemas de programación.
+ Ejemplo: Programación estructurada vs. programación orientada a objetos.
+ Ejercicio: Comparar y contrastar dos técnicas de programación.
### Fases de un programa
+ Contenido: Etapas del desarrollo de un programa (análisis, diseño, codificación, prueba, mantenimiento).
+ Ejemplo: Describir cada fase con un ejemplo práctico.
+ Ejercicio: Crear un plan de desarrollo para un programa simple.
## 3. Lenguajes de programación y procesos de programación
### Evolución de los lenguajes de programación
+ Contenido: Historia y evolución de los lenguajes de programación.
+ Ejemplo: Comparar lenguajes de bajo nivel (ensamblador) con lenguajes de alto nivel (Python).
+ Ejercicio: Investigar y presentar la evolución de un lenguaje de programación específico.
### Lenguajes de desarrollo en la www
+ Contenido: Lenguajes utilizados en el desarrollo web (HTML, CSS, JavaScript, Python).
+ Ejemplo: Crear una página web simple usando HTML y Python (con Flask).
```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hola, mundo desde Flask!"

if __name__ == '__main__':
    app.run(debug=True)
```
+ Ejercicio: Desarrollar una aplicación web básica que muestre información del usuario.
### Ciclo de vida
+ Contenido: Ciclo de vida del desarrollo de software (planificación, análisis, diseño, implementación, prueba, mantenimiento).
+ Ejemplo: Describir cada fase con ejemplos de proyectos reales.
+ Ejercicio: Crear un diagrama del ciclo de vida de un proyecto de software.
## 4. Principios de la programación
### Introducción
+ Contenido: Conceptos básicos y objetivos de la programación.
+ Ejemplo: Explicar la importancia de la lógica y la resolución de problemas.
+ Ejercicio: Resolver un problema lógico simple usando Python.
### Elementos básicos de programación
+ Contenido: Variables, tipos de datos, operadores, expresiones.
+ Ejemplo: Programa que usa diferentes tipos de datos y operadores.
```python
x = 10
y = 5
print(x + y)  # Suma
print(x > y)  # Comparación
```
+ Ejercicio: Crear un programa que realice operaciones básicas con diferentes tipos de datos.
### Constantes y variables
+ Contenido: Diferencias entre constantes y variables.
+ Ejemplo: Uso de constantes y variables en Python.
```python
PI = 3.14159  # Constante
radio = 5  # Variable
print("El área del círculo es:", PI * radio * radio)
```
+ Ejercicio: Escribir un programa que use constantes y variables para calcular el área y el perímetro de un círculo.
### Metodología para el desarrollo de programas
+ Contenido: Pasos para desarrollar un programa (análisis, diseño, codificación, prueba, mantenimiento).
+ Ejemplo: Describir cada paso con un ejemplo práctico.
+ Ejercicio: Desarrollar un programa siguiendo los pasos de la metodología.
### Estructuras básicas de la programación imperativa
+ Contenido: Secuencia, selección (if, else), iteración (for, while).
+ Ejemplo: Programa que usa estructuras de control básicas.
```python
# Selección
if x > y:
    print("x es mayor que y")
else:
    print("x no es mayor que y")

# Iteración
for i in range(5):
    print(i)
```
+ Ejercicio: Crear un programa que use selección e iteración para resolver un problema.
### Selección e iteración
+ Contenido: Detalle de las estructuras de control de selección e iteración.
+ Ejemplo: Programa que calcula la suma de los primeros n números naturales.
```python
n = 10
suma = 0
for i in range(1, n + 1):
    suma += i
print("La suma es:", suma)
```
+ Ejercicio: Escribir un programa que encuentre el factorial de un número dado.
## 5. Introducción al paradigma orientado a objetos (POO)
+ Contenido: Conceptos básicos de POO (clases, objetos, herencia, polimorfismo).
+ Ejemplo: Crear una clase simple en Python.
```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print(f"Hola, mi nombre es {self.nombre} y tengo {self.edad} años.")

persona1 = Persona("Juan", 30)
persona1.saludar()
```
+ Ejercicio: Crear una clase Coche con atributos y métodos, y crear instancias de la clase.
## 6. Entorno de desarrollo (IDE) acorde al paradigma orientado a objetos
+ Contenido: Introducción a los entornos de desarrollo integrados (IDE) y su uso en POO.
+ Ejemplo: Configuración y uso de PyCharm para desarrollar programas en Python.
+ Ejercicio: Instalar PyCharm y crear un proyecto simple que use clases y objetos.
## 7. Clases y objetos
+ Contenido: Definición y uso de clases y objetos en Python.
+ Ejemplo: Crear una clase Animal con atributos y métodos.
```python
class Animal:
    def __init__(self, nombre, especie):
        self.nombre = nombre
        self.especie = especie

    def describir(self):
        print(f"Este es un {self.especie} llamado {self.nombre}.")

animal1 = Animal("Rex", "perro")
animal1.describir()
```
+ Ejercicio: Crear una clase Libro con atributos como título, autor y año, y métodos para mostrar la información del libro.
## 8. Sintaxis
+ Contenido: Reglas de sintaxis en Python.
+ Ejemplo: Mostrar ejemplos de sintaxis correcta e incorrecta.
```python
# Sintaxis correcta
a = 10
if a > 5:
    print("a es mayor que 5")

# Sintaxis incorrecta
a = 10
if a > 5
print("a es mayor que 5")
```
+ Ejercicio: Corregir errores de sintaxis en un conjunto de ejemplos proporcionados.
## 9. Tipos de datos y operadores
+ Contenido: Tipos de datos en Python (enteros, flotantes, cadenas, listas, diccionarios) y operadores.
+ Ejemplo: Uso de diferentes tipos de datos y operadores.
```python
entero = 10
flotante = 10.5
cadena = "Hola"
lista = [1, 2, 3]
diccionario = {"clave": "valor"}

print(entero + flotante)  # Operador aritmético
print(cadena * 3)  # Operador de repetición
```
+ Ejercicio: Crear un programa que use diferentes tipos de datos y operadores para realizar cálculos y manipular datos.
## 10. Estructuras de control
+ Contenido: Estructuras de control de flujo (if, for, while).
+ Ejemplo: Uso de estructuras de control en Python.
```python
# Estructura de control if
edad = 18
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")

# Estructura de control for
for i in range(5):
    print(i)

# Estructura de control while
contador = 0
while contador < 5:
    print(contador)
    contador += 1
```
+ Ejercicio: Escribir un programa que use estructuras de control para resolver un problema específico, como encontrar los números pares en un rango dado.
## 11. Estilos y documentación
+ Contenido: Buenas prácticas de programación, estilo de código y documentación.
+ Ejemplo: Uso de comentarios y docstrings en Python.
```python
def suma(a, b):
    """
    Esta función suma dos números y devuelve el resultado.
    :param a: Primer número
    :param b: Segundo número
    :return: Suma de a y b
    """
    return a + b

# Comentario de una línea
resultado = suma(5, 3)  # Suma de 5 y 3
print(resultado)
```
+ Ejercicio: Documentar un programa existente usando comentarios y docstrings.
## 12. Excepciones
+ Contenido: Manejo de excepciones en Python.
+ Ejemplo: Uso de try, except, finally.
```python
try:
    resultado = 10 / 0
except ZeroDivisionError:
    print("Error: División por cero")
finally:
    print("Esta línea se ejecuta siempre")
```
+ Ejercicio: Escribir un programa que maneje diferentes tipos de excepciones.
## 13. Herencia: clases abstractas e interfaces
+ Contenido: Conceptos de herencia, clases abstractas e interfaces en Python.
+ Ejemplo: Crear una clase base y una clase derivada.
```python
class Animal:
    def __init__(self, nombre):
        self.nombre = nombre

    def hacer_sonido(self):
        raise NotImplementedError("Este método debe ser implementado por la subclase")

class Perro(Animal):
    def hacer_sonido(self):
        return "Guau"

perro = Perro("Rex")
print(perro.hacer_sonido())
```
+ Ejercicio: Crear una jerarquía de clases que represente diferentes tipos de vehículos.
## 14. Introducción a las estructuras de datos
+ Contenido: Conceptos básicos de estructuras de datos (listas, pilas, colas, árboles).
+ Ejemplo: Uso de listas y diccionarios en Python.
```python
# Lista
frutas = ["manzana", "banana", "cereza"]
print(frutas)  # Acceder al primer elemento

# Diccionario
persona = {"nombre": "Juan", "edad": 30}
print(persona["nombre"])  # Acceder al valor de la clave "nombre"
```
+ Ejercicio: Implementar una pila y una cola usando listas en Python.
