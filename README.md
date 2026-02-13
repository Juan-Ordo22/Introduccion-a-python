# Introduccion-a-python
Repositorio de cuadernos introductorios de Python (strings, tuplas, listas, sets, diccionarios, condiciones, bucles, funciones y clases) con membrete, documentación en Markdown, quiz y un ejercicio integrador final con validación.

# Ejercicios de Python — Procesamiento de Datos a Gran Escala

Este repositorio reúne una colección de cuadernos introductorios de **Python** desarrollados para el curso **Procesamiento de Datos a Gran Escala** (Pontificia Universidad Javeriana).  
Cada cuaderno está organizado de forma progresiva e incluye **documentación en Markdown**, un **quiz** (o autoevaluación) y un **ejercicio integrador final** que acumula lo trabajado.

---

## Autor
**Nombre:** Juan David Ordoñez  
**Código estudiantil:** 20523791  
**Universidad:** Pontificia Universidad Javeriana  
**Curso:** Procesamiento de Datos a Gran Escala  

---

## Estructura del repositorio

Cada notebook cumple con:
- **Membrete** (autor, código, fecha, descripción, objetivos y evidencias).
- **Secciones documentadas** (explicación clara de lo que hace cada bloque de código).
- **Quiz** al final (con descripción de lo que evalúa y, cuando aplica, alternativas de solución).
- **Ejercicio integrador final** (uno por cuaderno) con validación mediante `assert`.
- **Conclusiones**.

---

## Contenido de los cuadernos

### 01 — Cadenas (Strings) | `01-Python-Cadenas.ipynb`
Conceptos trabajados:
- Creación de cadenas (`str`) con comillas simples/dobles
- Longitud con `len()`
- Indexación positiva y negativa
- Slicing y stride
- Concatenación
- Secuencias de escape (`\n`, `\t`, `\\`) y cadenas raw `r""`
- Métodos: `upper()`, `replace()`, `find()`
Incluye quiz y un bono/práctica aplicada.

---

### 02 — Tuplas (Tuples) | `02-Python-Tuplas.ipynb`
Conceptos trabajados:
- Definición de tuplas y sus características (ordenadas e inmutables)
- Indexación (positiva y negativa)
- Slicing (subtuplas)
- Concatenación de tuplas
- Ordenamiento con `sorted()` (y conversión a `tuple` si se requiere)
- Tuplas anidadas y acceso con múltiples índices
Incluye quiz documentado y ejercicio integrador final.

---

### 03 — Listas (Lists) | `03-Python-Listas.ipynb`
Conceptos trabajados:
- Creación de listas y contenido heterogéneo
- Indexación y slicing
- `extend()` vs `append()`
- Modificación y eliminación (`A[i] = ...`, `del`)
- Transformación de texto a lista con `split()`
- **Aliasing vs clonación** (`B = A` vs `B = A[:]`)
Incluye quiz y ejercicio integrador final con evidencia.

---

### 04 — Conjuntos (Sets) | `04-Python-Conjuntos.ipynb`
Conceptos trabajados:
- Creación de conjuntos y eliminación automática de duplicados
- Conversión lista → set
- Operaciones de modificación: `add()`, `remove()` (y recomendación `discard()`)
- Pertenencia con `in`
- Operaciones entre conjuntos: intersección, diferencia, unión y diferencia simétrica
- Subconjunto y superconjunto
Incluye quiz y ejercicio integrador final.

---

### 05 — Diccionarios (Dictionaries) | `05-Python-Diccionarios.ipynb`
Conceptos trabajados:
- Diccionarios como pares llave → valor
- Acceso a valores por llave y manejo de casos (recomendación `get()`)
- Consultar llaves y valores: `keys()`, `values()`
- Agregar, actualizar y eliminar entradas (`del`)
- Verificación de existencia con `in`
Incluye quiz con recomendaciones de tipos (evitar números como strings) y ejercicio integrador final.

---

### 06 — Condiciones | `06-Python-Condiciones.ipynb`
Conceptos trabajados:
- Booleanos y comparaciones (`==`, `!=`, `>`, `<`, `>=`, `<=`)
- Estructuras `if`, `elif`, `else`
- Operadores lógicos `and`, `or`, `not`
- Importancia de la indentación y control de flujo
Incluye quiz alineado al enunciado y ejercicio integrador final **sin funciones**.

---

### 07 — Bucles | `07-Python-Bucles.ipynb`
Conceptos trabajados:
- `range()` y sus variantes
- Bucle `for` sobre rangos y listas
- `enumerate()` para índice + valor
- Modificación de listas dentro de un `for`
- Bucle `while` con condición de parada (sentinela)
- Buenas prácticas para evitar `IndexError`
Incluye quiz y ejercicio integrador final **sin funciones**.

---

### 08 — Funciones | `08-Python-Funciones.ipynb`
Conceptos trabajados:
- Definición de funciones (`def`), parámetros, `return` y docstrings
- Diferencia entre funciones que retornan vs imprimen
- Variables locales y globales, uso de `global`
- Funciones predefinidas (`sum`, `len`, `print`) y buenas prácticas (no sobrescribir built-ins)
- Control de flujo dentro de funciones (if/else y ciclos)
- Argumentos por defecto
Incluye quiz y ejercicio integrador final con `assert`.

---

### 09 — Clases y Objetos | `09-Python-Clases.ipynb`
Conceptos trabajados:
- Programación orientada a objetos: clases e instancias
- Constructor `__init__`, atributos y notación punto
- Métodos y modificación del estado del objeto
- Uso de `dir()` y `isinstance()`
- Ejemplos con clases **Circle** y **Rectangle** (incluye visualización con matplotlib)
Incluye autoevaluación y ejercicio integrador final.

---

## Requisitos
- Python 3.x
- Jupyter Notebook / JupyterLab
- Librerías usadas en algunos cuadernos:
  - `matplotlib` (para el cuaderno de clases/figuras)
  - `math` (cálculos)

---

## Cómo ejecutar
1. Clona o descarga el repositorio.
2. Abre Jupyter Notebook / JupyterLab.
3. Ejecuta cada cuaderno en orden (01 → 09) para seguir la progresión.

---
