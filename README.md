<<<<<<< HEAD
# 📘 Proyecto Gestión de Aprendices en Java

## Descripción del proyecto
Este proyecto es una aplicación básica desarrollada en **Java** que permite **crear, almacenar y mostrar información de aprendices**, aplicando los principios fundamentales de la **Programación Orientada a Objetos (POO)**.

El objetivo principal es reforzar conceptos como:
- Creación de clases y objetos
- Uso de constructores
- Encapsulamiento de atributos
- Getters y setters
- Validación de datos
- Uso de listas (`ArrayList`)
- Métodos personalizados

---

## Tecnologías utilizadas
- Lenguaje: **Java**
- JDK: **Java 21** (o compatible)
- IDE sugerido: VS Code / IntelliJ / Eclipse

---

## Estructura del proyecto
El proyecto se encuentra organizado dentro del paquete `com.sena` y contiene dos clases principales:

- **App.java**: clase principal que contiene el método `main`.
- **Aprendiz.java**: clase que representa al aprendiz y define sus atributos y comportamientos.

---

## Funcionamiento del programa

### 🔹 Clase `Aprendiz`
La clase `Aprendiz` representa a un aprendiz del SENA y contiene los siguientes atributos privados:
- `nombre`
- `documento`
- `correo`
- `edad`

Se aplicó **encapsulamiento**, por lo que el acceso a los atributos se realiza mediante **getters y setters**.

#### Constructores
- Un **constructor vacío**, que permite crear objetos sin inicializar los datos.
- Un **constructor con parámetros**, que permite crear objetos con los datos completos desde el inicio.

#### Validaciones
- El correo se valida para que contenga el carácter `@`.
- La edad se valida para que esté dentro de un rango válido.
- Si los datos no son correctos, el programa lanza una excepción (`IllegalArgumentException`).

#### Método `presentarse()`
Este método retorna un mensaje con toda la información del aprendiz en forma de texto.

---

### 🔹 Clase `App`
La clase `App` contiene el método `main`, donde se ejecuta el programa. En esta clase se realiza lo siguiente:

1. Se crean varios objetos de tipo `Aprendiz`.
2. Se utilizan diferentes formas de creación de objetos (constructor con parámetros y constructor vacío + setters).
3. Los aprendices se almacenan en una lista de tipo `ArrayList`.
4. Se recorre la lista utilizando un ciclo `for-each`.
5. Se imprime la información de cada aprendiz en consola.

---

## Salida esperada
El programa muestra en consola la información de cada aprendiz registrado, incluyendo su nombre, documento, correo y edad.

---

## Objetivo académico
Este proyecto fue desarrollado con fines académicos para:
- Comprender el uso de clases y objetos en Java
- Aplicar buenas prácticas de encapsulamiento
- Manejar listas y ciclos
- Reforzar la lógica básica de programación orientada a objetos

---

## Autor
**Ivonne Dayana Sanchez Contreras**  
Aprendiz SENA – Desarrollo de Software - Ficha: 3311983