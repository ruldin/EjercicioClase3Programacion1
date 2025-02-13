# Ejercicio en Clase 3

**Instrucciones Generales:**
- Trabajarlo en parejas (Obligatorio).
- No utilizar IA para el análisis.
- Se comparte un proyecto en C#. Analiza y, en un archivo de Word, ve anotando tus sugerencias, análisis y respuestas a lo siguiente:

---

## **1. Análisis del Programa**

### **Tareas Repetitivas o que pueden encapsularse en funciones**
- Identificar las tareas repetitivas o que pueden encapsularse en funciones. Por ejemplo:
  - Agregar estudiantes.
  - Mostrar la lista de estudiantes.
  - Calcular promedios.
  - Encontrar al estudiante con la calificación más alta.

### **Variables Locales vs Variables Globales**
- Discutir cuándo es apropiado usar variables locales y cuándo usar variables globales.
  - ¿Qué datos deben ser accesibles en todo el programa?
  - ¿Qué datos solo son necesarios dentro de una función específica?

---

## **2. Modularización**

### **Convertir el Programa en Funciones**
- Modulariza el programa creando funciones claras y específicas. Por ejemplo:
  - `AgregarEstudiante()`
  - `MostrarEstudiantes()`
  - `CalcularPromedio()`
  - `MostrarEstudianteConMaxCalificacion()`
  - *(No necesariamente tienen que ser estas funciones, puedes asignarles tus propios nombres).*

### **Definir Variables Locales y Globales**
- Define qué variables deben ser locales y cuáles deben ser globales.
  - ¿Qué datos necesitan ser compartidos entre múltiples funciones?
  - ¿Qué datos solo son relevantes dentro de una función específica?

---

## **3. Preguntas Guía**

Responde las siguientes preguntas en tu análisis:

1. **¿Qué ventajas tiene dividir el código en funciones?**
   - Reflexiona sobre cómo la modularidad mejora la organización, reutilización y mantenimiento del código.

2. **¿Por qué es importante limitar el uso de variables globales?**
   - Considera los riesgos de tener demasiadas variables globales, como la posibilidad de errores inesperados o dificultades para depurar el código.

3. **¿Cómo se puede mejorar la legibilidad del código?**
   - Piensa en cómo nombrar funciones y variables de manera descriptiva, así como en la importancia de comentarios y estructura clara.

---

## **Mejoras Adicionales**
 
- **Validación de Entradas del Usuario:**
  - Implementa validaciones para evitar errores si el usuario ingresa texto en lugar de números.
  - Ejemplo: Si se pide una calificación, asegúrate de que el valor ingresado sea numérico y esté dentro de un rango válido.

---

## **Entregables**

1. **Archivo `program.cs`:**
   - Sube el archivo modificado con las funciones implementadas.

2. **Documento en Word:**
   - Incluye tus análisis, sugerencias y respuestas a las preguntas guía.

- Ambos archivos deben ser subidos a Canvas de forma **individual**.