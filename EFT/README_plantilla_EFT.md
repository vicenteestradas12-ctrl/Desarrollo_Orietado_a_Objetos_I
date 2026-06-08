![Duoc UC](https://www.duoc.cl/wp-content/uploads/2022/09/logo-0.png)
# 🧠 Evaluación Final Transversal – Desarrollo Orientado a Objetos I

## 👤 Autor del proyecto
- **Nombre completo:** [vicente estrada]
- **Sección:** [Desarrollo Orientado a Objetos]
- **Carrera:** diseño de aplicaciones
- **Sede:** [Duoc UC - Escuela de Informática y Telecomunicaciones]

---

## 📘 Descripción del Proyecto

Este proyecto corresponde al desarrollo de un sistema básico orientado a objetos para la agencia de turismo Llanquihue Tour.

El objetivo principal es representar de manera estructurada a las personas vinculadas a la organización mediante la aplicación de conceptos fundamentales de Programación Orientada a Objetos (POO), tales como:

Encapsulamiento.
Herencia.
Composición.
Reutilización de clases.
Organización modular mediante paquetes.
---

## 🧱 Estructura general del proyecto

```plaintext
📁 src
│
├── model
│    ├── Direccion.java
│    ├── Persona.java
│    └── Empleado.java
│
└── app
     └── Main.java
````
Clases Implementadas
Direccion

Clase encargada de almacenar la información de ubicación de una persona.

Atributos
calle
ciudad
region
Persona

Clase base que representa una persona relacionada con la agencia.

Atributos
nombre
rut
telefono
direccion
Empleado

Clase derivada de Persona.

Atributos adicionales
cargo
sueldo
Concepto aplicado
Herencia (extends Persona)
Relaciones entre Clases
Composición
Persona
   │
   └── Direccion

Una persona posee una dirección, por lo que se implementa una relación de composición.

Herencia
Persona
   │
   └── Empleado

Empleado reutiliza los atributos y comportamientos definidos en Persona.
---



## ⚙️ Ejecución del Programa

La clase principal se encuentra en:

app/Main.java

Para ejecutar el sistema:

Abrir el proyecto en IntelliJ IDEA.
Verificar la estructura de paquetes.
Compilar el proyecto.
Ejecutar Main.java.
Revisar la salida en consola.
Resultado Esperado
---



=== PERSONA 1 ===
Nombre: María González
RUT: 12.345.678-9
Teléfono: +56 9 1234 5678
Dirección: Av. Vicente Pérez Rosales 120, Llanquihue, Los Lagos

=== EMPLEADO 1 ===
EMPLEADO
Nombre: Carlos Muñoz
RUT: 15.987.654-3
Teléfono: +56 9 8765 4321
Dirección: Calle O'Higgins 450, Puerto Varas, Los Lagos
Cargo: Guía Turístico
Sueldo: $950000.0
Tecnologías Utilizadas
Java
IntelliJ IDEA
Programación Orientada a Objetos (POO)

---


**Fecha de entrega:** \[08/06/2026]

---

© Duoc UC | Escuela de Informática y Telecomunicaciones | Evaluación Final Transversal EFT




