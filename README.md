# Tutorial básico de C#

Este proyecto es una página web sencilla creada con **HTML** y **CSS** para ayudar a estudiantes que están comenzando a aprender el lenguaje de programación **C#**.

## Descripción

La página explica los conceptos básicos de C# de forma clara y con ejemplos simples:

- Qué es C#
- Primer programa en C#
- Variables y tipos de datos
- Condicionales con `if` y `else`
- Bucles con `for` y `while`
- Funciones o métodos
- Ejercicio práctico

## Tecnologías utilizadas

- HTML5
- CSS3

## Estructura del proyecto

```text
tutorial-csharp/
│
├── index.html
├── estilos.css
└── README.md
```

## Cómo usarlo

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Lee cada sección y practica los ejemplos de código.

```bash
git clone [https://github.com/tu-usuario/tutorial-csharp.git](https://github.com/tu-usuario/tutorial-csharp.git)
```

## Contenido del tutorial

### 1. ¿Qué es C#?

C# es un lenguaje de programación creado por Microsoft. Se utiliza para crear aplicaciones de escritorio, videojuegos, aplicaciones web y sistemas empresariales.

### 2. Variables

Las variables permiten guardar información como textos, números o valores verdaderos y falsos.

```csharp
string nombre = "Ana";
int edad = 20;
```

### 3. Condicionales

Los condicionales permiten que el programa tome decisiones.

```csharp
if (edad >= 18)
{
    Console.WriteLine("Eres mayor de edad");
}
else
{
    Console.WriteLine("Eres menor de edad");
}
```

### 4. Bucles

Los bucles sirven para repetir instrucciones varias veces.

```csharp
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine("Número: " + i);
}
```

### 5. Funciones

Las funciones permiten reutilizar código.

```csharp
static int Sumar(int a, int b)
{
    return a + b;
}
```

## Ejercicio práctico

Crea un programa que muestre tu nombre y tu edad:

```csharp
string nombre = "Tu nombre";
int edad = 18;

Console.WriteLine("Mi nombre es: " + nombre);
Console.WriteLine("Mi edad es: " + edad);
```

## Autor

Creado como material de estudio para estudiantes principiantes en programación.

## Licencia

Este proyecto puede usarse libremente con fines educativos.
